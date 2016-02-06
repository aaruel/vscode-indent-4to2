# Indent 4-to-2

Convert indentation from tab or 4 spaces into 2 spaces.

![Demostration of using this extension](https://raw.githubusercontent.com/compulim/vscode-indent-4to2/master/demo.gif)

## Usage

### Quick keyboard usage

* Press `F1` or `Ctrl+Shift+P` for Command Palette
* Type or find "Convert indentation from tab or 4 spaces into 2 spaces"

### Binding to keyboard shortcuts

* File > Preferences > Keyboard Shortcuts
* Append the following into `keybindings.json`

```js
{
  "key": "ctrl+shift+2",
  "command": "4to2.convert4to2",
  "when": "editorFocus"
}
```

### For more information
* [GitHub](https://github.com/compulim/vscode-4to2/)
