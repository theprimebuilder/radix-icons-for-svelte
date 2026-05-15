<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <RulerHorizontal size={24} color="red" />
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
    <path fill="currentColor" d="M14.6 4.01a.5.5 0 0 1 .4.49v6a.5.5 0 0 1-.5.5H.5a.5.5 0 0 1-.5-.5v-6l.01-.1A.5.5 0 0 1 .5 4h14zM1 10h13V5h-1.075v1.5a.425.425 0 1 1-.85 0V5h-1.15v1.5a.425.425 0 1 1-.85 0V5h-1.15v2.5a.425.425 0 1 1-.85 0V5h-1.15v1.5a.425.425 0 1 1-.85 0V5h-1.15v1.5a.425.425 0 1 1-.85 0V5h-1.15v2.5a.425.425 0 1 1-.85 0V5H1z"/>
</svg>
