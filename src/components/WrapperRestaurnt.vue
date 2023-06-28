<template>
    <div class="wrapper">
        <div class="container-fluid">
            <div class="row mb-5 ">
                <div class="col d-flex flex-column  w-50 mb-5 black">
                    <div class="col h-nav m-5 d-flex align-items-center ">
                        <img src="/img/logo-restaurant-2x-300x58.png" alt="restaurant logo" class="">
                    </div>
                    <FirstComponent />
                </div>
                <div class="col backgroud-restaurant px-0 mb-5">
                    <div class="nav m-5 d-flex justify-content-center align-items-center">
                        <RestaurantNav v-for="link in links" 
                        :navElement = "link"
                        />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import RestaurantNav from './restaurantHeader_children/RestaurantNav.vue'
import FirstComponent from './restaurantMain_children/FirstComponent.vue';

export default {
    name : 'WrapperRestaurant',
    components : {
        FirstComponent,
        RestaurantNav,

    },

    data() {
    return {

    links : [
        {
                text : 'home',
            },

            {
                text : 'history',
            },

            {
                text : 'team',
            },

            {
                text : 'menu',
            },

            {
                text : 'takeout',
            },
            
            {
                text : 'bulletin'
            },

            {
                text : 'reservation'
            },
        ]
    }
  },


}
</script>
<style lang="scss" >
    

    .wrapper{

        .h-nav{
            height: 100px;
        }

        .backgroud-restaurant{
            background-image: url(/img/slider52x.jpg/);
            background-repeat: no-repeat;
            background-size: cover;
        }

    }

</style>