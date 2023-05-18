<script></script>
<template>
  <div class="blue-row">
    <ul
      class="container contents d-flex justify-content-around align-items-center h-100"
    >
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
      <li></li>
    </ul>
  </div>
</template>

<style lang="scss" update>
@use "./../assets/styles/partials/variables" as *;

.blue-row {
  height: 130px;
  background-color: $blue-comics;
  color: white;
  ul {
    list-style: none;
  }
  a {
    color: white;
    text-decoration: none;
  }
}
.contents {
  width: 80%;
}
.box {
  img {
    height: 50px;
  }
}
</style>
