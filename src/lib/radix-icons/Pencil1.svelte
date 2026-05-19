<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Pencil1 size={24} color="red" />
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
    <path fill="currentColor" d="M11.225 1.082a.5.5 0 0 1 .629.064l2 2 .064.079a.5.5 0 0 1-.064.629l-7.432 7.431a1 1 0 0 1-.228.171l-.086.041-3.41 1.463a.5.5 0 0 1-.658-.657l1.463-3.411.04-.086q.07-.126.172-.228l7.432-7.432zM4.422 9.285 3.78 10.78l.438.438 1.497-.64L12.793 3.5 11.5 2.207z"/>
</svg>
