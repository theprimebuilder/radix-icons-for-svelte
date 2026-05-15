<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Table size={24} color="red" />
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
    <path fill="currentColor" d="M12.653 1.008A1.5 1.5 0 0 1 14 2.5v10l-.008.153a1.5 1.5 0 0 1-1.339 1.34L12.5 14h-10l-.153-.008a1.5 1.5 0 0 1-1.34-1.339L1 12.5v-10a1.5 1.5 0 0 1 1.347-1.492L2.5 1h10zM2 12.5a.5.5 0 0 0 .5.5H7v-3H2zm6 .5h4.5a.5.5 0 0 0 .5-.5V10H8zM2 6v3h5V6zm6 0v3h5V6zM2.5 2a.5.5 0 0 0-.5.5V5h5V2zM8 5h5V2.5a.5.5 0 0 0-.5-.5H8z"/>
</svg>
