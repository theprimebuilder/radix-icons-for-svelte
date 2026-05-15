# Redix icons for svelte

[![npm version](https://img.shields.io/npm/v/@theprimebuilder/radix-icons-for-svelte?color=f5f5f7&labelColor=1c1c1e&style=flat-square)](https://www.npmjs.com/package/@theprimebuilder/radix-icons-for-svelte)
[![license](https://img.shields.io/npm/l/@theprimebuilder/radix-icons-for-svelte?color=f5f5f7&labelColor=1c1c1e&style=flat-square)](./LICENSE)
[![svelte](https://img.shields.io/badge/svelte-%23FF3E00.svg?style=flat-square&logo=svelte&logoColor=white)](https://svelte.dev)
## Information

Note : This package has been created to provide Redix Icons for svelte because Redix Icons support only React.

See Redix icons page to learn more and discover page [Radix Icons](https://www.radix-ui.com/icons).

NPM Page [NPM](https://www.npmjs.com/package/@theprimebuilder/radix-icons-for-svelte)

Github Project Page [Github](https://github.com/theprimebuilder/radix-icons-for-svelte)

Report issues [Issues](https://github.com/theprimebuilder/radix-icons-for-svelte/issues)

Share your insights about this [Discussions](https://github.com/theprimebuilder/radix-icons-for-svelte/discussions/1)

## Installation

```bash
bun add @theprimebuilder/radix-icons-for-svelte
# or npm i @theprimebuilder/radix-icons-for-svelte
```

## Usage

Sample use case example

```svelte
<script>
	import { ArrowBottomLeft } from '@theprimebuilder/radix-icons-for-svelte';
</script>

<ArrowBottomLeft size={24} color="pink" />

```
## Props

This package supports all standard SVG attributes (`class`, `style`, `aria-label`, etc.) via Svelte rest props, along with the following custom properties:

| Prop | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `size` | `number` | `15` | Icon size in pixels (applies to both height and width). |
| `color` | `string` | `'currentColor'` | Icon color. Accepts any valid CSS color value (hex, rgb, currentColor, variables). |

## License

- **Library & Scripts:** MIT © 2026 [The Prime Builder](https://github.com/theprimebuilder)
- **Icons Design:** MIT © [WorkOS](https://www.radix-ui.com/)

This package is an independent tool that optimizes and builds Radix Icons for Svelte 5.
