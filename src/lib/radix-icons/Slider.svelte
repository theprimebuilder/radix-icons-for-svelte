<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Slider size={24} color="red" />
     * ```
     */
    interface Props extends SVGAttributes<SVGElement> {
        /**
         * Icon size in pixels (Height & Width).
         * @default 15
         */
        size?: number;
        
        /**
         * Icon color. Accepts any valid CSS value (currentColor, hex, rgb, variable, etc.).
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
	{color}
    xmlns="http://www.w3.org/2000/svg"
    {...rest}
>
// Optimized svg
    <path fill="currentColor" d="M8.78 4.764A2.75 2.75 0 0 1 11.204 7H14.5l.1.01a.5.5 0 0 1 0 .98l-.1.01h-3.297A2.75 2.75 0 0 1 8.5 10.25l-.281-.014A2.75 2.75 0 0 1 5.796 8H.5a.5.5 0 0 1 0-1h5.297A2.75 2.75 0 0 1 8.5 4.75zM8.5 5.7a1.801 1.801 0 1 0 .001 3.602A1.801 1.801 0 0 0 8.5 5.7"/>
</svg>
