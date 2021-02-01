<template>
  <div>
    <Navbar v-on:changeMode="changeMode"/>
    <Home v-bind:darkMode="darkMode"/>
  </div>
</template>

<script>
export default {
	data () {
		return {
			darkMode: false
		}
	},
	methods: {
		changeMode(mode) {
			this.darkMode = mode
		}
	}
}
</script>

<style>

</style>
