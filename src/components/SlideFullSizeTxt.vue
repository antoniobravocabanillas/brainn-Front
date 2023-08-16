<template>
    <div class="container-txt">
        <div class="tittle">
            <h2>Full Stack Java</h2>
            <h1>Software Developer</h1>
        </div>
        <p>Hi! I'm Antonio Bravo. I am 28 years old and I live in Buenos Aires. Currently, I am studying to become an
            Informatics Engineer. In the future, I aspire to work as a Computer Software Developer.</p>
        <div class="button-slide">
            <BtnSlide />
        </div>
    </div>
</template>

<script lang="ts" setup>
    import BtnSlide from './BtnSlide.vue';
</script>

<style lang="scss" scoped>
    .container-txt {
        margin: auto;
        width: 80%;
        height: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;

        h1 {
            margin: 0;
            padding: 0;
        }

        h2 {
            margin: 0;
            padding: 0;
        }

        p {
            margin: 0;
            margin-top: 20px;
            margin-bottom: 50px;
            padding: 0;

        }
    }
</style>