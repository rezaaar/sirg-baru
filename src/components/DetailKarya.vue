<template>
  <div class="container skarya my-5 pt-5">
    <div class="row mt-5">
        <div class="col-lg-5 col-md-12 col-12">
            <img class="img-fluid w-100 pb-1" src="@/assets/1.jpg" id="MainImg" alt="">

            <div class="small-img-group">
                <div class="small-img-col">
                    <img src="@/assets/2.jpg" width="100%" class="small-img" alt="">
                </div>
                <div class="small-img-col">
                    <img src="@/assets/3.jpg" width="100%" class="small-img" alt="">
                </div>
                <div class="small-img-col">
                    <img src="@/assets/4.jpg" width="100%" class="small-img" alt="">
                </div>
                <div class="small-img-col">
                    <img src="@/assets/5.jpg" width="100%" class="small-img" alt="">
                </div>
            </div>
        </div>
        <div class="col-lg-6 col-md-12 col-12">
            <h3 class="py-4">Sistem Informasi Riset Grup - SIRG</h3>
            <h4 class="mt-5 mb-5">Detail Karya</h4>
            <span>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sint dolore, alias necessitatibus magnam facilis commodi consequatur nemo pariatur quibusdam ut illum repellendus quos excepturi recusandae. Vitae harum veritatis dicta asperiores.</span>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'DetailKarya',
    mounted: function() {
        var MainImg = document.getElementById("MainImg");
        var smallimg = document.getElementByClassName("small-img");

        smallimg[0].onclick = function(){
            MainImg.src = smallimg[0].src;
        }
        smallimg[1].onclick = function(){
            MainImg.src = smallimg[1].src;
        }
        smallimg[2].onclick = function(){
            MainImg.src = smallimg[2].src;
        }
        smallimg[3].onclick = function(){
            MainImg.src = smallimg[3].src;
        }
  }
}




</script>

<style>
.small-img-group {
    display:  flex;
    justify-content: space-between;   
}

.small-img-col {
    flex-basis: 24%;
    cursor: pointer;

}
</style>