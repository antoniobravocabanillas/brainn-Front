<template>

    <div class="container">
      <NavBar />
      <SlideFullSize />
    </div>

</template>
<script lang="ts" setup>
  import NavBar from './components/NavBar.vue';
  import SlideFullSize from './components/SlideFullSize.vue';
</script>
<style lang="scss">


@media screen and (max-width: 567px) {
  body{
    margin: 0;
    padding: 0;
    background-color: #141414;
    color: white;
    max-width: 100vw;
    overflow: hidden;
    cursor: url('../src/assets/img/Handwriting.cur'),auto;
  }
  
}

  
  body{
    margin: 0;
    padding: 0;
    background-color: #141414;
    color: white;
    max-width: 100vw;
    overflow: hidden;
    cursor: url('../src/assets/img/Handwriting.cur'),auto;
  }

  //General font size
  h1 {
    font-size: 3rem;
    font-family: 'Quicksand', sans-serif;
  }

  h2 {
    font-size: 2.5rem;
    font-family: 'Pathway Extreme', sans-serif;
    font-weight: 200;
    letter-spacing: 1px;
  }

  h3 {
    font-size: 2.5rem;
    font-family: 'Pathway Extreme', sans-serif;
    font-weight: 200;
    letter-spacing: 1px;
  }

  p {
    font-family: 'Red Hat Mono', monospace;
    font-weight: 300;
    font-size: 1.1rem;
  }

  a {
    font-family: 'Quicksand', sans-serif;
    font-weight: 300;
  }

  button {
    font-family: 'Pathway Extreme', sans-serif;
    transition: ease-in .4s;
    background-color: #0B6F83;
    color: white;
    font-weight: 200;
  }
  button:hover {
    background-color: #46C2D8;
    color: #fff;
    margin-left: 5px;
    cursor: pointer;
    
  }

  .btn-big {
    font-size: 1rem;
  }
</style>