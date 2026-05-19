<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TextAlignTop size={24} color="red" />
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
    <path fill="currentColor" d="M3.5 1.1c.106 0 .208.042.283.117l2 2a.401.401 0 0 1-.566.567L3.9 2.467V9.5a.401.401 0 0 1-.8 0V2.467L1.783 3.784l-.063.05a.4.4 0 0 1-.554-.554l.05-.063 2-2A.4.4 0 0 1 3.5 1.1m11 6.9a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1zm0-3a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1zm0-3a.5.5 0 1 1 0 1h-6a.5.5 0 0 1 0-1z"/>
</svg>
