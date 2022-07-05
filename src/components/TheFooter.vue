<template>
  <div class="myFooter position-relative">
    <div class="bgFooter"><img src="/img/footer-background-scaled.jpg" alt=""></div>
    <div class="position-relative">
      <div class="container myContainer">
        <div class="d-flex justify-content-between mb-4">
          <!-- ORDER ONLINE -->
          <div class="">
            <ul class="list-unstyled myList">
              <h6 class="text-white mb-3">ORDER ONLINE</h6>
              <li>
                <a href="#">Appetizers</a>
              </li>
              <li>
                <a href="#">Burgers</a> 
              </li>
              <li>
                <a href="#">Pizza</a>
              </li>
              <li>
                <a href="#">Fries</a> 
              </li>
              <li>
                <a href="#">Sides</a>
              </li>
              <li>
                <a href="#">Desserts</a>
              </li>
              <li>
                <a href="#">Beverages</a>
              </li>
              <li>
                <a href="#">Specials</a>
              </li>
            </ul>
          </div>
          <!-- NAVIGATE -->
          <div class="">
            <ul class="list-unstyled myList">
              <h6 class="text-white mb-3">NAVIGATE</h6>
              <li>
                <a class="primaryColor" href="#">Home</a>
              </li>
              <li>
                <a href="#">Alternate Home</a>
              </li>
              <li>
                <a href="#">Menu</a>
              </li>
              <li>
                <a href="#">About</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
              <li>
                <a href="#">Contact Us</a>
              </li>
              <li>
                <a href="#">Cart</a>
              </li>
            </ul>
          </div>
          <!-- INFORMATION -->
          <div>
            <ul class="list-unstyled myList thirdList">
              <h6 class="text-white mb-3">INFORMATION</h6>
              <li>
                <a href="#">My Account</a>
              </li>
              <li>
                <a href="#">Terms Of Service</a>
              </li>
              <li class="mb-3">
                <a href="#">Privacy Policy</a>
              </li>
              <li>
                <a href="#">
                  <img class="mb-2" src="/img/app-store-badge-200x67.png" alt="">
                </a>
              </li>
              <li>
                <a href="#">
                  <img src="/img/play-store-badge-200x67.png" alt="">
                </a>
              </li>
            </ul>
          </div>
          <!-- OPENING HOURS -->
          <div class="openingList">
            <h6 class="text-white">OPENING HOURS</h6>
            <ul class="list-unstyled">
              <li>
                  Mon - <span class="primaryColor">10AM to 11PM</span>
              </li>
              <li>
                  Tue - <span class="primaryColor">10AM to 11PM</span>
              </li>
              <li>
                  Wed - <span class="primaryColor">10AM to 11PM</span>
              </li>
              <li>
                  Thur - <span class="primaryColor">10AM to 11PM</span>
              </li>
              <li>
                  Fri - <span class="primaryColor">10AM to 11PM</span>
              </li>
              <li>
                  Sat - <span class="primaryColor">10AM to 1AM</span>
              </li>
              <li>
                  Sun - <span class="primaryColor">11AM to 10PM</span>
              </li>
            </ul>
          </div>
          <!-- VOUCHER -->
          <div>
            <h6 class="text-white text-center">VOUCHER</h6>
            <img class="coupon" src="/img/footer-coupon-200x200.png" alt="">
            <div class="text-center orderText">
              <p class="text-white mb-0">Just Use The Code</p>
              <h5 class="primaryColor mb-0">FIRSTORDER</h5>
              <p class="text-white">At Checkout</p>
            </div>
          </div>
        </div>

        <!-- STAY IN THE LOOP -->
        <div class="d-flex justify-content-center pt-3">
          <div class="text-center myForm">
            <img class="pb-4" src="/img/takeout-logo-mobile.png" alt="">
            <p class="primaryColor mt-2 fs-1 fw-bold mb-2">Stay In The Loop</p>
            <small class="text-white">Sign up receive up to date news and offers directly in your inbox:</small>
            <input class="d-block form-control m-auto rounded-pill my-4" type="text" placeholder="you@email.com">
            <button type="button" class="btn btn-danger myButton rounded-pill mt-2 mb-5">SUBSCRIBE</button>
            <div class="d-flex justify-content-center mt-2 mb-4">
              <div class="d-flex text-white gap-3">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-linkedin-in"></i>
                <i class="fa-solid fa-rss"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-regular fa-envelope"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="text-center mt-3">
          <small class="copyright">
              <span class="primaryColor">
                © Copryright 2012 - 2020 | Avada Theme by
              </span>
              <span class="text-white">
                Theme Fusion
              </span>
              <span class="primaryColor">
                | All Rights Reserved | Powered By
              </span>
              <span class="text-white">
                WordPress
              </span>
            </small>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    
  }
}
</script>

<style lang="scss" scoped>
    .myFooter{
      min-height: 100%;
    }
    .bgFooter{
      position: absolute;
      top: 0;
      bottom: 0;
      left: 0;
      right: 0
    }
    .bgFooter img{
      width: 100%;
    }
    .myList li{
      font-size: 13px;
      font-weight: 700;
      line-height: 40px;
    }
    h6{
      font-size: 14px;
      font-weight: 700;
    }
    a{
      color: white;
      text-decoration: none;
    }
    .primaryColor{
      color: rgb(252, 220, 49);
    }
    .thirdList img{
      width: 140px;
      border: 1px solid white;
      border-radius: 8px;
    }
    .openingList li{
      font-size: 14px;
      font-weight: 700;
      color: white;
      line-height: 24px;
    }
    .openingList h6{
      margin-bottom: 42px;
    }
    .coupon{
      transform: scale(0.7);
      margin-top: -21px;
    }
    .orderText p{
      font-size: 15px;
      font-weight: 700;
    }
    .orderText h5{
      font-weight: 700;
    }
    .orderText{
      margin-top: -18px;
    }
    .myContainer{
      padding-top: 120px;
    }
    .myForm{
      width: 630px;
    }
    .myButton{
    --bs-btn-color: #fff;
    --bs-btn-bg: #ce1a26;
    --bs-btn-border-color: #dc3545;
    --bs-btn-hover-color: #fff;
    --bs-btn-hover-bg: #bb2d3b;
    --bs-btn-hover-border-color: #b02a37;
    --bs-btn-focus-shadow-rgb: 225,83,97;
    --bs-btn-active-color: #fff;
    --bs-btn-active-bg: #b02a37;
    --bs-btn-active-border-color: #a52834;
    --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
    --bs-btn-disabled-color: #fff;
    --bs-btn-disabled-bg: #dc3545;
    --bs-btn-disabled-border-color: #dc3545;
    font-size: 12px;
    font-weight: 700;
    padding: 0.4rem 1.4rem;
    width: 630px;
    height: 38px;
    }
    .copyright{
      font-size: 11px;
      font-weight: 700;
    }
</style>