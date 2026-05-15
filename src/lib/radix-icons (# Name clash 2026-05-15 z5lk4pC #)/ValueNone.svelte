<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ValueNone size={24} color="red" />
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
    <path fill="currentColor" d="M7.5.877c1.648 0 3.155.604 4.315 1.6l.832-.83a.5.5 0 0 1 .707.707l-.832.83a6.623 6.623 0 0 1-9.337 9.337l-.831.833a.5.5 0 0 1-.707-.707l.83-.832A6.623 6.623 0 0 1 7.499.877M3.856 11.85a5.673 5.673 0 0 0 7.991-7.991zM7.5 1.826A5.674 5.674 0 0 0 1.826 7.5a5.65 5.65 0 0 0 1.325 3.642l7.99-7.99a5.65 5.65 0 0 0-3.642-1.325"/>
</svg>
