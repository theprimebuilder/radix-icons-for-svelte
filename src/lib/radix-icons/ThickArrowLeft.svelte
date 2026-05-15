<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ThickArrowLeft size={24} color="red" />
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
    <path fill="currentColor" d="M1 7.5a.5.5 0 0 0 .209.407l7 5A.5.5 0 0 0 9 12.5V10h2.5a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-.5-.5H9V2.5a.5.5 0 0 0-.791-.407l-7 5-.088.08A.5.5 0 0 0 1 7.5m7-4.027V5.5a.5.5 0 0 0 .5.5H11v3H8.5a.5.5 0 0 0-.5.5v2.027L2.36 7.5z"/>
</svg>
