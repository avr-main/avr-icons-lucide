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
		cx="16"
		cy="4"
		r="1"
	/>
	<path d="m18 19 1-7-6 1" />
	<path d="m5 8 3-3 5.5 3-2.36 3.5" />
	<path d="M4.24 14.5a5 5 0 0 0 6.88 6" />
	<path d="M13.76 17.5a5 5 0 0 0-6.88-6" />
</svg>
