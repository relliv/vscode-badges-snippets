# snippet-badge

[![vsm-version](https://img.shields.io/visual-studio-marketplace/v/alexzshl.badges-snippets?style=flat&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=alexzshl.badges-snippets)
[![license](https://img.shields.io/github/license/alexzshl/vscode-badges-snippets?style=flat&color=lightgrey)](https://github.com/alexzshl/vscode-badges-snippets/blob/master/LICENSE)

Snippets to quickly insert shields.io badges into Markdown documents.

## Preview

![preview](images/preview_01.gif)

![preview](images/preview_02.gif)

## Features

- Static badge with list of color/style/logo
- Quick and easy service support
- Quickly generate badges using clipboard data

## Requirements

none.

## Extension Settings

If the snippets for markdown doesn't work,please add the following settings in settings.json:

```json
  "[markdown]": {
    "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true,
    }
  }
```

## Usages

Enter the full name or shorthand for the code snippet item, select and press the tab key. Next you need to fill in the placeholders in order.

- `badge static` or `bs` - Create tatic badge
- `badge vsm version` - Create dynamic badge for an extension on Visual Studio Marketplace
- `badge github stars` - Create dynamic badge for stars of a repository on Github

## Known Issues

none.

## Release Notes

### 0.0.1

Initial release of ...

**Enjoy!**
