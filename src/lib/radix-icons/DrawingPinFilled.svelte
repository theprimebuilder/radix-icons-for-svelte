<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DrawingPinFilled size={24} color="red" />
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
    <path fill="currentColor" d="M9.621 1.136a.5.5 0 0 1 .707 0l3.536 3.535a.5.5 0 0 1-.707.707l-.653-.652-3.637 4.848 1.107 1.108a.5.5 0 0 1-.707.707L6.793 8.913v.001l-3.27 3.27a.5.5 0 0 1-.708-.706l3.27-3.27v-.002L3.612 5.732a.5.5 0 1 1 .707-.707l1.108 1.108 4.848-3.637-.653-.653a.5.5 0 0 1 0-.707"/><path fill="currentColor" d="M9.621 1.136a.5.5 0 0 1 .707 0l3.536 3.535a.5.5 0 0 1-.707.707l-.653-.652-3.637 4.848 1.107 1.108a.5.5 0 0 1-.707.707L6.793 8.913v.001l-3.27 3.27a.5.5 0 0 1-.708-.706l3.27-3.27v-.002L3.612 5.732a.5.5 0 1 1 .707-.707l1.108 1.108 4.848-3.637-.653-.653a.5.5 0 0 1 0-.707"/>
</svg>
