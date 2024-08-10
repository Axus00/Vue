<template>
    <section>
        <div class="banner-left">
            <h1>A Bootstrap 5 template for modern business</h1>
            <p>Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit!</p>
            <div class="buttons">
                <button class="learn">Get Started</button>
                <button class="started">Learn More</button>
            </div>
        </div>

        <div class="banner-rigth">
            <img :src="require('../../../public/img/image.png')" alt="image" width="488px">
        </div>
    </section>
</template>

<script lang="ts">


</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$text-color: #fff;
$text-nav:  #ADB5BD;
$text-nav-hover: #CED4DA;
$background: #212529;

//variables buttons
$button-learn: #0D6EFD;
$button-started: #6C757D;

section{
    background: $background;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 10%;
    height: 450px;

    .banner-left{
        width: 500px;
        h1{
            font-family: 'Poppins', sans-serif;
            font-size: 40px;
            font-weight: bold;
            color: $text-color;
        }

        p{
            font-family: 'Poppins', sans-serif;
            font-size: medium;
            font-weight: 400;
            color: $text-nav;
        }

        .buttons{
            display: flex;
            flex-direction: row;
            gap: 10px;
            margin-top: 20px;

            .learn{
                font-family: 'Poppins', sans-serif;
                font-size: small;

                border-radius: 5px;
                background: $button-learn;
                color: $text-color;
                cursor: pointer;
                width: 150px;
                height: 47px;

                &:hover{
                    background: blue;
                    transition: .5s ease;
                }
            }

            .started{
                font-family: 'Poppins', sans-serif;
                font-size: small;

                border-radius: 5px;
                border: 1px solid #fff;
                background: $background;
                color: $text-color;
                cursor: pointer;
                width: 150px;
                height: 47px;

                &:hover{
                    background: #fff;
                    color: #000;
                    transition: .5s ease;
                }
            }
        }


    }

    img{
        border-radius: 10px;
    }
}

</style>