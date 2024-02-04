<script>
export default{
  name: 'AppIcon'
}
</script>


<template>
  
    <div class="main_bottom">

      <div class="container">
        
        <div class="icons d-flex">

          <div class="icon">
            <img src="/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
          </div>

          <div class="icon">
            <img src="/img/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
          </div>

          <div class="icon">
            <img src="/img/buy-comics-subscriptions.png" alt="">
            <span>SUBSCRIPTIONS</span>
          </div>

          <div class="icon">
            <img src="/img/buy-comics-shop-locator.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
          </div>

          <div class="icon">
            <img src="/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
          </div>

        </div>

      </div>

    </div>

</template>


<style scoped>

.main_bottom{
  background-color: var(--dc-primary);
  color: var(--dc-light);
  padding: 2rem 0;
}

.icons{
  justify-content: space-around;
}

.icon{
  display: flex;
  align-items: center;
}

.icon img{
  width: 35px;
  transition: all 0.25s;
}

.icon span{
  padding-left: 1rem;
  font-size: 10px;
}

.icon:hover img{
  transform: scale(1.5);
}

</style>