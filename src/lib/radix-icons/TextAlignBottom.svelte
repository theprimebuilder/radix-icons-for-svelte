<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TextAlignBottom size={24} color="red" />
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
    <path fill="currentColor" d="M3.5 13.9a.4.4 0 0 0 .283-.117l2-2a.401.401 0 0 0-.566-.567L3.9 12.533V5.5a.401.401 0 0 0-.8 0v7.033l-1.317-1.317-.063-.05a.4.4 0 0 0-.554.554l.05.063 2 2a.4.4 0 0 0 .284.117m11-6.9a.5.5 0 1 0 0-1h-6a.5.5 0 0 0 0 1zm0 3a.5.5 0 1 0 0-1h-6a.5.5 0 0 0 0 1zm0 3a.5.5 0 1 0 0-1h-6a.5.5 0 0 0 0 1z"/>
</svg>
