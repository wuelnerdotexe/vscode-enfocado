# Enfocado for VS Code

![Banner](https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/banner.png)

[![License Badge](https://img.shields.io/badge/License-MIT-3FC5B7.svg?style=for-the-badge)](https://github.com/wuelnerdotexe/vscode-enfocado/blob/main/LICENSE)
[![README Style Badge](https://img.shields.io/badge/README%20Style-Standard-3FC5B7.svg?style=for-the-badge)](https://github.com/RichardLitt/standard-readme)

**Enfocado** is more than a theme, it is a concept of **"how themes should be"**, focusing on what is really important to developers: **the code and nothing else**.

What you **won't have** if you **don't install Enfocado**:

- **CIELAB Colors:** use of the well-founded Selenized black color scheme created with the magic of the **CIELAB color space**. Learn about its features and design in its [official repository](https://github.com/jan-warchol/selenized/blob/master/features-and-design.md).
- **Human Writing:** human writing is simulated by using italic typeface for syntax groups (comments, methods, stucts, and more ...) that are generally named and **written in human language**.
- **Minimal Syntax:** only three colors are used to highlight syntax, following the **color guidelines for web design**, which state that **only three main colors** should be used in interfaces, no more.
- **Signal Alerts:** the yellow, orange and red colors are reserved to be used only with important alerts, following the standards for the meanings of the **signal colors in the industrial area**.
- **Styles:** choose the style that best suits your **personality**:

<div align="center">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-light-nature.png">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-dark-nature.png">
  <strong>Nature:</strong> go for the <code>nature</code> style if you are a minimalist developer who is always <strong>connected to nature</strong>.
</div>
<br />
<div align="center">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-light-neon.png">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-dark-neon.png">
  <strong>Neon:</strong> go for the <code>neon</code> style if you are an outgoing developer that is always <strong>surrounded by RGBs</strong>.
</div>

## Installation

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=wuelnerdotexe.vscode-enfocado).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):
   - `Enfocado Light Nature` ✨ new ✨
   - `Enfocado Light Neon` ✨ new ✨
   - `Enfocado Dark Nature`
   - `Enfocado Dark Neon`

## Recommendations

### Settings

For the best **Enfocado** experience, I recommend adding this setting to your VS Code `settings.json` file:

```jsonc
// ENFOCADO INDISTRACTABLE SETUP: {{{

// Clean the editor of useless stuff.
"window.menuBarVisibility": "compact",
"breadcrumbs.enabled": false,
"editor.minimap.enabled": false,

// Disable unseless icons.
"workbench.iconTheme": null,
"workbench.editor.showIcons": false,
"workbench.editor.tabSizing": "shrink",

// *Disable explorer and tabs colors in filenames. 
"explorer.decorations.colors": false,
"workbench.editor.decorations.colors": false,

// *Enable explorer and tabs colors in filename's badges.
"explorer.decorations.badges": true,
"workbench.editor.decorations.badges": true,

// *Enable semantic highlighting syntax.
"editor.semanticHighlighting.enabled": true,

// Enable bracket pair colorization.
"editor.bracketPairColorization.enabled": true,

// Enable indent lines with colorization pairs.
"editor.guides.indentation": true,
"editor.guides.bracketPairs": true,

// Show only trailing whitespaces.
"editor.renderWhitespace": "trailing",

// Sexy font customizations for sexy developers ;).
"editor.fontFamily": "'Victor Mono', 'IBM Plex Mono'",
"editor.fontSize": 18,
"editor.fontWeight": "500",
"editor.fontLigatures": true,

// Lastly and most importantly, enable Enfocado theme and enjoy coding.
"workbench.preferredDarkColorTheme": "Enfocado Dark {Nature or Neon}",
"workbench.preferredLightColorTheme": "Enfocado Light {Nature or Neon}",
"workbench.colorTheme": "Enfocado {Light or Dark} {Nature or Neon}",

// }}} NOTE: groups marked with an '*' are highly required.
```

### Fonts

In order for the **Human Writing** simulation to work as it should, I recommend that you use either of these three beautiful fonts, which align with the **"Mankind and Machine"** concept.

- [IBM Plex Mono](https://www.ibm.com/plex/).
- [Victor Mono](https://rubjo.github.io/victor-mono/).

### Extras

- [Selenized black for terminals](https://github.com/jan-warchol/selenized/tree/master/terminals).
- [Enfocado for Vim](https://github.com/wuelnerdotexe/vim-enfocado).

## Maintainer

> Hola 👋, soy **[Wuelner](https://linktr.ee/wuelnerdotexe)**, un **software developer de Guatemala**, apasionado por crear soluciones minimalistas utilizando fundamentos sólidos enfocados en **"cómo deben ser las cosas"**.

## Contributing

All your ideas and suggestions are welcome! 🙌

Let me see your captures and let me know what you think with the hashtag **#HowThemesShouldBe**. 👀

And of course, if you want to motivate me to constantly improve this theme, your donations are welcome at [PayPal](https://paypal.me/wuelnerdotexe). 👉👈

## Extensions

The following extensions are supported:

- [Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [PostCSS Language Support](https://marketplace.visualstudio.com/items?itemName=csstools.postcss)

## Credits

- Theme colorscheme by [Jan Warchol](https://github.com/jan-warchol) on [Github](https://github.com/jan-warchol/selenized/blob/master/the-values.md).
- Enfocado Nature wallpaper by [Josefin](https://unsplash.com/@josefin?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/nature?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).
- Enfocado Neon wallpaper by [Dilyara Garifullina](https://unsplash.com/@dilja96?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/neon?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).

## License

[MIT &copy; Wuelner Martínez.](https://github.com/wuelnerdotexe/vscode-enfocado/blob/main/LICENSE)

<p align="center">¡Con 💖 de <strong>Latinoamérica</strong> para el mundo!</p>
