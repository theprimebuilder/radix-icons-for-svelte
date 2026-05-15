<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Clock size={24} color="red" />
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
    <path fill="currentColor" d="M7.5.877a6.623 6.623 0 1 1 0 13.246A6.623 6.623 0 0 1 7.5.877m0 .95A5.674 5.674 0 1 0 7.5 13.17a5.674 5.674 0 0 0-.002-11.345M7.5 4a.5.5 0 0 1 .5.5v2.793l1.854 1.854.064.078a.5.5 0 0 1-.693.693l-.078-.064-2-2A.5.5 0 0 1 7 7.5v-3a.5.5 0 0 1 .5-.5"/>
</svg>
