<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Height size={24} color="red" />
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
    <path fill="currentColor" d="M7.252 1.624a.45.45 0 0 1 .566.058l2.5 2.5.058.07a.45.45 0 0 1-.624.624l-.07-.057L7.95 3.087v8.826l1.731-1.731a.45.45 0 0 1 .637.637l-2.5 2.5a.45.45 0 0 1-.637 0l-2.5-2.5-.057-.07a.45.45 0 0 1 .624-.625l.07.058 1.732 1.731V3.087L5.318 4.82a.45.45 0 0 1-.637-.637l2.5-2.5z"/>
</svg>
