<template>
    <header class="encabezado">
        <a href="/">Start Bootstrap</a>
        <!--Navegación-->
        <nav class="menu">
            <ul>
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/about">About</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
            </ul>
        </nav>
        <!--Navegación-->
    </header>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$text-color: #fff;
$text-nav:  #ADB5BD;
$text-nav-hover: #CED4DA;

header{
    background-color: #212529;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    padding: 30px;
    a{
        font-family: 'Poppins', sans-serif;
        font-weight: 400;
        font-style: normal;
        font-size: large;
        color: $text-color;
        cursor: pointer;
        text-decoration: none;
    }
    nav{
        ul{
            list-style: none;
            display: flex;
            gap: 10px;


        }
        a{
            font-family: 'Poppins', sans-serif;
            font-weight: 400;
            font-size: medium;
            text-decoration: none;
            color: $text-nav;

            &:hover{
                color: $text-nav-hover;
                transition: 0.5s ease-in-out;
            }
        }
    }
}
   


</style>
