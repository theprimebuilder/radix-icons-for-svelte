<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Button size={24} color="red" />
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
    <path fill="currentColor" d="M13.204 4.01A2 2 0 0 1 15 6v3l-.01.204a2 2 0 0 1-1.786 1.785L13 11H2l-.204-.01A2 2 0 0 1 .01 9.203L0 9V6a2 2 0 0 1 1.796-1.99L2 4h11zM2 5a1 1 0 0 0-.995.897L1 6v3a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1V6a1 1 0 0 0-.898-.995L13 5zm2.5 1.75a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m3 0a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m3 0a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5"/>
</svg>
