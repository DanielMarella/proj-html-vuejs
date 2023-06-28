<template>
    <footer>
        <div class="container-fluid">
            <div class="row">
                <div class="col my-height">
                    <img src="/img/footer2x.jpg" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    name : 'RestaurantFooter'
}

</script>

<style lang="scss" scoped>
    footer{

        img{
            height: 100%;
            width: 100%;
            object-fit: cover;
        }

        .col{
            margin: 0;
        }
    }

    .my-height{
        height: 500px;
        padding: 0;
    }

</style>

