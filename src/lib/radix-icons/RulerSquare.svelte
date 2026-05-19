<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <RulerSquare size={24} color="red" />
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
    <path fill="currentColor" d="M14.6.01a.5.5 0 0 1 .4.49v4a.5.5 0 0 1-.5.5H5v9.5a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5V.5L.01.4A.5.5 0 0 1 .5 0h14zM1 4.925V14h3v-1.075H2.75a.425.425 0 1 1 0-.85H4v-1.15H2.25a.425.425 0 1 1 0-.85H4v-1.15H2.75a.425.425 0 1 1 0-.85H4v-1.15H2.75a.425.425 0 1 1 0-.85H4v-1.15zm0-.85h3.075V1H1zM4.925 4h1.15V2.75a.425.425 0 1 1 .85 0V4h1.15V2.75a.425.425 0 1 1 .85 0V4h1.15V2.25a.425.425 0 1 1 .85 0V4h1.15V2.75a.425.425 0 1 1 .85 0V4H14V1H4.925z"/>
</svg>
