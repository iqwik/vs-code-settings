# Preset VSCode settings
First of all, you need to install all the necessary extensions from the list below:

## Extensions

- [**Auto Import**](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [**Bracket Pair Colorization Toggler**](https://marketplace.visualstudio.com/items?itemName=dzhavat.bracket-pair-toggler)
- [**ENV**](https://marketplace.visualstudio.com/items?itemName=IronGeek.vscode-env)
- [**ESLint**](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [**TSLint**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
- [**GitLens — Git supercharged**](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [**Import Cost**](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [**JetBrains IDE Keymap**](https://marketplace.visualstudio.com/items?itemName=isudox.vscode-jetbrains-keybindings)
- [**SCSS Formatter**](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter)
- [**Swagger Viewer**](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer)
- [**Visual Studio IntelliCode**](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [**VSCode Great Icons**](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons)
- [**YAML**](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## settings.json
You need to add into `File -> Preferences -> Settings`

```
{
  "autoimport.useSemiColon": false,
  "autoimport.filesToScan": "**/*.{js,jsx,ts,tsx}",
  "editor.bracketPairColorization.enabled": true,
  "editor.defaultFormatter": "dbaeumer.vscode-eslint",
  "editor.fontSize": 13,
  "editor.foldingMaximumRegions": 10000,
  "editor.occurrencesHighlight": true,
  "editor.renderFinalNewline": true,
  "editor.showUnused": true,
  "eslint.format.enable": true,
  "eslint.packageManager": "yarn",
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"],
  "eslint.rules.customizations": [
    { "rule": "no-unused-vars", "severity": "error" },
    { "rule": "@typescript-eslint/no-unused-vars", "severity": "error" },
    { "rule": "@typescript-eslint/no-unused-expressions", "severity": "error" },
  ],
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "files.autoSave": "onFocusChange",
  "files.eol": "\n",
  "redhat.telemetry.enabled": false,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.iconTheme": "vscode-great-icons"
}
```
