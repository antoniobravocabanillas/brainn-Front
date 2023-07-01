<template>
<div class="container">
    <div class="texts">
        <SlideFullSizeTxt />
    </div>
    <div class="img">
        <img src="../assets/img/home/develop.png" alt="">
    </div>

</div>
</template>
<script lang="ts" setup >
import SlideFullSizeTxt from './SlideFullSizeTxt.vue'
</script>

<style lang="scss" scoped>
.container {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 80vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    align-items: center;
    
    .texts {
        display: block;
        width: 100%;
        margin: 0;
        padding: 0;
        height: auto;
       
    }
    .img{
        width: 80%;
        height: 500px;
        margin: auto;
        img{
            width: 80%;
            object-fit: cover;
            aspect-ratio: 4/4;
            mix-blend-mode:color-dodge;
            filter: brightness(90%);
            transition: ease-in 0.4s;
            
        }
        img:hover{
            width: 90%;
            filter: brightness(105%);
        }
        
    }

}
</style>