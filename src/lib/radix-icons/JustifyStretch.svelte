<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <JustifyStretch size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M13.5 1.05a.45.45 0 0 1 .45.45v12a.45.45 0 0 1-.9 0v-12a.45.45 0 0 1 .45-.45m-12 0a.45.45 0 0 1 .45.45v12a.45.45 0 0 1-.9 0v-12a.45.45 0 0 1 .45-.45M4 6h7v3H4zm7.25-1a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-.75.75h-7.5A.75.75 0 0 1 3 9.25v-3.5A.75.75 0 0 1 3.75 5z" clip-rule="evenodd"/>
</svg>
