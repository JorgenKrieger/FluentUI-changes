# Fluent UI custom changes

This repo contains a custom config that extends the base styling provided by the [Fluent UI for VSCode](https://marketplace.visualstudio.com/items?itemName=leandro-rodrigues.fluent-ui-vscode) plugin.

## Installation
Clone the repo somewhere on your system and symlink it over the file in the plugin directory.
Keep in mind the directory folder might change with updates to the plugin.

VS Code
```sh
ln -nfs $PWD/editor_chrome.css $HOME/.vscode/extensions/leandro-rodrigues.fluent-ui-vscode-3.9.0/out/css
```

VS Code Insiders
```sh
ln -nfs $PWD/editor_chrome.css $HOME/.vscode-insiders/extensions/leandro-rodrigues.fluent-ui-vscode-3.9.0/out/css
```
