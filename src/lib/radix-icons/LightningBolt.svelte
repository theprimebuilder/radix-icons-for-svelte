<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <LightningBolt size={24} color="red" />
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
    <path fill="currentColor" d="M8.156.137a.5.5 0 0 1 .837.445L8.09 6h4.41a.5.5 0 0 1 .4.8l-6 8a.5.5 0 0 1-.893-.382L6.91 9H2.5a.5.5 0 0 1-.4-.8l6-8zM3.5 8h4a.5.5 0 0 1 .493.582l-.663 3.977L11.5 7h-4a.5.5 0 0 1-.493-.582l.662-3.977z"/>
</svg>
