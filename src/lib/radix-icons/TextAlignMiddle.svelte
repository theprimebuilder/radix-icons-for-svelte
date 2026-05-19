<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TextAlignMiddle size={24} color="red" />
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
    <path fill="currentColor" d="M3.5 5.9a.4.4 0 0 0 .283-.117l2-2a.401.401 0 0 0-.566-.567L3.9 4.533V.5L3.892.419a.401.401 0 0 0-.792.08v4.034L1.783 3.216l-.063-.05a.4.4 0 0 0-.554.554l.05.063 2 2A.4.4 0 0 0 3.5 5.9m11-.9a.5.5 0 0 0 0-1h-6a.5.5 0 0 0 0 1zm0 3a.5.5 0 0 0 0-1h-6a.5.5 0 0 0 0 1zm-11 6.9a.4.4 0 0 0 .392-.32l.008-.08v-4.034l1.317 1.317a.4.4 0 0 0 .566-.567l-2-2a.4.4 0 0 0-.566 0l-2 2-.051.064a.4.4 0 0 0 .554.554l.063-.051L3.1 10.466V14.5c0 .22.179.4.4.4m11-3.9a.5.5 0 0 0 0-1h-6a.5.5 0 0 0 0 1z"/>
</svg>
