# My dotfiles

This is where I keep my configuration files for bash, git, vim, tmux and so on.
Before running any command though, make sure you've installed *iTerm2*, *Vim*, *git*
and *tmux*. Optionally, you should also update the default (oldish)
*bash*.

To install my *dotfiles*:

    make dotfiles

To configure *vim*:

    make vim

To install my *UltiSnippets snippets* for Vim:

    make snippets

**Note:** This will checkout my snippets repo using SSH. I need this, in case I may
create more snippets.

To update *tmux adio colors*:

    make tmux-colors

To import *iTerm2 adio preset*:

    make iterm-colors

**Note:** After this, you have to manually load the adio preset from iTerm2's Preferences.

To do all of the above:

    make



