<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ViewHorizontal size={24} color="red" />
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
    <path fill="currentColor" d="M13.653 1.008A1.5 1.5 0 0 1 15 2.5v10l-.008.153a1.5 1.5 0 0 1-1.339 1.34L13.5 14h-12l-.153-.008a1.5 1.5 0 0 1-1.34-1.339L0 12.5v-10a1.5 1.5 0 0 1 1.347-1.492L1.5 1h12zM1 8v4.5a.5.5 0 0 0 .5.5h12a.5.5 0 0 0 .5-.5V8zm.5-6a.5.5 0 0 0-.5.5V7h13V2.5a.5.5 0 0 0-.5-.5z"/>
</svg>
