<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Update size={24} color="red" />
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
    <path fill="currentColor" d="M7.988 1.563a.52.52 0 0 1 .608-.417l.269.056c2.764.638 5.188 3.036 5.188 6.501 0 1.537-.7 2.745-1.515 3.663-.585.659-1.255 1.193-1.793 1.602h1.637a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 1 0v1.846l.182-.138c.534-.405 1.152-.892 1.694-1.502.715-.804 1.252-1.776 1.252-2.97 0-3.012-2.16-5.073-4.606-5.533l-.102-.03a.52.52 0 0 1-.314-.578M.86 7.297c0-1.536.7-2.744 1.515-3.663.585-.658 1.255-1.192 1.793-1.602H2.532a.5.5 0 0 1 0-1h3a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0V2.687l-.182.137c-.534.405-1.152.892-1.694 1.502-.715.804-1.252 1.776-1.252 2.971 0 3.044 2.207 5.118 4.685 5.547a.522.522 0 0 1-.177 1.027C3.5 13.367.86 10.913.86 7.297"/>
</svg>
