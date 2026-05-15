<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Strikethrough size={24} color="red" />
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
    <path fill="currentColor" d="M10.5 2.75a.5.5 0 0 1 .5.5V7.1h1.5l.081.008a.4.4 0 0 1 0 .784l-.08.008H11v.65a3.5 3.5 0 0 1-7 0V7.9H2.5a.4.4 0 0 1 0-.8H4V3.25a.5.5 0 1 1 1 0V7.1h5V3.25a.5.5 0 0 1 .5-.5M5 7.9v.65a2.5 2.5 0 1 0 5 0V7.9z"/>
</svg>
