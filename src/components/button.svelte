<script>
	export let text = '';
</script>

<button
	class="mt-4 inline-flex items-center rounded border-2 border-white bg-white py-1.5  px-3 text-base  text-neutral-900 hover:bg-neutral-900 hover:text-white md:mt-0"
	>{text}
	<svg
		fill="none"
		stroke="currentColor"
		stroke-linecap="round"
		stroke-linejoin="round"
		stroke-width="2"
		class="ml-1 h-4 w-4"
		viewBox="0 0 24 24"
	>
		<path d="M5 12h14M12 5l7 7-7 7" />
	</svg>
</button>
