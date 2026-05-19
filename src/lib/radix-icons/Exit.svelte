<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Exit size={24} color="red" />
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
    <path fill="currentColor" d="M10.5 1a.5.5 0 1 1 0 1H3v11h7.5a.5.5 0 1 1 0 1H3a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1zm1.396 3.896a.5.5 0 0 1 .63-.064l.077.064 2.25 2.25.065.078a.5.5 0 0 1-.065.63l-2.25 2.25a.5.5 0 0 1-.707-.708L13.293 8H6.5a.5.5 0 0 1 0-1h6.793l-1.397-1.397-.064-.078a.5.5 0 0 1 .064-.629"/>
</svg>
