## Installation
Using homebrew to install tmux:
```
$ brew install tmux
```

Confirm installation by running:
```
$ tmux
```
This should create a tmux session.

## Custom Config:
create the `.tmux.conf` file:
```
$ touch ~/.tmux.conf
```

copy the `.tmux.conf` file from github into this file

install [tpm](https://github.com/tmux-plugins/tpm) - This is a package manager for tmux:
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

source the chagnes:
```
$ tmux source ~/.tmux.conf
```







