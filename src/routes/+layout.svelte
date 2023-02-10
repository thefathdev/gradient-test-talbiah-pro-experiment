<script>
	import Button from '$components/button.svelte';
	import '../app.css';
</script>

<header class="body-font border-b-[1px] border-neutral-800 bg-black text-neutral-400">
	<div class="container mx-auto flex flex-col flex-wrap items-center p-5 md:flex-row">
		<a class="title-font mb-4 flex items-center font-medium text-white md:mb-0" href="/">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				stroke="currentColor"
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				class="h-10 w-10 rounded-full bg-purple-500 p-2 text-white"
				viewBox="0 0 24 24"
			>
				<path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5" />
			</svg>
			<span class="ml-3 text-xl">Talbiah Pro</span>
		</a>
		<nav class="flex flex-wrap items-center justify-center text-base md:ml-auto md:mr-auto">
			<a class="mr-5 hover:text-white" href="/">Features</a>
			<a class="mr-5 hover:text-white" href="/">Pricing</a>
			<a class="mr-5 hover:text-white" href="/">Customers</a>
			<a class="mr-5 hover:text-white" href="/">Contact</a>
		</nav>
		<Button text="Sign Up" />
	</div>
</header>
<section class="container h-screen w-full bg-black">
	<slot />
</section>
