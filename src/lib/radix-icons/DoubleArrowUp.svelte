<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DoubleArrowUp size={24} color="red" />
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
    <path fill="currentColor" d="M7.147 8.146a.5.5 0 0 1 .707 0l4 4 .064.079a.5.5 0 0 1-.693.693l-.078-.064L7.5 9.207l-3.646 3.646-.078.065a.5.5 0 0 1-.694-.693l.065-.079zm0-6a.5.5 0 0 1 .707 0l4 4 .064.079a.5.5 0 0 1-.693.693l-.078-.065L7.5 3.207 3.854 6.853l-.078.065a.5.5 0 0 1-.694-.693l.065-.079z"/>
</svg>
