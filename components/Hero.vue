<template>
  <section class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="card">
          <div class="card-image">
            <figure class="image is-16by9">
              <p class="text">
                Better Yet
              </p>
              <img
                src="@/assets/betteryet.jpg"
                alt="Better Yet"
              >
            </figure>
          </div>
        </div>
        <Linkbar />
      </div>
    </div>
  </section>
</template>

<script>
import Linkbar from './Linkbar.vue';

export default {
  name: 'Hero',
  components: {
    Linkbar,
  },
};
</script>

<style scoped>
.has-bg-img {
  background: url("../assets/betteryet.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}

.text {
  z-index: 100;
  position: absolute;
  color: rgb(199, 199, 199);
  font-size: 300%;
  left: 5%;
  top: 1%;
}
</style>
