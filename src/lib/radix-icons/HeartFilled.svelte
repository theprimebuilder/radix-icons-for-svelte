<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <HeartFilled size={24} color="red" />
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
    <path fill="currentColor" d="M10.106 1.352a3.547 3.547 0 0 1 3.541 3.553c0 1.835-1.046 3.6-2.247 5.065-1.137 1.386-2.478 2.58-3.394 3.396l-.173.154a.5.5 0 0 1-.666 0l-.173-.154c-.916-.815-2.257-2.01-3.394-3.396-1.201-1.465-2.248-3.23-2.248-5.065a3.547 3.547 0 0 1 3.541-3.553c1.365 0 1.968.571 2.607 1.583.64-1.012 1.242-1.582 2.606-1.583"/>
</svg>
