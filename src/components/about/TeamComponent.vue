<template>
    <section>
        <div class="title">
            <h2>Our team</h2>
            <p>Dedicated to quality and your success</p>
        </div>

        <div class="buddy">
            <div class="profile">
                <div class="image"><span>150 x 150</span></div>
                <p>Ibbie Eckart</p>
                <span>Founder & CEO</span>
            </div>

            <div class="profile">
                <div class="image"><span>150 x 150</span></div>
                <p>Arden Vasek</p>
                <span>CFO</span>
            </div>

            <div class="profile">
                <div class="image"><span>150 x 150</span></div>
                <p>Toribio Nerthus</p>
                <span>Operations Manager</span>
            </div>

            <div class="profile">
                <div class="image"><span>150 x 150</span></div>
                <p>Malvina Cilla</p>
                <span>CTO</span>
            </div>
        </div>
    </section>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400..700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');



//variables
$background: #F8F9FA;
$text: #343A40;
$icon: #CED4DA;
$paragraph-color: #6C757D;

section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: $background;
    height: 650px;
    gap: 50px;

    .title{
        text-align: center;

        h2{
            font-family: 'Poppins', sans-serif;
            font-size: 27px;
            font-weight: 700;
            margin-bottom: 30px;
        }
        p{
            font-family: 'Poppins', sans-serif;
            font-size: larger;
            font-weight: 300;
            color: $paragraph-color;
        }
    }

    .buddy{
        display: flex;
        justify-content: center;
        gap: 120px;


        .profile{
            display: flex;
            flex-direction: column;
            text-align: center;
            gap: 10px;

            .image{
                background: lightgray;
                border-radius: 50%;
                display: flex;
                justify-content: center;
                align-items: center;
                width: 150px;
                height: 150px;

                span{
                    font-family: 'Poppins', sans-serif;
                    font-weight: 300;
                    color: $paragraph-color;
                }
            }

            p{
                font-family: 'Poppins', sans-serif;
                font-size: large;
                font-weight: 600;
            }

            span{
                font-family: 'Edu VIC WA NT Beginner', cursive;
                color: $paragraph-color;
            }
        }
    }
}

</style>
