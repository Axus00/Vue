<template>
    <section>
        <div class="title">
            <h2>Form our blog</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eaque fugit ratione dicta mollitia. Officiis ad.</p>
        </div>
        <!--Cards-->
        <div class="container-box">
            <div class="cards">
                <div class="image"><span>600x375</span></div>
                <div class="info">
                    <div class="tag"><span>News</span></div>
                    <h3>Blog post title</h3>
                    <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
                <div class="account">
                    <div class="profile"><span>40x40</span></div>
                    <div class="person">
                        <p>Kelly Rowman</p>
                        <span>March 12, 2023 / 6 min read</span>
                    </div>
                </div>
            </div>
            <div class="cards">
                <div class="image-two"><span>600x375</span></div>
                <div class="info">
                    <div class="tag"><span>Media</span></div>
                    <h3>Another blog post title</h3>
                    <p>This text is a bit longer to illustrate the adaptative height of each card. Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
                <div class="account">
                    <div class="profile"><span>40x40</span></div>
                    <div class="person">
                        <p>Josiah Barclay</p>
                        <span>March 12, 2023 / 6 min read</span>
                    </div>
                </div>
            </div>
            <div class="cards">
                <div class="image-three"><span>600x375</span></div>
                <div class="info">
                    <div class="tag"><span>News</span></div>
                    <h3>The last blog post title is a little bit longer than the others</h3>
                    <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
                <div class="account">
                    <div class="profile"><span>40x40</span></div>
                    <div class="person">
                        <p>Evelyn Martínez</p>
                        <span>March 12, 2023 / 6 min read</span>
                    </div>
                </div>
            </div>
        </div>
        <!--Cards-->
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
$paragraph-color: #6C757D;
$tag: #007BFF;
$card-three: #343A40;
$card-two: #6C757D;
$card-one: #CED4DA;
$profile: #CED4DA;

//styles
section{
    width: 100%;

    .title{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-top: 100px;

        h2{
            font-family: 'Poppins', sans-serif;
            font-weight: bold;
            font-size: 30px;
        }
        p{
            color: $paragraph-color;
            font-family: 'Poppins', sans-serif;
            font-size: medium;
            text-align: center;
            width: 588px;
            height: 60px;
        }
    }

    //cards
    .container-box{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 30px;

        .cards{
            width: 376px;
            height: 502px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            margin-top: 30px;
            margin-bottom: 70px;

            .image{
                background: $card-one;
                border-top-left-radius: 10px;
                border-top-right-radius: 10px;
                width: 376px;
                height: 200px;
                display: flex;
                justify-content: center;
                align-items: center;

                span{
                    font-family: 'Poppins', sans-serif;
                    font-weight: 300;
                    font-size: 30px;
                    color: $paragraph-color;
                }
            }
            .image-two{
                background: $card-two;
                border-top-left-radius: 10px;
                border-top-right-radius: 10px;
                width: 376px;
                height: 200px;
                display: flex;
                justify-content: center;
                align-items: center;

                span{
                    font-family: 'Poppins', sans-serif;
                    font-weight: 300;
                    font-size: 30px;
                    color: $text;
                }
            }
            .image-three{
                background: $card-three;
                border-top-left-radius: 10px;
                border-top-right-radius: 10px;
                width: 376px;
                height: 200px;
                display: flex;
                justify-content: center;
                align-items: center;

                span{
                    font-family: 'Poppins', sans-serif;
                    font-weight: 300;
                    font-size: 30px;
                    color: $paragraph-color;
                }
            }


        }

        .info{
            display: flex;
            flex-direction: column;
            padding: 20px;
            gap: 10px;

            .tag{
                background: $tag;
                border-radius: 10px;
                width: 55px;
                text-align: center;

                span{
                    font-family: 'poppins', sans-serif;
                    font-weight: bold;
                    font-size: small;
                    color: #fff;
                }
            }

            h3{
                font-family: 'Poppins', sans-serif;
                font-weight: 400;
                font-size: medium;
            }
            p{
                font-family: 'Poppins', sans-serif;
                font-weight: 300;
                font-size: medium;
            }
        }

        //profiles
        .account{
            display: flex;
            gap: 15px;
            margin-top: 20px;
            margin-left: 20px;

            .profile{
                background: $profile;
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

            .person{
                p{
                    font-family: 'Poppins', sans-serif;
                    font-weight: bold;
                    font-size: smaller;
                }
                span{
                    font-family: 'Poppins', sans-serif;
                    font-weight: 300;
                    font-size: smaller;
                    color: $paragraph-color;
                }
            }
        }

    }
}


</style>