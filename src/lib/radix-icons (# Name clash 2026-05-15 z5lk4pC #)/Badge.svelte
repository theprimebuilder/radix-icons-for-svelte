<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Badge size={24} color="red" />
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
    <path fill="currentColor" d="M11.756 5.013a2.5 2.5 0 0 1 0 4.974L11.5 10h-8l-.256-.013a2.5 2.5 0 0 1 0-4.974L3.5 5h8zM3.5 6a1.5 1.5 0 1 0 0 3h8a1.5 1.5 0 0 0 0-3zm7 1a.5.5 0 0 1 0 1h-6a.5.5 0 0 1 0-1z"/>
</svg>
