<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <BorderDotted size={24} color="red" />
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
    <path fill="currentColor" d="M1.5 6.625a.875.875 0 1 1 0 1.75.875.875 0 0 1 0-1.75m4 0a.875.875 0 1 1 0 1.75.875.875 0 0 1 0-1.75m4 0a.875.875 0 1 1 0 1.75.875.875 0 0 1 0-1.75m4 0a.875.875 0 1 1 0 1.75.875.875 0 0 1 0-1.75"/>
</svg>
