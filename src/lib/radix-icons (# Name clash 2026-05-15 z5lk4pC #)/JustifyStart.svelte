<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <JustifyStart size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M1.05 13.5a.45.45 0 0 0 .9 0v-12a.45.45 0 1 0-.9 0zM11 9H4V6h7zm-7.25 1A.75.75 0 0 1 3 9.25v-3.5A.75.75 0 0 1 3.75 5h7.5a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-.75.75z" clip-rule="evenodd"/>
</svg>
