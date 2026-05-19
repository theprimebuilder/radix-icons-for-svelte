<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Enter size={24} color="red" />
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
    <path fill="currentColor" d="M12 1a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4.5a.5.5 0 0 1 0-1H12V2H4.5a.5.5 0 0 1 0-1zM5.896 4.896a.5.5 0 0 1 .63-.064l.078.064 2.25 2.25.064.079a.5.5 0 0 1-.064.629l-2.25 2.25a.5.5 0 1 1-.708-.708L7.293 8H.5a.5.5 0 0 1 0-1h6.793L5.896 5.604l-.064-.079a.5.5 0 0 1 .064-.629"/>
</svg>
