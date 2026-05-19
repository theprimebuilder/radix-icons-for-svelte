<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DoubleArrowRight size={24} color="red" />
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
    <path fill="currentColor" d="M2.147 3.147a.5.5 0 0 1 .629-.065l.078.065 4 4a.5.5 0 0 1 0 .707l-4 4-.078.064a.5.5 0 0 1-.694-.693l.065-.078L5.793 7.5 2.147 3.854l-.065-.078a.5.5 0 0 1 .065-.63m6 0a.5.5 0 0 1 .629-.065l.078.065 4 4a.5.5 0 0 1 0 .707l-4 4-.078.064a.5.5 0 0 1-.694-.693l.065-.078L11.793 7.5 8.147 3.854l-.065-.078a.5.5 0 0 1 .065-.63"/>
</svg>
