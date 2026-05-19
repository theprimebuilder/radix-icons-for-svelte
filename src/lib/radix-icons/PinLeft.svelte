<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <PinLeft size={24} color="red" />
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
    <path fill="currentColor" d="M5.124 7.748a.45.45 0 0 1 0-.496l.058-.07 3.25-3.25a.45.45 0 0 1 .637.636L6.587 7.05H14.5a.45.45 0 0 1 0 .9H6.587L9.07 10.43l.057.07a.451.451 0 0 1-.624.625l-.07-.058-3.25-3.25zM2.05 1.5a.45.45 0 0 1 .9 0v12a.45.45 0 0 1-.9 0z"/>
</svg>
