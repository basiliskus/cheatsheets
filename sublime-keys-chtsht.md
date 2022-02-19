# Sublime Text Keybindings Cheatsheet

<!-- MarkdownTOC -->

* [Keybindingss](#keybindings)
  * [Files](#files)
  * [Quick Access](#quick-access)
  * [Editing & Selection](#editing--selection)
    * [Line](#line)
    * [Multiple line](#multiple-line)
    * [Word](#word)
    * [Convert Case](#convert-case)
    * [Clipboard](#clipboard)
    * [Bookmarks](#bookmarks)
  * [Code](#code)
    * [Goto](#goto)
    * [Expand Selection](#expand-selection)
    * [Indentation](#indentation)
    * [Snippets](#snippets)
    * [Folding](#folding)
    * [Comment](#comment)
    * [Tag](#tag)
    * [Hyperlinks](#hyperlinks)
  * [File Navigation](#file-navigation)
    * [Goto](#goto-1)
    * [Tab groups](#tab-groups)
      * [Origami](#origami)
  * [Find and Replace](#find-and-replace)
    * [Quick Find](#quick-find)
  * [View](#view)
    * [Font Size](#font-size)
    * [Layout](#layout)
  * [Console](#console)
    * [Useful commands](#useful-commands)
  * [Automation](#automation)
    * [Autocomplete](#autocomplete)
    * [Snippets](#snippets-1)
    * [Macros](#macros)
  * [Utilities](#utilities)
  * [Context Tools](#context-tools)
    * [PlainTasks](#plaintasks)
  * [Examples](#examples)
      * [Copy/paste text inside html tags, edit and copy/paste back](#copypaste-text-inside-html-tags-edit-and-copypaste-back)
* [Installed Packages](#installed-packages)
  * [AdvancedNewFile](#advancednewfile)
  * [ColorPicker](#colorpicker)
  * [Emmet](#emmet)
  * [HyperlinkHelper](#hyperlinkhelper)
  * [Open URL](#open-url)
  * [PlainTasks](#plaintasks-1)
  * [SideBarEnhacements](#sidebarenhacements)
  * [Origami](#origami-1)
* [Other Packages](#other-packages)
* [Missing Key Bindings](#missing-key-bindings)
* [Conflicting Key Bindings](#conflicting-key-bindings)
* [Modified Key Bindings](#modified-key-bindings)
* [Legend](#legend)
* [References](#references)

<!-- /MarkdownTOC -->


## Keybindings

### Files
`Ctrl + O`:                     Open new file  
`Ctrl + N`:                     New file  
`Ctrl + Alt + N`                New file (advanced)                 :hammer:      ([AdvancedNewFile](#advancednewfile))  
`Ctrl + S`:                     Save file  
`Ctrl + W`:                     Close current file                  :hammer:  
`Ctrl + Shift + T`:             Reopen closed file                  :hammer:  
`File > New View Into File`     Open current file again  


### Quick Access
`Ctrl + P`:                     Goto anything                      :hammer:  
  `#`:                          Fuzzy search  
  `:`:                          Line number  
  `@`:                          Symbol  
`Ctrl + Alt + P`:               Quick switch project  
`Ctrl + Shift + P`:             Command palette                     :hammer:  
* Access commands quickly  
* Quick way to learn key bindings for commands  
* Switch sintax mode  


### Editing & Selection

#### Line
`Ctrl + Shift + Up`:            Swap line up  
`Ctrl + Shift + Down`:          Swap line down  
`Ctrl + Shift + K`:             Delete line  
`Ctrl + Shift + D`:             Duplicate line  

#### Multiple line
`Ctrl + Click`:                 Add additional cursors  
`Ctrl + Alt + Up`:              Add previous line  
`Ctrl + Alt + Down`:            Add next line  
`Shift + R-Click Drag`:         Vertical select  
`Ctrl + Shift + L`:             Split into lines  
> Tip: first select multiple lines and then use  

#### Word
`Ctrl + Left or Right`:         Move one word at a time  
`Ctrl + Shift + Left or Right`: Select one word at a time  
`Ctrl + D`:                     Select current word                 :hammer:  
`Ctrl + L`:                     Select current line                 :hammer:  
`Selection > Expand Selection to Paragraph`: 

#### Convert Case
`Ctrl + K, Ctrl + U`:           Upper case  
`Ctrl + K, Ctrl + L`:           Lower case  
`Edit > Convert Case > Title Case`: 

#### Clipboard
`Ctrl + Shift + V`:             Paste                               :left_right_arrow: `Ctrl + V`  
`Ctrl + V`:                     Paste and indent                    :left_right_arrow: `Ctrl + Shift + V`  

#### Bookmarks
`Ctrl + F2`:                    Toggle bookmark  
`F2`:                           Next bookmark  
`Shift + F2`:                   Prev bookmark  
`Ctrl + Shift + F2`:            Clear bookmarks  


### Code

#### Goto
`Ctrl + M`:                     Jump to matching bracket            :hammer:  
`Ctrl + Alt + Left or Right`:   Jump to next/prev place                             ([Emmet](#emmet))  
`Ctrl + Alt + , or .`:          Selects next/prev tag                               ([Emmet](#emmet))  
`Ctrl + G`:                     Go to line  
`Ctrl + R`:                     Go to symbol  
`Ctrl + Shift + R`:             Go to symbol in project             :no_entry_sign:  
`F12`:                          Go to definition                    :warning: *replace with `Ctrl + Alt + Down`?*  
`Alt + -`:                      Jump back  

#### Expand Selection
`Ctrl + Shift + A`:             Expand selection to tag             :hammer:  
`Ctrl + Shift + M`:             Expand selection to bracket         :hammer:  
`Ctrl + Shift + J`:             Expand selection to indentation  
`Ctrl + Shift + Space`:         Expand selection to scope  

#### Indentation
`Ctrl + ] or [`:                Indent or unindent line             :hammer:  
`F12`:                          Indent file                         :warning:  
`Edit > Line > Reindent`  

#### Snippets
`#`:                            Add 'id' property to tag                            ([Emmet](#emmet))  
`.`:                            Add 'class' property to tag                         ([Emmet](#emmet))  

#### Folding
`Ctrl + Shift + [`:             Fold  
`Ctrl + Shift + ]`:             Unfold  
`Ctrl + K, Ctrl J`:             Unfold all  
`Ctrl + K, Ctrl + 1-9`:         Fold levels  

#### Comment
`Ctrl + /`:                     Toggle comment                      :hammer:  
`Ctrl + Shift + /`:             Toggle block comment                :hammer:  

#### Tag
`Alt + .`:                      Close tag  
`Ctrl + Shift + A`:             Expand selection to tag  
`Alt + Shift + W`:              Wrap selection with tag  

#### Hyperlinks
`Ctrl + Alt + U`                Open url, file, folder or search for word   :hammer:  ([Open URL](#open-url))  
`Ctrl + Alt + L`                Wrao word / selection as link                         ([Hyperlink Helper](#hyperlink-helper))  
`Ctrl + Alt + Shift + L`        Lookup with Google & link                             ([Hyperlink Helper](#hyperlink-helper))  


### File Navigation

#### Goto
`Alt + 1-9`:                    Switch file  
`Ctrl + PgUp or PgDn`:          Switch file next or previous  
`Ctrl + Tab`:                   Cycle forward open tabs  
`Ctrl + Shift + Tab`:           Cycle backward open tabs  
`Ctrl + P`:                     Palette of open files  
`Ctrl + 0`:                     Focus on sidebar  
`Esc`:                          Focus back to edit area when focus on sidebar  
`Ctrl + Alt + S`                Reveal in sidebar  

#### Tab groups
`Ctrl + 1-9`:                   Navigate tab groups  
`Ctrl + K, Ctrl + Up`:          Move file to new group  
`Ctrl + K, Ctrl + Down`:        Close group  

##### Origami
`Ctrl + K, Arrow`:             Move focus to the pane in that direction
`Ctrl + K, Shift + Arrow`:     Move the current file to the destination
`Ctrl + K, Alt + Arrow`        Clone the current file to the destination
`Ctrl + K, Ctrl + Arrow`:      Create an adjacent pane
`Ctrl + K, Ctrl + Shift + Arrow`: Destroy an adjacent pane
`Ctrl + K, Ctrl + Z`:          Zoom the current pane so it takes up 90% of the screen
`Ctrl + K, Ctrl + Shift + Z`:  Unzoom (equally space all panes)
`Ctrl + K, Ctrl + R`:          Adjust the top and bottom separator
`Ctrl + K, Ctrl + C`:          Adjust the left and right separator


### Find and Replace
`Ctrl + F`:                     Find  
`Enter or F3`:                  Next find                           :hammer:  
`Shift + Enter or Shift + F3`:  Previous find                       :hammer:  
`Ctrl + E`:                     Use selection for find              :hammer:  

`Ctrl + I`:                     Incremental find  

`Ctrl + H`:                     Find and replace  
`Ctrl + Shift + H`:             Replace next  
`Ctrl + Shift + E`:             Use selection for replace  

`Ctrl + Shift + F`:             Find in files                       :hammer:  
`F4`:                           Next result  
`Shift + F4`:                   Previous result  
> Tip: turn off "Use Buffer" to see results in botton panel  

#### Quick Find
`Ctrl + F3`:                    Quick find                          :hammer:  
`Alt + F3`:                     Quick find all                      :hammer:  
`Ctrl + D`:                     Quick add next                      :hammer:  
`Ctrl + K, Ctrl + D`:           Quick skip next                     :hammer:  
`Ctrl + U`:                     Undo selection                      :hammer:  


### View

#### Font Size
`Ctrl + =`:                     Larger font  
`Ctrl + -`:                     Smaller font  

#### Layout
`Alt + Shift + 1`:              Single  
`Alt + Shift + 2`:              Two columns  
`Alt + Shift + 4`:              Four grid  


### Console
`Ctrl + '`             Show Console

#### Useful commands
Show command actions
`sublime.log_commands(True)` 


### Automation

#### Autocomplete
`Ctrl + Spacebar`:              Auto complete list  
`Tab`:                          Auto complete commit  

#### Snippets
`Ctrl + Shift + P + "snip"`:    Displays available snippets  

#### Macros
`Ctrl + Q`:                     Start/end macro recording  
`Ctrl + Shift + Q`:             Playback macro  


### Utilities
`Ctrl + Shift + C`:             Open system color picker                          ([SideBarEnhacements](#sidebarenhacements))  


### Context Tools

#### PlainTasks
[PlainTasks](#plaintasks)  
`Ctrl + Enter`                  Add new task  
`Ctrl + D`                      Mark task as done (toggle)  
`Ctrl + Shift + A`              Archive task  
`C + Tab`                       Tag task priority as Critical  
`H + Tab`                       Tag task priority as High  
`L + Tab`                       Tag task priority as Low  
`T + Tab`                       Tag task priority as Today  


### Examples

##### Copy/paste text inside html tags, edit and copy/paste back  
* Select tag: `Ctrl + D`
* Move right: `Ctrl + Right`
* Expand tag selection: `Ctrl + Shift + A`
* Copy: `Ctrl + C`
* New file: `Ctrl + N`
* Paste: `Ctrl + V`
* Edit text
* Copy all: `Ctrl + A`
* Break selection into lines: `Ctrl + Shift + L`
* Copy multiple selection: `Ctrl + C`
* Go back to prev file:  
* Paste into selection: `Ctrl + V`


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
* [SublimeCodeIntel](https://sublimecodeintel.github.io/)
* [Word Count](https://github.com/titoBouzout/WordCount)


## Missing Key Bindings
* `File > New View Into File`
* `Edit > Line > Reindent`
* `Edit > Convert Case > Title Case`
* `Selection > Expand Selection to Paragraph`


## Conflicting Key Bindings
* `F12`:
  * `Goto > Goto definition...`
  * `Edit > Line > Reindent`
* `Ctrl + Shift + /`
  * `Edit > Comment > Toggle Block Comment `
  *  `Emmet Package > Toggle comment tag scope`


## Modified Key Bindings
* `Edit > Paste`: `Ctrl + V` → `Ctrl + Shift + V`
* `Edit > Paste and Indent`: `Ctrl + Shift + V` → `Ctrl + V`


## Legend
| Emoji              | Description                                    |
|--------------------|------------------------------------------------|
| :warning:          | Conflict (fix in `Preferences > Key Bindings`) |
| :hammer:           | Drill                                          |
| :left_right_arrow: | Modified                                       |
| :no_entry_sign:    | Not working                                    |


## References
* https://www.linkedin.com/learning/learning-sublime-text-3
* https://gist.github.com/mrliptontea/4c793ebdf72ed145bcbf
