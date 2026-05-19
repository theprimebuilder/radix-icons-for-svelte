<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <SpeakerLoud size={24} color="red" />
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
    <path fill="currentColor" d="M7.002 1.066a.5.5 0 0 1 .748.434v12a.5.5 0 0 1-.807.395L3.222 11H1.5A1.5 1.5 0 0 1 .008 9.653L0 9.5v-4A1.5 1.5 0 0 1 1.5 4h1.722l3.721-2.894zm5.113.318a.4.4 0 0 1 .564.047l.268.332a9.405 9.405 0 0 1 0 11.475l-.268.332-.059.056a.4.4 0 0 1-.598-.507l.046-.066.245-.304a8.605 8.605 0 0 0 .002-10.497l-.247-.305-.045-.066a.4.4 0 0 1 .092-.497M3.7 4.894A.5.5 0 0 1 3.393 5H1.5a.5.5 0 0 0-.5.5v4l.01.1a.5.5 0 0 0 .49.4h1.893l.083.007a.5.5 0 0 1 .224.099l3.05 2.372V2.522zm6.578-1.046a.4.4 0 0 1 .503.049l.052.062.13.203a6.41 6.41 0 0 1-.13 6.88.4.4 0 0 1-.666-.444 5.61 5.61 0 0 0 .112-6.019l-.113-.176-.037-.072a.4.4 0 0 1 .15-.483"/>
</svg>
