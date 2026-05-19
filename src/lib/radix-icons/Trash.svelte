<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Trash size={24} color="red" />
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
    <path fill="currentColor" d="M11.5 3a.5.5 0 0 1 0 1H11v8l-.005.102a1 1 0 0 1-.893.893L10 13H5l-.103-.005a1 1 0 0 1-.892-.893L4 12V4h-.5a.5.5 0 0 1 0-1zM5 12h5V4H5zM9.5 1a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1z"/>
</svg>
