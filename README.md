# Giscus Custom Themes

A collection of carefully crafted themes for [giscus](https://giscus.app) - a comments system powered by GitHub Discussions. This repository provides a variety of themes to match your website's design and improve accessibility.

## Available Themes

### Light Themes
- `light.css` - Default light theme
- `light_high_contrast.css` - High contrast light theme
- `light_protanopia.css` - Light theme optimized for protanopia
- `light_tritanopia.css` - Light theme optimized for tritanopia
- `noborder_light.css` - Borderless light theme
- `gruvbox_light.css` - Gruvbox light theme
- `catppuccin_latte.css` - Catppuccin Latte theme

### Dark Themes
- `dark.css` - Default dark theme
- `dark_high_contrast.css` - High contrast dark theme
- `dark_dimmed.css` - Dimmed dark theme
- `dark_protanopia.css` - Dark theme optimized for protanopia
- `dark_tritanopia.css` - Dark theme optimized for tritanopia
- `noborder_dark.css` - Borderless dark theme
- `gruvbox_dark.css` - Gruvbox dark theme
- `catppuccin_mocha.css` - Catppuccin Mocha theme
- `catppuccin_macchiato.css` - Catppuccin Macchiato theme
- `catppuccin_frappe.css` - Catppuccin Frappe theme

### Special Themes
- `preferred_color_scheme.css` - Adapts to user's system preference
- `transparent_dark.css` - Dark theme with transparency
- `purple_dark.css` - Purple-accented dark theme
- `cobalt.css` - Cobalt-inspired theme
- `fro.css` - Custom theme with unique styling
- `custom_example.css` - Example template for creating custom themes

## Usage with jsDelivr

To use these themes in your giscus implementation, you can use jsDelivr's CDN. Add the theme URL to your giscus configuration:

```html
<!-- Replace THEME_NAME with the desired theme file -->
<script src="https://giscus.app/client.js"
        data-theme="https://cdn.jsdelivr.net/gh/abd3lraouf/abd3lraouf.dev.giscus/styles/THEME_NAME.css"
        ...other-giscus-settings>
</script>
```

For example, to use the dark theme:
```html
data-theme="https://cdn.jsdelivr.net/gh/abd3lraouf/abd3lraouf.dev.giscus/styles/dark.css"
```

## Features

- 🎨 Wide variety of themes to match your website's design
- 🌓 Light and dark variants
- ♿ Accessibility-focused themes (high contrast, color blindness support)
- 🎯 Popular color schemes (Gruvbox, Catppuccin)
- 🔧 Easy integration with jsDelivr CDN
- 📱 Responsive design
- 🚀 Optimized CSS

## Local Development

To modify or create new themes:

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Modify existing themes or create new ones in the `styles` directory
4. Use the provided `purge.mjs` script to optimize CSS if needed

## Contributing

Contributions are welcome! Feel free to:
- Submit new themes
- Improve existing themes
- Fix bugs
- Enhance documentation

Please ensure your theme follows the existing structure and includes appropriate color schemes for both light and dark modes if applicable.

## License

MIT License - feel free to use these themes in your projects!

---

Made with ❤️ by [Abdelraouf Sabri](https://github.com/abd3lraouf)
