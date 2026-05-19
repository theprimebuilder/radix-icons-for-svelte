<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <LetterSpacing size={24} color="red" />
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
    <path fill="currentColor" d="M12.27 10.217a.4.4 0 0 1 .567 0l2 2 .05.061a.4.4 0 0 1-.05.505l-2 2-.063.05a.4.4 0 0 1-.554-.553l.05-.063 1.317-1.317H1.521l1.316 1.317a.401.401 0 0 1-.566.566l-2-2a.4.4 0 0 1 0-.566l2-2 .063-.051a.4.4 0 0 1 .554.554l-.05.063L1.52 12.1h12.066l-1.316-1.317a.4.4 0 0 1 0-.566m1.119-8.99a.5.5 0 0 1 .911.358l-.027.098-2.752 7.002a.5.5 0 0 1-.898.068l-.033-.068-2.752-7.002a.501.501 0 0 1 .932-.366l2.285 5.819 2.287-5.819zM4.553 1c.2 0 .38.12.46.303L8.01 8.3l.03.096a.5.5 0 0 1-.9.386l-.05-.089-.975-2.276H2.99l-.976 2.276-.05.09a.5.5 0 0 1-.87-.483l3-6.997.033-.066A.5.5 0 0 1 4.553 1m-1.2 4.567H5.75L4.552 2.77z"/>
</svg>
