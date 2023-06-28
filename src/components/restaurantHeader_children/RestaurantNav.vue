<template>
        <ul>
            <li>
                {{ navElement.text }}
            </li>
        </ul>
</template>


<script>

export default {
    name : 'RestaurantNav',
        props : {
            navElement : String,
        }
}
</script>


<style lang="scss">
    ul{
        color: white;
        list-style-type: none;
    }

    li{
        text-transform: uppercase;
    }
</style>