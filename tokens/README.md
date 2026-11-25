# Locumate design tokens

Exported from the Figma file (variables, text styles, effect styles) on 25 Nov 2026.

- `locumate-tokens.css`: CSS variables, ready to include in the app.
  1. Primitives: colour scales.
  2. Semantic colours, named as in Figma.
  3. Spacing, radii and sizes.
  4. Typography, as variables and `.lm-*` classes.
  5. Shadows and blurs.
  6. Element Plus 1.0.2 theme variables. Every `--el-color-primary-light-1…9` shade is set explicitly, because 1.0.2 does not derive them.
- `locumate-tokens.json`: the same tokens in the W3C design tokens format, for Style Dictionary and similar tools.

In components, use the semantic tokens (`--lm-color-*`, `--lm-text-*`, `--lm-bg-*`, `--lm-border-*`) rather than the primitives. Figma is the source: if a value changes there, export this file again.
