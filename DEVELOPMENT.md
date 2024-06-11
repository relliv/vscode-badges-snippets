# Development Notes

## Install vsce

Install `vsce` package with `npm i -g vsce` command.

## Pack this extension

Run `vsce package` command in your terminal and you will see `shieldsio-snippets-{current_version}.vsix` file.

## Install VSIX package

- Press `F1` (`fn + F1` *for mac users*) and run `Extensions: Install from VSIX` command.
- Select generated `shieldsio-snippets-{current_version}.vsix` file from file manager.
- Then restart to see differences with `F1` and `Reload Window` command.