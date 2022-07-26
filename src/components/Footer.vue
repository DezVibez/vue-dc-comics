<template>
  <div id="footer" >
    <div class="container">
      <div class="liste">
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
            <li>Shop Dc</li>
            <li>Shop Dc Collectibles</li>
          </ul>
        </div>

        <div>
            <ul>
            <li><H4>DC</H4></li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>

          
        </div>

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

          
        </div>
        
        
      </div>

      <div class="big-logo">
        
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
    width: 70%;
    height: auto;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
  }

#footer .liste {
  padding: 10px 0;
}

#footer ul {
  font-size: 12px;
  color: rgb(77,77,77);
  font-weight: 300;
  margin: 20px;
}

#footer h4{
  color: white;
  margin-bottom: 10px
}

#footer .big-logo{
  height: 270px;
  width: 50%;
  background-repeat: no-repeat;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-position-y: -6rem;
  background-position-x: 0rem;
  background-size: cover;
}

.liste {
  display: flex;
}



</style>