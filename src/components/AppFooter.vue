<script></script>

<template>
  <div class="footer">
    <div
      class="sub-footer container d-flex justify-content-between align-items-center p-3"
    >
      <button class="btn">SIGN-UP NOW!</button>
      <div class="follow d-flex justify-content-end">
        <ul class="d-flex justify-items-end align-items-center">
          <li>FOLLOW US</li>
          <li><img src="../assets/img/footer-facebook.png" alt="fb" /></li>
          <li>
            <img src="../assets/img/footer-twitter.png" alt="Twitter" />
          </li>
          <li>
            <img src="../assets/img/footer-youtube.png" alt="Youtube" />
          </li>
          <li>
            <img src="../assets/img/footer-pinterest.png" alt="Pinterest" />
          </li>
          <li>
            <img src="../assets/img/footer-periscope.png" alt="Periscope" />
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" update>
@use "./../assets/styles/partials/variables" as *;
.footer {
  height: 95px;
  background-color: $bg-footer;
  .btn {
    color: white;
    border: 2px solid $blue-comics;
    padding: 0.5rem;
  }
}
.sub-footer {
  height: 100%;
  .follow {
    width: 40%;

    ul {
      padding-top: 1.5rem;
      color: $blue-comics;
      font-weight: 800;
      list-style: none;
    }

    li {
      padding-right: 1rem;
    }
  }
}
</style>
