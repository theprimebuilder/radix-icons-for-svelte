<script lang="ts">
		import type { SVGAttributes } from 'svelte/elements';
    /**
     * @component
     * Icon built with Radix Icons design.
     * Check their page: https://www.radix-ui.com/icons
     * * @example
     * ```svelte
     * <Pencil2 size={24} color="red" />
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
    <path fill="currentColor" d="M9 3H4.9c-.428 0-.72 0-.945.019-.219.018-.331.05-.41.09a1 1 0 0 0-.436.437c-.04.078-.073.19-.09.41C3 4.18 3 4.471 3 4.9v6.2c0 .428 0 .72.019.945.017.219.05.33.09.41l.082.133a1 1 0 0 0 .355.303l.066.028c.075.027.179.049.343.062.225.019.517.019.945.019h6.2c.428 0 .72 0 .945-.019.219-.018.33-.05.409-.09l.134-.082c.127-.093.23-.214.303-.355l.028-.066c.026-.075.049-.179.062-.343.019-.225.019-.517.019-.945V7l1-1v5.1c0 .411 0 .75-.023 1.026-.017.21-.049.409-.116.597l-.079.185a2 2 0 0 1-.736.797l-.138.077c-.243.124-.501.172-.782.195C11.85 14 11.51 14 11.1 14H4.9c-.411 0-.75 0-1.026-.023a2.3 2.3 0 0 1-.597-.116l-.185-.079a2 2 0 0 1-.797-.736l-.077-.138c-.124-.242-.173-.501-.196-.782C2 11.851 2 11.511 2 11.1V4.9c0-.411 0-.75.022-1.026.023-.28.072-.54.196-.782a2 2 0 0 1 .874-.874c.242-.124.501-.172.782-.195C4.149 2 4.489 2 4.9 2H10zm3.225-1.918a.5.5 0 0 1 .628.065l2 2 .065.078a.5.5 0 0 1-.065.629l-3.942 3.942q-.115.115-.26.187L6.724 9.947a.5.5 0 0 1-.671-.67l1.964-3.928q.072-.145.187-.26l3.942-3.942zM8.91 5.796 7.872 7.872l.255.255 2.077-1.038L13.793 3.5 12.5 2.207z"/>
</svg>
