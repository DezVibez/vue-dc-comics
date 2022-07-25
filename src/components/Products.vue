<template>

  <div id="products">
    <div class="container">
  
        <div v-for="(card, index) in cards" :key="index" class="cards">
          <img :src="card.thumb" />
          <h3>{{ card.series }}</h3>
        </div>
        


    </div>
  </div>

</template>

<script>
export default {
  name: 'MyProducts',}
</script>

<style lang="scss">

#products {
    height: 90px;
    background-color: rgb(28,28,28);
  }

  #products .container {
    max-width: 70%;
    height: auto;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  #products .container .cards {
    padding: 10px;
    width: 100px;
    height: 100px;
  }

</style>

