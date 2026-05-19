<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <FramerLogo size={24} color="red" />
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
    <path fill="currentColor" d="M11.6 1.007a.5.5 0 0 1 .4.49V5.5a.5.5 0 0 1-.5.5H8.636l2.893 3.162.045.058a.5.5 0 0 1-.414.78H8v3.5a.5.5 0 0 1-.854.354l-4-4A.5.5 0 0 1 3 9.5v-4l.01-.1A.5.5 0 0 1 3.5 5h2.865L3.471 1.834A.5.5 0 0 1 3.84.997h7.66zM7 12.293V10H4.707zM4 9h6.025L7.28 6H4zm3.72-4H11V1.997H4.975z"/>
</svg>
