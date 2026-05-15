<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Margin size={24} color="red" />
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
    <path fill="currentColor" d="M1.5 13a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-3a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1M10 4a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H5l-.103-.005A1 1 0 0 1 4 10V5a1 1 0 0 1 1-1zm3.5 6a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1M5 10h5V5H5zM1.5 7a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-3a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-3a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m3 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1"/>
</svg>
