<script>
	import { Swiper, SwiperSlide } from 'swiper/svelte';

	// Import Swiper styles
	import 'swiper/css';

	import 'swiper/css/pagination';

	import './swiper.css';

	// import required modules
	import { Pagination } from 'swiper';
	import QuoteUp from 'iconsax-svelte/QuoteUp.svelte';
</script>

<section class="lg:px-80 md:px-40 px-5 testimonial my-10">
	<Swiper pagination={true} modules={[Pagination]} class="mySwiper ">
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="md:text-2xl text-sm lg:font-semibold">
						“Zibarr makes it easier to be an entrepreneur. It’s Technology that levels that playing
						field so anyone can access tools they need to get started--without a lot of upfront
						investment or experience.”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Kenny Nwokoye</span>
			</div>
		</SwiperSlide>
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="md:text-2xl text-sm lg:font-semibold">
						“Zibarr doubled my conversions instantly. And now being able to easily do subscriptions
						+ recurring membership, our lifetime value is skyrocketing. Add in the extra sales I
						make from add-on and one click upsells, and zibarr has literally multiplied the size of
						my business.”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Ineh Joseph</span>
			</div>
		</SwiperSlide>
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="md:text-2xl text-sm lg:font-semibold">
						“It’s by far the #1 tool I’ve found for selling stuff online. I highly recommend you to
						check it out.”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Kenny Nwokoye</span>
			</div>
		</SwiperSlide>
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="md:text-2xl text-sm lg:font-semibold">
						“Zibarr made our monthly billing so much easier. And now, moving to sales online for our
						programs has made our gym billing so much easier + saves us mucho $$$! It’s so easy to
						use, the support is outstanding. It’s by far the best financial decision we’ve made.”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Kenny Nwokoye</span>
			</div>
		</SwiperSlide>
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="md:text-2xl text-sm lg:font-semibold">
						“Just went live with my very first page on zibarr, and I sold something within
						15minutes! Plus they bought the order bump too. Brilliant system!”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Kenny Nwokoye</span>
			</div>
		</SwiperSlide>
	</Swiper>
</section>
