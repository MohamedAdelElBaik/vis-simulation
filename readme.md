# Keybindings Documentation

## General Navigation

| Key         | Command                            | Description                             |
| ----------- | ---------------------------------- | --------------------------------------- |
| `ctrl-h`    | `workbench.action.navigateLeft`    | Navigate left in editor                 |
| `ctrl-l`    | `workbench.action.navigateRight`   | Navigate right in editor                |
| `ctrl-k`    | `workbench.action.navigateUp`      | Navigate up in editor                   |
| `ctrl-j`    | `workbench.action.navigateDown`    | Navigate down in editor                 |
| `space ,`   | `workbench.action.showAllEditors`  | Show all editors (Vim Normal mode only) |
| `space l f` | `workbench.action.navigateForward` | Go forward in navigation history        |
| `space l b` | `workbench.action.navigateBack`    | Go back in navigation history           |

## Editor Management

| Key         | Command                                      | Description                   |
| ----------- | -------------------------------------------- | ----------------------------- |
| `space s a` | `workbench.action.toggleFullScreen`          | Toggle full screen mode       |
| `space s w` | `workbench.action.toggleEditorWidths`        | Toggle between editor widths  |
| `space s f` | `workbench.action.maximizeEditorHideSidebar` | Maximize editor, hide sidebar |
| `tab`       | `workbench.action.nextEditorInGroup`         | Next editor in group          |
| `shift-tab` | `workbench.action.previousEditorInGroup`     | Previous editor in group      |
| `space w`   | `workbench.action.closeActiveEditor`         | Close the current tab         |
| `space q`   | `workbench.action.closeAllEditors`           | Close all tabs                |

## Sidebar Management

| Key         | Command                                  | Description                  |
| ----------- | ---------------------------------------- | ---------------------------- |
| `space e`   | Toggle sidebar and explorer visibility   | Open/Close sidebar           |
| `space s t` | `workbench.action.terminal.moveToEditor` | Move terminal to editor pane |
| `space s n` | `workbench.action.moveEditorToNewWindow` | Move editor to a new window  |

## File Explorer

| Key       | Command               | Description                   |
| --------- | --------------------- | ----------------------------- |
| `r`       | `renameFile`          | Rename file in Explorer       |
| `c`       | `filesExplorer.copy`  | Copy file in Explorer         |
| `p`       | `filesExplorer.paste` | Paste file in Explorer        |
| `x`       | `filesExplorer.cut`   | Cut file in Explorer          |
| `d`       | `deleteFile`          | Delete file in Explorer       |
| `a`       | `explorer.newFile`    | Create new file in Explorer   |
| `shift-a` | `explorer.newFolder`  | Create new folder in Explorer |

## Terminal Management

| Key         | Command                                       | Description                 |
| ----------- | --------------------------------------------- | --------------------------- |
| `space t t` | `workbench.action.terminal.focus`             | Focus on the terminal       |
| `space t s` | `workbench.action.terminal.toggleTerminal`    | Toggle terminal visibility  |
| `space t n` | `workbench.action.terminal.new`               | Open a new terminal         |
| `space t w` | `workbench.action.terminal.kill`              | Kill the active terminal    |
| `space t a` | `workbench.action.terminal.killActiveTab`     | Kill active terminal tab    |
| `space t q` | `workbench.action.terminal.killAll`           | Kill all terminal tabs      |
| `space t =` | `workbench.action.terminal.fontZoomIn`        | Zoom in on terminal font    |
| `space t -` | `workbench.action.terminal.fontZoomOut`       | Zoom out on terminal font   |
| `space t o` | `workbench.action.terminal.moveIntoNewWindow` | Move terminal to new window |

## Code Editing

| Key         | Command                                     | Description                    |
| ----------- | ------------------------------------------- | ------------------------------ |
| `space a`   | `editor.action.codeAction`                  | Open code actions              |
| `space f`   | `editor.action.triggerSuggest`              | Open code suggestions          |
| `space r r` | `editor.action.rename`                      | Rename symbol                  |
| `space c`   | `editor.action.commentLine`                 | Comment out line               |
| `shift-h`   | `editor.action.showHover`                   | Show hover documentation       |
| `space g`   | `workbench.action.gotoSymbol`               | Open symbol search             |
| `space r g` | `editor.action.goToReferences`              | Go to references of the symbol |
| `space d`   | `editor.action.revealDefinition`            | Go to symbol definition        |
| `space n`   | `editor.action.addSelectionToNextFindMatch` | Find next match                |

## Unused Keys

| Key       | Description |
| --------- | ----------- |
| `space b` | Unused      |
| `space g` | Unused      |
| `space h` | Unused      |
| `space k` | Unused      |
