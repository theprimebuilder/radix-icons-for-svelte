<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Keyboard size={24} color="red" />
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
    <path fill="currentColor" d="M13.653 3.008A1.5 1.5 0 0 1 15 4.5v6l-.008.153a1.5 1.5 0 0 1-1.339 1.34L13.5 12h-12l-.153-.008a1.5 1.5 0 0 1-1.34-1.339L0 10.5v-6a1.5 1.5 0 0 1 1.347-1.492L1.5 3h12zM1.5 4a.5.5 0 0 0-.5.5v6a.5.5 0 0 0 .5.5h12a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5zM3 10H2V9h1zm8 0H4V9h7zm2 0h-1V9h1zM4 8H3V7h1zm2 0H5V7h1zm2 0H7V7h1zm2 0H9V7h1zm2 0h-1V7h1zM3 6H2V5h1zm2 0H4V5h1zm2 0H6V5h1zm2 0H8V5h1zm2 0h-1V5h1zm2 0h-1V5h1z"/>
</svg>
