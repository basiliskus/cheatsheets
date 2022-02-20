# IDE Keybindings Cheatsheet

## Keybindings

### Common

### Editing & Selection

#### Line

| Action                | Sublime               | VS Code              | PyCharm | Emacs | Vi  |          |
| --------------------- | --------------------- | -------------------- | ------- | ----- | --- | -------- |
| Swap line up          | `Ctrl + Shift + Up`   | `Alt + Up`           |         |       |     |          |
| Swap line down        | `Ctrl + Shift + Down` | `Alt + Down`         |         |       |     |          |
| Delete line           | `Ctrl + Shift + K`    | `Ctrl + Shift + K`   |         |       |     |          |
| Duplicate line (up)   |                       | `Shift + Alt + Up`   |         |       |     |          |
| Duplicate line (down) | `Ctrl + Shift + D`    | `Shift + Alt + Down` |         |       |     |          |
| Select current line   | `Ctrl + L`            | `Ctrl + L`           |         |       |     | :hammer: |

#### Multiple line

| Action                 | Sublime               | VS Code             | PyCharm | Emacs | Vi  |     |
| ---------------------- | --------------------- | ------------------- | ------- | ----- | --- | --- |
| Add additional cursors | `Ctrl + Click`        | `Ctrl + Click`      |         |       |     |     |
| Add previous line      | `Ctrl + Alt + Up`     | `Ctrl + Alt + Up`   |         |       |     |     |
| Add next line          | `Ctrl + Alt + Down`   | `Ctrl + Alt + Down` |         |       |     |     |
| Vertical select        | `Shift + R-ClickDrag` | :grey_question:     |         |       |     |     |
| Split into lines       | `Ctrl + Shift + L`    | :grey_question:     |         |       |     |     |

> Tip: first select multiple lines and then use

#### Move Cursor

| Action                        | Sublime                | VS Code                | PyCharm | Emacs | Vi  |     |
| ----------------------------- | ---------------------- | ---------------------- | ------- | ----- | --- | --- |
| Move one word at a time       | `Ctrl + Left or Right` | `Ctrl + Left or Right` |         |       |     |     |
| Move beginning or end of line |                        | `Fn + Left or Right`   |         |       |     |     |
| Move Page Up or Down          |                        | `Fn + Up or Down`      |         |       |     |     |
| Scroll Line Up or Down        |                        | `Ctrl + Up or Down`    |         |       |     |     |

#### Select

| Action                    | Sublime                        | VS Code                        | PyCharm | Emacs | Vi  |          |
| ------------------------- | ------------------------------ | ------------------------------ | ------- | ----- | --- | -------- |
| Select one word at a time | `Ctrl + Shift + Left or Right` | `Ctrl + Shift + Left or Right` |         |       |     |          |
| Select current word       | `Ctrl + D`                     | `Ctrl + D`                     |         |       |     | :hammer: |
| Select all of Find Match  | :grey_question:                | `Ctrl + Shift + L`             |         |       |     | :hammer: |

                            `Selection > Expand Selection to Paragraph`

#### Convert Case

| Action     | Sublime              | VS Code    | PyCharm | Emacs | Vi  |     |
| ---------- | -------------------- | ---------- | ------- | ----- | --- | --- |
| Upper case | `Ctrl + K, Ctrl + U` | :no_entry: |         |       |     |     |
| Lower case | `Ctrl + K, Ctrl + L` | :no_entry: |         |       |     |     |

                            `Edit > Convert Case > Title Case`

#### Clipboard

| Action           | Sublime            | VS Code | PyCharm | Emacs | Vi  |     |
| ---------------- | ------------------ | ------- | ------- | ----- | --- | --- |
| Paste            | `Ctrl + Shift + V` |         |         |       |     |     |
| Paste and indent | `Ctrl + V`         |         |         |       |     |     |

### Find and Replace

#### Find

| Action                 | Sublime                       | VS Code                       | PyCharm | Emacs | Vi  |          |
| ---------------------- | ----------------------------- | ----------------------------- | ------- | ----- | --- | -------- |
| Find                   | `Ctrl + F`                    | `Ctrl + F`                    |         |       |     |          |
| Next find              | `Enter or F3`                 | `Enter or F3`                 |         |       |     | :hammer: |
| Previous find          | `Shift + Enter or Shift + F3` | `Shift + Enter or Shift + F3` |         |       |     | :hammer: |
| Find in files          | `Ctrl + Shift + F`            | `Ctrl + Shift + F`            |         |       |     | :hammer: |
| Next result            | `F4`                          | `F4`                          |         |       |     |          |
| Previous result        | `Shift + F4`                  | `Shift + F4`                  |         |       |     |          |
| Use selection for find | `Ctrl + E`                    | :grey_question:               |         |       |     | :hammer: |

##### Quick Find

| Action              | Sublime              | VS Code     | PyCharm | Emacs | Vi  |          |
| ------------------- | -------------------- | ----------- | ------- | ----- | --- | -------- |
| Find next selection | `Ctrl + F3`          | `Ctrl + F3` |         |       |     | :hammer: |
| Quick find all      | `Alt + F3`           |             |         |       |     | :hammer: |
| Quick add next      | `Ctrl + D`           |             |         |       |     | :hammer: |
| Quick skip next     | `Ctrl + K, Ctrl + D` |             |         |       |     | :hammer: |
| Undo selection      | `Ctrl + U`           |             |         |       |     | :hammer: |

#### Replace

