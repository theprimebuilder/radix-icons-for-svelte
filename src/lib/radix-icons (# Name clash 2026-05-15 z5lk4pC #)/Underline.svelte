<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Underline size={24} color="red" />
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
    <path fill="currentColor" d="M11.581 13.108a.4.4 0 0 1 0 .784l-.08.008h-8a.4.4 0 0 1 0-.8h8zM10.501 2.25a.5.5 0 0 1 .5.5v5.3a3.5 3.5 0 0 1-7 0v-5.3a.5.5 0 1 1 1 0v5.3a2.5 2.5 0 1 0 5 0v-5.3a.5.5 0 0 1 .5-.5"/>
</svg>
