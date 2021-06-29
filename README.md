# angularjs-switcher

Easily navigate to `javscript(.js)`|`template(.html)`|`style(.scss/.sass/.less/.css)` in angularjs project.

## Usage

* Go to the definition of variables/functions when press `f12` within html.
* Switch `.js`|`.html`|`.css`|`.spec.js` quickly.
  >|   |  Windows  |     macOS     |
  >| - | :-------: | :-----------: |
  >| If on `.js`&#124;`.css`&#124;`.spec.js`:&ensp;go to `.html`<br>If on `.html`:&ensp;go to previous | `alt+o` | `shift+alt+o` |
  >| If on `.js`&#124;`.html`&#124;`.spec.js`:&ensp;go to `.css`<br>If on `.css`:&ensp;go to previous | `alt+i` | `shift+alt+i` |
  >| If on `.css`&#124;`.html`&#124;`.spec.js`:&ensp;go to `.js`<br>If on `ts`:&ensp;go to previous | `alt+u` | `shift+alt+u` |
  >| If on `.js`&#124;`.css`&#124;`.html`:&ensp;go to `.spec.js`<br>If on `.spec.js`:&ensp;go to previous | `alt+p` | `shift+alt+p` |

## Available Settings

* Open files side by side (`false` by default)
```json
  "angularjs-switcher.openSideBySide": true
```

* The order of angularjs-switcher find corresponding style file  (`[".scss", ".sass", ".less", ".css"]` by default)
```json
  "angularjs-switcher.styleFormats": [".scss", ".sass", ".less", ".css"]
```

* The order of angularjs-switcher find corresponding template file  (`[".html"]` by default)
```json
  "angularjs-switcher.templateFormats": [".html"]
```

## Source

[GitHub](https://github.com/infinity1207/angularjs-switcher)
