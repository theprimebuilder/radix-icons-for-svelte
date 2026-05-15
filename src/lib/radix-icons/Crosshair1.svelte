<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Crosshair1 size={24} color="red" />
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
    <path fill="currentColor" d="M7.502.877a6.626 6.626 0 1 1-.001 13.251A6.626 6.626 0 0 1 7.502.877M8 4.5a.5.5 0 0 1-1 0V1.85A5.676 5.676 0 0 0 1.85 7H4.5a.5.5 0 0 1 0 1H1.85A5.674 5.674 0 0 0 7 13.153V10.5a.5.5 0 1 1 1 0v2.653A5.674 5.674 0 0 0 13.154 8H10.5a.5.5 0 0 1 0-1h2.653A5.675 5.675 0 0 0 8 1.85z"/>
</svg>
