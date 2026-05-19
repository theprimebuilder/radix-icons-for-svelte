<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <OuterShadow size={24} color="red" />
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
    <path fill="currentColor" fill-rule="evenodd" d="M12.14 3.886a6 6 0 1 1-8.244 8.269l.425-.263a5.5 5.5 0 1 0 7.557-7.58z" clip-rule="evenodd" opacity=".05"/><path fill="currentColor" fill-rule="evenodd" d="M12.851 5.073a5.5 5.5 0 1 1-7.778 7.778l.357-.35a5 5 0 1 0 7.07-7.07z" clip-rule="evenodd" opacity=".2"/><path fill="currentColor" fill-rule="evenodd" d="M13.302 6.45a5 5 0 0 1-6.9 6.822l.26-.427a4.5 4.5 0 0 0 6.21-6.14z" clip-rule="evenodd" opacity=".35"/><path fill="currentColor" fill-rule="evenodd" d="M13.374 7.94q.125.511.126 1.06a4.5 4.5 0 0 1-5.627 4.358l.125-.485Q8.479 13 9 13a4 4 0 0 0 3.888-4.942z" clip-rule="evenodd" opacity=".5"/><path fill="currentColor" fill-rule="evenodd" d="M12.916 9.821a4 4 0 0 1-3.124 3.1l-.098-.49a3.5 3.5 0 0 0 2.732-2.712z" clip-rule="evenodd" opacity=".65"/><path fill="currentColor" fill-rule="evenodd" d="M1.277 7.503a6.225 6.225 0 1 1 12.45 0 6.225 6.225 0 0 1-12.45 0m6.225-5.275a5.275 5.275 0 1 0 0 10.55 5.275 5.275 0 0 0 0-10.55" clip-rule="evenodd"/>
</svg>
