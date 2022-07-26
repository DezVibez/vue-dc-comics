<template>
  <div id="main">

    <div class="container">
      <ul>
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>digital comics</span></li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>digital comics</span></li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>digital comics</span></li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>digital comics</span></li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>digital comics</span></li>
      </ul>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'MyMain',}
</script>

<style lang="scss" scoped>

#main {
    padding:14px;
    background-color: rgb(0,130,249);
}

#main img {
  width: 2.5rem;
}

#main ul, #main li{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

#main span{
  color: white;
  font-size: 14px;
  font-weight: 100;
  height: 100%;
  margin-left: 10px
}

#main .container {
    max-width: 70%;
    height: auto;
    margin: 0 auto;
  }
</style>