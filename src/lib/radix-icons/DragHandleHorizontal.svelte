<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DragHandleHorizontal size={24} color="red" />
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
    <path fill="currentColor" d="M12.581 10.109a.4.4 0 0 1 0 .783l-.08.009h-10a.401.401 0 0 1 0-.801h10zm0-2a.4.4 0 0 1 0 .783l-.08.009h-10a.401.401 0 0 1 0-.801h10zm0-2a.4.4 0 0 1 0 .783l-.08.009h-10a.401.401 0 0 1 0-.801h10zm0-2a.4.4 0 0 1 0 .783l-.08.009h-10a.401.401 0 0 1 0-.801h10z"/>
</svg>
