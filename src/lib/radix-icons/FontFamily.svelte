<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <FontFamily size={24} color="red" />
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
    <path fill="currentColor" d="M12.499 2a.5.5 0 0 1 .001 1H8.692l-.287.854c-.216.643-.51 1.518-.824 2.444L7.344 7H8.5a.5.5 0 0 1 0 1H7.004c-.437 1.285-.84 2.462-1.046 3.04-.322.899-.751 1.446-1.291 1.738-.504.273-1.025.272-1.383.272H3.25a.55.55 0 1 1 0-1.1c.392 0 .653-.01.894-.14.22-.119.511-.396.778-1.142.185-.517.531-1.527.92-2.668H4.5a.5.5 0 0 1 0-1h1.682l.357-1.055c.313-.925.607-1.799.823-2.441L7.532 3H5c-.849 0-1.5.651-1.5 1.5a.5.5 0 0 1-1 0C2.5 3.099 3.599 2 5 2z"/>
</svg>
