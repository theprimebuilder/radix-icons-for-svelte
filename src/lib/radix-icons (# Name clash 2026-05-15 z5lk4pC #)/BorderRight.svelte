<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <BorderRight size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M13.25 1v13h1.5V1z" clip-rule="evenodd"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 5 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 5 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 3 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 3 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 5)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 5)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 3)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 3)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 9)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 9)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 11)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 11)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 9 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 9 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 11 7)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 11 13)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 5 1)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 3 1)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 7 1)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 1 1)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 9 1)"/><rect width="1" height="1" fill="currentColor" rx=".5" transform="matrix(0 1 1 0 11 1)"/>
</svg>
