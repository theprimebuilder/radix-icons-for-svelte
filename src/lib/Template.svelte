<script lang="ts">
	/**
	 *@component
	 * Icon build with Radix Icons design
	 * Check their page https://www.radix-ui.com/icons
	 * * @example
	 * ```
	 * <ArrowBottomLeft size={24} color="red" />
	 * ```
	 */
	interface Props {
		/** * Icon size in pixel Height & Width
		 * @default 15
		 */
		size?: number;
		/** * Icon default color you can pass your custum color (css, currentColor, rgb, hex etc...)
		 * @default 'currentColor'
		 */
		color?: string;
	}
	let { size = 15, color = 'currentColor', ...rest }: Props = $props();
</script>

<svg
	width={size}
	height={size}
	viewBox="0 0 15 15"
	fill="none"
	{color}
	xmlns="http://www.w3.org/2000/svg"
	{...rest}
>
</svg>
