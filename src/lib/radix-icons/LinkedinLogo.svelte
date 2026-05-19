<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <LinkedinLogo size={24} color="red" />
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
    <path fill="currentColor" d="M13 1a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1zM9.675 5.85c-.38-.018-.758.061-1.096.231-.257.129-.527.424-.734.938h-.053V6H6v6.005h1.906V8.812c-.027-.328.077-.75.291-1.002s.521-.312.753-.342h.072c.607 0 1.056.375 1.056 1.321v3.216h1.906L12 8.357c0-1.804-1.166-2.506-2.325-2.506M3.05 12h1.9V6h-1.9zM4 2.93a1.075 1.075 0 1 0 0 2.15 1.075 1.075 0 0 0 0-2.15"/>
</svg>
