<template>
	<section>
   		<my-hero :title="'Halaman Blog'" :subtitle="'Selamat Datang'"></my-hero>
   		<div class="columns">
    		<div class="column is-8">
				<div class="box content">
					<div class="post-header has-text-centered">
						<img src="http://placehold.it/900x600">
						<h4 class="title is-4 has-text-left"><a href="#">Some Post</a></h4>
					</div>
					<hr>
					<div class="post-content-short">
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam sodales pulvinar laoreet. Quisque consequat justo velit, at aliquam ex aliquet eu. Nulla facilisi. Vivamus ac nibh congue, faucibus purus sit amet, malesuada est. Mauris fringilla vulputate libero, et interdum purus sollicitudin vel.</p>
						<div class="continue-reading has-text-centered">
						<a class="button is-primary is-outlined">Continue Reading</a>
						</div>
						<div class="post-content-details">
							<div class="is-pulled-left">
								<i>November 28, 2017 by <a>Author</a></i>
							</div>
						</div>
					</div>
				</div>
    		</div>
    		<div class="column is-4">
				<div class="card">
					<div class="card-image">
						<figure class="image is-4by3">
						<img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
						</figure>
					</div>
					<div class="card-content">
						<div class="media">
							<div class="media-left">
								<figure class="image is-48x48">
									<img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
								</figure>
							</div>
							<div class="media-content">
								<h3 class="has-text-danger has-text-weight-bold">John Smith</h3>
								<p class="subtitle is-7">@johnsmith</p>
							</div>
						</div>

						<div class="content">
							Lorem ipsum dolor sit amet, consectetur adipiscing elit.
							Phasellus nec iaculis mauris. <a>@bulmaio</a>.
							<a href="#">#css</a> <a href="#">#responsive</a>
							<br>
							<time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
						</div>
					</div>
				</div>
    		</div>
    	</div>
   </section>
</template>

<script>
import Hero from '@/components/Hero.vue'
export default {
	layout: 'frontend',
	head(){
		return {
			title : 'Blog Nuxt JS'
		}
	},
	components: {
		'my-hero' : Hero
	}
}
</script>

<style scoped>
.columns {
	padding: 30px;
}

.post-content-details {
	padding: 10px;
}
</style>