<template>
<div class="container text-center my-5">
    <p class="fst-italic fs-1 mb-4 mt-5">
        What critics are saying about us
    </p>
    <hr class="mb-5"> 
</div>
<div class="container">
    <div class="row mb-5">
        <div class="col blog">
        </div>
        <div class="col black t-white">
            <div class="container text-start my_margin" >
                <h3>meggy stewart</h3>
                <h1 class="mb-5">new york times</h1>
                <i v-for="star in 5" class="fa-solid fa-star mx-3 mb-3"></i>
                <div class="line my-5 ">
                </div>
                <p class="w-50 mb-4">
                    Non arcu mauris tortor ultrices mollis tellus euismod fermentum. Habitant amet tincidunt id sapien accumsan sed at.Mmalesuada ullamcorper amet. Pretium pretium dignissim nisi.
                </p>
                <button class="button black t-white">
                    read full article
                </button>
            </div>
        </div>
    </div>
    <div class="row text-center ">
        <div class="col article info52 t-white  my_mr">
            <div class="container text-start my_margin" >
                <h3>mary maxey</h3>
                <h1 class="mb-5">the guardian</h1>
                <i v-for="star in 5" class="fa-solid fa-star mx-3 mb-3"></i>
                <div class="line my-5 ">
                </div>
                <p class="w-50 mb-4">
                    Non arcu mauris tortor ultrices mollis tellus euismod fermentum. Habitant amet tincidunt id sapien accumsan sed.
                </p>
                <button class="button transparent t-white">
                    read full article
                </button>
            </div>
        </div>
        <div class="col article info12 t-white ">
            <div class="container text-start my_margin" >
                <h3>patrick monroe</h3>
                <h1 class="mb-5">globe and mail</h1>
                <i v-for="star in 5" class="fa-solid fa-star mx-3 mb-3"></i>
                <div class="line my-5 ">
                </div>
                <p class="w-50 mb-4">
                    Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Nulla porttitor accumsan tincidunt.
                </p>
                <button class="button transparent t-white">
                    read full article
                </button>
            </div>
        </div>
    </div>
</div>
</template>
<script>
export default {
    name : 'FourthComponent'
}
</script>
<style lang="scss">
    
</style>