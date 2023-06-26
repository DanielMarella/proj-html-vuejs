<script>
import RestaurantHeader from './components/RestaurantHeader.vue';
import RestaurantMain from './components/RestaurantMain.vue';
import RestaurantFooter from './components/RestaurantFooter.vue';


export default {
  name : 'App',

  components : {
    RestaurantMain,
    RestaurantHeader,
    RestaurantFooter,
  }

}

</script>

<template>

  <RestaurantHeader />
  <RestaurantMain />
  <RestaurantFooter />

</template>

<style lang="scss">
  @import '../node_modules/bootstrap/scss/bootstrap';
  @import './styles/general.scss';
</style>
