# Export styles to CSS variables

A small plugin to Figma for generating and exporting your styles to CSS custom properties (variables).

To use, create some styles, run the plugin, select your color system (RGBA, Hex, or HSLA) and if you want to use REM units for text, and hit Generate.

The plugin generates the following:
- Color in a selected color system.
- Text size (can select to export as REM units by selecting a style as base).
- Box-shadow from effects.
- Blur filter from effects.

Note:
- Slashes that Figma uses for grouping is converted to double-dashes to follow the BEM methodology (modifiers).
- spaces and camelCase naming is converted to kebab-case naming.
- Special characters are removed.
