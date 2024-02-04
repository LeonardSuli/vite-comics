<script>
export default{
  name: 'AppFooter',
}
</script>



<template>

    <footer>
       
      <div class="footer_top">
        
        <div class="container d-flex">

            <div class="row">

              <div class="col">

                <h4>DC COMICS</h4>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Comics</a></li>
                  <li><a href="#">Movies</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">Games</a></li>
                  <li><a href="#">Videos</a></li>
                  <li><a href="#">News</a></li>
                </ul>

                <h4>SHOP</h4>
                <ul>
                  <li><a href="#">Shop DC</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                </ul>

              </div>

              <div class="col">

                <h4>DC</h4>
                <ul>
                  <li><a href="#">Terms Of Use</a></li>
                  <li><a href="#">Privacy policy (New)</a></li>
                  <li><a href="#">Ad Choices</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshops</a></li>
                  <li><a href="#">CPSC Certificates</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Us</a></li>
                </ul>

              </div>

              <div class="col">

                <h4>SITES</h4>
                <ul>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power Visa</a></li>
                </ul>

              </div>

            </div>

        </div>
        
      </div>

      <div class="footer_bottom">

        <div class="container d-flex">
          
          <button class="sign_up">SIGN-UP NOW!</button>
          
          <div class="social">

            <span>FOLLOW US</span>
            <img src="/img/footer-facebook.png" alt="">
            <img src="/img/footer-twitter.png" alt="">
            <img src="/img/footer-youtube.png" alt="">
            <img src="/img/footer-pinterest.png" alt="">
            <img src="/img/footer-periscope.png" alt="">

          </div>

        </div>

      </div>

    </footer>

</template>


<style scoped>

footer{
  background-image: url('/img/footer-bg.jpg');
  background-size: 100%;
}

.footer_top .container{
  justify-content: space-between;
  background-image: url('/img/dc-logo-bg.png');
  background-repeat: no-repeat;
  background-position: right;
  background-size: 500px;
}

.footer_top col{
  padding-bottom: 2rem;
}

.footer_top h4{
  color: var(--dc-light);
  padding: 0.75rem 0;
}

.footer_top ul{
  padding-bottom: 1rem;
}

.footer_top li a{
  color: var(--dc-gray);
  font-size: 9px;
}

.footer_bottom{
  background-color: var(--dc-secondary);
}

.footer_bottom .container{
  justify-content: space-between;
}

.sign_up{
  color: var(--dc-light);
  font-weight: 600;
  border: 2px solid var(--dc-primary);
  background-color: var(--dc-secondary);
  padding: 0.75rem;
  margin: 1.5rem 0;
}

.social{
  display: flex;
  align-items: center;
  gap: 1rem;
}

.social span{
  color: var(--dc-primary);
  font-weight: 700;
}

.social img{
  width: 30px;
}

</style>