# TMUX Commands


### Useful Commands
* Show Keyboard Shortcuts : `Prefix -> ?` and Search `CTRL + s`
* List Commands : `tmux list-commands` `tmux lscm`
* Show Messages : `Prefix -> ~`


### Session Related Commands
* List Sessions : `tmux list-sessions` `tmux ls`
* Create a new Session : `tmux new-session` `tmux new`
* Create a new Session with name `tmux new-session -s NAME`
* Rename Session : `tmux rename-session NAME`
* Attach Session : `tmux attach-session -t NAME`
* Detach Session : `Prefix -> d`

* Choose Session Interface : `Prefix -> s`
* Move to Next Session : `Prefix -> )`
* Move to Previous Session : `Prefix ->(`


### Window Related Commands
* Create a new Window : `Prefix -> c`
* Rename the current Window : `Prefix -> ,`
* Kill the current Window : `Prefix -> &`

* Choose Window Interface : `Prefix -> w`
* Move to Previous Window : `Prefix -> p`
* Move to Next Window : `Prefix -> n`
* Move to Last window : `Prefix -> l`
* Move to Window using number : `Prefix -> NUMBER` 

* Find Window Prompt : `Prefix -> f`


### Pane Related Commands
* Show Pane index number : `Prefix -> q` -> Press Number to move to the pane
* Split the window Vertically : `Prefix -> %`
* Split the window Horizontally : `Prefix -> "`
* Move to Other Panes : `Prefix -> o`
* Kill the current Pane : `Prefix -> x`
* Zoom in/out the Pane : `Prefix -> z`
* Resize Pane : `Prefix -> Meta + Arrow keys`
* Change Panes Layout : `Prefix -> SPACE BAR`

### Show Options
* View Global Options : `tmux show-options -g`
* View Window Options : `tmux show-options -w`
* View Server Options : `tmux show-options -s`


## TMUX Configurations
* Set Option : `tmux set-option OPTION PARAMS` `Prefix -> :set-option OPTION PARAMS`
* Configuration file : `~/.tmux.conf`
* Reload Configuration file : `tmux source-file ~/.tmux.conf`