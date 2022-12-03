<script>
	import ArrowCircleDown from 'iconsax-svelte/ArrowCircleDown.svelte';
	import Menu from 'iconsax-svelte/Menu.svelte';
	let isNavOpen = false;

	const handleNavMenu = () => {
		isNavOpen = !isNavOpen;
	};
</script>

<nav class="flex items-center justify-between px-5 py-5">
	<img src="/logo.png" alt="" class="lg:w-32 w-20" />
	<div class="md:block hidden">
		<div class="relative">
			<div class="flex items-center space-x-5">
				<div class="group inline-block">
					<button class="outline-none focus:outline-none border py-1 rounded-sm flex items-center">
						<span class="pr-1 flex-1">Why Zibarr?</span>
						<span>
							<svg
								class="fill-current h-4 w-4 transform group-hover:-rotate-180 transition duration-150 ease-in-out"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
								/>
							</svg>
						</span>
					</button>
					<ul
						class="bg-white border rounded-sm transform scale-0 group-hover:scale-100 absolute transition duration-150 ease-in-out origin-top min-w-32"
					>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<button class="w-full text-left flex items-center outline-none focus:outline-none">
								<span class="pr-1 flex-1">Platform</span>
								<span class="mr-auto">
									<svg
										class="fill-current h-4 w-4 transition duration-150 ease-in-out"
										xmlns="http://www.w3.org/2000/svg"
										viewBox="0 0 20 20"
									>
										<path
											d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
										/>
									</svg>
								</span>
							</button>
							<ul
								class="bg-white border rounded-sm absolute top-0 right-0 transition duration-150 ease-in-out origin-top-left min-w-32"
							>
								<li class="px-3 py-1 hover:bg-gray-100">Features</li>
								<li class="px-3 py-1 hover:bg-gray-100">CreatorU</li>
								<li class="px-3 py-1 hover:bg-gray-100">Courses App</li>
								<li class="px-3 py-1 hover:bg-gray-100">Integration</li>
							</ul>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<button class="w-full text-left flex items-center outline-none focus:outline-none">
								<span class="pr-1 flex-1">Industries</span>
								<span class="mr-auto">
									<svg
										class="fill-current h-4 w-4 transition duration-150 ease-in-out"
										xmlns="http://www.w3.org/2000/svg"
										viewBox="0 0 20 20"
									>
										<path
											d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
										/>
									</svg>
								</span>
							</button>
							<ul
								class="bg-white border rounded-sm absolute top-0 right-0 transition duration-150 ease-in-out origin-top-left w-52"
							>
								<li class="px-3 py-1 hover:bg-gray-100">Course Creators</li>
								<li class="px-3 py-1 hover:bg-gray-100">Agencies</li>
								<li class="px-3 py-1 hover:bg-gray-100">Physical Product Sellers</li>
								<li class="px-3 py-1 hover:bg-gray-100">Authors</li>
								<li class="px-3 py-1 hover:bg-gray-100">Amazon/Etsy Sellers</li>
								<li class="px-3 py-1 hover:bg-gray-100">Entrepreneurs</li>
								<li class="px-3 py-1 hover:bg-gray-100">Coaches & Consultants</li>
								<li class="px-3 py-1 hover:bg-gray-100">Side Hustlers</li>
								<li class="px-3 py-1 hover:bg-gray-100">Non Profit</li>
							</ul>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<button class="w-full text-left flex items-center outline-none focus:outline-none">
								<span class="pr-1 flex-1">Partnership</span>
								<span class="mr-auto">
									<svg
										class="fill-current h-4 w-4 transition duration-150 ease-in-out"
										xmlns="http://www.w3.org/2000/svg"
										viewBox="0 0 20 20"
									>
										<path
											d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
										/>
									</svg>
								</span>
							</button>
							<ul
								class="bg-white border rounded-sm absolute top-0 right-0 transition duration-150 ease-in-out origin-top-left min-w-32"
							>
								<li class="px-3 py-1 hover:bg-gray-100">Our Partners</li>
								<li class="px-3 py-1 hover:bg-gray-100">Become a Partner</li>
							</ul>
						</li>
					</ul>
				</div>
				<a href="#!">Customer Stories</a>
				<a href="#!">Pricing</a>
				<div class="group inline-block">
					<button class="outline-none focus:outline-none border py-1 rounded-sm flex items-center">
						<span class="pr-1 flex-1">Learn</span>
						<span>
							<svg
								class="fill-current h-4 w-4 transform group-hover:-rotate-180 transition duration-150 ease-in-out"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
								/>
							</svg>
						</span>
					</button>
					<ul
						class="bg-white border rounded-sm transform scale-0 group-hover:scale-100 absolute transition duration-150 ease-in-out origin-top min-w-32"
					>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Blog</span>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Knowledge Base</span>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Free Training</span>
						</li>
					</ul>
				</div>
				<div class="group inline-block">
					<button class="outline-none focus:outline-none border py-1 rounded-sm flex items-center">
						<span class="pr-1 flex-1">About</span>
						<span>
							<svg
								class="fill-current h-4 w-4 transform group-hover:-rotate-180 transition duration-150 ease-in-out"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
								/>
							</svg>
						</span>
					</button>
					<ul
						class="bg-white border rounded-sm transform scale-0 group-hover:scale-100 absolute transition duration-150 ease-in-out origin-top min-w-32"
					>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Team</span>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Careers</span>
						</li>
						<li class="rounded-sm relative px-3 py-1 hover:bg-gray-100">
							<span class="pr-1 flex-1">Contact Us</span>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
	<div class="md:flex items-center space-x-5 hidden">
		<button class="border-2 border-black shadow px-5 py-2 rounded ">Log In</button>
		<button class="bg-primary-500 text-white py-2 px-5 rounded">Try for free</button>
	</div>
	<div class="md:hidden">
		<Menu size="24" color="#C5A059" variant="Linear" />
	</div>
</nav>

<style>
	/* since nested groupes are not supported we have to use 
     regular css for the nested dropdowns 
  */
	li > ul {
		transform: translatex(100%) scale(0);
	}
	li:hover > ul {
		transform: translatex(101%) scale(1);
	}
	li > button svg {
		transform: rotate(-90deg);
	}
	li:hover > button svg {
		transform: rotate(-270deg);
	}

	/* Below styles fake what can be achieved with the tailwind config
     you need to add the group-hover variant to scale and define your custom
     min width style.
  	 See https://codesandbox.io/s/tailwindcss-multilevel-dropdown-y91j7?file=/index.html
  	 for implementation with config file
  */
	.group:hover .group-hover\:scale-100 {
		transform: scale(1);
	}
	.group:hover .group-hover\:-rotate-180 {
		transform: rotate(180deg);
	}
	.scale-0 {
		transform: scale(0);
	}
	.min-w-32 {
		min-width: 8rem;
	}
</style>
