# vscode-settings

Just some stuff that I like to keep...
```
{
    "workbench.colorTheme": "Ayu Dark",
    "workbench.colorCustomizations": {
        "activityBar.background": "#000000",
        "activityBar.foreground": "#000000",
        "activityBar.border": "#000000",
        "activityBar.activeBackground": "#000000",
        "activityBar.activeBorder": "#000000",
        "sideBar.background": "#000000",
        "sideBar.border": "#000000",
        "editor.background": "#000000",
        "editorWidget.border": "#000000",
        "editorHoverWidget.border": "#000000",
        "editorSuggestWidget.border": "#000000",
        "editorGroup.border": "#000000",
        "editorGutter.background": "#000000",
        "editorGroupHeader.noTabsBackground": "#000000",
        "editorGroupHeader.tabsBackground": "#000000",
        "editorGroupHeader.border": "#000000",
        "editorGroupHeader.tabsBorder": "#000000",
        "editorOverviewRuler.background": "#000000",
        "editorOverviewRuler.border": "#000000",
        "sideBarSectionHeader.background": "#000000",
        "statusBar.background": "#000000",
        "statusBar.border": "#000000",
        "scrollbarSlider.activeBackground": "#000000",
        "scrollbarSlider.hoverBackground": "#000000",
        "scrollbarSlider.background": "#000000",
        "badge.background": "#000000",
        "minimap.background": "#000000",
        "tab.activeBackground": "#000000",
        "tab.inactiveBackground": "#000000",
        "tab.border": "#000000",
        "terminal.background": "#000000",
        "terminal.tab.activeBorder": "#000000",
        "terminal.border": "#000000",
        "panel.background": "#000000",
        "panel.border": "#000000",
        "titleBar.activeBackground": "#000000",
        "titleBar.border": "#000000",
        "focusBorder": "#000000",
        "sideBarSectionHeader.border": "#000000",
        "pickerGroup.border": "#000000",
        "peekView.border": "#000000",
        "statusBarItem.prominentBackground": "#000000",
        "diffEditor.diagonalFill": "#000000",
    },    
    "vim.normalModeKeyBindings": [
        {
            "before":["<C-k>"],
            "commands": [
                "editor.action.showHover",
            ],
        },
    ],
    "vim.handleKeys": {
        "<C-p>": false,
        "<C-b>": false,
    },
}
```
```
// Place your key bindings in this file to override the defaults
[
    {
        "key":     "ctrl+`",
        "command": "workbench.action.terminal.focus"
    },
    {
        "key":     "ctrl+`",
        "command": "workbench.action.focusActiveEditorGroup",
        "when":    "terminalFocus"
    },
    {
        "key": "shift+tab",
        "command": "workbench.action.nextEditor"
    },
    {
        "key": "ctrl+shift+t",
        "command": "workbench.action.previousEditor"
    },
    {
        "key": "capslock",
        "command": "extension.vim_escape",
        "when": "editorTextFocus && vim.active && !inDebugRepl"
    },
]
```
