<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <SpaceBetweenHorizontally size={24} color="red" />
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
    <path fill="currentColor" d="M6 8a1 1 0 0 1-1 1H1v4.5a.5.5 0 0 1-1 0v-12a.5.5 0 0 1 1 0V6h4a1 1 0 0 1 1 1zm4 1a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h4V1.5a.5.5 0 1 1 1 0v12a.5.5 0 0 1-1 0V9z"/>
</svg>
