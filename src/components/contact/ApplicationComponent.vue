<template>
    <section>
        <div class="container-box">
            <div class="title">
                <div class="img">
                    <i class="bi bi-envelope"></i>
                </div>
                <h1>Get in touch</h1>
                <p>We'd love to hear from you</p>
            </div>
            <form action="">
                <input type="text" placeholder="Full name">
                <input type="text" placeholder="Email address">
                <input type="text" placeholder="Phone number">
                <textarea name="" id="" placeholder="Message"></textarea>
                <button>Submit</button>
            </form>
        </div>

    </section>
    <!--cards-->
    <div class="cards-section">
        <div class="container-cards">
            <div class="card">
                <div class="img">
                    <i class="bi bi-chat-dots"></i>
                </div>
                <h3>Chat with us</h3>
                <p>Chat live with one of our support specialists.</p>
            </div>
        </div>
    
        <div class="container-cards">
            <div class="card">
                <div class="img">
                    <i class="bi bi-people-fill"></i>
                </div>
                <h3>Ask the community</h3>
                <p>Explore our community forums and communicate with other users.</p>
            </div>
        </div>
    
        <div class="container-cards">
            <div class="card">
                <div class="img">
                    <i class="bi bi-question-circle"></i>
                </div>
                <h3>Support center</h3>
                <p>Browse FAQ's and support articles to find solutions.</p>
            </div>
        </div>
    
        <div class="container-cards">
            <div class="card">
                <div class="img">
                    <i class="bi bi-telephone"></i>
                </div>
                <h3>Call us</h3>
                <p>Call us during normal business hours at (555) 892-9403.</p>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

//variables
$background: #F8F9FA;
$text: #343A40;
$paragraph-color: #6C757D;
$cards: #007BFF;


section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 845px;
    

    .container-box{
        border-radius: 5px;
        background: rgb(248, 249, 250);
        width: 880px;
        height: 736px;
        margin-top: 50px;
        margin-bottom: 50px;

        .title{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-top: 50px;
            gap: 20px;

            h1{
                font-family: 'Poppins', sans-serif;
                font-weight: bold;
                font-size: 35px;
            }
            p{
                font-family: 'Poppins', sans-serif;
                font-weight: 300;
                font-size: 20px;
                color: $paragraph-color;
            }

            .img{
                display: flex;
                justify-content: center;
                align-items: center;
                border-radius: 5px;
                background: $cards;
                width: 48px;
                height: 48px;

                i{
                    color: $background;
                    font-size: 24px;
                }
            }
        }

        form{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin-top: 30px;
            margin-bottom: 30px;
            gap: 15px;

            input{
                border-radius: 5px;
                border: 1px solid lightgrey;
                width: 496px;
                height: 58px;

                &::placeholder{
                    font-family: 'Poppins', sans-serif;
                    font-size: 15px;
                    padding: 13px;
                    color: $text;
                }
            }
            textarea{
                border-radius: 5px;
                border: 1px solid lightgrey;
                width: 496px;
                height: 160px;

                &::placeholder{
                    font-family: 'Poppins', sans-serif;
                    font-size: 15px;
                    padding: 13px;
                    color: $text;
                }
            }

            button{
                background: $cards;
                border: none;
                border-radius: 10px;
                color: #fff;
                font-family: 'Poppins', sans-serif;
                font-size: 20px;
                width: 496px;
                height: 47.6px;

            }
        }
    }

}
//cards style
.container-cards{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    // width: 912px;
    // height: 288px;

    .card{
        h3{
            font-family: 'Poppins', sans-serif;
            font-weight: 400;
            font-size: 20px;
        }
        p{
            color: $paragraph-color;
            font-family: 'Poppins', sans-serif;
            font-weight: 300;
            font-size: 15px;
            width: 180px;
            height: 100px;
        }
        .img{
                display: flex;
                justify-content: center;
                align-items: center;
                border-radius: 5px;
                background: $cards;
                width: 48px;
                height: 48px;

                i{
                    color: $background;
                    font-size: 24px;
                }
            }
    }
}

.cards-section {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 60px;
    flex-wrap: wrap;
    margin-bottom: 50px;
}
</style>