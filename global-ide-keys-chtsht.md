# IDE Keybindings Cheatsheet

## Keybindings

### Practice :hammer:

- Find all instances
- Expand/Shrink

### Editing & Selection

#### Line

| Action                | Sublime     | VS Code     | PyCharm | Emacs | Vi  |          |
| --------------------- | ----------- | ----------- | ------- | ----- | --- | -------- |
| Swap line up          | `^ + ⇧ + ↑` | `⌥ + ↑`     |         |       |     |          |
| Swap line down        | `^ + ⇧ + ↓` | `⌥ + ↓`     |         |       |     |          |
| Delete line           | `^ + ⇧ + K` | `^ + ⇧ + K` |         |       |     |          |
| Duplicate line (up)   |             | `⇧ + ⌥ + ↑` |         |       |     |          |
| Duplicate line (down) | `^ + ⇧ + D` | `⇧ + ⌥ + ↓` |         |       |     |          |
| Select current line   | `^ + L`     | `^ + L`     |         |       |     | :hammer: |

#### Multiple line

| Action                 | Sublime           | VS Code         | PyCharm | Emacs | Vi  |     |
| ---------------------- | ----------------- | --------------- | ------- | ----- | --- | --- |
| Add additional cursors | `^ + Click`       | `^ + Click`     |         |       |     |     |
| Add previous line      | `^ + ⌥ + ↑`       | `^ + ⌥ + ↑`     |         |       |     |     |
| Add next line          | `^ + ⌥ + ↓`       | `^ + ⌥ + ↓`     |         |       |     |     |
| Vertical select        | `⇧ + R-ClickDrag` | :grey_question: |         |       |     |     |
| Split into lines       | `^ + ⇧ + L`       | :grey_question: |         |       |     |     |

> Tip: first select multiple lines and then use

#### Move Cursor

| Action                 | Sublime | VS Code      | PyCharm | Emacs | Vi  |     |
| ---------------------- | ------- | ------------ | ------- | ----- | --- | --- |
| Scroll Line Up or Down |         | `^ + ↑ or ↓` |         |       |     |     |

#### Select

| Action                   | Sublime         | VS Code     | PyCharm | Emacs | Vi  |          |
| ------------------------ | --------------- | ----------- | ------- | ----- | --- | -------- |
| Select current word      | `^ + D`         | `^ + D`     |         |       |     | :hammer: |
| Select all of Find Match | :grey_question: | `^ + ⇧ + L` |         |       |     | :hammer: |

                            `Selection > Expand Selection to Paragraph`

#### Convert Case

| Action     | Sublime        | VS Code    | PyCharm | Emacs | Vi  |     |
| ---------- | -------------- | ---------- | ------- | ----- | --- | --- |
| Upper case | `^ + K, ^ + U` | :no_entry: |         |       |     |     |
| Lower case | `^ + K, ^ + L` | :no_entry: |         |       |     |     |

                            `Edit > Convert Case > Title Case`

#### Clipboard

| Action           | Sublime     | VS Code | PyCharm | Emacs | Vi  |     |
| ---------------- | ----------- | ------- | ------- | ----- | --- | --- |
| Paste            | `^ + ⇧ + V` |         |         |       |     |     |
| Paste and indent | `^ + V`     |         |         |       |     |     |

### Find and Replace

#### Find

| Action                 | Sublime           | VS Code           | PyCharm | Emacs | Vi  |          |
| ---------------------- | ----------------- | ----------------- | ------- | ----- | --- | -------- |
| Next find              | `↵ or F3`         | `↵ or F3`         |         |       |     | :hammer: |
| Previous find          | `⇧ + ↵ or ⇧ + F3` | `⇧ + ↵ or ⇧ + F3` |         |       |     | :hammer: |
| Find in files          | `^ + ⇧ + F`       | `^ + ⇧ + F`       |         |       |     |          |
| Next result            | `F4`              | `F4`              |         |       |     |          |
| Previous result        | `⇧ + F4`          | `⇧ + F4`          |         |       |     |          |
| Use selection for find | `^ + E`           | :grey_question:   |         |       |     | :hammer: |

##### Quick Find

