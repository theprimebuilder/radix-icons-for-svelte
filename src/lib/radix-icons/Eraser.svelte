<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Eraser size={24} color="red" />
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
    <path fill="currentColor" d="M8.36.73a.5.5 0 0 1 .707 0l5.203 5.202.065.079a.5.5 0 0 1-.065.628l-6.923 6.924a1.5 1.5 0 0 1-2.122 0L1.436 9.774a1.5 1.5 0 0 1-.102-2.007l.102-.114zM2.143 8.36a.5.5 0 0 0 0 .707l3.79 3.79a.5.5 0 0 0 .707 0L7.894 11.6 3.398 7.105zm1.962-1.962 4.496 4.496 4.609-4.608L8.714 1.79z"/>
</svg>
