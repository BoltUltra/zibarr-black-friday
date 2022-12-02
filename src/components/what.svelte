<script>
	import Sell from './Sell.svelte';
</script>

<section class="px-5 my-10 space-y-5 text-center __what">
	<p class="font-bold text-sm ">WHAT IS ZIBARR?</p>
	<h3 class="font-red font-extrabold text-3xl">
		An All Inclusive eCommerce Platform That Helps You Sell Without Marketing
	</h3>
	<p class="text-sm">
		If you’re selling digital products online, you need more than a pretty way to deliver your
		content. You need an easy way to boost conversions, maximize customer value, and run your
		business without worrying about technology. That’s why we built Zibarr.
	</p>
	<div>
		<iframe
			class="w-full rounded-md lg:h-96 h-48"
			src="https://www.youtube.com/embed/4NemRIHV_ew"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
			allowfullscreen
		/>
	</div>

	<Sell />
</section>