| Action              | Sublime        | VS Code  | PyCharm | Emacs | Vi  |          |
| ------------------- | -------------- | -------- | ------- | ----- | --- | -------- |
| Find next selection | `^ + F3`       | `^ + F3` |         |       |     | :hammer: |
| Quick find all      | `⌥ + F3`       |          |         |       |     | :hammer: |
| Quick add next      | `^ + D`        |          |         |       |     | :hammer: |
| Quick skip next     | `^ + K, ^ + D` |          |         |       |     | :hammer: |
| Undo selection      | `^ + U`        |          |         |       |     | :hammer: |

#### Replace

| Action                    | Sublime         | VS Code         | PyCharm | Emacs | Vi  |     |
| ------------------------- | --------------- | --------------- | ------- | ----- | --- | --- |
| Incremental find          | `^ + I`         | :grey_question: |         |       |     |     |
| Replace next              | `^ + ⇧ + H`     | :grey_question: |         |       |     |     |
| Replace in files          | :grey_question: | `^ + ⇧ + H`     |         |       |     |     |
| Use selection for replace | `^ + ⇧ + E`     | :grey_question: |         |       |     |     |

### Quick Access

| Action               | Sublime     | VS Code     | PyCharm | Emacs | Vi  |          |
| -------------------- | ----------- | ----------- | ------- | ----- | --- | -------- |
| Goto anything        | `^ + P`     | `^ + P`     |         |       |     | :hammer: |
| Command palette      | `^ + ⇧ + P` | `^ + ⇧ + P` |         |       |     | :hammer: |
| Quick switch project | `^ + ⌥ + P` | `^ + ⌥ + P` |         |       |     |          |
| Fuzzy search         | `#`         | `^ + P + #` |         |       |     |          |
| Line number          | `:`         | `^ + P + :` |         |       |     |          |
| Symbol               | `@`         |             |         |       |     |          |

### Files

| Action                  | Sublime                     | VS Code     | PyCharm | Emacs | Vi  |                                              |
| ----------------------- | --------------------------- | ----------- | ------- | ----- | --- | -------------------------------------------- |
| New file (advanced)     | `^ + ⌥ + N`                 |             |         |       |     | :hammer: [AdvancedNewFile](#advancednewfile) |
| Reopen closed file      | `^ + ⇧ + T`                 | `^ + ⇧ + T` |         |       |     | :hammer:                                     |
| Open current file again | `File > New View Into File` |             |         |       |     |                                              |

#### Goto

| Action                                        | Sublime      | VS Code     | PyCharm | Emacs | Vi  |     |
| --------------------------------------------- | ------------ | ----------- | ------- | ----- | --- | --- |
| Go to file                                    |              | `^ + P`     |         |       |     |     |
| Switch file                                   | `⌥ + 1-9`    | `⌥ + 1-9`   |         |       |     |     |
| Switch file next or previous                  | `^ + ⇞ or ⇟` |             |         |       |     |     |
| Cycle forward open tabs                       | `^ + ⇥`      | `^ + ⇥`     |         |       |     |     |
| Cycle backward open tabs                      | `^ + ⇧ + ⇥`  | `^ + ⇧ + ⇥` |         |       |     |     |
| Palette of open files                         | `^ + P`      |             |         |       |     |     |
| Focus on sidebar                              | `^ + 0`      | `^ + 0`     |         |       |     |     |
| Focus back to edit area when focus on sidebar | `⎋`          |             |         |       |     |     |
| Reveal in sidebar                             | `^ + ⌥ + S`  |             |         |       |     |     |

### Layout

| Action      | Sublime     | VS Code | PyCharm | Emacs | Vi  |     |
| ----------- | ----------- | ------- | ------- | ----- | --- | --- |
| Single      | `⌥ + ⇧ + 1` |         |         |       |     |     |
| Two columns | `⌥ + ⇧ + 2` |         |         |       |     |     |
| Four grid   | `⌥ + ⇧ + 4` |         |         |       |     |     |

### Console

| Action               | Sublime | VS Code | PyCharm | Emacs | Vi  |     |
| -------------------- | ------- | ------- | ------- | ----- | --- | --- |
| Show/Hide Console    | `^ + '` | `^ + J` |         |       |     |     |
| Show/Hide Side Panel |         | `^ + B` |         |       |     |     |

## References

- [Sublime Text 3 - Useful Shortcuts (Windows)](https://gist.github.com/mrliptontea/4c793ebdf72ed145bcbf)
- [PyCharm keyboard shortcuts](https://www.jetbrains.com/help/pycharm/mastering-keyboard-shortcuts.html)
