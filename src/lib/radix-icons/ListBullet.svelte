<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ListBullet size={24} color="red" />
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
    <path fill="currentColor" d="M1.5 9.75a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m12.1.26a.5.5 0 0 1 0 .98l-.1.01h-9a.5.5 0 1 1 0-1h9zM1.5 6.75a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m12.1.26a.5.5 0 0 1 0 .98l-.1.01h-9a.5.5 0 0 1 0-1h9zM1.5 3.75a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m12.1.26a.5.5 0 0 1 0 .98l-.1.01h-9a.5.5 0 0 1 0-1h9z"/>
</svg>
