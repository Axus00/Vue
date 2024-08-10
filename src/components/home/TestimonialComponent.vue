<template>
    <section>
        <div class="container-box">
            <div class="paragraph"><p>"Working with Start Bootstrap templates has saved me tons of development time when building new projects! Starting with a Bootstrap template just makes things easier!"</p></div>

            <div class="info">
                <div class="image"><span>40x40</span></div>
                <p>Tom Ato</p>
                <span>/</span>
                <p>CEO, Pomodoro</p>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>

//import font
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400..700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$background: #F8F9FA;
$text: #343A40;
$simbol: #007BFF;
$icon: #CED4DA;
$paragraph-color: #6C757D;
$font: 'Helvetica Neue', Arial, sans-serif;

.container-box{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: $background;
    width: 100%;
    height: 364px;

    .paragraph{
        
        p{
            font-family: 'Edu VIC WA NT Beginner', cursive;
            font-size: 25px;
            color: $text;
            width: 694px;
            height: 108px;
            text-align: center;
        }

    }

    .info{
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 15px;
        margin-top: 30px;

        .image{
            background: $icon;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: flex;
            justify-content: center;
            align-items: center;

            span{
                font-family: 'Poppins', sans-serif;
                font-weight: 300;
                font-size: small;
                color: $paragraph-color
            }
        }

        p{
            font-family: 'Poppins', sans-serif;
            font-weight: bold;
            font-size: small;
        }
        span{
            color: $simbol;
            font-weight: bold;
            font-size: larger;
        }
    }
}

</style>
