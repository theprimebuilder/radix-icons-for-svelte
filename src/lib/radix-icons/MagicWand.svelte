<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <MagicWand size={24} color="red" />
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
    <path fill="currentColor" d="M9.224 5.082a.5.5 0 0 1 .694.694l-.065.078-7 7a.5.5 0 0 1-.707-.707l7-7zM13.5 5.1c.22 0 .4.18.4.4v.6h.6l.08.009a.4.4 0 0 1 0 .783l-.08.009h-.6v.6a.401.401 0 0 1-.8 0v-.6h-.6a.401.401 0 0 1 0-.801h.6v-.6c0-.22.179-.4.4-.4m-2.275-2.018a.5.5 0 0 1 .693.694l-.065.078-1 1a.5.5 0 0 1-.707-.707l1-1zM8.5.1c.22 0 .4.18.4.4v.6h.6l.08.009a.4.4 0 0 1 0 .783l-.08.009h-.6v.6a.401.401 0 0 1-.8 0v-.6h-.6a.401.401 0 0 1 0-.801h.6V.5c0-.22.179-.4.4-.4m5 0c.22 0 .4.18.4.4v.6h.6l.08.009a.4.4 0 0 1 0 .783l-.08.009h-.6v.6a.401.401 0 0 1-.8 0v-.6h-.6a.401.401 0 0 1 0-.801h.6V.5c0-.22.179-.4.4-.4"/>
</svg>
