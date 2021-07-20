# @astrojs/parser

## 0.18.0-next.2

### Patch Changes

- a7e6666: compile javascript to target Node v12.x

## 0.15.4

### Patch Changes

- 6a660f1: Adds low-level custom element support that renderers can use to enable server side rendering. This will be used in renderers such as a Lit renderer.

## 0.15.0

### Patch Changes

- 47ac2cc: Fix #521, allowing `{...spread}` props to work again

## 0.13.10

### Patch Changes

- 7f8d586: Bugfix: template literals in JSX tags breaking parser

## 0.13.9

### Patch Changes

- f9f2da4: Add repository key to all package.json

## 0.13.8

### Patch Changes

- 490f2be: Add support for Fragments with `<>` and `</>` syntax

## 0.13.3

### Patch Changes

- ab2972b: Update package.json engines for esm support

## 0.12.1

### Patch Changes

- 6de740d: Fix for when there's a parser error with unmatched backticks

## 0.12.0

### Patch Changes

- d2330a5: Improve error display for missing local files

### 0.12.0-next.0

### Patch Changes

- Fixes a few more Markdown issues

## 0.11.0

### Patch Changes

- 9cdada0: Fixes a few edge case bugs with Astro's handling of Markdown content

## 0.1.0

### Minor Changes

- b3886c2: Enhanced **Markdown** support! Markdown processing has been moved from `micromark` to `remark` to prepare Astro for user-provided `remark` plugins _in the future_.

  This change also introduces a built-in `<Markdown>` component for embedding Markdown and any Astro-supported component format inside of `.astro` files. [Read more about Astro's Markdown support.](https://docs.astro.build/markdown/)
