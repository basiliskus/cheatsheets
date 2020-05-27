# Sublime Text 3 Cheatsheet 

## Key Bindings

### Files
`Ctrl + O`:                     Open new file  
`Ctrl + N`:                     New file  
`Ctrl + S`:                     Save file  
`Ctrl + W`:                     Close current file                  :hammer:  
`Ctrl + Shift + T`:             Reopen closed file                  :hammer:


### Navigate
`Alt + 1-9`:                    Switch file  
`Ctrl + PgUp or PgDn`:          Switch file next or previous  
`Ctrl + Tab`:                   Cycle forward open tabs  
`Ctrl + Shift + Tab`:           Cycle backward open tabs  
`Ctrl + P`:                     Palette of open files  


### Indentation
`Ctrl + ] or [`:                Indent or unindent line             :hammer:  
`F12`:                          Indent file                         :warning:  
`Edit > Line > Reindent`


### Line editing
`Ctrl + Shift + Up`:            Swap line up  
`Ctrl + Shift + Down`:          Swap line down  
`Ctrl + Shift + K`:             Delete line  
`Ctrl + Shift + D`:             Duplicate line  


### Code editing
`Ctrl + M`:                     Jump to matching bracket            :hammer:  

#### Comment
`Ctrl + /`:                     Toggle comment                      :hammer:  
`Ctrl + Shift + /`:             Toggle block comment                :hammer:  

#### Tag
`Alt + .`:                      Close tag  
`Ctrl + Shift + A`:             Expand selection to tag  
`Alt + Shift + W`:              Wrap selection with tag  

#### Code Folding
`Ctrl + Shift + [`:             Fold  
`Ctrl + Shift + ]`:             Unfold  
`Ctrl + K, Ctrl + 1-9`:         Fold levels  

#### Convert Case
`Ctrl + K, Ctrl + U`:           Upper case  
`Ctrl + K, Ctrl + L`:           Lower case  
`Edit > Convert Case > Title Case`: 

#### Clipboard
`Ctrl + Shift + V`:             Paste                               :left_right_arrow: `Ctrl + V`  
`Ctrl + V`:                     Paste and indent                    :left_right_arrow: `Ctrl + Shift + V`  


### Layout

#### Tab groups
`Alt + Shift + 1`:              Single  
`Alt + Shift + 2`:              Two columns  
`Alt + Shift + 4`:              Four grid  
`Ctrl + 1-9`:                   Navigate tab groups  
`Ctrl + K, Ctrl + Up`:          Move file to new group  
`Ctrl + K, Ctrl + Down`:        Close group  
`File > New view into file`: 


### Project
`Ctrl + Alt + P`:               Quick switch project  


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

`Ctrl + F3`:                    Quick find                          :hammer:  


### Preferences
`Ctrl + =`:                     Larger font  
`Ctrl + -`:                     Smaller font  


### Power Editing
`Ctrl + Left or Right`:         Move one word at a time  
`Ctrl + Shift + Left or Right`: Select one word at a time  

`Ctrl + D`:                     Select current word                 :hammer:  
`Ctrl + L`:                     Select current line                 :hammer:  
`Selection > Expand Selection to Paragraph`: 

`Ctrl + Shift + A`:             Expand selection to tag             :hammer:  
`Ctrl + Shift + M`:             Expand selection to bracket         :hammer:  
`Ctrl + Shift + J`:             Expand selection to indentation  
`Ctrl + Shift + Space`:         Expand selection to scope  

#### Bookmarks
`Ctrl + F2`:                    Toggle bookmark  
`F2`:                           Next bookmark  
`Shift + F2`:                   Prev bookmark  
`Ctrl + Shift + F2`:            Clear bookmarks  

#### Go to anything
`Ctrl + P`:                     Go to anything                      :hammer:  
  `#`:                          Fuzzy search  
  `:`:                          Line number  
  `@`:                          Symbol  

#### Symbol Browsing
`Ctrl + R`:                     Go to symbol  
`Ctrl + Shift + R`:             Go to symbol in project             :no_entry_sign:  
`F12`:                          Go to definition                    :warning: *replace with `Ctrl + Alt + Down`?*  
`Alt + -`:                      Jump back  

#### Command
`Ctrl + Shift + P`:             Command palette                     :hammer:  
* Access commands quickly  
* Quick way to learn key bindings for commands  
* Switch sintax mode  

#### Multiple selection
`Ctrl + Click`:                 Add additional cursors  
`Ctrl + Alt + Up`:              Add previous line  
`Ctrl + Alt + Down`:            Add next line  
`Shift + R-Click Drag`:         Vertical select  
`Ctrl + Shift + L`:             Split into lines  
> Tip: first select multiple lines and then use  

`Alt + F3`:                     Quick find all                      :hammer:  
`Ctrl + D`:                     Quick add next                      :hammer:  
`Ctrl + K, Ctrl + D`:           Quick skip next                     :hammer:  
`Ctrl + U`:                     Undo selection                      :hammer:  

##### Use case  
* Select tag: `Ctrl + D`: 
* Move right: `Ctrl + Right`: 
* Expand tag selection: `Ctrl + Shift + A`: 
* Copy: `Ctrl + C`: 
* New file: `Ctrl + N`: 
* Paste: `Ctrl + V`: 
* Edit text  
* Copy all: `Ctrl + A`: 
* Break selection into lines: `Ctrl + Shift + L`: 
* Copy multiple selection: `Ctrl + C`: 
* Go back to prev file:  
* Paste into selection: `Ctrl + V`: 


### Automation

#### Autocomplete
`Ctrl + Spacebar`:              Auto complete list  
`Tab`:                          Auto complete commit  

#### Snippets
`Ctrl + Shift + P + "snip"`:    Displays available snippets  

#### Macros
`Ctrl + Q`:                     Start/end macro recording  
`Ctrl + Shift + Q`:             Playback macro  


### Essential Packages

#### ColorPicker
`Ctrl + Shift + C`:             Open system color picker  

#### SideBarEnhacements
* Open in browser (add key?)  

#### HyperlinkHelper
* Create html link retrieved link meta info from google  

#### Emmet
Abbreviation that expands into full html code  
`Ctrl + Alt + Left or Right`:   Jump to next/prev place  
`Ctrl + Alt + , or .`:          Selects next/prev tag  
`Ctrl + Shift + /`:             Toggle comment tag scope  
`#`:                            Add 'id' property to tag  
`.`:                            Add 'class' property to tag  

#### Other Packages to Check
* SublimeCodeIntel  


## Missing Key Bindings
* `Edit > Line > Reindent`
* `Edit > Convert Case > Title Case`
* `Selection > Expand Selection to Paragraph`


## Conflicting Key Bindings
* `F12`:
  * `Goto > Goto definition...`
  * `Edit > Line > Reindent`


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
