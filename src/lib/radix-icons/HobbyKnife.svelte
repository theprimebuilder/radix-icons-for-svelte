<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <HobbyKnife size={24} color="red" />
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
    <path fill="currentColor" d="M12.225 13.918a.5.5 0 0 0 .629-.064l1.5-1.5.064-.079a.5.5 0 0 0 0-.55l-.064-.079-5.75-5.75A.5.5 0 0 0 8.5 5.82V5.5a.5.5 0 0 0-.164-.37l-5.4-4.9a.5.5 0 0 0-.809.535l2.4 6.9.032.071c.086.16.255.264.441.264H6.32a.5.5 0 0 0 .078.104l5.75 5.75zM3.716 2.289 7.5 5.722v.071L6.293 7h-.938zM7.457 7.75l.793-.793L13.293 12l-.793.793z"/>
</svg>
