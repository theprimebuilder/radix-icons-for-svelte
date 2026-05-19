<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <PinRight size={24} color="red" />
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
    <path fill="currentColor" d="M9.876 7.252c.099.15.099.346 0 .496l-.058.07-3.25 3.25a.45.45 0 0 1-.637-.636L8.413 7.95H.5a.45.45 0 0 1 0-.9h7.913L5.93 4.569l-.057-.07a.451.451 0 0 1 .624-.625l.07.058 3.25 3.25zM12.95 13.5a.45.45 0 0 1-.9 0v-12a.45.45 0 0 1 .9 0z"/>
</svg>
