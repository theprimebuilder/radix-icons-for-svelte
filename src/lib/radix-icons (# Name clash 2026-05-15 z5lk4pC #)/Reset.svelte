<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Reset size={24} color="red" />
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
    <path fill="currentColor" d="M4.225 2.082a.5.5 0 0 1 .693.694l-.065.078L3.707 4H9a4.5 4.5 0 0 1 0 9H5a.5.5 0 1 1 0-1h4a3.5 3.5 0 1 0 0-7H3.707l1.146 1.147.065.078a.5.5 0 0 1-.693.693l-.079-.064-2-2a.5.5 0 0 1 0-.707l2-2z"/>
</svg>
