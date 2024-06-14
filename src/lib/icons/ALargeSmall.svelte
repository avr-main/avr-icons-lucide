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
	<path d="M21 14h-5" />
	<path d="M16 16v-3.5a2.5 2.5 0 0 1 5 0V16" />
	<path d="M4.5 13h6" />
	<path d="m3 16 4.5-9 4.5 9" />
</svg>
