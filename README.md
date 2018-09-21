# Visual Studio Keymap for Visual Studio Code

This extension ports popular Visual Studio keyboard shortcuts to Visual Studio Code. After installing the extension and restarting VS Code your favorite keyboard shortcuts from Visual Studio are now available. 

## What keyboard shortcuts are included?

You can see all the keyboard shortcuts in the extension's contribution list. 


## Why don't all the keyboard shortcuts work? 

VS Code does not implement all of the commands available in Visual Studio. If you would like to see a feature in VS Code that is in Visual Studio, please open an [issue on GitHub](https://github.com/Microsoft/vscode/issues/new). 

## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR. 

1. Head over to our [GitHub repository](https://github.com/rebornix/vscode-vs-keybindings). 
2. Open [`package.json`](https://github.com/rebornix/vscode-vs-keybindings/blob/master/package.json). 
3. Add a JSON object to [`contributes.keybindings`](https://github.com/rebornix/vscode-vs-keybindings/blob/master/package.json#L26) as seen below. 
4. Open a pull request. 

```json
{
    "mac": "<keyboard shortcut for mac>",
    "linux": "<keyboard shortcut for linux",
    "win": "<keyboard shortcut for windows",
    "key": "<default keyboard shortcut>",
    "command": "<name of the command in VS Code"
}
```

You can read more about how to contribute keybindings in extensions in the [official documentation](http://code.visualstudio.com/docs/extensionAPI/extension-points#_contributeskeybindings). 

## What keyboard shortcuts are included?

| Command | Key |
| :---------: | :---------: |
|cursorColumnSelectDown|shift+alt+down|
|cursorColumnSelectLeft|shift+alt+left|
|cursorColumnSelectPageDown|shift+alt+pagedown|
|cursorColumnSelectPageUp|shift+alt+pageup|
|cursorColumnSelectRight|shift+alt+right|
|cursorColumnSelectUp|shift+alt+up|
|cursorWordStartRight|ctrl+right|
|cursorWordStartRightSelect|ctrl+shift+right|
|deleteWordEndRight|ctrl+delete|
|deleteWordStartLeft|ctrl+backspace|
|editor.action.addSelectionToNextFindMatch|ctrl+w|
|editor.action.clipboardCutAction|ctrl+l|
|editor.action.copyLinesDownAction|ctrl+d|
|editor.action.deleteLines|ctrl+shift+l|
|editor.action.formatDocument|ctrl+kctrl+d|
|editor.action.insertLineAfter|shift+enter|
|editor.action.insertLineBefore|ctrl+enter|
|editor.action.referenceSearch.trigger|alt+f12|
|editor.action.rename|ctrl+rctrl+r|
|editor.action.toggleRenderWhitespace|ctrl+rctrl+w|
|editor.action.triggerSuggest|ctrl+alt+space|
|editor.debug.action.runToCursor|ctrl+f10|
|editor.foldAll|ctrl+kctrl+m|
|insertSnippet|ctrl+kctrl+x|
|redo|ctrl+y|
|undo|alt+space|
|workbench.action.closeActiveEditor|ctrl+f4|
|workbench.action.debug.restart|ctrl+shift+f5|
|workbench.action.files.openFileFolder|ctrl+shift+g|
|workbench.action.files.saveAll|ctrl+shift+s|
|workbench.action.navigateBack|ctrl+-|
|workbench.action.navigateForward|ctrl+shift+-|
|workbench.action.output.toggleOutput|ctrl+alt+o|
|workbench.action.quickOpen|ctrl+|
|workbench.action.tasks.build|ctrl+shift+b|
|workbench.action.toggleZenMode|shift+alt+enter|
|workbench.debug.viewlet.action.addFunctionBreakpointAction|ctrl+b|
|workbench.debug.viewlet.action.removeAllBreakpoints|ctrl+shift+f9|
|workbench.view.explorer|ctrl+alt+l|




