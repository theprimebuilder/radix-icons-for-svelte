<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <EnvelopeOpen size={24} color="red" />
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
    <path fill="currentColor" d="M7.16.119a1 1 0 0 1 .787.046l6.5 3.25.121.072a1 1 0 0 1 .432.822V12a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4.31a1 1 0 0 1 .553-.894l6.5-3.25zm.55 8.08a.45.45 0 0 1-.42 0L1 4.884V12h13V4.884zM1.43 4.093 7.5 7.291l6.068-3.198L7.5 1.06z"/>
</svg>
