<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TextAlignCenter size={24} color="red" />
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
    <path fill="currentColor" d="M11.5 10a.5.5 0 0 1 0 1h-8a.5.5 0 0 1 0-1zm-1-3a.5.5 0 0 1 0 1h-6a.5.5 0 0 1 0-1zm2-3a.5.5 0 0 1 0 1h-10a.5.5 0 0 1 0-1z"/>
</svg>