| Action                    | Sublime            | VS Code            | PyCharm | Emacs | Vi  |     |
| ------------------------- | ------------------ | ------------------ | ------- | ----- | --- | --- |
| Incremental find          | `Ctrl + I`         | :grey_question:    |         |       |     |     |
| Find and replace          | `Ctrl + H`         | `Ctrl + H`         |         |       |     |     |
| Replace next              | `Ctrl + Shift + H` | :grey_question:    |         |       |     |     |
| Replace in files          | :grey_question:    | `Ctrl + Shift + H` |         |       |     |     |
| Use selection for replace | `Ctrl + Shift + E` | :grey_question:    |         |       |     |     |

### Quick Access

| Action               | Sublime            | VS Code            | PyCharm | Emacs | Vi  |          |
| -------------------- | ------------------ | ------------------ | ------- | ----- | --- | -------- |
| Goto anything        | `Ctrl + P`         | `Ctrl + P`         |         |       |     | :hammer: |
| Command palette      | `Ctrl + Shift + P` | `Ctrl + Shift + P` |         |       |     | :hammer: |
| Quick switch project | `Ctrl + Alt + P`   | `Ctrl + Alt + P`   |         |       |     |          |
| Fuzzy search         | `#`                | `Ctrl + P + #`     |         |       |     |          |
| Line number          | `:`                | `Ctrl + P + :`     |         |       |     |          |
| Symbol               | `@`                |                    |         |       |     |          |

### Files

| Action                  | Sublime                     | VS Code            | PyCharm | Emacs | Vi  |                                              |
| ----------------------- | --------------------------- | ------------------ | ------- | ----- | --- | -------------------------------------------- |
| Open new file           | `Ctrl + O`                  | `Ctrl + O`         |         |       |     |                                              |
| New file                | `Ctrl + N`                  | `Ctrl + N`         |         |       |     |                                              |
| New file (advanced)     | `Ctrl + Alt + N`            |                    |         |       |     | :hammer: [AdvancedNewFile](#advancednewfile) |
| Save file               | `Ctrl + S`                  | `Ctrl + S`         |         |       |     |                                              |
| Close current file      | `Ctrl + W`                  | `Ctrl + W`         |         |       |     | :hammer:                                     |
| Reopen closed file      | `Ctrl + Shift + T`          | `Ctrl + Shift + T` |         |       |     | :hammer:                                     |
| Open current file again | `File > New View Into File` |                    |         |       |     |                                              |

#### Goto

| Action                                        | Sublime               | VS Code              | PyCharm | Emacs | Vi  |     |
| --------------------------------------------- | --------------------- | -------------------- | ------- | ----- | --- | --- |
| Go to file                                    |                       | `Ctrl + P`           |         |       |     |     |
| Switch file                                   | `Alt + 1-9`           | `Alt + 1-9`          |         |       |     |     |
| Switch file next or previous                  | `Ctrl + PgUp or PgDn` |                      |         |       |     |     |
| Cycle forward open tabs                       | `Ctrl + Tab`          | `Ctrl + Tab`         |         |       |     |     |
| Cycle backward open tabs                      | `Ctrl + Shift + Tab`  | `Ctrl + Shift + Tab` |         |       |     |     |
| Palette of open files                         | `Ctrl + P`            |                      |         |       |     |     |
| Focus on sidebar                              | `Ctrl + 0`            | `Ctrl + 0`           |         |       |     |     |
| Focus back to edit area when focus on sidebar | `Esc`                 |                      |         |       |     |     |
| Reveal in sidebar                             | `Ctrl + Alt + S`      |                      |         |       |     |     |

### View

#### Appearance

| Action       | Sublime    | VS Code    | PyCharm | Emacs | Vi  |     |
| ------------ | ---------- | ---------- | ------- | ----- | --- | --- |
| Larger font  | `Ctrl + =` | `Ctrl + =` |         |       |     |     |
| Smaller font | `Ctrl + -` | `Ctrl + -` |         |       |     |     |

#### Layout

| Action      | Sublime           | VS Code | PyCharm | Emacs | Vi  |     |
| ----------- | ----------------- | ------- | ------- | ----- | --- | --- |
| Single      | `Alt + Shift + 1` |         |         |       |     |     |
| Two columns | `Alt + Shift + 2` |         |         |       |     |     |
| Four grid   | `Alt + Shift + 4` |         |         |       |     |     |

### Console

| Action               | Sublime    | VS Code    | PyCharm | Emacs | Vi  |     |
| -------------------- | ---------- | ---------- | ------- | ----- | --- | --- |
| Show/Hide Console    | `Ctrl + '` | `Ctrl + J` |         |       |     |     |
| Show/Hide Side Panel |            | `Ctrl + B` |         |       |     |     |

### Other

| Action | Sublime | VS Code | PyCharm | Emacs | Vi  |     |
| ------ | ------- | ------- | ------- | ----- | --- | --- |
|        |         |         |         |       |     |     |
|        |         |         |         |       |     |     |
|        |         |         |         |       |     |     |
|        |         |         |         |       |     |     |
|        |         |         |         |       |     |     |
|        |         |         |         |       |     |     |

## References

- [Sublime Text 3 - Useful Shortcuts (Windows)](https://gist.github.com/mrliptontea/4c793ebdf72ed145bcbf)
- [PyCharm keyboard shortcuts](https://www.jetbrains.com/help/pycharm/mastering-keyboard-shortcuts.html)
