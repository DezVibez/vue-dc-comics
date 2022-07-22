<template>
  <div>
    <body>
      <MyHeader/>
      <MyProducts/>
      <MyMain/>
      <MyFooter/>
      <MyFollow/>
    </body>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Products from './components/Products.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Follow from './components/Follow.vue'


export default {
  name: 'App',
  components: {
    MyHeader: Header,
    MyProducts: Products,
    MyMain: Main,
    MyFooter: Footer,
    MyFollow: Follow,
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

ul{
  list-style-type: none;
}

body {
  max-height: 100vh;
  background-color: black;
  font-family:'Open Sans', sans-serif;;
}
</style>


