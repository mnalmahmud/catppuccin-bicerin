<div align="center">
  <h1>Bicerin</h1>
  <p><strong>bee-cheh-REEN</strong> · An unofficial <a href="https://github.com/catppuccin/catppuccin">Catppuccin</a> color palette</p>
  <img src="assets/palette.svg" alt="Bicerin palette: 14 accents and 12 neutrals" width="100%">
</div>

## Colors

### Accents

| Color | Hex | Color | Hex |
| :--- | :--- | :--- | :--- |
| `rosewater` | `#f6e4e1` | `yellow` | `#ffedbe` |
| `flamingo` | `#f4d3d3` | `green` | `#a6ecad` |
| `pink` | `#f5c7e8` | `teal` | `#9defe0` |
| `mauve` | `#cfaaf7` | `sky` | `#81e0f2` |
| `red` | `#f98fba` | `sapphire` | `#6acaf4` |
| `maroon` | `#e8a7b8` | `blue` | `#88baff` |
| `peach` | `#ffbd8f` | `lavender` | `#b3bfff` |

### Neutrals

| Color | Hex | Color | Hex |
| :--- | :--- | :--- | :--- |
| `crust` | `#0c0c14` | `overlay0` | `#6b6e82` |
| `mantle` | `#14121d` | `overlay1` | `#7e8297` |
| `base` | `#1a1826` | `overlay2` | `#9398ad` |
| `surface0` | `#2d2d3d` | `subtext0` | `#a7adc5` |
| `surface1` | `#424353` | `subtext1` | `#bdc4db` |
| `surface2` | `#56586b` | `text` | `#d0d9f3` |

## Files

- [`bicerin.json`](bicerin.json) — 26 hex values.
- [`bicerin.css`](bicerin.css) — CSS custom properties (`--ctp-bicerin-*`).
- [`whiskers-overrides.json`](whiskers-overrides.json) — optional [Whiskers](https://whiskers.catppuccin.com/concepts/overrides/) color overrides.

### Whiskers

Whiskers does not accept `bicerin` as a flavor name. To render an existing single-flavor template with Bicerin's colors, override Mocha's values:

```sh
whiskers template.tera --flavor mocha --color-overrides "$(cat whiskers-overrides.json)"
```

This replaces **the colors only**; Whiskers still identifies the flavor as `mocha`.

## License

[MIT](LICENSE). Not affiliated with or endorsed by Catppuccin.
