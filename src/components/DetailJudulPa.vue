
<template>
<div class="detailpa">
    <div class="heading pt-4">
        <h3><b>Saran Judul PA</b></h3>
        <p>disini adalah list saran judul PA untuk Mahasiswa PENS</p>
    </div>
    <input type="text" class="" v-model="search" name="" placeholder="Cari Judul PA" id="">
    <div class="container-karya skarya my-5 p-5" v-for="research in searchPA" :key="research.id">
        <div class="row">
            <div class="col-lg-9 col-md-12 col-12 px-5">
                <h3 class="">{{ research.judul }}</h3>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                <h4 class=" ">2018</h4>
            </div>
            <div class="col-lg-3 col-md-12 col-12">
                <div class="btn-pa">
                    <p><button>Baca Selengkapnya...</button></p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
/* eslint-disable */
import { computed } from 'vue'
export default {
    name: 'DetailJudulPa',
    data() {
        return {
            search: "",
            researches: [
                {
                    id: 1,
                    judul: "Rekayasa Perangkat Lunak Sistem Administrasi Transaksi Pada Bank BCA"
                },
                {
                    id: 2,
                    judul: "Sistem Pendukung Keputusan Pemberian Kredit Pada Koperasi Simpan Pinjam Bahari Jombang Jawa Timur"
                }
            ]
        };
    },
    computed: {
        searchPA() {
            return this.researches.filter(research => research.judul.toLowerCase().includes(this.search.toLowerCase()));
        }
    }
}
</script>

<style>

.container-karya {
    background: #fff;
    border: 1px solid #ccc;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    width: 90%;
    margin: 50px auto;
}
button {
  border: none;
  padding: 8px;
  display: inline-block;
  color: #fff;
  background-color: rgb(20, 72, 122);
  width: 80%;
  font-size: 14px;
}
button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 40px -10px rgba(0, 0, 0, 0.25);
}

input {
    display: block;
    width: 90%;
    height: 3em;
    padding-left: 2em;
    margin: auto;
}

input::placeholder, input {
    font-size: 18pt;
}
</style>