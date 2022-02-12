<template>
    <div class="home">
      <Header></Header>
    </div>

    <div class="container content-align is-overlay">
        <figure class="image">
          <img src="../assets/images/love-park-hero.jpeg">
        </figure>
    </div>
      <AboutDetails></AboutDetails>
    <div>

    </div>
</template>

<script>
  import Header from '@/views/Header.vue'
  import aboutDetails from '@/components/about-details.vue'
import AboutDetails from '../components/about-details.vue'

  export default {
    name: 'About',
    components: {
        Header,
        AboutDetails,
    }
  }
</script>

<style scoped>
  .hero.is-info .title {
      color: black;
  }
  .navbar-end {
      color: black;
  }
  .hero.is-info {
      background-color: #b3e8f9;
      color: #fff;
  }
  .top-padding {
      padding-top: 20px;
  }

</style>
