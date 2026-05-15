<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <JustifyCenter size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M7.95 6H11v3H7.95zm0-1V1.5a.45.45 0 0 0-.9 0V5h-3.3a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75h3.3v3.5a.45.45 0 1 0 .9 0V10h3.3a.75.75 0 0 0 .75-.75v-3.5a.75.75 0 0 0-.75-.75zm-.9 4H4V6h3.05z" clip-rule="evenodd"/>
</svg>
