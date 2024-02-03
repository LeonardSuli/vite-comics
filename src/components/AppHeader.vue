<script>
export default{
  name: 'AppHeader'
}
</script>

<template>

  <header>

    <div class="container">

      <div class="logo">
        <img src="/img/dc-logo.png">
      </div>
  
      <nav>
        <ul class="main_menu">
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#" class="active">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </nav>

    </div>

  </header>

</template>

<style scoped>

header{

}

.container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 0;
}

.logo img{
  width: 60px;
}

.main_menu{
  list-style: none;
  display: flex;
}

.main_menu a{
  text-decoration: none;
  padding: 2.15rem 0.75rem;
  color: var(--dc-secondary);
  font-size: 10px;
  font-weight: 700;
}
.main_menu a.active{
  border-bottom: 5px solid var(--dc-primary);
  color: var(--dc-primary);
}


</style>