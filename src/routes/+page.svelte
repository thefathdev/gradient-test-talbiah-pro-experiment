<script>
	import Button from '$components/button.svelte';
</script>

<main class="w-ful flex h-full flex-col items-center gap-8 px-8 pt-10">
	<h1 class="text-center font-sans text-9xl font-bold text-white">
		<span class="text-gradient-1">Mudah.</span>
		<span class="text-gradient-2">Murah.</span>
		<span class="text-gradient-3">Amanah.</span>
	</h1>
	<p class="max-w-prose text-center font-sans text-2xl text-neutral-400">
		Talbiah Pro adalah platform management travel haji dan umroh pertama di Indonesia yang
		memberikan kenyaman kepada admin travel serta keamanan data dengan tingkat reliabilitas yang
		tinggi.
	</p>
	<!-- CALL OUT -->
	<div><Button text="Sign Up" /></div>
</main>

<style lang="postcss">
	.text-gradient-1 {
		animation: gradient-1 forwards 8s ease-in-out infinite;
		/* transition: background 300ms ease-in-out; */
	}
	.text-gradient-2 {
		animation: gradient-2 forwards 8s ease-in-out infinite;
		/* transition: background 300ms ease-in-out; */
	}
	.text-gradient-3 {
		animation: gradient-3 forwards 8s ease-in-out infinite;
		/* transition: background 300ms ease-in-out; */
	}

	@keyframes gradient-1 {
		0% {
			/* background: linear-gradient(0.125turn, #2365ff, #55fffc);
			background-clip: text;
			-webkit-text-fill-color: transparent; */

			background-clip: text;
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
			background-image: linear-gradient(90deg, #007cf0, #00dfd8);
			position: relative;
			z-index: 1;
		}
		33.34%,
		100% {
			background: white;
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}
	}
	@keyframes gradient-2 {
		33.34% {
			/* background: linear-gradient(0.125turn, #ff11ff, #ff3ca4);
			background-clip: text;
			-webkit-text-fill-color: transparent; */

			background-clip: text;
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
			background-image: linear-gradient(90deg, #7928ca, #ff0080);
			position: relative;
			z-index: 1;
		}
		66.66% {
			background: white;
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}
	}
	@keyframes gradient-3 {
		66.67% {
			/* background: linear-gradient(0.125turn, #ff11ff, #ff3ca4);
			background-clip: text;
			-webkit-text-fill-color: transparent; */

			background-clip: text;
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
			background-image: linear-gradient(90deg, #ff4d4d, #f9cb28);
			position: relative;
			z-index: 1;
		}
		100%,
		0%,
		66.66% {
			background: white;
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}
	}
</style>
