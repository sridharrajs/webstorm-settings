# Webstorm-settings

A repo for my [WebStorm](https://www.jetbrains.com/webstorm/) settings

For Templates, check [Template](https://github.com/sridharrajs/webstorm-settings/blob/master/Template.md)

### Command-line launcher

At times, you might want to launch webstorm on the current folder. To do so, configure commandline launcher.

> Tools -> Create Command-line Launcher

and add an `alias` in `.bashrc`

**.bashrc**

    # ws = webstorm
    alias ws='/usr/local/bin/webstorm'

From now, you can open any project directory by `ws .` in it.


### Navigation

|Description| Command |
|-----------|---------| 
|Open to the file| `Ctrl/Command` + `P`|
|File in files| `Ctrl/Command` + `Shift` + `F`|
|Toggle to breadcrumb| `Ctrl/Command` + `UP`|
|Go to specific line| `Ctrl/Command` + `L`|
|Go to Next tab|`Ctrl/Command` + `Alt/Option` + `Right`|
|Go to Previous tab|`Ctrl/Command` + `Alt/Option` + `Left`|
|Go to Next splitter tab|`Ctrl/Command` + `Alt/Option` + `Shift` + `Right`|
|Go to Previous splitter tab|`Ctrl/Command` + `Alt/Option` + `Shift` + `Left`|
|Collapse region| `Command` + `-`|
|Collapse all region| `Shift` + `Command` + `-`|
|Expand region| `Command` + `+`|
|Expand all region| `Shift` + `Command` + `+`|

### Find

|Description| Command |
|-----------|---------| 
|Find in folder|`Ctrl/Command` + `Shift` + `F`|

### Refactoring
|Description| Command |
|-----------|---------| 
|Refactor name/variables| `Shift` + `F6`|
|Copy file| `F5`|
|Move file| `F6`|

### Window
|Description| Command |
|-----------|---------| 
|Split Vertically| `Alt/Option` + `x`|
|Split Horizontally| `Alt/Option` + `h`|
|Unsplit All| `Ctrl/Command` + `O`|
|Close everything except current file| `Alt/Option` + `W`|
|Close the current panel|`Ctrl/Command` + `W`|
|Toggle sidebar|`Ctrl/Command` + `1`|
|Toggle Terminal|`Alt/Option` + `F12`|

### Selection/Cut/Copy/Paste

|Description| Command |
|-----------|---------| 
|Find and replace|`Ctrl/Command` + `R`|
|Duplicate line|`Ctrl/Command` + `D`|
|Recursive selection|`Alt/Option` + `up`|
|Clone Carot above|`Ctrl/Command` + `Alt/option` + `UP`|
|Clone Carot below|`Ctrl/Command` + `Alt/option` + `DOWN`|

### Refactoring

|Description| Command |
|-----------|---------| 
|Refactoring to a variable|`Shift` + `F6`|

### LICENSE

MIT
