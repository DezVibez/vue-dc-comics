<template>
  <div id="footer" >
    <div class="container">
      <div>
        <ul>
          <li><H4>DC COMICS</H4></li>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>

        <ul>
          <li><H4>SHOP</H4></li>
          <li>SHOP DC</li>
          <li>SHOP DC COLLECTIBLES</li>
          
        </ul>
        
      </div>

      <div class="big-logo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>

    </div>
    
  </div>
</template>

<script>
export default {
  name: 'MyFooter',}
</script>

<style lang="scss" scoped>

#footer {
    
    height: 270px;
    background-color: white;
    background-image: url(../assets/img/footer-bg.jpg);
}

#footer .container {
    padding: 10px 0;
    width: 70%;
    height: auto;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
  }

#footer ul {
  font-size: 12px;
  color: rgb(77,77,77);
  font-weight: 300;
}

#footer h4{
  color: white;
  margin-bottom: 10px
}

#footer .big-logo{
  height: 80%;
  width: auto;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-size: cover;
  background-position-y: 10%;
}



</style>