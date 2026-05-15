<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <OpenInNewWindow size={24} color="red" />
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
    <path fill="currentColor" d="M8.5 6q.049 0 .098.009.076.017.142.054.061.034.114.083.05.052.082.113A.5.5 0 0 1 9 6.5v3a.5.5 0 0 1-1 0V7.707l-5.146 5.147a.5.5 0 1 1-.708-.707L7.293 7H5.5a.5.5 0 0 1 0-1zM12 2a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H8.5a.5.5 0 0 1 0-1H12V3H3v3.5a.5.5 0 0 1-1 0V3a1 1 0 0 1 1-1z"/>
</svg>
