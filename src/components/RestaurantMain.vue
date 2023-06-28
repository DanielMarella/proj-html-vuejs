<template>
    <main>

        <!-- SECOND COMPONENT -->
        <SecondComponent />

        <!-- THIRD COMPONENT -->
        <ThirdComponent />

        <!-- FOURTH COMPONENT -->
        <FourthComponent />

        <!-- FIFTH COMPONENT -->
        <FifthComponent />

        <!--SIXTH COMPONENT -->
        <SixthComponent />

        <!-- SEVENTH COMPONENT  -->
        <SeventhComponent />

        <!-- HEIGHT COMPONENT -->
        <HeightComponent />

        <!-- NINTH COMPONENT -->
        <NinthComponent />
    </main>
</template>

<script>
import SecondComponent from './restaurantMain_children/SecondComponent.vue';
import ThirdComponent from './restaurantMain_children/ThirdComponent.vue';
import FourthComponent from './restaurantMain_children/FourthComponent.vue';
import FifthComponent from './restaurantMain_children/FifthComponent.vue';
import SixthComponent from './restaurantMain_children/SixthComponent.vue';
import SeventhComponent from './restaurantMain_children/SeventhComponent.vue';
import HeightComponent from './restaurantMain_children/HeightComponent.vue';
import NinthComponent from './restaurantMain_children/NinthComponent.vue';



export default {
    name : 'RestaurantMain',

    components : {
        SecondComponent, 
        ThirdComponent,
        FourthComponent,
        FifthComponent,
        SixthComponent,
        SeventhComponent,
        HeightComponent,
        NinthComponent
    }
    
    
}

</script>

<style lang="scss" >

    .my_margin{
        margin: 150px 150px;
    }
    .article {
        height: 750px;
    }

    main{

        .col-5{
            height: 500px;
        }

        .col-12{
            height: 800px;
        }
        
        
    }
    .my_mr{
            margin-right: 50px;
        }

    .my_fs{
        font-size: 90px;
        text-transform: uppercase;  
    }


    // background-image
.couple{
    background-image: url(/img/slider72x-scaled.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.divider{
    background-image: url(/img/page52x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.divider-hero{
    background-image: url(/img/hero42x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}
.blog{
    background-image: url(/img/blog72x-1200x1375.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.blog82{
    background-image: url(/img/blog82x-1200x1375.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.blog92{
    background-image: url(/img/blog92x-1200x1375.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.menu {
    background-image:
    linear-gradient(to bottom, rgb(0, 0, 0), rgba(0, 0, 0, 0.561)),
    url(/img/misc22x.jpg);
    background-size: cover;
    color: white;
}
.info12 {
    background-image:
    linear-gradient(to bottom, rgb(0, 0, 0), rgba(255, 255, 255, 0)),
    url(/img/info12x.jpg);
    background-size: cover;
    color: white;
}

.info22{
    background-image: url(/img/info22x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.info52{
    background-image:
    linear-gradient(to bottom, rgb(0, 0, 0), rgba(255, 255, 255, 0)),
    url(/img/info52x.jpg);
    background-size: cover;
    background-repeat: no-repeat;

}

.slider32{
    background-image: url(/img/slider32x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

</style>
