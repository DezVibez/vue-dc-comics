<template>

  <div id="products">

    <div class="productsJumbo">

    </div>

    <div class="container">
  
        <div v-for="(card, index) in cards" :key="index" class="card">
          <img :src="card.thumb"/>
          <h6>{{ card.series }}</h6>
        </div>
        
    </div>
  </div>

</template>

<script>
export default {
  name: 'MyProducts',
  props:{
    cards: Array
  }
  
  
  }

</script>

<style lang="scss" scoped >

#products {
    padding: 20px;
    height: auto;
    background-color: rgb(28,28,28);
  }

  #products .container {
    width: 70%;
    height: auto;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
  }

  #products .container .card {
    color: white;
    width: calc(100% / 6);
    height: auto;
    padding: 10px
  }

  .card img {
    width: 95%;
    height: auto;
  }

  .card h4 {
    font-size: 16px;
    display: inline-block;
    width: 90%
  }

  .productsJumbo {
    width: 100%;
    height: 300px
  }
 

</style>

