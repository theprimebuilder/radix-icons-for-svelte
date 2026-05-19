<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <StarFilled size={24} color="red" />
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
    <path fill="currentColor" d="M7.223.666a.3.3 0 0 1 .554 0L9.413 4.6a.3.3 0 0 0 .253.183l4.248.34a.3.3 0 0 1 .17.528L10.85 8.424a.3.3 0 0 0-.097.298l.99 4.144a.3.3 0 0 1-.45.326l-3.636-2.221a.3.3 0 0 0-.312 0l-3.637 2.221a.3.3 0 0 1-.448-.326l.989-4.144a.3.3 0 0 0-.097-.298L.915 5.652a.3.3 0 0 1 .17-.527l4.249-.34a.3.3 0 0 0 .253-.184z"/>
</svg>
