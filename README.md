# vscode-settings

## Font

- [Fira code](https://github.com/tonsky/FiraCode)

## Themes

- [Halcyon](https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode)

## IntelliSense/AutoComplete

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Autocompletes filenames
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  - Autocompletes npm modules in import statements
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  - Vue tooling

## Style/Formatting

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- json
- Prettify JSON
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint JS
- [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  - Automatically format javascript, JSON, CSS, Sass, and HTML files.
- HTML Snippets
- Live Sass Compiler
- Prettier - Code formatter
- ~~[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)~~
  - ~~Auto-rename paired HTML/XML tags~~ 🚀 [Now native support in VSCode](https://code.visualstudio.com/updates/v1_49#_html-tag-rename-on-type)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  - Highlight CSV and TSV files in different colors, Run SQL-like queries

## MISC

- Import Cost
- [Github Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Wakatime](https://wakatime.com/@ensina)
  - Metrics, insights, and time tracking automatically generated from programming activity.
- Live Server

### VS Code Settings

```json
{
  "editor.tabSize": 2,
  "workbench.editor.pinnedTabSizing": "compact",
  "workbench.iconTheme": "material-icon-theme",
  "javascript.preferences.quoteStyle": "single",
  "editor.fontLigatures": true,
  "workbench.editor.highlightModifiedTabs": true,
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
  "prettier.bracketSameLine": false,
  "prettier.singleQuote": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
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
  "git.autofetch": true,
  "git.defaultCloneDirectory": "",
  "githubPullRequests.remotes": [
    "origin",
    "upstream",
    "master",
    "development",
    "main"
  ],
  "workbench.colorTheme": "Halcyon",
  "telemetry.enableTelemetry": false,
  "telemetry.enableCrashReporter": false,
  "terminal.integrated.automationShell.windows": "",
  "workbench.colorCustomizations": {
    "[Halcyon]": {
      "terminal.ansiBlue": "#1f1876",
      "terminal.ansiRed": "#ffffff"
    }
  },
  "editor.linkedEditing": true,
  "editor.formatOnSave": true,
  "editor.tabCompletion": "onlySnippets",
  "prettier.vueIndentScriptAndStyle": true,
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "diffEditor.ignoreTrimWhitespace": true,
  "tailwindCSS.emmetCompletions": true,
  "editor.fontFamily": "Fira Code",
  "terminal.integrated.fontSize": 14,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "window.zoomLevel": 1,
  "css.lint.unknownAtRules": "ignore",
  "less.lint.unknownAtRules": "ignore",
  "scss.lint.unknownAtRules": "ignore",
  "volar.inlayHints.eventArgumentInInlineHandlers": false,
  "editor.inlineSuggest.enabled": true
}
```
