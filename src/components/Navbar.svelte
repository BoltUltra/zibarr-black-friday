<script>
	import ArrowCircleDown from 'iconsax-svelte/ArrowCircleDown.svelte';
	let isDropdownOpen = false;
	const handleDropDown = () => {
		isDropdownOpen = !isDropdownOpen;
	};
</script>

<nav class="flex items-center justify-between px-5 py-5">
	<img src="/logo.png" alt="" class="lg:w-32 w-20" />
	<div class="md:block hidden">
		<div class="relative">
			<div class="flex items-center space-x-5">
				<button type="button" class="dropdown" id="why-button" on:click={handleDropDown}>
					<span>Why Zibarr?</span>
					<ArrowCircleDown size="16" color="#000" variant="Linear" />
				</button>
				<a href="#!">Customer Stories</a>
				<a href="#!">Pricing</a>
				<button type="button" class="dropdown" id="learn-button" on:click={handleDropDown}>
					<span>Learn</span>
					<ArrowCircleDown size="16" color="#000" variant="Linear" />
				</button>
				<button type="button" class="dropdown" id="about-button" on:click={handleDropDown}>
					<span>About</span>
					<ArrowCircleDown size="16" color="#000" variant="Linear" />
				</button>
			</div>
			<!-- >Why Zibarr? -->
			<div class={isDropdownOpen ? 'block' : 'hidden'}>
				<div
					class="absolute right-0 z-10 mt-2 w-56 origin-top-right rounded-md bg-white shadow-lg ring-1 ring-black ring-opacity-5 focus:outline-none"
					role="menu"
					aria-orientation="vertical"
					aria-labelledby="why-button"
					tabindex="-1"
				>
					<div class="py-1" role="none">
						<!-- Active: "bg-gray-100 text-gray-900", Not Active: "text-gray-700" -->
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-0">Account settings</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-1">Support</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-2">License</a
						>
						<form method="POST" action="#" role="none">
							<button
								type="submit"
								class="text-gray-700 block w-full px-4 py-2 text-left text-sm"
								role="menuitem"
								tabindex="-1"
								id="menu-item-3">Sign out</button
							>
						</form>
					</div>
				</div>
			</div>
			<!-- Learn -->
			<div class={isDropdownOpen ? 'block' : 'hidden'}>
				<div
					class="absolute right-0 z-10 mt-2 w-56 origin-top-right rounded-md bg-white shadow-lg ring-1 ring-black ring-opacity-5 focus:outline-none"
					role="menu"
					aria-orientation="vertical"
					aria-labelledby="learn-button"
					tabindex="-1"
				>
					<div class="py-1" role="none">
						<!-- Active: "bg-gray-100 text-gray-900", Not Active: "text-gray-700" -->
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-0">Account settings</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-1">Support</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-2">License</a
						>
						<form method="POST" action="#" role="none">
							<button
								type="submit"
								class="text-gray-700 block w-full px-4 py-2 text-left text-sm"
								role="menuitem"
								tabindex="-1"
								id="menu-item-3">Sign out</button
							>
						</form>
					</div>
				</div>
			</div>
			<!-- About -->
			<div class={isDropdownOpen ? 'block' : 'hidden'}>
				<div
					class="absolute right-0 z-10 mt-2 w-56 origin-top-right rounded-md bg-white shadow-lg ring-1 ring-black ring-opacity-5 focus:outline-none"
					role="menu"
					aria-orientation="vertical"
					aria-labelledby="about-button"
					tabindex="-1"
				>
					<div class="py-1" role="none">
						<!-- Active: "bg-gray-100 text-gray-900", Not Active: "text-gray-700" -->
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-0">Account settings</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-1">Support</a
						>
						<a
							href="#!"
							class="text-gray-700 block px-4 py-2 text-sm"
							role="menuitem"
							tabindex="-1"
							id="menu-item-2">License</a
						>
						<form method="POST" action="#" role="none">
							<button
								type="submit"
								class="text-gray-700 block w-full px-4 py-2 text-left text-sm"
								role="menuitem"
								tabindex="-1"
								id="menu-item-3">Sign out</button
							>
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="md:flex items-center space-x-5 hidden">
		<button class="border-2 border-black shadow px-5 py-2 rounded ">Log In</button>
		<button class="bg-primary-500 text-white py-2 px-5 rounded">Try for free</button>
	</div>
	<div class="md:hidden">Mobile Nav</div>
</nav>
