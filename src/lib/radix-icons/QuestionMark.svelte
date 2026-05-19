<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <QuestionMark size={24} color="red" />
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
    <path fill="currentColor" d="M7.5 11.607a.876.876 0 1 1 0 1.751.876.876 0 0 1 0-1.75M7.5.775c1.719 0 3.575 1.353 3.575 3.325 0 1.653-.942 2.474-1.693 3.14-.752.667-1.307 1.176-1.307 2.26a.575.575 0 0 1-1.15 0c0-1.642.946-2.457 1.693-3.12.75-.665 1.307-1.181 1.307-2.28 0-1.189-1.182-2.174-2.425-2.175S5.075 2.911 5.075 4.1a.576.576 0 0 1-1.15 0C3.925 2.128 5.782.775 7.5.775"/>
</svg>
