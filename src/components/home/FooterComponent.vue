<template>
    <footer>
        <div class="copy-right">
            <p>Copyright © Your Website 2023</p>
        </div>
        <div class="pages">
            <a href=""><router-link to="">Privacy</router-link></a>
            <a href=""><router-link to="">Terms</router-link></a>
            <a href=""><router-link to="/contact">Contact</router-link></a>  
        </div>
    </footer>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>

//font
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$background: #212529;
$text-color: #fff;

footer{
    display: flex;
    justify-content: space-around;
    align-items: center;
    background: $background;
    height: 72px;
    padding: 10px;

    .copy-right{
        p{
            font-family: 'Poppins', sans-serif;
            font-size: small;
            color: $text-color;
        }
    }

    .pages{
        a{
            color: $text-color;
            cursor: pointer;
            font-family: 'Poppins', sans-serif;
            font-size: small;
            gap: 10px;
            margin-right: 7px;
        }
    }
}

</style>