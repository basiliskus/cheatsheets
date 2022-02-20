# Sublime Text Keybindings Cheatsheet

## Keybindings

### Files

| Action                  | Keybind                     |                                              |
| ----------------------- | --------------------------- | -------------------------------------------- |
| Open new file           | `^ + O`                     |                                              |
| New file                | `^ + N`                     |                                              |
| New file (advanced)     | `^ + ⌥ + N`                 | :hammer: [AdvancedNewFile](#advancednewfile) |
| Save file               | `^ + S`                     |                                              |
| Close current file      | `^ + W`                     | :hammer:                                     |
| Reopen closed file      | `^ + ⇧ + T`                 | :hammer:                                     |
| Open current file again | `File > New View Into File` |                                              |

### Quick Access

| Action               | Keybind     |          |
| -------------------- | ----------- | -------- |
| Goto anything        | `^ + P`     | :hammer: |
| Fuzzy search         | `^ + P + #` |          |
| Line number          | `^ + P + :` |          |
| Symbol               | `^ + P + @` |          |
| Quick switch project | `^ + ⌥ + P` |          |
| Command palette      | `^ + ⇧ + P` | :hammer: |

- Access commands quickly
- Quick way to learn key bindings for commands
- Switch sintax mode

### Editing & Selection

#### Line

| Action         | Keybind     |     |
| -------------- | ----------- | --- |
| Swap line up   | `^ + ⇧ + ↑` |     |
| Swap line down | `^ + ⇧ + ↓` |     |
| Delete line    | `^ + ⇧ + K` |     |
| Duplicate line | `^ + ⇧ + D` |     |

#### Multiple line

| Action                 | Keybind            |     |
| ---------------------- | ------------------ | --- |
| Add additional cursors | `^ + Click`        |     |
| Add previous line      | `^ + ⌥ + ↑`        |     |
| Add next line          | `^ + ⌥ + ↓`        |     |
| Vertical select        | `⇧ + R-Click Drag` |     |
| Split into lines       | `^ + ⇧ + L`        |     |

> Tip: first select multiple lines and then use

#### Word

| Action                    | Keybind          |          |
| ------------------------- | ---------------- | -------- |
| Move one word at a time   | `^ + ← or →`     |          |
| Select one word at a time | `^ + ⇧ + ← or →` |          |
| Select current word       | `^ + D`          | :hammer: |
| Select current line       | `^ + L`          | :hammer: |

`Selection > Expand Selection to Paragraph`

#### Convert Case

| Action     | Keybind        |     |
| ---------- | -------------- | --- |
| Upper case | `^ + K, ^ + U` |     |
| Lower case | `^ + K, ^ + L` |     |

`Edit > Convert Case > Title Case`

#### Clipboard

| Action           | Keybind     |                                |
| ---------------- | ----------- | ------------------------------ |
| Paste            | `^ + ⇧ + V` | :left_right_arrow: `^ + V`     |
| Paste and indent | `^ + V`     | :left_right_arrow: `^ + ⇧ + V` |

#### Bookmarks

| Action          | Keybind      |     |
| --------------- | ------------ | --- |
| Toggle bookmark | `^ + F2`     |     |
| Next bookmark   | `F2`         |     |
| Prev bookmark   | `⇧ + F2`     |     |
| Clear bookmarks | `^ + ⇧ + F2` |     |

### Code

#### Goto

| Action                   | Keybind          |                                    |
| ------------------------ | ---------------- | ---------------------------------- |
| Jump to matching bracket | `^ + M`          | :hammer:                           |
| Jump to next/prev place  | `^ + ⌥ + ← or →` | [Emmet](#emmet)                    |
| Selects next/prev tag    | `^ + ⌥ + , or .` | [Emmet](#emmet)                    |
| Go to line               | `^ + G`          |                                    |
| Go to symbol             | `^ + R`          |                                    |
| Go to symbol in project  | `^ + ⇧ + R`      | :no_entry:                         |
| Go to definition         | `F12`            | :warning: replace with `^ + ⌥ + ↓` |
| Jump back                | `⌥ + -`          |                                    |

#### Expand Selection

| Action                          | Keybind     |          |
| ------------------------------- | ----------- | -------- |
| Expand selection to tag         | `^ + ⇧ + A` | :hammer: |
| Expand selection to bracket     | `^ + ⇧ + M` | :hammer: |
| Expand selection to indentation | `^ + ⇧ + J` |          |
| Expand selection to scope       | `^ + ⇧ + ⎵` |          |

#### Indentation

| Action                  | Keybind      |           |
| ----------------------- | ------------ | --------- |
| Indent or unindent line | `^ + ] or [` | :hammer:  |
| Indent file             | `F12`        | :warning: |

`Edit > Line > Reindent`

#### Snippets

| Action                      | Keybind |                 |
| --------------------------- | ------- | --------------- |
| Add 'id' property to tag    | `#`     | [Emmet](#emmet) |
| Add 'class' property to tag | `.`     | [Emmet](#emmet) |

#### Folding

| Action      | Keybind          |     |
| ----------- | ---------------- | --- |
| Fold        | `^ + ⇧ + [`      |     |
| Unfold      | `^ + ⇧ + ]`      |     |
| Unfold all  | `^ + K, ^ J`     |     |
| Fold levels | `^ + K, ^ + 1-9` |     |

#### Comment

| Action               | Keybind     |          |
| -------------------- | ----------- | -------- |
| Toggle comment       | `^ + /`     | :hammer: |
| Toggle block comment | `^ + ⇧ + /` | :hammer: |

#### Tag

| Action                  | Keybind     |     |
| ----------------------- | ----------- | --- |
| Close tag               | `⌥ + .`     |     |
| Expand selection to tag | `^ + ⇧ + A` |     |
| Wrap selection with tag | `⌥ + ⇧ + W` |     |

#### Hyperlinks

| Action                                    | Keybind         |                                       |
| ----------------------------------------- | --------------- | ------------------------------------- |
| Open url, file, folder or search for word | `^ + ⌥ + U`     | :hammer: [Open URL](#open-url)        |
| Wrao word / selection as link             | `^ + ⌥ + L`     | [Hyperlink Helper](#hyperlink-helper) |
| Lookup with Google & link                 | `^ + ⌥ + ⇧ + L` | [Hyperlink Helper](#hyperlink-helper) |

### File Navigation

#### Goto

| Action                                        | Keybind      |     |
| --------------------------------------------- | ------------ | --- |
| Switch file                                   | `⌥ + 1-9`    |     |
| Switch file next or previous                  | `^ + ⇞ or ⇟` |     |
| Cycle forward open tabs                       | `^ + ⇥`      |     |
| Cycle backward open tabs                      | `^ + ⇧ + ⇥`  |     |
| Palette of open files                         | `^ + P`      |     |
| Focus on sidebar                              | `^ + 0`      |     |
| Focus back to edit area when focus on sidebar | `⎋`          |     |
| Reveal in sidebar                             | `^ + ⌥ + S`  |     |

#### Tab groups

| Action                 | Keybind        |     |
| ---------------------- | -------------- | --- |
| Navigate tab groups    | `^ + 1-9`      |     |
| Move file to new group | `^ + K, ^ + ↑` |     |
| Close group            | `^ + K, ^ + ↓` |     |

##### Origami

| Action                                                 | Keybind                |     |
| ------------------------------------------------------ | ---------------------- | --- |
| Move focus to the pane in that direction               | `^ + K, Arrow`         |     |
| Move the current file to the destination               | `^ + K, ⇧ + Arrow`     |     |
| Clone the current file to the destination              | `^ + K, ⌥ + Arrow`     |     |
| Create an adjacent pane                                | `^ + K, ^ + Arrow`     |     |
| Destroy an adjacent pane                               | `^ + K, ^ + ⇧ + Arrow` |     |
| Zoom the current pane so it takes up 90% of the screen | `^ + K, ^ + Z`         |     |
| Unzoom (equally space all panes)                       | `^ + K, ^ + ⇧ + Z`     |     |
| Adjust the top and bottom separator                    | `^ + K, ^ + R`         |     |
| Adjust the left and right separator                    | `^ + K, ^ + C`         |     |

### Find and Replace

| Action                    | Keybind           |          |
| ------------------------- | ----------------- | -------- |
| Find                      | `^ + F`           |          |
| Next find                 | `↵ or F3`         | :hammer: |
| Previous find             | `⇧ + ↵ or ⇧ + F3` | :hammer: |
| Use selection for find    | `^ + E`           | :hammer: |
| Incremental find          | `^ + I`           |          |
| Find and replace          | `^ + H`           |          |
| Replace next              | `^ + ⇧ + H`       |          |
| Use selection for replace | `^ + ⇧ + E`       |          |
| Find in files             | `^ + ⇧ + F`       | :hammer: |
| Next result               | `F4`              |          |
| Previous result           | `⇧ + F4`          |          |

> Tip: turn off "Use Buffer" to see results in botton panel

#### Quick Find

| Action          | Keybind        |          |
| --------------- | -------------- | -------- |
| Quick find      | `^ + F3`       | :hammer: |
| Quick find all  | `⌥ + F3`       | :hammer: |
| Quick add next  | `^ + D`        | :hammer: |
| Quick skip next | `^ + K, ^ + D` | :hammer: |
| Undo selection  | `^ + U`        | :hammer: |

### View

#### Font Size

| Action       | Keybind |     |
| ------------ | ------- | --- |
| Larger font  | `^ + =` |     |
| Smaller font | `^ + -` |     |

#### Layout

| Action      | Keybind     |     |
| ----------- | ----------- | --- |
| Single      | `⌥ + ⇧ + 1` |     |
| Two columns | `⌥ + ⇧ + 2` |     |
| Four grid   | `⌥ + ⇧ + 4` |     |

### Console

| Action       | Keybind |     |
| ------------ | ------- | --- |
| Show Console | `^ + '` |     |

#### Useful commands

| Action               | Keybind                      |     |
| -------------------- | ---------------------------- | --- |
| Show command actions | `sublime.log_commands(True)` |     |

### Automation

#### Autocomplete

| Action               | Keybind        |     |
| -------------------- | -------------- | --- |
| Auto complete list   | `^ + Spacebar` |     |
| Auto complete commit | `⇥`            |     |

#### Snippets

| Action                      | Keybind              |     |
| --------------------------- | -------------------- | --- |
| Displays available snippets | `^ + ⇧ + P + "snip"` |     |

#### Macros

| Action                    | Keybind     |     |
| ------------------------- | ----------- | --- |
| Start/end macro recording | `^ + Q`     |     |
| Playback macro            | `^ + ⇧ + Q` |     |

### Utilities

| Action                   | Keybind     |                                           |
| ------------------------ | ----------- | ----------------------------------------- |
| Open system color picker | `^ + ⇧ + C` | [SideBarEnhacements](#sidebarenhacements) |

### Context Tools

#### PlainTasks

[PlainTasks](#plaintasks)

| Action                        | Keybind     |     |
| ----------------------------- | ----------- | --- |
| Add new task                  | `^ + Enter` |     |
| Mark task as done (toggle)    | `^ + D`     |     |
| Archive task                  | `^ + ⇧ + A` |     |
| Tag task priority as Critical | `C + ⇥`     |     |
| Tag task priority as High     | `H + ⇥`     |     |
| Tag task priority as Low      | `L + ⇥`     |     |
| Tag task priority as Today    | `T + ⇥`     |     |

### Examples

##### Copy/paste text inside html tags, edit and copy/paste back

| Action                     | Keybind     |     |
| -------------------------- | ----------- | --- |
| Select tag                 | `^ + D`     |     |
| Move right                 | `^ + →`     |     |
| Expand tag selection       | `^ + ⇧ + A` |     |
| Copy                       | `^ + C`     |     |
| New file                   | `^ + N`     |     |
| Paste                      | `^ + V`     |     |
| Edit text                  |             |     |
| Copy all                   | `^ + A`     |     |
| Break selection into lines | `^ + ⇧ + L` |     |
| Copy multiple selection    | `^ + C`     |     |
| Go back to prev file       |             |     |
| Paste into selection       | `^ + V`     |     |

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

| Action                  | Keybind               |     |
| ----------------------- | --------------------- | --- |
| Edit > Paste            | `^ + V` → `^ + ⇧ + V` |     |
| Edit > Paste and Indent | `^ + ⇧ + V` → `^ + V` |     |

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
