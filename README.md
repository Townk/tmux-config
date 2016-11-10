# tmux-config #

Welcome to my full tmux configuration!

## Target audience ##

Anyone can use and modify my configurations in any way needed. I would only
suggest that you 1) give me credit for something interesting you find here and
2) share your changes so other could benefit from it.

That being said I would like to point out that I work as a software engineer so
most of my configurations are target for that kind of work.

## Installation ##

You can use this in any way you prefer but I would like to show you how I use
it in my machines.

1. Clone this project on any directory;
2. Link the `tmux.conf` file to your home directory with a `.` prepended;
3. Link the directory `tmux` to your home directory with a `.` prepended;

Like this:

```sh
    $ mkdir -p ~/Projects/tmux
    $ cd ~/Projects/tmux
    $ git clone https://github.com/Townk/tmux-config.git
    $ ln -sf ~/Projects/tmux/tmux-config/tmux.config ~/.tmux.config
    $ ln -sf ~/Projects/tmux/tmux-config/tmux ~/.tmux
```

**Note:** I only tested these configurations on macOS, so use at your own risk.

