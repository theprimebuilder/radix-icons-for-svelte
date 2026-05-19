<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <DropdownMenu size={24} color="red" />
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
    <path fill="currentColor" d="M14.581 11.109a.4.4 0 0 1 0 .783l-.081.009h-7a.4.4 0 0 1 0-.801h7zm0-2a.4.4 0 0 1 0 .783L14.5 9.9h-7a.401.401 0 0 1 0-.801h7zM2.5 9.25 0 6h5zM14.581 7.11a.4.4 0 0 1 0 .783L14.5 7.9h-7a.401.401 0 0 1 0-.801h7zm0-2a.4.4 0 0 1 0 .783L14.5 5.9h-7a.401.401 0 0 1 0-.801h7zm0-2a.4.4 0 0 1 0 .783l-.081.009h-7a.401.401 0 0 1 0-.801h7z"/>
</svg>
