<script>
	import { Tab, TabGroup, TabList, TabPanel, TabPanels } from '@rgossiaux/svelte-headlessui';
	import GrowFeatures from './growFeatures.svelte';
	import LaunchFeatures from './launchFeatures.svelte';
	import ScaleFeatures from './scaleFeatures.svelte';
</script>

<div class="plan">
	<TabGroup class="-mt-14 lg:-mt-48">
		<TabList class="flex bg-secondary rounded-full mx-5 lg:mx-96 md:mx-60 mb-10">
			<Tab
				class={({ selected }) =>
					`${
						selected ? 'border-primary-500 bg-primary-50' : 'border-slate-400'
					} px-3 py-2 w-full text-sm text-primary-500 rounded-full uppercase font-bold lg:py-4`}
				>monthly plan</Tab
			>
			<Tab
				class={({ selected }) =>
					`${
						selected ? 'border-primary-500 bg-primary-50' : 'border-slate-400'
					} px-3 py-2 w-full text-sm text-primary-500 rounded-full uppercase font-bold lg:py-4`}
				>yearly plan</Tab
			>
		</TabList>
		<TabPanels>
			<TabPanel class="px-5 lg:px-40 text-secondary">
				<div class="md:flex lg:justify-between md:space-y-0 space-y-10 lg:space-x-10 md:space-x-5">
					<div>
						<div class="__plan-card transit">
							<div class="text-center font-red">
								<img src="/launch.svg" alt="" class="mx-auto w-28" />
								<p class="uppercase font-semibold">launch</p>
								<div class="mt-10 space-y-10">
									<p class="text-2xl font-semibold">
										<span class="text-primary-500 text-5xl font-bold">$49</span>/MO
									</p>
									<div class="flex justify-center">
										<button class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
											>Get Started Free</button
										>
									</div>
									<p class="px-5">
										Launch your business and create a beautiful one-page website to showcase our
										products.
									</p>
								</div>
							</div>
						</div>
						<LaunchFeatures />
					</div>
					<div>
						<div>
							<div class="__plan-card transit">
								<div class="text-center font-red">
									<img src="/grow.svg" alt="" class="mx-auto w-28" />
									<p class="uppercase font-semibold">grow</p>
									<div class="mt-10 space-y-10">
										<p class="text-2xl font-semibold">
											<span class="text-primary-500 text-5xl font-bold">$99</span>/MO
										</p>
										<div class="flex justify-center">
											<button
												class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
												>Get Started Free</button
											>
										</div>
										<p class="px-5">
											Convert more of your visitors into customers, and increase the value of each
											purchase.
										</p>
									</div>
								</div>
							</div>
						</div>
						<GrowFeatures />
					</div>
					<div>
						<div class="__plan-card transit">
							<div class="text-center font-red">
								<img src="/scale.svg" alt="" class="mx-auto w-28" />
								<p class="uppercase font-semibold">scale</p>
								<div class="mt-10 space-y-10">
									<p class="text-2xl font-semibold">
										<span class="text-primary-500 text-5xl font-bold">$199</span>/MO
									</p>
									<div class="flex justify-center">
										<button class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
											>Get Started Free</button
										>
									</div>
									<p class="px-5">
										Everything we have including all the advanced features you will need for selling
										at scale.
									</p>
								</div>
							</div>
						</div>
						<ScaleFeatures />
					</div>
				</div>
			</TabPanel>
			<TabPanel class="px-5 lg:px-40 text-secondary">
				<div class="md:flex lg:justify-between md:space-y-0 space-y-10 lg:space-x-10 md:space-x-5">
					<div>
						<div class="__plan-card transit">
							<div class="text-center font-red">
								<img src="/launch.svg" alt="" class="mx-auto w-28" />
								<p class="uppercase font-semibold">launch</p>
								<div class="mt-10 space-y-10">
									<p class="text-2xl font-semibold flex flex-col space-y-2">
										<span class="pb-5"
											><span class="text-primary-500 text-5xl font-bold">$39</span>/MO</span
										>
										<span class="line-through text-base"><span>$49</span>/MO</span>
										<span class="text-base"><span>Billed Anually</span></span>
									</p>
									<div class="flex justify-center">
										<button class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
											>Get Started Free</button
										>
									</div>
									<p class="px-5">
										Launch your business and create a beautiful one-page website to showcase our
										products.
									</p>
								</div>
							</div>
						</div>
						<LaunchFeatures />
					</div>
					<div>
						<div>
							<div class="__plan-card transit">
								<div class="text-center font-red">
									<img src="/grow.svg" alt="" class="mx-auto w-28" />
									<p class="uppercase font-semibold">grow</p>
									<div class="mt-10 space-y-10">
										<p class="text-2xl font-semibold flex flex-col space-y-2">
											<span class="pb-5"
												><span class="text-primary-500 text-5xl font-bold">$79</span>/MO</span
											>
											<span class="line-through text-base"><span>$99</span>/MO</span>
											<span class="text-base"><span>Billed Anually</span></span>
										</p>
										<div class="flex justify-center">
											<button
												class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
												>Get Started Free</button
											>
										</div>
										<p class="px-5">
											Convert more of your visitors into customers, and increase the value of each
											purchase.
										</p>
									</div>
								</div>
							</div>
						</div>
						<GrowFeatures />
					</div>
					<div>
						<div class="__plan-card transit">
							<div class="text-center font-red">
								<img src="/scale.svg" alt="" class="mx-auto w-28" />
								<p class="uppercase font-semibold">scale</p>
								<div class="mt-10 space-y-10">
									<p class="text-2xl font-semibold flex flex-col space-y-2">
										<span class="pb-5"
											><span class="text-primary-500 text-5xl font-bold">$159</span>/MO</span
										>
										<span class="line-through text-base"><span>$199</span>/MO</span>
										<span class="text-base"><span>Billed Anually</span></span>
									</p>
									<div class="flex justify-center">
										<button class="font-bold border-2 border-secondary py-3 px-10 rounded-lg shadow"
											>Get Started Free</button
										>
									</div>
									<p class="px-5">
										Everything we have including all the advanced features you will need for selling
										at scale.
									</p>
								</div>
							</div>
						</div>
						<ScaleFeatures />
					</div>
				</div>
			</TabPanel>
		</TabPanels>
	</TabGroup>
</div>
