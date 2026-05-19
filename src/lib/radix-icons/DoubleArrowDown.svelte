<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DoubleArrowDown size={24} color="red" />
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
    <path fill="currentColor" d="M11.225 8.082a.5.5 0 0 1 .693.694l-.064.078-4 4a.5.5 0 0 1-.707 0l-4-4-.065-.078a.5.5 0 0 1 .694-.694l.078.065L7.5 11.793l3.647-3.646zm0-6a.5.5 0 0 1 .693.694l-.064.078-4 4a.5.5 0 0 1-.707 0l-4-4-.065-.078a.5.5 0 0 1 .694-.694l.078.065L7.5 5.793l3.647-3.646z"/>
</svg>
