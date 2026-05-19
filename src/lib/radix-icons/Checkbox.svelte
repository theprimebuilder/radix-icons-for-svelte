<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Checkbox size={24} color="red" />
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
    <path fill="currentColor" d="M12.103 2.005A1 1 0 0 1 13 3v9l-.005.102a1 1 0 0 1-.893.893L12 13H3l-.103-.005a1 1 0 0 1-.892-.893L2 12V3a1 1 0 0 1 .897-.995L3 2h9zM3 12h9V3H3zm6.525-7.055a.5.5 0 0 1 .825.567L7.09 10.26a.5.5 0 0 1-.797.036l-1.865-2.25-.057-.083a.5.5 0 0 1 .754-.626l.072.071L6.64 9.147z"/>
</svg>
