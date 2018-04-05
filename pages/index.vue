<template>
   <section>
   		<my-hero :title="'Halaman Home'" :subtitle="'Selamat Datang'"></my-hero>
   		<div class="columns">
    		<div class="column is-10">
				<div class="box content">
					<article class="post">
						<h4>Bulma: How do you center a button in a box?</h4>
						<div class="media">
							<div class="media-left">
								<p class="image is-32x32">
									<img src="http://bulma.io/images/placeholders/128x128.png">
								</p>
							</div>
							<div class="media-content">
								<div class="content">
									<p>
										<a href="#">@jsmith</a> replied 34 minutes ago  &nbsp; 
										<span class="tag">Question</span>
									</p>
								</div>
							</div>
							<div class="media-right">
								<span class="has-text-grey-light"><i class="fa fa-comments"></i> 1</span>
							</div>
						</div>
					</article>
				</div>
				<div class="box content">
					<article class="post">
						<h4>Bulma: How do you center a button in a box?</h4>
						<div class="media">
							<div class="media-left">
								<p class="image is-32x32">
									<img src="http://bulma.io/images/placeholders/128x128.png">
								</p>
							</div>
							<div class="media-content">
								<div class="content">
									<p>
										<a href="#">@jsmith</a> replied 34 minutes ago  &nbsp; 
										<span class="tag">Question</span>
									</p>
								</div>
							</div>
							<div class="media-right">
								<span class="has-text-grey-light"><i class="fa fa-comments"></i> 1</span>
							</div>
						</div>
					</article>
				</div>
				<div class="box content">
					<article class="post">
						<h4>Bulma: How do you center a button in a box?</h4>
						<div class="media">
							<div class="media-left">
								<p class="image is-32x32">
									<img src="http://bulma.io/images/placeholders/128x128.png">
								</p>
							</div>
							<div class="media-content">
								<div class="content">
									<p>
										<a href="#">@jsmith</a> replied 34 minutes ago  &nbsp; 
										<span class="tag">Question</span>
									</p>
								</div>
							</div>
							<div class="media-right">
								<span class="has-text-grey-light"><i class="fa fa-comments"></i> 1</span>
							</div>
						</div>
					</article>
				</div>
				<div class="box content">
					<article class="post">
						<h4>Bulma: How do you center a button in a box?</h4>
						<div class="media">
							<div class="media-left">
								<p class="image is-32x32">
									<img src="http://bulma.io/images/placeholders/128x128.png">
								</p>
							</div>
							<div class="media-content">
								<div class="content">
									<p>
										<a href="#">@jsmith</a> replied 34 minutes ago  &nbsp; 
										<span class="tag">Question</span>
									</p>
								</div>
							</div>
							<div class="media-right">
								<span class="has-text-grey-light"><i class="fa fa-comments"></i> 1</span>
							</div>
						</div>
					</article>
				</div>
    		</div>
    		<div class="column is-2">
				<aside class="menu">
					<p class="menu-label"> General </p>
					<ul class="menu-list">
						<li><a>Dashboard</a></li>
						<li><a>Customers</a></li>
					</ul>
					<p class="menu-label"> Transactions </p>
					<ul class="menu-list">
						<li><a>Payments</a></li>
						<li><a>Transfers</a></li>
						<li><a>Balance</a></li>
					</ul>
				</aside>
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
			title : 'Home Nuxt Js'
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
</style>
