<template>
  <section class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <b-image
          :src="require('@/assets/bandname.png')"
          alt="Better Yet"
          style="width: 300px;"
          class="is-inline-block"
        />
        <div class="card">
          <div class="card-image">
            <figure class="image is-16by9">
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
</style>
