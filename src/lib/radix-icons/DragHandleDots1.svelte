<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DragHandleDots1 size={24} color="red" />
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
    <circle cx="4.5" cy="2.5" r=".6" fill="currentColor"/><circle cx="4.5" cy="4.5" r=".6" fill="currentColor"/><circle cx="4.5" cy="6.499" r=".6" fill="currentColor"/><circle cx="4.5" cy="8.499" r=".6" fill="currentColor"/><circle cx="4.5" cy="10.498" r=".6" fill="currentColor"/><circle cx="4.5" cy="12.498" r=".6" fill="currentColor"/><circle cx="6.5" cy="2.5" r=".6" fill="currentColor"/><circle cx="6.5" cy="4.5" r=".6" fill="currentColor"/><circle cx="6.5" cy="6.499" r=".6" fill="currentColor"/><circle cx="6.5" cy="8.499" r=".6" fill="currentColor"/><circle cx="6.5" cy="10.498" r=".6" fill="currentColor"/><circle cx="6.5" cy="12.498" r=".6" fill="currentColor"/><circle cx="8.499" cy="2.5" r=".6" fill="currentColor"/><circle cx="8.499" cy="4.5" r=".6" fill="currentColor"/><circle cx="8.499" cy="6.499" r=".6" fill="currentColor"/><circle cx="8.499" cy="8.499" r=".6" fill="currentColor"/><circle cx="8.499" cy="10.498" r=".6" fill="currentColor"/><circle cx="8.499" cy="12.498" r=".6" fill="currentColor"/><circle cx="10.499" cy="2.5" r=".6" fill="currentColor"/><circle cx="10.499" cy="4.5" r=".6" fill="currentColor"/><circle cx="10.499" cy="6.499" r=".6" fill="currentColor"/><circle cx="10.499" cy="8.499" r=".6" fill="currentColor"/><circle cx="10.499" cy="10.498" r=".6" fill="currentColor"/><circle cx="10.499" cy="12.498" r=".6" fill="currentColor"/>
</svg>
