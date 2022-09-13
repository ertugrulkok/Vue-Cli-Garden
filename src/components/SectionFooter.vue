<template>
  <section>
    <div class="container">
      <div class="footer-wrapper">
        <div class="footer-left">
          <img class="footer-logo" src="@/assets/logo-black.svg" alt="" />
          <p class="footer-text">
            2021 Award winning Gardening and Lorem ipsum dolor sit amet
          </p>
          <div class="footer-social-media">
            <img src="@/assets/facebook.png" alt="" />
            <img src="@/assets/twitter.png" alt="" />
            <img src="@/assets/instagram.png" alt="" />
          </div>
        </div>
        <div class="footer-right">
          <div class="footer-menu-list">
            <p class="footer-menu-title">Location</p>
            <ul>
              <li><a href="#">America</a></li>
              <li><a href="#">Asia</a></li>
              <li><a href="#">Europe</a></li>
              <li><a href="#">Africa</a></li>
            </ul>
          </div>
          <div class="footer-menu-list">
            <p class="footer-menu-title">Contact</p>
            <ul>
              <li><a href="#">About Me</a></li>
              <li><a href="#">Teams</a></li>
              <li><a href="#">Profile</a></li>
              <li><a href="#">FAQ</a></li>
            </ul>
          </div>
          <div class="footer-menu-list">
            <p class="footer-menu-title">Legals</p>
            <ul>
              <li><a href="#">Privacy</a></li>
              <li><a href="#">Disclaimer</a></li>
              <li><a href="#">Terms</a></li>
              <li><a href="#">Company</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-wrapper {
  display: flex;
  justify-content: space-between;
}
.footer-logo {
  width: 220px;
  margin-bottom: 1rem;
}
.footer-text {
  max-width: 320px;
  margin-bottom: 1rem;
  font-weight: 400;
  font-size: 20px;
  line-height: 180%;
}

.footer-social-media {
  display: flex;
  max-width: 220px;
  justify-content: space-between;
}

.footer-right {
  display: flex;
  gap: 150px;
}

.footer-menu-title {
  font-weight: 700;
  margin-bottom: 0.5rem;
}

.footer-menu-list ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.footer-menu-list ul li {
  padding: 0.6rem 0;
}

.footer-menu-list ul li a {
  font-weight: 400;
  font-size: 18px;
  line-height: 32px;
  text-decoration: none;
  color: #70737c;
}
</style>
