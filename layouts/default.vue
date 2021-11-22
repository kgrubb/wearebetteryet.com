<template>
  <Nuxt />
</template>
<style lang="scss">
// Import Bulma's core
@import "bulma/sass/utilities/_all";
// Set your colors
$primary: #3e495c;
$light-invert: findcolorinvert($light);
$primary-invert: findcolorinvert($primary);
$darkish: #4a4a4a;
$darkish-invert: findcolorinvert($darkish);
$control-border-width: 0.125em;
$card-radius: 0.25rem;
$card-color: #000;
// Setup $colors to use as bulma classes (e.g. 'is-light-blue')
$colors: (
  "white": (
    $white,
    $black
  ),
  "black": (
    $black,
    $white
  ),
  "light": (
    $light,
    $light-invert
  ),
  "dark": (
    $dark,
    $dark-invert
  ),
  "darkish": (
    $darkish,
    $darkish-invert
  ),
  "primary": (
    $primary,
    $primary-invert
  ),
  "info": (
    $info,
    $info-invert
  ),
  "success": (
    $success,
    $success-invert
  ),
  "warning": (
    $warning,
    $warning-invert
  ),
  "danger": (
    $danger,
    $danger-invert
  ),
);
// Links
$link: $primary;
$link-invert: $primary-invert;
$link-focus-border: $primary;
// Import Bulma
@import "bulma/bulma.sass";
@import "@fortawesome/fontawesome-free/css/all.css";

html {
  scroll-behavior: smooth;
  overflow: hidden;
}

::-webkit-scrollbar {
  display: none;
}

.navbar {
  &.is-transparent {
    background-color: transparent;
    background-image: none;
  }
}
</style>
