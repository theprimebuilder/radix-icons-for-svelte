<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <BorderNone size={24} color="red" />
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
    <rect width="1" height="1" x="7" y="5.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="5.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="3.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="3.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="5" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="5" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="5" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="3" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="3" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="3" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="9" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="9" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="9" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="11" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="11" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="11" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="9.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="9.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="7" y="11.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="13" y="11.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="5.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="3.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="7.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="13.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="1.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="9.025" fill="currentColor" rx=".5"/><rect width="1" height="1" x="1" y="11.025" fill="currentColor" rx=".5"/>
</svg>
