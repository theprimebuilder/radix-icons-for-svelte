<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <RowSpacing size={24} color="red" />
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
    <path fill="currentColor" d="M7.5 9.05a.45.45 0 0 1 .45.45v3.413l1.232-1.231a.45.45 0 0 1 .636.637l-2 2a.45.45 0 0 1-.568.055l-.068-.055-2-2-.058-.07a.45.45 0 0 1 .624-.625l.07.058 1.232 1.231V9.5a.45.45 0 0 1 .45-.45m6.1-2.04a.5.5 0 0 1 0 .98l-.1.01h-12a.5.5 0 0 1 0-1h12zM7.253.624a.45.45 0 0 1 .566.058l2 2 .058.07a.45.45 0 0 1-.624.624l-.07-.057L7.95 2.087V5.5a.45.45 0 0 1-.9 0V2.087L5.818 3.32a.45.45 0 0 1-.636-.637l2-2z"/>
</svg>
