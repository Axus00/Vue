<template>
    <section>
        <div class="form">
            <div class="title">
                <div>
                    <h3>New products, delivered to you</h3>
                    <p>Sign up for our newsletter for the latest updates.</p>
                </div>

                <div class="form-input">
                    <div class="send-email">
                        <input type="text" placeholder="Email address...">
                        <button>Sign up</button>
                    </div>
                    <p>We care about privacy, and will never share your data</p>
                </div>
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
$background: #007BFF;
$text: #F8F9FA;
$paragraph-color: #6C757D;

//styles
section{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 250px;

    .form{
        background: $background;
        border-radius: 10px;
        width: 1224px;
        height: 162.6px;

        .title{
            display: flex;
            justify-content: space-between;
            padding: 50px;

            h3{
                font-family: 'Poppins', sans-serif;
                font-size: 25px;
                color: $text;
                margin-bottom: 7px;
            }
            p{
                font-family: 'Poppins', sans-serif;
                font-size: 12px;
                color: lightgray;
            }
            
        }

        .form-input{
            .send-email{
                input{
                    border-top-left-radius: 10px;
                    border-bottom-left-radius: 10px;
                    border: none;
                    cursor: text;
                    outline: none;
                    width: 253.6px;
                    height: 37.6px;

                    &::placeholder{
                        font-family: 'Poppins', sans-serif;
                        font-weight: 400;
                        text-align: left;
                        padding-left: 10px;
                        color: $paragraph-color;
                    }

                    &:focus{
                        border: none;
                        outline: none;
                    }
                }
                button{
                    background: $background;
                    border-top-right-radius: 10px;
                    border-bottom-right-radius: 10px;
                    border: 1px solid #fff;
                    cursor: pointer;
                    color: $text;
                    width: 79.3px;
                    height: 37px;
                    font-family: 'Poppins', sans-serif;
                    font-size: small;
                    font-weight: 300;


                    &:hover{
                        background: #fff;
                        color: #000;
                        transition: .5s ease-in-out;
                    }
                }
            }

            p{
                margin-top: 7px;
                font-size: 12px;
            }
        }
    }
}

</style>
