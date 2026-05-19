<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <TrackNext size={24} color="red" />
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
    <path fill="currentColor" d="M12.5 2.2a.55.55 0 0 1 .55.55v9.5a.55.55 0 1 1-1.1 0V7.716a.5.5 0 0 1-.217.226l-9 4.75A.5.5 0 0 1 2 12.25v-9.5a.5.5 0 0 1 .733-.443l9 4.75a.5.5 0 0 1 .217.227V2.75a.55.55 0 0 1 .55-.55M3 11.42l7.428-3.92L3 3.579z"/>
</svg>
