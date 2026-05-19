<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <QuestionMarkCircled size={24} color="red" />
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
    <path fill="currentColor" d="M7.5.877a6.623 6.623 0 1 1 0 13.246A6.623 6.623 0 0 1 7.5.877m0 .95A5.674 5.674 0 1 0 7.5 13.17a5.674 5.674 0 0 0-.002-11.345m0 7.923a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m0-5.925c1.435 0 2.55 1.103 2.55 2.425 0 1.104-.73 1.64-1.265 1.965-.3.182-.48.271-.634.391a.5.5 0 0 0-.1.097l-.002.001A.55.55 0 0 1 6.95 8.7c0-.468.282-.773.525-.962.22-.172.54-.34.74-.463.465-.282.735-.534.735-1.025 0-.678-.585-1.325-1.45-1.325s-1.45.647-1.45 1.325a.55.55 0 1 1-1.1 0c0-1.322 1.115-2.425 2.55-2.425"/>
</svg>
