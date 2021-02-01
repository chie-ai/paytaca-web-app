<template>
  <img :src="[ logo ? 'paytaca_dark_mode.svg' : 'paytaca.svg']" class="NuxtLogo" width="150">

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
  transition: all .5s !important;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
