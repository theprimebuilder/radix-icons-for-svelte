<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Cross1 size={24} color="red" />
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
    <path fill="currentColor" d="M12.225 2.082a.5.5 0 0 1 .693.694l-.064.078L8.207 7.5l4.647 4.647.064.078a.5.5 0 0 1-.693.693l-.078-.064L7.5 8.207l-4.646 4.647a.5.5 0 1 1-.707-.707L6.793 7.5 2.147 2.854l-.065-.078a.5.5 0 0 1 .694-.694l.078.065L7.5 6.793l4.647-4.646z"/>
</svg>
