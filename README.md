# nim-native-dialogs
Native Operating System Dialogs implementation for Nim-lang via single API.
The library is GUI framework agnostic and supports the next platforms:

 * GNU/Linux + GTK+3
 * OSX + Cocoa
 * Windows + Win32 API

Currently the next dialogs are implemented in a single-file mode:

 * Open File Dialog
 * Save File Dialog
 * Folder Creation Dialog
 * Folder Selection Dialog

## Installation

```bash
$ nimble install https://github.com/SSPkrolik/nim-native-dialogs
```

## Usage
```nim
import native_dialogs

echo callDialogFileOpen("Open File")
echo callDialogFileSave("Save File")
echo callDialogFolderCreate("Create New Folder")
echo callDialogFolderSelect("Open Folder")
```
