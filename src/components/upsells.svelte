<script>
	import TickSquare from 'iconsax-svelte/TickSquare.svelte';
</script>

<section class="lg:px-48 md:px-20 px-5 my-10">
	<div class="grid md:grid-cols-2 md:space-y-0 space-y-5 text-sm items-center">
		<div class="md:order-first order-last">
			<img src="/upsells.png" alt="" />
		</div>
		<div class="space-y-3">
			<h4 class="tracking-widest uppercase text-primary-500 text-sm">UPSELLS & ADD-ONS</h4>
			<p class="capitalize font-red lg:text-4xl text-3xl font-extrabold text-secondary">
				Double your sales by maximizing every order
			</p>
			<p class="text-secondary">
				Pick a template. Customize it with ease. Then publish. You’ll be ready to start accepting
				orders in minutes.
			</p>
			<div class="space-y-2">
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">Order Bumps</p>
				</div>
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">1-Click Upgrades</p>
				</div>
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">1-Click Upsells</p>
				</div>
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">Automated Cart Recovery</p>
				</div>
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">Automated Subscription Recovery</p>
				</div>
				<div class="flex items-center space-x-1">
					<TickSquare size="24" color="#C5A059" variant="Bold" />
					<p class="text-secondary">Easy A/B Testing</p>
				</div>
			</div>
		</div>
	</div>
</section>
