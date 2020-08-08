# vscode-settings

## Font
* [Fira code](https://github.com/tonsky/FiraCode)

## Themes
* [Halcyon](https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode)

## IntelliSense/AutoComplete
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling

## Style/Formatting
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.
* HTML Snippets
* Live Sass Compiler
* Prettier - Code formatter

## MISC
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [Wakatime](https://wakatime.com/@ensina)
  * Metrics, insights, and time tracking automatically generated from programming activity.
* Live Server

### VS Code Settings

``` json
{
  "editor.tabSize": 2,
  "workbench.iconTheme": "material-icon-theme",
  "window.zoomLevel": 0,
  "javascript.preferences.quoteStyle": "single",
  "editor.minimap.enabled": false,
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "workbench.editor.highlightModifiedTabs": true,
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",

  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/dist/css"
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/dist/css"
    }
  ],
  "liveServer.settings.donotShowInfoMsg": true,
  "prettier.jsxBracketSameLine": false,
  "prettier.trailingComma": "es5",
  "prettier.singleQuote": true,
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.wordWrap": "bounded",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.autoSave": "off",

  "workbench.startupEditor": "newUntitledFile",
  "typescript.preferences.quoteStyle": "single",
  "extensions.confirmedUriHandlerExtensionIds": [],
  "typescript.suggest.paths": false,
  "git.enableSmartCommit": true,
  "githubPullRequests.remotes": [
    "origin",
    "upstream",
    "master",
    "development"
  ],
  "workbench.colorTheme": "Halcyon",
}

```