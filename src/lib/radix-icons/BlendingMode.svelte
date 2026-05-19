<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <BlendingMode size={24} color="red" />
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
    <path fill="currentColor" d="M7.5 1.5c3 2.75 4.5 5 4.5 7.5l-.006.231A4.5 4.5 0 0 1 3 9c0-2.5 1.5-4.75 4.5-7.5m0 1.376C5.028 5.274 4 7.112 4 9q.001.425.098.82c1.864.428 4.534-2.39 6.854-1.516C10.725 6.65 9.668 4.978 7.5 2.876"/>
</svg>
