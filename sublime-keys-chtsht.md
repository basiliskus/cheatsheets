# Sublime Text Keybindings Cheatsheet

## Keybindings

### Files

| Action                  | Keybind                     |                                              |
| ----------------------- | --------------------------- | -------------------------------------------- |
| Open new file           | `Ctrl + O`                  |                                              |
| New file                | `Ctrl + N`                  |                                              |
| New file (advanced)     | `Ctrl + Alt + N`            | :hammer: [AdvancedNewFile](#advancednewfile) |
| Save file               | `Ctrl + S`                  |                                              |
| Close current file      | `Ctrl + W`                  | :hammer:                                     |
| Reopen closed file      | `Ctrl + Shift + T`          | :hammer:                                     |
| Open current file again | `File > New View Into File` |                                              |

### Quick Access

| Action               | Keybind            |          |
| -------------------- | ------------------ | -------- |
| Goto anything        | `Ctrl + P`         | :hammer: |
| Fuzzy search         | `#`                |          |
| Line number          | `:`                |          |
| Symbol               | `@`                |          |
| Quick switch project | `Ctrl + Alt + P`   |          |
| Command palette      | `Ctrl + Shift + P` | :hammer: |

- Access commands quickly
- Quick way to learn key bindings for commands
- Switch sintax mode

### Editing & Selection

#### Line

| Action         | Keybind               |     |
| -------------- | --------------------- | --- |
| Swap line up   | `Ctrl + Shift + Up`   |     |
| Swap line down | `Ctrl + Shift + Down` |     |
| Delete line    | `Ctrl + Shift + K`    |     |
| Duplicate line | `Ctrl + Shift + D`    |     |

#### Multiple line

| Action                 | Keybind                |     |
| ---------------------- | ---------------------- | --- |
| Add additional cursors | `Ctrl + Click`         |     |
| Add previous line      | `Ctrl + Alt + Up`      |     |
| Add next line          | `Ctrl + Alt + Down`    |     |
| Vertical select        | `Shift + R-Click Drag` |     |
| Split into lines       | `Ctrl + Shift + L`     |     |

> Tip: first select multiple lines and then use

#### Word

| Action                    | Keybind                        |          |
| ------------------------- | ------------------------------ | -------- |
| Move one word at a time   | `Ctrl + Left or Right`         |          |
| Select one word at a time | `Ctrl + Shift + Left or Right` |          |
| Select current word       | `Ctrl + D`                     | :hammer: |
| Select current line       | `Ctrl + L`                     | :hammer: |

`Selection > Expand Selection to Paragraph`

#### Convert Case

| Action     | Keybind              |     |
| ---------- | -------------------- | --- |
| Upper case | `Ctrl + K, Ctrl + U` |     |
| Lower case | `Ctrl + K, Ctrl + L` |     |

`Edit > Convert Case > Title Case`

#### Clipboard

| Action           | Keybind            |                                       |
| ---------------- | ------------------ | ------------------------------------- |
| Paste            | `Ctrl + Shift + V` | :left_right_arrow: `Ctrl + V`         |
| Paste and indent | `Ctrl + V`         | :left_right_arrow: `Ctrl + Shift + V` |

#### Bookmarks

| Action          | Keybind             |     |
| --------------- | ------------------- | --- |
| Toggle bookmark | `Ctrl + F2`         |     |
| Next bookmark   | `F2`                |     |
| Prev bookmark   | `Shift + F2`        |     |
| Clear bookmarks | `Ctrl + Shift + F2` |     |

### Code

#### Goto

| Action                   | Keybind                      |                                            |
| ------------------------ | ---------------------------- | ------------------------------------------ |
| Jump to matching bracket | `Ctrl + M`                   | :hammer:                                   |
| Jump to next/prev place  | `Ctrl + Alt + Left or Right` | [Emmet](#emmet)                            |
| Selects next/prev tag    | `Ctrl + Alt + , or .`        | [Emmet](#emmet)                            |
| Go to line               | `Ctrl + G`                   |                                            |
| Go to symbol             | `Ctrl + R`                   |                                            |
| Go to symbol in project  | `Ctrl + Shift + R`           | :no_entry:                                 |
| Go to definition         | `F12`                        | :warning: replace with `Ctrl + Alt + Down` |
| Jump back                | `Alt + -`                    |                                            |

#### Expand Selection

| Action                          | Keybind                |          |
| ------------------------------- | ---------------------- | -------- |
| Expand selection to tag         | `Ctrl + Shift + A`     | :hammer: |
| Expand selection to bracket     | `Ctrl + Shift + M`     | :hammer: |
| Expand selection to indentation | `Ctrl + Shift + J`     |          |
| Expand selection to scope       | `Ctrl + Shift + Space` |          |

#### Indentation

| Action                  | Keybind         |           |
| ----------------------- | --------------- | --------- |
| Indent or unindent line | `Ctrl + ] or [` | :hammer:  |
| Indent file             | `F12`           | :warning: |

`Edit > Line > Reindent`

#### Snippets

| Action                      | Keybind |                 |
| --------------------------- | ------- | --------------- |
| Add 'id' property to tag    | `#`     | [Emmet](#emmet) |
| Add 'class' property to tag | `.`     | [Emmet](#emmet) |

#### Folding

| Action      | Keybind                |     |
| ----------- | ---------------------- | --- |
| Fold        | `Ctrl + Shift + [`     |     |
| Unfold      | `Ctrl + Shift + ]`     |     |
| Unfold all  | `Ctrl + K, Ctrl J`     |     |
| Fold levels | `Ctrl + K, Ctrl + 1-9` |     |

#### Comment

| Action               | Keybind            |          |
| -------------------- | ------------------ | -------- |
| Toggle comment       | `Ctrl + /`         | :hammer: |
| Toggle block comment | `Ctrl + Shift + /` | :hammer: |

#### Tag

| Action                  | Keybind            |     |
| ----------------------- | ------------------ | --- |
| Close tag               | `Alt + .`          |     |
| Expand selection to tag | `Ctrl + Shift + A` |     |
| Wrap selection with tag | `Alt + Shift + W`  |     |

#### Hyperlinks

| Action                                    | Keybind                  |                                       |
| ----------------------------------------- | ------------------------ | ------------------------------------- |
| Open url, file, folder or search for word | `Ctrl + Alt + U`         | :hammer: [Open URL](#open-url)        |
| Wrao word / selection as link             | `Ctrl + Alt + L`         | [Hyperlink Helper](#hyperlink-helper) |
| Lookup with Google & link                 | `Ctrl + Alt + Shift + L` | [Hyperlink Helper](#hyperlink-helper) |

### File Navigation

#### Goto

| Action                                        | Keybind               |     |
| --------------------------------------------- | --------------------- | --- |
| Switch file                                   | `Alt + 1-9`           |     |
| Switch file next or previous                  | `Ctrl + PgUp or PgDn` |     |
| Cycle forward open tabs                       | `Ctrl + Tab`          |     |
| Cycle backward open tabs                      | `Ctrl + Shift + Tab`  |     |
| Palette of open files                         | `Ctrl + P`            |     |
| Focus on sidebar                              | `Ctrl + 0`            |     |
| Focus back to edit area when focus on sidebar | `Esc`                 |     |
| Reveal in sidebar                             | `Ctrl + Alt + S`      |     |

#### Tab groups

| Action                 | Keybind                 |     |
| ---------------------- | ----------------------- | --- |
| Navigate tab groups    | `Ctrl + 1-9`            |     |
| Move file to new group | `Ctrl + K, Ctrl + Up`   |     |
| Close group            | `Ctrl + K, Ctrl + Down` |     |

##### Origami

| Action                                                 | Keybind                          |     |
| ------------------------------------------------------ | -------------------------------- | --- |
| Move focus to the pane in that direction               | `Ctrl + K, Arrow`                |     |
| Move the current file to the destination               | `Ctrl + K, Shift + Arrow`        |     |
| Clone the current file to the destination              | `Ctrl + K, Alt + Arrow`          |     |
| Create an adjacent pane                                | `Ctrl + K, Ctrl + Arrow`         |     |
| Destroy an adjacent pane                               | `Ctrl + K, Ctrl + Shift + Arrow` |     |
| Zoom the current pane so it takes up 90% of the screen | `Ctrl + K, Ctrl + Z`             |     |
| Unzoom (equally space all panes)                       | `Ctrl + K, Ctrl + Shift + Z`     |     |
| Adjust the top and bottom separator                    | `Ctrl + K, Ctrl + R`             |     |
| Adjust the left and right separator                    | `Ctrl + K, Ctrl + C`             |     |

### Find and Replace

| Action                    | Keybind                       |          |
| ------------------------- | ----------------------------- | -------- |
| Find                      | `Ctrl + F`                    |          |
| Next find                 | `Enter or F3`                 | :hammer: |
| Previous find             | `Shift + Enter or Shift + F3` | :hammer: |
| Use selection for find    | `Ctrl + E`                    | :hammer: |
| Incremental find          | `Ctrl + I`                    |          |
| Find and replace          | `Ctrl + H`                    |          |
| Replace next              | `Ctrl + Shift + H`            |          |
| Use selection for replace | `Ctrl + Shift + E`            |          |
| Find in files             | `Ctrl + Shift + F`            | :hammer: |
| Next result               | `F4`                          |          |
| Previous result           | `Shift + F4`                  |          |

> Tip: turn off "Use Buffer" to see results in botton panel

#### Quick Find

| Action          | Keybind              |          |
| --------------- | -------------------- | -------- |
| Quick find      | `Ctrl + F3`          | :hammer: |
| Quick find all  | `Alt + F3`           | :hammer: |
| Quick add next  | `Ctrl + D`           | :hammer: |
| Quick skip next | `Ctrl + K, Ctrl + D` | :hammer: |
| Undo selection  | `Ctrl + U`           | :hammer: |

### View

#### Font Size

| Action       | Keybind    |     |
| ------------ | ---------- | --- |
| Larger font  | `Ctrl + =` |     |
| Smaller font | `Ctrl + -` |     |

#### Layout

| Action      | Keybind           |     |
| ----------- | ----------------- | --- |
| Single      | `Alt + Shift + 1` |     |
| Two columns | `Alt + Shift + 2` |     |
| Four grid   | `Alt + Shift + 4` |     |

### Console

| Action       | Keybind    |     |
| ------------ | ---------- | --- |
| Show Console | `Ctrl + '` |     |

#### Useful commands

| Action               | Keybind                      |     |
| -------------------- | ---------------------------- | --- |
| Show command actions | `sublime.log_commands(True)` |     |

### Automation

#### Autocomplete

| Action               | Keybind           |     |
| -------------------- | ----------------- | --- |
| Auto complete list   | `Ctrl + Spacebar` |     |
| Auto complete commit | `Tab`             |     |

#### Snippets

| Action                      | Keybind                     |     |
| --------------------------- | --------------------------- | --- |
| Displays available snippets | `Ctrl + Shift + P + "snip"` |     |

#### Macros

| Action                    | Keybind            |     |
| ------------------------- | ------------------ | --- |
| Start/end macro recording | `Ctrl + Q`         |     |
| Playback macro            | `Ctrl + Shift + Q` |     |

### Utilities

| Action                   | Keybind            |                                           |
| ------------------------ | ------------------ | ----------------------------------------- |
| Open system color picker | `Ctrl + Shift + C` | [SideBarEnhacements](#sidebarenhacements) |

### Context Tools

#### PlainTasks

[PlainTasks](#plaintasks)

| Action                        | Keybind            |     |
| ----------------------------- | ------------------ | --- |
| Add new task                  | `Ctrl + Enter`     |     |
| Mark task as done (toggle)    | `Ctrl + D`         |     |
| Archive task                  | `Ctrl + Shift + A` |     |
| Tag task priority as Critical | `C + Tab`          |     |
| Tag task priority as High     | `H + Tab`          |     |
| Tag task priority as Low      | `L + Tab`          |     |
| Tag task priority as Today    | `T + Tab`          |     |

### Examples

##### Copy/paste text inside html tags, edit and copy/paste back

| Action                     | Keybind            |     |
| -------------------------- | ------------------ | --- |
| Select tag                 | `Ctrl + D`         |     |
| Move right                 | `Ctrl + Right`     |     |
| Expand tag selection       | `Ctrl + Shift + A` |     |
| Copy                       | `Ctrl + C`         |     |
| New file                   | `Ctrl + N`         |     |
| Paste                      | `Ctrl + V`         |     |
| Edit text                  |                    |     |
| Copy all                   | `Ctrl + A`         |     |
| Break selection into lines | `Ctrl + Shift + L` |     |
| Copy multiple selection    | `Ctrl + C`         |     |
| Go back to prev file       |                    |     |
| Paste into selection       | `Ctrl + V`         |     |

## Installed Packages

### AdvancedNewFile

File creation plugin
https://github.com/skuroda/Sublime-AdvancedNewFile  
https://github.com/skuroda/Sublime-AdvancedNewFile/wiki/Commands

### ColorPicker

Color picker for Sublime Text
http://weslly.github.io/ColorPicker/

### Emmet

Improves HTML & CSS workflow
https://github.com/sergeche/emmet-sublime

### HyperlinkHelper

Quickly create hyperlinks from selected text or clipboard contents
https://github.com/sentience/HyperlinkHelper

### Open URL

Open URLs, files, folders, or google text under the cursor or in selected text for Sublime Text
https://github.com/noahcoad/open-url

### PlainTasks

An opinionated todo-list plugin for Sublime Text editor
https://github.com/aziz/PlainTasks

### SideBarEnhacements

Provides enhancements to the operations on Sidebar of Files and Folders for Sublime Text
https://github.com/titoBouzout/SideBarEnhancements

### Origami

Split the window however you like! Create new panes, delete panes, move and clone views from pane to pane.
https://github.com/SublimeText/Origami

## Other Packages

- [SublimeCodeIntel](https://sublimecodeintel.github.io/)
- [Word Count](https://github.com/titoBouzout/WordCount)

## Missing Key Bindings

- `File > New View Into File`
- `Edit > Line > Reindent`
- `Edit > Convert Case > Title Case`
- `Selection > Expand Selection to Paragraph`

## Conflicting Key Bindings

- `F12`:
  - `Goto > Goto definition...`
  - `Edit > Line > Reindent`
- `Ctrl + Shift + /`
  - `Edit > Comment > Toggle Block Comment `
  - `Emmet Package > Toggle comment tag scope`

## Modified Key Bindings

| Action                  | Keybind                         |     |
| ----------------------- | ------------------------------- | --- |
| Edit > Paste            | `Ctrl + V` → `Ctrl + Shift + V` |     |
| Edit > Paste and Indent | `Ctrl + Shift + V` → `Ctrl + V` |     |

## Legend

| Emoji              | Description                                    |
| ------------------ | ---------------------------------------------- |
| :warning:          | Conflict (fix in `Preferences > Key Bindings`) |
| :hammer:           | Drill                                          |
| :left_right_arrow: | Modified                                       |
| :no_entry:         | Not working or Missing                         |

## References

- https://www.linkedin.com/learning/learning-sublime-text-3
- https://gist.github.com/mrliptontea/4c793ebdf72ed145bcbf

## Resources

- [Sublime Text - Devhints](https://devhints.io/sublime-text)
- [Sublime Text 3 - Awesome Cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets/blob/master/tools/sublime_text.md)
