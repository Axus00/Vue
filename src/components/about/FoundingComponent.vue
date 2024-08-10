<template>
    <section>
        <div class="image"><span>600 x 400</span></div>

        <div class="title">
            <h2>Our founding</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto est, ut esse a labore aliquam beatae expedita. Blanditiis impedit numquam libero molestiae et fugit cupiditate, quibusdam expedita, maiores eaque quisquam.</p>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
//import font
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');


//variables
$background: #F8F9FA;
$text: #fff;
$text: #343A40;
$icon: #CED4DA;
$paragraph-color: #6C757D;

section{
    display: flex;
    justify-content: center;
    align-items: center;
    background: $background;
    height: 500px;
    gap: 50px;

    .image{
        background: #343A40;
        border-radius: 5px;
        width: 588px;
        height: 392px;
        display: flex;
        justify-content: center;
        align-items: center;

        span{
            color: $paragraph-color;
            font-family: 'Poppins', sans-serif;
            font-size: 50px;
            font-weight: 200;
        }
    }

    .title{

        h2{
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            font-size: 25px;
            width: 588px;
            height: 39px;
        }
        p{
            font-family: 'Poppins', sans-serif;
            font-size: 17px;
            color: $paragraph-color;
            width: 588px;
            height: 120px;
        }
    }
}

</style>