<script lang="ts">
	import { twMerge } from 'tailwind-merge';

	let classList: string = '';
	export { classList as class };
</script>

<svg
	{...$$restProps}
	xmlns="http://www.w3.org/2000/svg"
	viewBox="0 0 24 24"
	stroke-linecap="round"
	stroke-linejoin="round"
	class={twMerge('size-6 fill-none stroke-current stroke-2', classList)}
>
	<rect
		width="18"
		height="18"
		x="3"
		y="3"
		rx="2"
		ry="2"
	/>
	<polyline points="11 3 11 11 14 8 17 11 17 3" />
</svg>
