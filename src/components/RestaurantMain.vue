<template>
    <main>
        <!-- FIRST COMPONENT -->
        <div class="container ">
            <div class="row">
                <div class="col-4">
                    <h1>TESTO</h1>
                </div>
                <div class="col-8">
                    <h1>IMMAGINE</h1>
                </div>
            </div>
        </div>

        <!-- SECOND COMPONENT -->
        <div class="container">
            <div class="row mb-5">
                <div class="col-6">
                    <h1>TESTO</h1>
                </div>
                <div class="col-6">
                    <h1>IMMAGINE</h1>
                </div>
            </div>
            <div class="row ">
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
            </div>
        </div>

        <!-- THIRD COMPONENT -->
        <div class="container ">
            <div class="row">
                <div class="col-8">
                    <h1>IMMAGINE</h1>
                </div>
                <div class="col-4">
                    <h1>TESTO</h1>
                </div>
            </div>
        </div>

        <!-- FOURTH COMPONENT -->
        <div class="container">
            <h1>
                What critics are saying about us
            </h1>
            <div class="row mb-5">
                <div class="col-6">
                    <h1>IMMAGINE</h1>
                </div>
                <div class="col-6">
                    <h1>TESTO</h1>
                </div>
            </div>
            <div class="row ">
                <div class="col-6  my_width-r">
                    <h1>TESTO</h1>
                    <H1>BUTTON</H1>
                </div>
                <div class="col-6 my_width-l">
                    <h1>TESTO</h1>
                    <H1>BUTTON</H1>
                </div>
            </div>
        </div>

        <!-- FIFTH COMPONENT -->
        <div class="container ">
            <div class="row">
                <div class="col-12">
                    <h1>SFONDO</h1>
                </div>
            </div>
        </div>

        <!--SIXTH COMPONENT -->
        <div class="container">
            <div class="row ">
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
            </div>
        </div>

        <!-- SEVENTH COMPONENT -->
        <div class="container ">
            <div class="row">
                <div class="col-8">
                    <h1>IMMAGINE</h1>
                </div>
                <div class="col-4">
                    <h1>TESTO</h1>
                </div>
            </div>
        </div>
    </main>
</template>

<script>

export default {
    name : 'RestaurantMain'
}

</script>

<style lang="scss" >
    main{
        border: 3px solid blue;

        .container{
            padding: 20px 0;
        }
        .col-4{
            border: 2px solid red;
            height: 500px;
        }

        .col-5{
            border: 2px solid red;
            height: 500px;
        }

        .col-6{
            border: 2px solid red;
            height: 500px;
        }

        .col-8{
            border: 2px solid fuchsia;
        }

        .col-12{
            border: 2px solid red;
            height: 500px;
        }
        
        
    }
    
            .my_width-r{
                width: calc(50% - 20px);
                margin-right: 20px;
            }

            .my_width-l{
            width: calc(50% - 20px);
            margin-left: 20px;
        }
</style>