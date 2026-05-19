<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DrawingPinSolid size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M9.621 1.136a.5.5 0 0 1 .707 0l1.061 1.06 1.414 1.415 1.06 1.06a.5.5 0 1 1-.706.708l-.653-.653-3.637 4.848 1.108 1.108a.5.5 0 0 1-.707.707L7.854 9.975l-1.061-1.06-3.27 3.27a.5.5 0 1 1-.708-.708l3.27-3.27-1.06-1.06-1.414-1.415a.5.5 0 1 1 .707-.707l1.108 1.108 4.848-3.637-.653-.653a.5.5 0 0 1 0-.707" clip-rule="evenodd"/><path fill="currentColor" fill-rule="evenodd" d="M9.621 1.136a.5.5 0 0 1 .707 0l1.061 1.06 1.414 1.415 1.06 1.06a.5.5 0 1 1-.706.708l-.653-.653-3.637 4.848 1.108 1.108a.5.5 0 0 1-.707.707L7.854 9.975l-1.061-1.06-3.27 3.27a.5.5 0 1 1-.708-.708l3.27-3.27-1.06-1.06-1.414-1.415a.5.5 0 1 1 .707-.707l1.108 1.108 4.848-3.637-.653-.653a.5.5 0 0 1 0-.707" clip-rule="evenodd"/>
</svg>
