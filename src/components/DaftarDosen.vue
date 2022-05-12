<template>
  <div class="daftardosen">
    <div class="container">
      <div class="row">
        <div class="col-md-6 pt-5">
          <h1>RG RPL</h1>
          <p>
            Research Group RPL adalah sebuah grup penelitian dari program studi
            teknik informatika, berspesialisasi pada subjek rekayasa perangkat
            lunak dan bekerja bersama dalam masalah atau topik seputar RPL.
          </p>
        </div>
        <div class="col-md-6 my-5">
          <img src="@/assets/6.jpg" alt="ini foto" />
        </div>
      </div>
    </div>

    <h1 class="text-center">Dosen Tim RG RPL</h1>
    <div class="container-dosen sdosen my-5 pt-3">
      <div class="row"></div>
      <div class="row">
        <div class="col-3 cardDosen text-center p-5" v-for="lecturer in lecturers" :key="lecturer.id">
            <img
              class="img-fluid"
              width="100"
              height="100"
              src="@/assets/7.png"
              id="MainImg"
              alt=""
            />
            <h3 class="mt-5">{{ lecturer.nama }}</h3>
            <p>{{ lecturer.nip }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DaftarDosen",
  data() {
    return {
      lecturers: [
        {
          id: 1,
          nama: "Umi Sa'adah, S.Kom, M.Kom.",
          nip: "NIP: 197404162000032003",
        },
        {
          id: 2,
          nama: "Desy Intan Permatasari, S.Kom., M.Kom.",
          nip: "NIP: 198603232015042004",
        },
        {
          id: 3,
          nama: "Fadilah Fahrul Hardiansyah, S.ST., M. Kom.",
          nip: "NIP: 2000000061",
        },
      ],
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}

.container {
  max-width: 1170px;
  margin: auto;
}

.row {
  display: flex;
  flex-wrap: wrap;
}
.col-md-6 img {
  width: 80%;
}
.col-lg-3 .img-fluid {
  width: 30%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
button {
  border: none;
  padding: 8px;
  display: inline-block;
  color: #fff;
  background-color: rgb(20, 72, 122);
  width: 80%;
  font-size: 14px;
  text-decoration: none;
}
button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 40px -10px rgba(0, 0, 0, 0.25);
}

.cardDosen {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
/* .container-dosen {
  background: #fff;
  border: 1px solid #ccc;
  width: 90%;
  margin: 50px auto;
} */
.btn-dosen a {
  text-decoration: none;
  color: #ffff;
}
</style>