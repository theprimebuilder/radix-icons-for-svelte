<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Cube size={24} color="red" />
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
    <path fill="currentColor" d="M7.393.762a.5.5 0 0 1 .319.035l6 2.8A.5.5 0 0 1 14 4.05v6.9a.5.5 0 0 1-.288.453l-6 2.8a.5.5 0 0 1-.424 0l-6-2.8A.5.5 0 0 1 1 10.95v-6.9a.5.5 0 0 1 .288-.453l6-2.8zM2 10.63l5 2.333V6.93L2 4.805zm6-3.7v6.033l5-2.333V4.805zM2.728 4.028 7.5 6.057l4.772-2.029L7.5 1.802z"/>
</svg>
