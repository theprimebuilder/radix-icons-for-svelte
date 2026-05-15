<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <PaperPlane size={24} color="red" />
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
    <path fill="currentColor" d="M.628 1.166a.5.5 0 0 1 .575-.123l13.5 6a.5.5 0 0 1 0 .914l-13.5 6a.5.5 0 0 1-.635-.709L3.921 7.5.568 1.752a.5.5 0 0 1 .06-.586M4.845 7.1H9l.081.008a.4.4 0 0 1 0 .784L9 7.9H4.845l-2.633 4.513L13.269 7.5 2.212 2.586z"/>
</svg>
