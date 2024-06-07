# TMUX cheatsheet

~~Default leader key: `C-b`~~

Leader key: `C-s`

List key bindings: `Leader ?`

Command mode: `Leader :`

Install plugins: `Leader I`

## Sessions
List sessions: `tmux ls`

Attach session: `tmux attach`

Dettach session: `Leader d`

Switch session: `Leader s`

Rename session: `Command mode: rename-session <new-name>`

New session: `tumx new -s <session-name>` or `Command mode: new`

## Windows
New window: `Leader c`

Goto next window: `Leader n`

Goto previous window: `Leader p`

Goto n window: `Leader <n>`

Rename window: `Command mode: rename-window <new-name>`

## Panes
New horizontal pane: `Leader %`

New vertical pane: `Leader "`

Navigate between panes: ~~`Leader <up>, <down>, <left>, <right>`~~ or `C-h, C-j, C-k, C-l`

Goto pane: `Leader q`

Swap panes: `Leader {` or `Leader }`

Zoom pane: `Leader z`

Zoom out pane: `Command mode: resize-pane -Z`

Pane to window: `Leader !`

Kill pane: `Leader x`
