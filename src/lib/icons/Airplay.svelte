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
	<path d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1" />
	<path d="m12 15 5 6H7Z" />
</svg>
