# vscode setting

### Fira Code Font

[download here](https://github.com/tonsky/FiraCode)

### Install Extesions

[ref](https://stackoverflow.com/a/51403163/4100275)

```
code --install-extension bierner.github-markdown-preview
code --install-extension bierner.markdown-checkbox
code --install-extension bierner.markdown-emoji
code --install-extension bierner.markdown-preview-github-styles
code --install-extension bierner.markdown-yaml-preamble
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension dracula-theme.theme-dracula
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension HookyQR.beautify
code --install-extension jeremyljackson.vs-docblock
code --install-extension joelday.docthis
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension mikestead.dotenv
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-mssql.mssql
code --install-extension naumovs.color-highlight
code --install-extension Orta.vscode-jest
code --install-extension PKief.material-icon-theme
code --install-extension ritwickdey.LiveServer
code --install-extension stylelint.vscode-stylelint
code --install-extension syler.sass-indented
code --install-extension william-voyek.vscode-nginx
````


### Settings.json
```json
{
  "workbench.colorTheme": "Dracula",
  "editor.fontSize": 16,
  "editor.lineHeight": 24,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.formatOnSave": false,

  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    { "language": "typescript", "autoFix": true },
    { "language": "typescriptreact", "autoFix": true }
  ],
  //lembrar de quebra a linha
  "editor.rulers": [109, 140, 170],
  "editor.tabSize": 2,
  "workbench.editor.enablePreview": false,
  "workbench.editor.showTabs": true,
  "window.zoomLevel": 0,
  "workbench.sideBar.location": "left",
  "window.openFoldersInNewWindow": "on",
  "search.useGlobalIgnoreFiles": true,
  "editor.detectIndentation": false,
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.eol": "\n",
  "files.insertFinalNewline": true,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "javascript.updateImportsOnFileMove.enabled": "never",
  "timeline.excludeSources": ["git-history"],
  "color-highlight.markerType": "dot-before",
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.activeIconPack": "react_redux",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.files.associations": {
    "Route.tsx": "Routing",
    "saga.ts": "Redux-store",
    "sagas.ts": "Redux-store",
    "selector.ts": "Redux-action",
    "selectors.ts": "Redux-action",
    "styleds.tsx": "Styled-components"
  }
}

```
