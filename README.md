# tmux config

### Introduction

My own tmux config

### Installation

Tmux's configurations are located under the following paths, depending on your OS:

| OS | PATH |
| :- | :--- |
| Linux | `$XDG_CONFIG_HOME/tmux`, `~/.config/tmux` |
| MacOS | `$XDG_CONFIG_HOME/tmux`, `~/.config/tmux` |

Clone tpm:
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Clone config.tmux:

```sh
# on Linux and Mac
git clone https://github.com/linchengweiii/config.tmux.git "${XDG_CONFIG_HOME:-$HOME/.config}"/tmux
```

### Post Installation

Installing the plugins

Press `prefix` + <kbd>I</kbd> (capital i, as in Install) to fetch the plugin.

You're good to go! The plugin was cloned to ~/.tmux/plugins/ dir and sourced.

