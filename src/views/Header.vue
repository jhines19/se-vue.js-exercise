<template>
  <section class="hero is-info is-small">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <span class="navbar-burger burger" data-target="navbarMenuHeroA">
              <span></span>
              <span></span>
            </span>
          </div>
          <div id="navbarMenuHeroA" class="navbar-menu">
            <div class="navbar-end has-text-black">
              <a class="navbar-item">
              <router-link to="/">
                  Home
              </router-link>
              </a>
              <a class="navbar-item">
              <router-link to="about">
                  About
              </router-link>
              </a>
            </div>
          </div>
      </div>
    </nav>
  </div>
  <div class="hero-body">
      <div class="container has-text-left">
          <p class="title has-text-black">
              <router-link to="/">
                <a>
                  <img class="banner-image" src="../assets/images/love-park-logo.png">
                </a>
              </router-link>
              Spring into LOVE
          </p>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Header',
  }
</script>

<style scoped>

  .banner-image {
    height: 220px;
  }

  .container {
    padding-bottom: 25px;
  }
</style>