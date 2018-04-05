<template>
	<nav class="navbar is-warning">
		<div class="navbar-brand">
			<nuxt-link class="navbar-item" to="/">
				<img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
			</nuxt-link>
			<div class="navbar-burger burger" data-target="navbarExampleTransparentExample" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');">
				<span></span>
				<span></span>
				<span></span>
			</div>
		</div>

		<div id="navbarExampleTransparentExample" class="navbar-menu">
			<div class="navbar-start">
				<nuxt-link to="/" class="navbar-item">Home</nuxt-link>
				<nuxt-link to="/blog" class="navbar-item">Blog</nuxt-link>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
  name: 'NavBar',

  data () {
    return {

    }
  }
}
</script>

<style lang="css" scoped>
/*.nuxt-link-exact-active .nuxt-link-active {
	background-color: #00d1b2;
	color: white;
}*/
</style>
