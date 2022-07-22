<template>
  <div id="header">
    <div class="container">
      <img src="../assets/img/dc-logo.png" alt="">

      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li> 
      </ul>
      </div>
    
  </div>
</template>

<script>
export default {
  name: 'MyHeader',}
</script>

<style lang="scss">



#header {
    margin-top: 75px;
    padding: 14px 0;
    background-color: white;
    
    }

  #header .container {
  max-width: 70%;
  height: auto;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

  #header .container img { 
    width: 4.5rem;
  }

  #header ul { 
    display: flex;
  }

  #header li { 
    display: flex;
    margin: 0 10px;
    font-size: 12px;
    font-weight: bold;
  }
</style>


