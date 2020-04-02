# vscode setting

### Fira Code Font

[download here](https://github.com/tonsky/FiraCode)

### Install Extesions

[ref](https://stackoverflow.com/a/51403163/4100275)

```
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension dbaeumer.vscode-eslint
code --install-extension dracula-theme.theme-dracula
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension HookyQR.beautify
code --install-extension jeremyljackson.vs-docblock
code --install-extension joelday.docthis
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension mikestead.dotenv
code --install-extension ms-mssql.mssql
code --install-extension octref.vetur
code --install-extension Orta.vscode-jest
code --install-extension PKief.material-icon-theme
code --install-extension ritwickdey.LiveServer
code --install-extension syler.sass-indented
code --install-extension vscode-icons-team.vscode-icons
code --install-extension yzhang.markdown-all-in-one
````


### Settings.json
```json
{
    "workbench.colorTheme": "Dracula",
    "editor.fontSize":16,
    "editor.lineHeight":24,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,

    "editor.rulers": [
        80,
        120
    ],
    "editor.renderLineHighlight": 14,
    "workbench.iconTheme": "vscode-icons",
    "editor.tabSize": 2,
    "workbench.editor.enablePreview": false,
    "window.nativeTabs": true,
    "workbench.editor.showTabs": true,
    "window.zoomLevel": 0,
    "workbench.sideBar.location": "left",
    "window.openFoldersInNewWindow": "on",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "explorer.confirmDelete": false,
    "search.useGlobalIgnoreFiles": true,
    "editor.detectIndentation": false,
    "editor.formatOnSave": true,
}
```
