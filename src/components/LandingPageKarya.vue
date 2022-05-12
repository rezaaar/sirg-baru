<template>
  <div class="container">
        <div class="container-riset-grup">
            <div class="riset-grup">
                <br><h3><b>Sistem Informasi Riset Grup</b></h3>
                <p>Sebuah wadah untuk memberikan informasi mengenai profile dan kegiatan riset grup. Meliputi profile dosen Riset Grup terkait penelitian, prestasi dan pengabdian, kemudian dokumentasi karya, kerjasama industri, penawaran judul PA, rekomendasi materi dan informasi seputar riset grup lainnya.</p>
            </div>
        </div>
        <div class="heading">
            <h3><b>Karya Mahasiswa</b></h3>
            <p>Pada kegiatan pembelajaran mengenai mata kuliah mahasiswa dengan bimbingan Riset Grup membuat suatu karya yang sangat bermanfaat kedepannya</p>
        </div>
        <div class="row">
            <div class="card my-2">
                <img src="@/assets/dtik.png" class="card-img">
                <div class="card-detail">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
                <p><a href="/detailkarya"><button>Baca Selengkapnya...</button></a></p>
            </div>
            <div class="card my-2">
                <img src="@/assets/dtik.png" class="card-img">
                <div class="card-detail">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
                <p><a href="/detailkarya"><button>Baca Selengkapnya...</button></a></p>
            </div>
            <div class="card my-2">
                <img src="@/assets/dtik.png" class="card-img">
                <div class="card-detail">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
                <p><a href="/detailkarya"><button>Baca Selengkapnya...</button></a></p>
            </div>
            <div class="card my-2">
                <img src="@/assets/dtik.png" class="card-img">
                <div class="card-detail">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
                <p><a href="/detailkarya"><button>Baca Selengkapnya...</button></a></p>
            </div>
        </div>
        <div class="karya-lain">
          <a href="/karya" class="button-karya-lain"><b>KARYA LAIN</b></a>
        </div>
    </div>
</template>

<script>
export default {
    name : 'LandingPageKarya'
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
} 
.container {
  width: 90%;
  margin: 50px auto;
}

.riset-grup h3 {
    color: rgb(20, 72, 122);
    font-family: 'Roboto', sans-serif;
    text-align: center;
}

.riset-grup p {
  font-family: 'Roboto', sans-serif;
  text-align: center;
}

.heading {
  text-align: center;
  margin-bottom: 50px;
}

.row {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-flow: wrap;
}

.card {
  width: 20%;
  background: #fff;
  border: 1px solid #ccc;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.card a {
  font-size: 16px;
}

.card-detail {
  padding: 30px 20px;
  text-align: center;
  font-family: 'Roboto', sans-serif;
}

.card-detail p {
  font-size: 16px;
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

p button a {
  text-decoration: none;
  color: #fff;
}

.heading h3 {
  color: rgb(20, 72, 122);
}

.card p {
  text-align: center;
}

button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 40px -10px rgba(0, 0, 0, 0.25);
}

.karya-lain {
  padding-top: 80px;
  text-align: center;
}

.karya-lain a {
  text-decoration: none;
  color: #fff;
}

.button-karya-lain {
  background-color: rgb(20, 72, 122);
  border: none;
  color: white;
  padding: 10px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

@media screen and (max-width: 1000px) {
  .card {
    width: 40%;
  }
}

@media screen and (max-width: 620px) {
  .container {
    width: 100%;
  }

  .heading {
    padding: 20px;
    font-size: 20px;
  }

  .card {
    width: 80%;
  }
}
</style>