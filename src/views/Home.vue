<template>
  <div class="home">
    <Header></Header>
  </div>

  <div class="container content-align is-overlay">
    <figure class="image">
      <img src="../assets/images/love-park-hero.jpeg" />
    </figure>
  </div>
  <div class="container content-align">
    <AboutDetails></AboutDetails>
  </div>
  <div class="container is-flex-direction-row">
    <TopAttractions></TopAttractions>
    <TopAttractions></TopAttractions>
  </div>
  <div class="container content-align">
      <Events></Events>
    </div>
</template>

<script>
import Header from "@/views/Header.vue";
import AboutDetails from "../components/about-details.vue";
import TopAttractions from "../components/top-attractions.vue";
import Events from '../components/events.vue'

export default {
  name: "About",
  components: {
    Header,
    AboutDetails,
    TopAttractions,
    Events,
  },
};
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
