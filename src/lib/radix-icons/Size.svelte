<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Size size={24} color="red" />
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
    <path fill="currentColor" d="M11.591 3.059c.205.042.36.224.36.441v4l-.01.091a.45.45 0 0 1-.882 0l-.009-.09V4.585L4.587 11.05l2.913.001.091.009a.45.45 0 0 1-.092.89H3.5a.45.45 0 0 1-.45-.45V7.5l.01-.09a.45.45 0 0 1 .882 0l.008.09v2.914l6.464-6.464H7.5a.45.45 0 0 1 0-.9h4z"/>
</svg>
