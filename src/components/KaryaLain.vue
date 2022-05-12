<template>
<div class="container">
    <div class="karya-wrapper">
        <div class="container-karya-mahasiswa">
            <div class="karya-mahasiswa">
                <br><h3><b>Karya Mahasiswa</b></h3><br>
            </div>
        </div>
        <div class="wrapper">
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
        </div>
        <div class="wrapper">
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
        </div>
    </div>
</div>
</template>

<script>
export default {
    name : 'KaryaLain'
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

.karya-mahasiswa h3 {
    color: rgb(20, 72, 122);
    font-family: 'Roboto', sans-serif;
    text-align: center;
}

.karya-mahasiswa p {
  font-family: 'Roboto', sans-serif;
  text-align: center;
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

.card p {
  text-align: center;
}

button:hover {
  transform: scale(1.05);
  box-shadow: 0 0 40px -10px rgba(0, 0, 0, 0.25);
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

.karya-mahasiswa {
    padding-top: 80px;
    text-align: center;
    color: rgb(20, 72, 122);
}
</style>