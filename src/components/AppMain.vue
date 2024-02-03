<script>
export default{
  name: 'AppMain'
}
</script>


<template>

    <main>

      <div class="main_top">

        <div class="container">
          Content
        </div>

      </div>
  
      <div class="main_bottom">

        <div class="container">
          
          <div class="cards d-flex">

            <div class="card">
              <img src="/img/buy-comics-digital-comics.png" alt="">
              <span>DIGITAL COMICS</span>
            </div>

            <div class="card">
              <img src="/img/buy-comics-merchandise.png" alt="">
              <span>DC MERCHANDISE</span>
            </div>

            <div class="card">
              <img src="/img/buy-comics-subscriptions.png" alt="">
              <span>SUBSCRIPTIONS</span>
            </div>

            <div class="card">
              <img src="/img/buy-comics-shop-locator.png" alt="">
              <span>COMIC SHOP LOCATOR</span>
            </div>

            <div class="card">
              <img src="/img/buy-dc-power-visa.svg" alt="">
              <span>DC POWER VISA</span>
            </div>

          </div>

        </div>

      </div>

    </main>

</template>


<style scoped>

.main_top{
  background-color: var(--dc-dark);
  color: var(--dc-light);
  padding: 2rem 0;
}

.main_bottom{
  background-color: var(--dc-primary);
  color: var(--dc-light);
  padding: 2rem 0;
}

.cards{
  justify-content: space-around;
}

.card{
  display: flex;
  align-items: center;
}

.card img{
  width: 35px;
}

.card span{
  padding-left: 1rem;
  font-size: 10px;
}

</style>