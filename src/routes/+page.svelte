<script>
	import Button from '$components/button.svelte';
</script>

<main class="w-ful flex h-full flex-col items-center gap-8 px-10 pt-10">
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
		animation: gradient-1 both 10s ease-in-out infinite;
		transition: background;
	}

	@keyframes gradient-1 {
		0%,
		33.33% {
			background: linear-gradient(0.125turn, #2365ff, #55fffc);
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}
		33.34% {
			background: white;
			background-clip: text;
			-webkit-text-fill-color: transparent;
		}
	}
</style>
