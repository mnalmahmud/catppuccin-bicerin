<div align="center">

# ☕ Bicerin

**bee-cheh-REEN**

An unofficial, extra-dark [Catppuccin](https://catppuccin.com/)-inspired color palette.

<img src="assets/palette.svg" alt="Bicerin palette showing fourteen pastel accents and twelve dark-to-light neutrals" width="100%">

<sub>14 accents · 12 neutrals · 26 colors</sub>

</div>

## Palette

### Accents

| Color | Hex | Color | Hex |
| :-- | :-- | :-- | :-- |
| Rosewater | `#f6e4e1` | Yellow | `#ffedbe` |
| Flamingo | `#f4d3d3` | Green | `#a6ecad` |
| Pink | `#f5c7e8` | Teal | `#9defe0` |
| Mauve | `#cfaaf7` | Sky | `#81e0f2` |
| Red | `#f98fba` | Sapphire | `#6acaf4` |
| Maroon | `#e8a7b8` | Blue | `#88baff` |
| Peach | `#ffbd8f` | Lavender | `#b3bfff` |

### Neutrals

| Color | Hex | Color | Hex |
| :-- | :-- | :-- | :-- |
| Crust | `#0c0c14` | Overlay 0 | `#6b6e82` |
| Mantle | `#14121d` | Overlay 1 | `#7e8297` |
| Base | `#1a1826` | Overlay 2 | `#9398ad` |
| Surface 0 | `#2d2d3d` | Subtext 0 | `#a7adc5` |
| Surface 1 | `#424353` | Subtext 1 | `#bdc4db` |
| Surface 2 | `#56586b` | Text | `#d0d9f3` |

## Files

| File | Format |
| :-- | :-- |
| [`bicerin.json`](bicerin.json) | Named hex colors |
| [`bicerin.css`](bicerin.css) | CSS custom properties (`--ctp-bicerin-*`) |
| [`whiskers-overrides.json`](whiskers-overrides.json) | Optional Whiskers color overrides |

### CSS

Load [`bicerin.css`](bicerin.css) and reference the variables:

```css
@import url("./bicerin.css");

body {
  background: var(--ctp-bicerin-base);
  color: var(--ctp-bicerin-text);
}

a {
  color: var(--ctp-bicerin-blue);
}
```

<details>
<summary>Whiskers</summary>

Use the [color overrides](https://whiskers.catppuccin.com/concepts/overrides/) to render a Whiskers template with Bicerin's colors:

```sh
whiskers template.tera --flavor mocha --color-overrides "$(cat whiskers-overrides.json)"
```

Whiskers still identifies the selected flavor as `mocha`; only its colors are replaced.

</details>

## License

[MIT](LICENSE). Bicerin is an independent project, not affiliated with or endorsed by Catppuccin.
