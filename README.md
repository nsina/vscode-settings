# vscode-settings

## Font
* [Fira code](https://github.com/tonsky/FiraCode)

## Themes
* [Halcyon](https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode)

## IntelliSense/AutoComplete
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import statements
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
* ~~[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)~~
  * ~~Auto-rename paired HTML/XML tags~~ 🚀 [Now native support in VSCode](https://code.visualstudio.com/updates/v1_49#_html-tag-rename-on-type)
* [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  * Highlight CSV and TSV files in different colors, Run SQL-like queries

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
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
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
  "telemetry.enableTelemetry": false,
  "telemetry.enableCrashReporter": false,
  "terminal.integrated.cwd": "c:\\dev",
  "git.defaultCloneDirectory": "",
  "terminal.integrated.automationShell.windows": "",
  "workbench.colorCustomizations": {
  "[Halcyon]": {
    "terminal.ansiBlue": "#251c9b",
    "terminal.ansiRed": "#ffffff"
  }
  },
  "auto-rename-tag.activationOnLanguage": [
    "*"
  ],
  "editor.renameOnType": true,
}

```