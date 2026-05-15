<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <AlignVerticalCenters size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M2 3.25C2 2.56 2.56 2 3.25 2h8.5c.69 0 1.25.56 1.25 1.25v2.5C13 6.44 12.44 7 11.75 7h-8.5C2.56 7 2 6.44 2 5.75zM3.25 3a.25.25 0 0 0-.25.25v2.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-2.5a.25.25 0 0 0-.25-.25zM4 9.25C4 8.56 4.56 8 5.25 8h4.5c.69 0 1.25.56 1.25 1.25v2.5c0 .69-.56 1.25-1.25 1.25h-4.5C4.56 13 4 12.44 4 11.75z" clip-rule="evenodd"/>
</svg>
