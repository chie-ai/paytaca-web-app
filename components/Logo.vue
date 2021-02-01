<template>
  <img v-if="logo" src="paytaca_dark_mode.svg" class="NuxtLogo" width="150">
  <img v-else src="paytaca.svg" class="NuxtLogo" width="150">

</template>

<script>
  export default {
    props: ['logo']
  }
</script>

<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
  transition: .3s !important;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
