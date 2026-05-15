<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Width size={24} color="red" />
     * ```
     */
    interface Props {
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
    <path fill="currentColor" d="M10.182 4.682a.45.45 0 0 1 .566-.058l.07.058 2.5 2.5.058.07a.45.45 0 0 1 0 .496l-.058.07-2.5 2.5a.45.45 0 0 1-.636-.636l1.731-1.732H3.087l1.731 1.732.058.07a.451.451 0 0 1-.624.624l-.07-.058-2.5-2.5a.45.45 0 0 1 0-.636l2.5-2.5.07-.058a.45.45 0 0 1 .624.624l-.058.07L3.087 7.05h8.826l-1.731-1.732-.058-.07a.45.45 0 0 1 .058-.566"/>
</svg>
