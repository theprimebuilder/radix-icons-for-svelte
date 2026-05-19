<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ComponentNone size={24} color="red" />
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
    <path fill="currentColor" d="M7.224 1.425a.5.5 0 0 1 .63.065l2.475 2.474 2.318-2.317a.5.5 0 1 1 .707.707L11.036 4.67l2.474 2.476.065.077a.5.5 0 0 1-.065.63L7.854 13.51a.5.5 0 0 1-.707 0L4.67 11.036l-2.317 2.318a.5.5 0 0 1-.707-.707l2.317-2.318L1.49 7.854a.5.5 0 0 1 0-.707L7.147 1.49zM5.378 10.33l2.122 2.12L12.45 7.5l-2.121-2.122zM2.55 7.5l2.121 2.121 4.95-4.95-2.12-2.12z"/>
</svg>
