<template>
    <main>
        <!-- FIRST COMPONENT -->
        <div class="container ">
            <div class="row">
                <div class="col-5">
                    <h1 class='my_fs'>fine dining experience</h1>
                    <p>Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.</p>
                    <button>
                        buy avada today
                    </button>
                </div>
                <div class="col-7">
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
            <div class="row d-flex justify-content-between ">
                <div class="col-5">
                    <h1>TESTO</h1>
                    <H1>BUTTON</H1>
                </div>
                <div class="col-5">
                    <h1>TESTO</h1>
                    <H1>BUTTON</H1>
                </div>
            </div>
        </div>

        <!-- FIFTH COMPONENT -->
        <div class="container-fluid my-5">
            <div class="row">
                <div class="col-12 divider">
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

        <!-- HEIGHT COMPONENT -->
        <div class="container">
            <div class="row ">
                <div class="col-4 mt-5">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
                <div class="col-4 mt-5">
                    <h1>IMMAGINE</h1>
                    <h1>TITOLTO</h1>
                    <h1>TESTO</h1>
                </div>
            </div>
        </div>

        <!-- NINTH COMPONENT -->
        <div class="container">
            <div class="row">
                <div class="col-4 m-5">
                    <h1>TITOLO</h1>
                    <h1>LINE BRAKET</h1>
                    <h1>TESTO</h1>
                    <h1>BUTTON</h1>
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
            margin: 80px auto;
        }
        .col-4{
            border: 2px solid red;
            height: 700px;
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
            border: 2px solid fuchsia;
            height: 800px;
        }
        
        
    }

    .row{
        border: 3px solid cyan;
    }

    .divider{
        background-image: url(../assets/img/page52x.jpg);
        background-position: top;
        scale: 1.2;
    }

    .my_fs{
        font-size: 90px;
        text-transform: uppercase;  
        }

</style>