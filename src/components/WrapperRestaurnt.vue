<template>
    <div class="wrapper">
        <FirstComponent />
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
        background-image: url(../assets/img/slider52x.jpg);
    }

</style>