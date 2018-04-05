<template>
  <div>
  	<my-nav></my-nav>
    <nuxt/>
  </div>
</template>
<script>
import NavBar from '~/components/NavBar.vue'
export default {
	components: {
		'my-nav' : NavBar
	}	
}	
</script>


<style>

</style>
