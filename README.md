# scipm.extman

scipm.extman is a [scipm](https://github.com/aminassian/scipm) package

## install

```
cd myScipmProject
npm install scipm.extman --save
scipm build
[restart SciTE]
```

## tool menu

- ``Shift+Ctrl+R`` reload current lua (save before)

## lua functions

```
scite_OnWord (called when user has entered a word)
scite_OnEditorLine (called when a line is entered into the editor)
scite_OnOutputLine (called when a line is entered into the output pane)
scite_OnMarginClick(fn,remove)
scite_OnDoubleClick(fn,remove)
scite_OnSavePointLeft(fn,remove)
scite_OnSavePointReached(fn,remove)
scite_OnOpen(fn,remove)
scite_OnSwitchFile(fn,remove)
scite_OnBeforeSave(fn,remove)
scite_OnSave(fn,remove)
scite_OnUpdateUI(fn,remove)
scite_OnChar(fn,remove)
scite_OnOpenSwitch(fn,remove)
scite_GetProp(key,default)
scite_FileExists(f)
scite_CurrentFile()
scite_WordAtPos(pos)
scipm.extman.reload_script()
```
