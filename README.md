# vscode

## Toggle terminal insert in the keybinbing file (File>Preferences>Keyboard Shortcuts (or simply Ctrl+K,Ctrl+S)

{
    "key": "ctrl+`",
    "command": "workbench.action.terminal.focus"
},
{
    "key": "ctrl+`",
    "command": "workbench.action.focusActiveEditorGroup",
    "when": "terminalFocus"
}
