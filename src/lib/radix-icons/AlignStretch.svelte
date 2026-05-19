<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <AlignStretch size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M1.05 1.5a.45.45 0 0 1 .45-.45h12a.45.45 0 0 1 0 .9h-12a.45.45 0 0 1-.45-.45m0 12a.45.45 0 0 1 .45-.45h12a.45.45 0 0 1 0 .9h-12a.45.45 0 0 1-.45-.45M6 11V4h3v7zM5 3.75A.75.75 0 0 1 5.75 3h3.5a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-.75.75h-3.5a.75.75 0 0 1-.75-.75z" clip-rule="evenodd"/>
</svg>
