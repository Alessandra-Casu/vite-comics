<script></script>
<template>
  <div class="blue-row">
    <ul class="headBox">
      <li>
        <div class="box">
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt="digital-comic"
          />
          <a href="#"> DIGITAL COMICS</a>
        </div>
      </li>
      <li>
        <div class="box">
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="merchandise-comic"
          />
          <a href="#"> DC MERCHANDISE</a>
        </div>
      </li>
      <li>
        <div class="box">
          <img
            src="../assets/img/buy-comics-shop-locator.png"
            alt="shop-locator"
          />
          <a href="#"> COMIC SHOP LOCATOR</a>
        </div>
      </li>
      <li>
        <div class="box">
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="subscriptions"
          />
          <a href="#"> DC POWER VISA</a>
        </div>
      </li>
    </ul>
  </div>
</template>

<style lang="scss" update>
@use "./../assets/styles/partials/variables" as *;

.blue-row {
  height: 110px;
  background-color: $blue-comics;
  color: white;
  ul {
    display: flex;
    list-style: none;
    justify-content: space-between;
  }
  a {
    color: white;
    text-decoration: none;
  }
}

.box {
  img {
    height: 50px;
  }
}
</style>
