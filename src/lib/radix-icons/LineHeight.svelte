<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <LineHeight size={24} color="red" />
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
    <path fill="currentColor" d="M3.5 2.1c.106 0 .208.042.283.117l2 2 .05.064a.4.4 0 0 1-.05.503.4.4 0 0 1-.503.05l-.063-.05L3.9 3.467v8.067l1.317-1.317a.4.4 0 0 1 .566.567l-2 2a.4.4 0 0 1-.566 0l-2-2-.051-.064a.4.4 0 0 1 .554-.554l.063.051 1.316 1.317V3.467L1.783 4.784a.401.401 0 0 1-.566-.567l2-2 .061-.05A.4.4 0 0 1 3.5 2.1m11 7.9a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1zm0-3a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1zm0-3a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1z"/>
</svg>
