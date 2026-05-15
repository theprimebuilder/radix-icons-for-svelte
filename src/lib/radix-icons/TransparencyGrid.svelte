<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TransparencyGrid size={24} color="red" />
     * ```
     */
    interface Props {
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
    <path fill="currentColor" d="M3 15H0v-3h3zm6 0H6v-3h3zm6 0h-3v-3h3zm-9-3H3V9h3zm6 0H9V9h3zM3 9H0V6h3zm6 0H6V6h3zm6 0h-3V6h3zM6 6H3V3h3zm6 0H9V3h3zM3 3H0V0h3zm6 0H6V0h3zm6 0h-3V0h3z" opacity=".25"/>
</svg>
