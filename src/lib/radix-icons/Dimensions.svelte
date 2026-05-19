<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Dimensions size={24} color="red" />
     * ```
     */
    interface Props extends SVGAttributes<SVGElement> {
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
    <path fill="currentColor" d="M13.303 4.004a.25.25 0 0 1 .394 0l1.24 1.593a.25.25 0 0 1-.199.403H14v6h.738a.25.25 0 0 1 .199.403l-1.24 1.593a.25.25 0 0 1-.394 0l-1.24-1.593a.25.25 0 0 1 .198-.403H13V6h-.74a.25.25 0 0 1-.197-.403zm-3.65.004A1.5 1.5 0 0 1 11 5.5v7l-.008.153a1.5 1.5 0 0 1-1.339 1.34L9.5 14h-7l-.153-.008a1.5 1.5 0 0 1-1.34-1.339L1 12.5v-7a1.5 1.5 0 0 1 1.347-1.492L2.5 4h7zM2.5 5a.5.5 0 0 0-.5.5v7a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.5-.5zM9 .262a.25.25 0 0 1 .403-.198l1.593 1.239a.25.25 0 0 1 0 .394l-1.593 1.24A.25.25 0 0 1 9 2.739V2H3v.74a.25.25 0 0 1-.403.197l-1.593-1.24a.25.25 0 0 1 0-.394L2.597.063A.25.25 0 0 1 3 .262V1h6z"/>
</svg>
