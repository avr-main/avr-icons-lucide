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
	<circle
		cx="12"
		cy="13"
		r="8"
	/>
	<path d="M12 9v4l2 2" />
	<path d="M5 3 2 6" />
	<path d="m22 6-3-3" />
	<path d="M6.38 18.7 4 21" />
	<path d="M17.64 18.67 20 21" />
</svg>
