<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <ExclamationTriangle size={24} color="red" />
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
    <path fill="currentColor" d="M6.642.483a1.1 1.1 0 0 1 1.803.125l6.394 10.729A1.1 1.1 0 0 1 13.894 13H1.106a1.1 1.1 0 0 1-.944-1.663L6.555.608zm.81.6-.037.038L1.02 11.848a.1.1 0 0 0 .086.152h12.788a.1.1 0 0 0 .086-.152L7.586 1.121a.1.1 0 0 0-.134-.037m.047 8.643a.75.75 0 1 1 0 1.5.75.75 0 0 1 0-1.5m0-5.94c.383 0 .689.318.674.7L8.02 8.487a.52.52 0 0 1-1.038 0l-.154-4.001a.674.674 0 0 1 .672-.7"/>
</svg>
