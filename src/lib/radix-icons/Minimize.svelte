<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Minimize size={24} color="red" />
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
    <path fill="currentColor" d="M6.5 8.05a.45.45 0 0 1 .45.45v4a.45.45 0 0 1-.9 0V9.584l-3.732 3.733a.45.45 0 1 1-.636-.636l3.731-3.731L2.5 8.95a.449.449 0 1 1 0-.9zm6.182-6.368a.45.45 0 0 1 .637.636L9.586 6.05H12.5a.45.45 0 0 1 0 .9h-4l-.09-.01a.45.45 0 0 1-.36-.44v-4a.45.45 0 0 1 .9 0v2.914z"/>
</svg>
