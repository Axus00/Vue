<template>
    <section>
      <div class="banner">
        <h2>Our mission is to make building websites easier for everyone.</h2>
        <p>Start Bootstrap was built on the idea that quality, functional website templates and themes should be available to everyone. Use our open source, free products, or support us by purchasing one of our premium products or services.</p>
        <button>Read our story</button>
      </div>
    </section>
</template>
  
<script lang="ts" setup>

</script>

<style lang="scss" scoped>

//font
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$text-color: #fff;
$title-color: #212529;
$paragraph-color: #6C757D;
$background-body: #fff;
$background-icons: #0D6EFD;

section{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 450px;
    .banner{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        width: 600px;
        height: 304px;
        gap: 20px;

        h2{
            font-family: 'Poppins', sans-serif;
            font-size: 30px;
            font-weight: 600;
        }
        p{
            color: $paragraph-color;
            font-family: 'Poppins', sans-serif;
            font-size: 17px;
            font-weight: 400;
            font-weight: 300;
        }
        button{
            border-radius: 10px;
            border: none;
            background: $background-icons;
            color: $text-color;
            cursor: pointer;
            font-family: 'Poppins', sans-serif;
            width: 162px;
            height: 48px;

            &:hover{
                background: blue;
                transition: .5s ease;
            }
        }
    }
}

</style>
  
  