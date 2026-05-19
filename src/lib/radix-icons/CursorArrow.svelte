<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <CursorArrow size={24} color="red" />
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
    <path fill="currentColor" d="M3.292.049a.5.5 0 0 1 .535.077l9.031 7.824a.5.5 0 0 1-.304.878l-3.335.147 1.931 4.244a.5.5 0 0 1-.248.662l-2.152.98a.5.5 0 0 1-.662-.247L6.152 10.37l-2.29 2.416A.5.5 0 0 1 3 12.441V.504l.005-.072a.5.5 0 0 1 .287-.383M4 11.187l1.938-2.042.045-.042a.5.5 0 0 1 .773.178l2.034 4.462 1.243-.565-2.031-4.463a.5.5 0 0 1 .433-.706l2.82-.125L4 1.598z"/>
</svg>
