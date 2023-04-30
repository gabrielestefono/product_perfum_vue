<template>
  <Product></Product>
</template>

<script>
import Product from './components/Product.vue';

export default{
  name: 'App',
  components: {
    Product
  }
}
</script>

<style>
@import url(reset.css);
@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

/* Estilizando todo o body*/ 
body{
    font-family: 'Montserrat', sans-serif;
    background-color: hsl(30, 38%, 92%);
}
@media screen and (min-width: 376px){
    /* Estilizando o body*/
    body{
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
      }
    }
</style>
