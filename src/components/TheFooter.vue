<template>
  <div class="myFooter position-relative">
    <div class="bgFooter"><img src="/img/footer-background-scaled.jpg" alt=""></div>
    <div class="position-relative">
      <div class="container myContainer">
        <div class="d-flex justify-content-between">
          <!-- ORDER ONLINE -->
          <div class="">
            <ul class="list-unstyled myList">
              <h6 class="text-white">ORDER ONLINE</h6>
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
              <h6 class="text-white">NAVIGATE</h6>
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
              <h6 class="text-white">INFORMATION</h6>
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
</style>