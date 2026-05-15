<script lang="ts">
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <PinTop size={24} color="red" />
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
    <path fill="currentColor" d="M7.252 4.124c.15-.099.346-.099.496 0l.07.058 3.25 3.25a.45.45 0 0 1-.636.637L7.95 5.587V13.5a.45.45 0 0 1-.9 0V5.587L4.569 8.07l-.07.057a.451.451 0 0 1-.625-.624l.058-.07 3.25-3.25zM13.5 1.05a.45.45 0 0 1 0 .9h-12a.45.45 0 0 1 0-.9z"/>
</svg>
