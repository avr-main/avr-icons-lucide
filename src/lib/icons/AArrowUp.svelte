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
	<path d="M3.5 13h6" />
	<path d="m2 16 4.5-9 4.5 9" />
	<path d="M18 16V7" />
	<path d="m14 11 4-4 4 4" />
</svg>
