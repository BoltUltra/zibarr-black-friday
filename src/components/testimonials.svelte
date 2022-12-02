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

<section class="lg:px-80 px-5 testimonial my-10">
	<Swiper pagination={true} modules={[Pagination]} class="mySwiper ">
		<SwiperSlide class="py-10">
			<div class="flex flex-col">
				<div class="flex items-start space-x-2">
					<span class="text-primary-500 text-[100px] p-0"
						><QuoteUp size="32" color="#C5A059" variant="Bold" /></span
					>
					<p class="lg:text-2xl text-sm lg:font-semibold">
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
					<p class="lg:text-2xl text-sm lg:font-semibold">
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
					<p class="lg:text-2xl text-sm lg:font-semibold">
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
					<p class="lg:text-2xl text-sm lg:font-semibold">
						“Zibarr makes it easier to be an entrepreneur. It’s Technology that levels that playing
						field so anyone can access tools they need to get started--without a lot of upfront
						investment or experience.”
					</p>
				</div>
				<span class="text-right text-xs lg:text-base font-semibold">-Kenny Nwokoye</span>
			</div>
		</SwiperSlide>
	</Swiper>
</section>
