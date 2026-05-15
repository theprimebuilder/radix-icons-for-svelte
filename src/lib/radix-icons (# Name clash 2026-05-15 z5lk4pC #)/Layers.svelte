<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Layers size={24} color="red" />
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
    <path fill="currentColor" d="M12.838 10.277a.5.5 0 0 1 .498.843l-.082.06-5.5 3.25a.5.5 0 0 1-.508 0l-5.5-3.25-.082-.06a.5.5 0 0 1 .498-.843l.092.042 5.246 3.1 5.246-3.1zm0-3a.5.5 0 0 1 .498.843l-.082.06-5.5 3.25a.5.5 0 0 1-.508 0l-5.5-3.25-.082-.06a.5.5 0 0 1 .498-.843l.092.042 5.246 3.1 5.246-3.1zM7.306.79a.5.5 0 0 1 .448.03l5.5 3.25a.5.5 0 0 1 0 .862l-5.5 3.25a.5.5 0 0 1-.508 0l-5.5-3.25a.5.5 0 0 1 0-.862l5.5-3.25zM2.982 4.5 7.5 7.17 12.017 4.5 7.5 1.83z"/>
</svg>
