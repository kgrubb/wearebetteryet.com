<template>
  <section class="hero is-black is-fullheight">
    <div class="hero-body has-bg-img">
      <div class="container has-text-centered">
        <!-- <p class="title has-text-light">
          Better Yet
        </p> -->
        <b-image
          :src="require('@/assets/bandname.png')"
          alt="Better Yet"
          style="max-width: 300px;"
        />
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <div class="has-text-centered">
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://twitter.com/wearebetteryet"
            class="has-text-light"
          >
            <span class="icon is-large">
              <i class="fab fa-lg fa-twitter" />
            </span>
          </a>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://www.facebook.com/BetterYetBand/"
            class="has-text-light"
          >
            <span class="icon is-large">
              <i class="fab fa-lg fa-facebook" />
            </span>
          </a>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://www.instagram.com/betteryetband/"
            class="has-text-light"
          >
            <span class="icon is-large">
              <i class="fab fa-lg fa-instagram" />
            </span>
          </a>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://music.apple.com/us/artist/better-yet/1551358546"
            class="has-text-light"
          >
            <span class="icon is-large">
              <i class="fab fa-lg fa-apple" />
            </span>
          </a><a
            target="_blank"
            rel="noopener noreferrer"
            href="https://open.spotify.com/artist/58DQU2SUmJj5FzzbxLHSke"
            class="has-text-light"
          >
            <span class="icon is-large">
              <i class="fab fa-lg fa-spotify" />
            </span>
          </a>
        </div>
      </div>
    </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped>
.has-bg-img {
  background: url("../assets/betteryet.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
}
</style>
