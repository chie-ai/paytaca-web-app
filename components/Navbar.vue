<template>
	<nav class="navbar navbar-expand-lg navbar-light py-4 navbar-content" id="navbar">
		<div class="container-fluid mx-5-md mx-1 mx-md-5">
		    <NuxtLink to="/" class="navbar-brand"><Logo v-bind:logo="darkMode" /></NuxtLink>
		    <button class="navbar-toggler btn-navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		      	<i class="fas fa-bars" :class="{ 'navbar-icon-toggler': darkMode }"></i>
		    </button>
		    <div class="collapse navbar-collapse" id="navbarSupportedContent">
		      	<ul class="navbar-nav ms-auto mb-2 mb-lg-0">
			        <li class="nav-item">
			          	<a class="nav-link" @click="changePageMode" aria-current="page" :class="{ 'navbar-night-mode': darkMode }" href="#">
			          		<i class="far" :class="[ darkMode ? 'fa-sun' : 'fa-moon' ]"></i>
			          	</a>
			        </li>
			        <li class="nav-item">
			          	<a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#">Home</a>
			        </li>
			        <li class="nav-item">
			          	<a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#features">Features</a>
			        </li>
			        <li class="nav-item">
				        <a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#ecosystem">Ecosystem</a>
			        </li>
			        <li class="nav-item">
				        <a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#faq">FAQ</a>
			        </li>
			        <li class="nav-item">
				        <a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#team">Team</a>
			        </li>
			        <li class="nav-item">
				        <a class="nav-link fw-bolder" :class="{ 'navbar-night-mode': darkMode }" href="#contact">Contact</a>
			        </li>
		      	</ul>
		    </div>
		</div>
	</nav>
</template>

<script>

export default {
	data () {
		return {
			darkMode: false,
		}
	},
	methods: {
		changePageMode () {
			this.darkMode = !this.darkMode
			this.$emit('changeMode', this.darkMode)
		}
	}
}
</script>

<style>
	.navbar-content {
		border-top: 12px solid #ed5e59;
	}
</style>