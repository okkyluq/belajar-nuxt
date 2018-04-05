<template>
	<nav class="navbar is-transparent">
		<div class="navbar-brand">
			<nuxt-link class="navbar-item" to="/">
				<img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
			</nuxt-link>
			<div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
				<span></span>
				<span></span>
				<span></span>
			</div>
		</div>

		<div id="navbarExampleTransparentExample" class="navbar-menu">
			<div class="navbar-start">
				<nuxt-link to="/" class="navbar-item">Home</nuxt-link>
				<nuxt-link to="/blog" class="navbar-item">Blog</nuxt-link>
				<div class="navbar-item has-dropdown is-hoverable">
					<a class="navbar-link" href="/documentation/overview/start/">
					Docs
					</a>
					<div class="navbar-dropdown is-boxed">
						<a class="navbar-item" href="/documentation/overview/start/"> Overview </a>
						<a class="navbar-item" href="https://bulma.io/documentation/modifiers/syntax/"> Modifiers </a>
						<a class="navbar-item" href="https://bulma.io/documentation/columns/basics/"> Columns </a>
						<a class="navbar-item" href="https://bulma.io/documentation/layout/container/"> Layout </a>
						<a class="navbar-item" href="https://bulma.io/documentation/form/general/"> Form </a>
					</div>
				</div>
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