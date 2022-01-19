# Serendipity.

[Serendipity Theme](https://serendipitytheme.com)

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/serendipityHero.png)

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for **`serendipity`**
3. Click **Install** to install it.
4. Code > Preferences > Color Theme >
 **serendipity-light - serendipity-dark - serendipity-dark-italic - serendipity-light-italic**
5. Optional: Use the recommended settings below for best experience

## Recommended Settings

```json5
// These are my personal preferences.
"editor.fontFamily": "'IBM Plex Mono', monospace",
"editor.fontSize": 18,
"editor.lineHeight": 38,
"editor.letterSpacing": 0.5,
"files.trimTrailingWhitespace": true,
"editor.fontWeight": "normal",
"prettier.eslintIntegration": true,
"editor.cursorStyle": "line",
"editor.cursorWidth": 5,
"editor.cursorBlinking": "phase",
"editor.renderWhitespace": "all",
```

If you want to disable italics, add this snippet to your `settings.json`:

```json5
"editor.tokenColorCustomizations": {
  "[Serendipity]": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "entity.other.attribute-name",
          "entity.other.inherited-class",
          "support.function",
          "variable",
          "meta.directive.vue",
        ],
        "settings": {
          "fontStyle": "",
        },
      },
    ],
  },
},
```

## Colors

I have worked to create a color palette that's comfortable for your eyes when using retina screens.
This color combination made it possible, thanks to using pastel colors on a dark background instead of "neonish" colors.

This theme is available for editors, shells, UI's and more coming up.

## Available Options

### Visual Studio Code

- Dark Morning
- Dark Sunset
- Dark Midnight

### JetBrains

- Dark (only text)
- <https://github.com/WickedLabs/serendipity>

### Slack

- Dark
- Light

### Linear App

- Light
- Dark

### iTerm

- Light
- Dark

### Firefox

- Light
- Dark

### Dark Version

#### Color Palette

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/darkColors.png)

#### HTML

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/darkHtml.png)

#### CSS

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/darkCss.png)

#### JS

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/darkJs.png)

### Light Version

#### Color Palette

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/lightColors.png)

#### HTML

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/lightHtml.png)

#### CSS

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/lightCss.png)

#### JS

![Preview](https://raw.githubusercontent.com/michael-andreuzza/wvsc-serendipity/master/lightJs.png)

## Feedback

Contact me on Twitter if you're wondering about anything: `@Mike_Andreuzza`.
