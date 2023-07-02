<template>
    <section>
        <a href="#">
            <div class="brand">
                <img src="../assets/img/brand/Logo.png" alt="">
            </div>
        </a>
        
        <nav >
            <ul>
                <div class="container-items">
                    <li><a href="">Home</a></li>
                <li><a href="">Services</a></li>
                <li><a href="">Projects</a></li>
                <li><a href="">About me</a></li>
                <li><a href="">Resources</a></li>
                <li><a href="">Contact me</a></li>
                </div>
            </ul>
        </nav>

        <ToggleButton />


    </section>
</template>

<script lang="ts">
    import {
        defineComponent
    } from 'vue';
    import ToggleButton from './ToggleButton.vue';


    export default defineComponent({
        components: {
            ToggleButton
        }, 
        name: 'NavBar'
    })
</script>

<style lang="scss">
//VERSION MOBILE
@media screen and (max-width: 567px) {
    section {
        width: 100%;
        height: 16vh;
        display: flex;
        border-bottom: 0.5px solid rgba($color: #46C2D8, $alpha: 0.1);
        padding: 0% 10%;
        flex: row;
        justify-content: space-between;
        align-items: center;
       

        .brand {
            width: 100%;
            height: 100%;
            

            img {
                width: 150px;
                height: 100%;
                object-fit: contain;
                opacity: .8;
                transition: 0.4s ease-in;
                filter: brightness(100%);
                filter:grayscale(1)
                
            }
            
            img:hover {
                opacity: 1;
                filter: brightness(140%);
                width: 160px;
            }
        }



        nav {
            width: 70%;
            height: 45px;
            margin: 0;
            padding: 0;
            display: none;
            ul{
                width: auto;
                height: 40px;
                border-radius: 40px;
                margin: 0;
            padding: 0;
            }

            .container-items {
                margin: 0;
                padding: 0;
                width: auto;
                height: inherit;
                display: flex;
                flex-direction: row;
                justify-content: center;
                align-items: center;

                li {
                    list-style: none;

                    a {
                        height: 38px;
                        margin: 0;
                        text-decoration: none;
                        padding: 10px;
                        color: white;
                        letter-spacing: 1px;
                        font-size: 1.1rem;
                        border-radius: 30px;
                        transition: ease-in .3s;
                    }
                    a:hover{
                        background-color:#0B6F83;
                        box-shadow: inset 0px 0px 10px 0px rgba(#0707072a, 0.8);
                        margin-left: 5px;
                        margin-right: 5px;
                    }
                }
            }
            ul:hover{
                
                background-color: #0707072a;
                box-shadow: inset 0px 0px 1px 0px rgba(#0707072a, 0.8)
            }
        }

    }}

//VERSION MOBILE

    section {
        width: 100%;
        height: 16vh;
        display: flex;
        border-bottom: 0.5px solid rgba($color: #46C2D8, $alpha: 0.1);
        padding: 0% 10%;
        flex: row;
        justify-content: space-between;
        align-items: center;
       

        .brand {
            width: 100%;
            height: 100%;
            

            img {
                width: 150px;
                height: 100%;
                object-fit: contain;
                opacity: .8;
                transition: 0.4s ease-in;
                filter: brightness(100%);
                filter:grayscale(1)
                
            }
            
            img:hover {
                opacity: 1;
                filter: brightness(140%);
                width: 160px;
            }
        }



        nav {
            width: 70%;
            height: 45px;
            margin: 0;
            padding: 0;
            ul{
                width: auto;
                height: 40px;
                border-radius: 40px;
                margin: 0;
            padding: 0;
            }

            .container-items {
                margin: 0;
                padding: 0;
                width: auto;
                height: inherit;
                display: flex;
                flex-direction: row;
                justify-content: center;
                align-items: center;

                li {
                    list-style: none;

                    a {
                        height: 38px;
                        margin: 0;
                        text-decoration: none;
                        padding: 10px;
                        color: white;
                        letter-spacing: 1px;
                        font-size: 1.1rem;
                        border-radius: 30px;
                        transition: ease-in .3s;
                    }
                    a:hover{
                        background-color:#0B6F83;
                        box-shadow: inset 0px 0px 10px 0px rgba(#0707072a, 0.8);
                        margin-left: 5px;
                        margin-right: 5px;
                    }
                }
            }
            ul:hover{
                
                background-color: #0707072a;
                box-shadow: inset 0px 0px 1px 0px rgba(#0707072a, 0.8)
            }
        }

    }
</style>