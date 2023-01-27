# Enfocado for VS Code

![Banner](https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/banner.png)

[![License Badge](https://img.shields.io/badge/License-MIT-3FC5B7.svg?style=for-the-badge)](https://github.com/wuelnerdotexe/vscode-enfocado/blob/main/LICENSE)
[![README Style Badge](https://img.shields.io/badge/README%20Style-Standard-3FC5B7.svg?style=for-the-badge)](https://github.com/RichardLitt/standard-readme)
[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-3FC5B7.svg?style=for-the-badge)](https://vscode.dev/theme/wuelnerdotexe.vscode-enfocado)

**Enfocado** is more than a theme, it is a concept of **"how themes should be"**, focusing on what is really important to developers: **the code and nothing else**.

What you **won't have** if you **don't install Enfocado**:

- **CIELAB Colors:** use of the well-founded Selenized color scheme created with the magic of the **CIELAB color space**. Learn about its features and design in its [official repository](https://github.com/jan-warchol/selenized/blob/master/features-and-design.md).
- **Human Writing:** human writing is simulated by using italic typeface for syntax groups (comments, methods, stucts, and more ...) that are generally named and **written in human language**.
- **Minimal Syntax:** only three colors are used to highlight syntax, following the **color guidelines for web design**, which state that **only three main colors** should be used in interfaces, no more.
- **Signal Alerts:** the yellow, orange and red colors are reserved to be used only with important alerts, following the standards for the meanings of the **signal colors in the industrial area**.
- **Styles:** choose the style that best suits your **personality**:

<div align="center">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-dark-nature.png">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-light-nature.png">
  <strong>Nature:</strong> go for the <code>nature</code> style if you are a minimalist developer who is always <strong>connected to nature</strong>.
</div>
<br />
<div align="center">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-dark-neon.png">
  <img src="https://raw.githubusercontent.com/wuelnerdotexe/enfocado/main/assets/vscode-light-neon.png">
  <strong>Neon:</strong> go for the <code>neon</code> style if you are an outgoing developer that is always <strong>surrounded by RGBs</strong>.
</div>

## Installation

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=wuelnerdotexe.vscode-enfocado).
2. Click on the "Install" button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):
   - `Enfocado Light Nature`
   - `Enfocado Light Neon`
   - `Enfocado Dark Nature`
   - `Enfocado Dark Neon`
4. Lastly, [rate us](https://marketplace.visualstudio.com/items?itemName=wuelnerdotexe.vscode-enfocado&ssr=false#review-details) !! we are eager to hear your priceless review. ✨

## Usage

### Syntax

Master your theme, understand and recognize minimal syntax, improve your muscle memory.

| SELENIZED COLOR | HEX COLOR | HEX COLOR (light) |  TEXT TYPE  |       NATURE SYNTAX TOKENS        |        NEON SYNTAX TOKENS         |
| --------------- | :-------: | :---------------: | :---------: | :-------------------------------: | :-------------------------------: |
| Dimmed          | `#777777` |     `#878787`     |  `Italic`   |             Comments              |             Comments              |
| Foreground 0    | `#b9b9b9` |     `#474747`     |   `NONE`    |   Constants, punctuation, text    |   Constants, punctuation, text    |
| Foreground 1    | `#dedede` |     `#282828`     |   `Bold`    |              Titles               |              Titles               |
| Red             | `#ed4a46` |     `#d6000c`     | ~~`NONE`~~  |    ~~Not used in the syntax~~     |    ~~Not used in the syntax~~     |
| Yellow          | `#dbb32d` |     `#c49700`     |   `NONE`    | Constant and readonly identifiers | Constant and readonly identifiers |
| Green           | `#70b433` |     `#1d9700`     |   `NONE`    |            Identifiers            |       Language identifiers        |
| Blue            | `#368aeb` |     `#0064e4`     |   `NONE`    |             Keywords              |         Support keywords          |
| Magenta         | `#eb6eb7` |     `#dd0f9d`     |   `NONE`    |       Language identifiers        |            Identifiers            |
| Cyan            | `#3fc5b7` |     `#00ad9c`     |   `NONE`    |              Strings              |              Strings              |
| Orange          | `#e67f43` |     `#d04a00`     |   `NONE`    |      Exceptions (`trycatch`)      |      Exceptions (`trycatch`)      |
| Violet          | `#a580e2` |     `#7f51d6`     |   `NONE`    |         Support keywords          |             Keywords              |
| Bright red      | `#ff5e56` |     `#bf0000`     |   `Bold`    |              Errors               |              Errors               |
| Bright yellow   | `#efc541` |     `#af8500`     | ~~`NONE`~~  |    ~~Not used in the syntax~~     |    ~~Not used in the syntax~~     |
| Bright green    | `#83c746` |     `#008400`     |  `Italic`   |              Methods              |         Language methods          |
| Bright blue     | `#4f9cfe` |     `#0054cf`     |   `Bold`    |               Types               |           Support types           |
| Bright magenta  | `#ff81ca` |     `#c7008b`     |  `Italic`   |         Language methods          |              Methods              |
| Bright cyan     | `#56d8c9` |     `#009a8a`     | `Underline` |               Links               |               Links               |
| Bright orange   | `#fa9153` |     `#ba3700`     | ~~`NONE`~~  |    ~~Not used in the syntax~~     |    ~~Not used in the syntax~~     |
| Bright violet   | `#b891f5` |     `#6b40c3`     |   `Bold`    |           Support types           |               Types               |

DISCLAIMER: **Enfocado** doesn't customize individual tokens for each language, it just defines the default base, if your syntax doesn't look as described here, it's not our responsibility, it's the responsibility of those who assign wrong tokens to some language's syntax, and we don't correct those problems constantly.

## Recommendations

### Settings

For the best **Enfocado** experience, I recommend adding this setting to your VS Code `settings.json` file:

```jsonc
// ENFOCADO INDISTRACTABLE SETUP: {{{

// Clean the editor of useless stuff.
"window.menuBarVisibility": "compact",
"editor.renderLineHighlight": "none",
"editor.minimap.enabled": false,
"breadcrumbs.enabled": true,
"breadcrumbs.filePath": "off",

// Disable unseless icons.
"workbench.editor.showIcons": false,
"workbench.editor.tabSizing": "shrink",

// Disable explorer and tabs colors in filenames.
"explorer.decorations.colors": false,
"workbench.editor.decorations.colors": false,

// Enable explorer and tabs colors in filename's badges.
"explorer.decorations.badges": true,
"workbench.editor.decorations.badges": true,

// Enable semantic highlighting syntax.
"editor.semanticHighlighting.enabled": true,

// Enable bracket pair colorization.
"editor.bracketPairColorization.enabled": true,

// Enable indent lines with colorization pairs.
"editor.guides.indentation": true,
"editor.guides.bracketPairs": true,

// Show only trailing whitespaces.
"editor.renderWhitespace": "trailing",

// Customize only the editor font to make it stand out from the rest.
"editor.fontSize": 18,
"editor.fontWeight": "500",
"editor.letterSpacing": 1.2,
"editor.lineHeight": 1.8,

// Lastly and most importantly, enable Enfocado theme and enjoy coding.
"workbench.preferredLightColorTheme": "Enfocado Light {Nature or Neon}",
"workbench.preferredDarkColorTheme": "Enfocado Dark {Nature or Neon}",
"workbench.colorTheme": "Enfocado {Light or Dark} {Nature or Neon}",
// Choose only one option inside the curly braces and then delete them.

// }}}
```

### Fonts

In order for the **Human Writing** simulation to work as it should, I recommend that you use either of these three beautiful fonts, which align with the **"Mankind and Machine"** concept.

- [IBM Plex Mono](https://www.ibm.com/plex/).
- [Victor Mono](https://rubjo.github.io/victor-mono/).

### Extensions

- It is recommended to install the official extensions that provide semantic improvement to the language in which you work, to enrich the Minimal Syntax.
- Also, for better alerts, it is recommended to install [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) as **Enfocado** provides native support by default.

### Extras

- [Enfocado for Vim](https://github.com/wuelnerdotexe/vim-enfocado).
- [Selenized for terminals](https://github.com/jan-warchol/selenized/tree/master/terminals).

## Maintainer

> Hi 👋, I'm **[Wuelner](https://linktr.ee/wuelnerdotexe)**, a **software developer from Guatemala**, passionate about creating minimalist solutions using solid fundamentals focused on **"how things should be"**.

## Contributing

All your ideas and suggestions are welcome! 🙌

Let me see your captures and let me know what you think with the hashtag **#HowThemesShouldBe**. 👀

And of course, if you want to motivate me to constantly improve this theme, your donations are welcome at [PayPal](https://paypal.me/wuelnerdotexe). 👉👈

## Credits

- Theme colorscheme by [Jan Warchol](https://github.com/jan-warchol) on [Github](https://github.com/jan-warchol/selenized/blob/master/the-values.md).
- Enfocado Nature wallpaper by [Josefin](https://unsplash.com/@josefin?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/nature?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).
- Enfocado Neon wallpaper by [Dilyara Garifullina](https://unsplash.com/@dilja96?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/neon?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).

## License

[MIT &copy; Wuelner Martínez.](https://github.com/wuelnerdotexe/vscode-enfocado/blob/main/LICENSE)

<p align="center">¡With 💖 from <strong>LATAM</strong> to the world!</p>
