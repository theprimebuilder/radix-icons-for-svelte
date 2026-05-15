<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <PinBottom size={24} color="red" />
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
    <path fill="currentColor" d="M7.748 10.876a.45.45 0 0 1-.496 0l-.07-.058-3.25-3.25a.45.45 0 0 1 .636-.637L7.05 9.413V1.5a.45.45 0 0 1 .9 0v7.913L10.43 6.93l.07-.057a.451.451 0 0 1 .625.624l-.058.07-3.25 3.25zM1.5 13.95a.45.45 0 0 1 0-.9h12a.45.45 0 0 1 0 .9z"/>
</svg>
