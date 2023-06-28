<template>
    <div class="wrapper">
        <div class="container-fluid">

            <div class="row mb-5 ">
                <div class="col w-50 mb-5 black">
                    <FirstComponent />
                </div>
                <div class="col px-0 mb-5">
                    <img src="/img/slider52x.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>

import FirstComponent from './restaurantMain_children/FirstComponent.vue';

export default {
    name : 'WrapperRestaurant',
    components : {
        FirstComponent
    }
}
</script>
<style lang="scss" >
    

    .wrapper{
        img{
            width: 100%;
            height: 100%;
        }
    }

</style>