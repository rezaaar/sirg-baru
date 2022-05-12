<template>
    <div class="container-riset">
        <div class="heading-riset">
            <h3><b>Riset Grup</b></h3>
            <p>Kelompok riset di dalam IT PENS</p>
        </div>
        <div class="row-riset">
            <div class="card-riset my-2">
                <img src="@/assets/search.png" class="card-img">
                <div class="card-detail-riset">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
            </div>
            <div class="card-riset my-2">
                <img src="@/assets/search.png" class="card-img">
                <div class="card-detail-riset">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
            </div>
            <div class="card-riset my-2">
                <img src="@/assets/search.png" class="card-img">
                <div class="card-detail-riset">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
            </div>
            <div class="card-riset my-2">
                <img src="@/assets/search.png" class="card-img">
                <div class="card-detail-riset">
                    <h4><b>DTIK Fest</b></h4>
                    <p>Lorem Ipsum dolor sit amet</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'LandingPageRiset'
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} 
.container-riset {
  width: 90%;
  margin: 50px auto;
}
.heading-riset {
  text-align: center;
  margin-bottom: 50px;
}

.heading-riset h3{
  text-align: center;
  color: #14487A;
}

.row-riset {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-flow: wrap;
}

.card-riset {
  width: 20%;
  background: #fff;
  border: 1px solid #ccc;
}

.card-riset a {
  font-size: 16px;
}

.card-detail-riset {
  padding: 30px 20px;
  text-align: center;
  font-family: 'Roboto', sans-serif;
}

.card-detail-riset p {
  font-size: 16px;
}

.card-riset p {
  text-align: center;
}

@media screen and (max-width: 1000px) {
  .card-riset {
    width: 40%;
  }
}

@media screen and (max-width: 620px) {
  .container-riset {
    width: 100%;
  }

  .heading-riset {
    padding: 20px;
    font-size: 20px;
  }

  .card-riset {
    width: 80%;
  }
}
</style>