<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Container size={24} color="red" />
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
    <path fill="currentColor" d="M1.5 13a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m8.603-11.995a1 1 0 0 1 .892.892L11 2v11l-.005.102a1 1 0 0 1-.893.893L10 14H5a1 1 0 0 1-.995-.898L4 13V2l.005-.103A1 1 0 0 1 5 1h5zM13.5 13a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1M5 13h5V2H5zm-3.5-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m-12-2a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1m12 0a.5.5 0 1 1 0 1 .5.5 0 0 1 0-1"/>
</svg>
