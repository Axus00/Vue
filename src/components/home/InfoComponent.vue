<template>
    <section class="container">
        <div class="title"><h2>A better way to start building.</h2></div>
        <div class="container-box">
            <div class="box-icons">
                <div class="icons">
                    <div class="icon"><i class="bi bi-collection"></i></div>
                    <h2>Featured title</h2>
                    <p>Paragraph of text beneath the heading to explain the heading. Here is just a bit more text.</p>
                </div>
                <div class="icons">
                    <div class="icon"><i class="bi bi-building"></i></div>
                    <h2>Featured title</h2>
                    <p>Paragraph of text beneath the heading to explain the heading. Here is just a bit more text.</p>
                </div>
                <div class="icons">
                    <div class="icon"><i class="bi bi-toggles2"></i></div>
                    <h2>Featured title</h2>
                    <p>Paragraph of text beneath the heading to explain the heading. Here is just a bit more text.</p>
                </div>
                <div class="icons">
                    <div class="icon"><i class="bi bi-toggles2"></i></div>
                    <h2>Featured title</h2>
                    <p>Paragraph of text beneath the heading to explain the heading. Here is just a bit more text.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>

//import font Poppins
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css");

//variables
$text-color: #fff;
$title-color: #212529;
$paragraph-color: #6C757D;
$background-body: #fff;
$background-icons: #0D6EFD;

.container{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    height: 500px;
    margin-top: 100px;

    //main title
    .title{
        font-family: 'Poppins', sans-serif;
        font-weight: bold;
        font-size: large;
        width: 376px;
        height: 77px;
        margin-left: 150px;
    }

    //container icons
    .container-box{
        width: 847px;
        height: 336px;
    }
    .box-icons{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
    .icons{
        margin-bottom: 15px;


        h2{
            font-family: 'Poppins', sans-serif;
            font-weight: 500;
            font-size: large;
            color: $title-color;
        }
        p{
            font-family: 'Poppins', sans-serif;
            font-weight: 400;
            font-size: small;
            color: $paragraph-color;
            width: 376px;
            height: 48px;
        }
        .icon{
            background: $background-icons;
            border-radius: 5px;
            width: 48px;
            height: 48px;
            margin-bottom: 15px;
            display: flex;
            justify-content: center;
            align-items: center;

            i{
                color: #fff;
                font-size: 24px;
                
            }
        }
    }
}

</style>