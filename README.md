tube-vim
============
```
 _         _                     _
| |_ _   _| |__   ___     __   _(_)_ __ ___
| __| | | | '_ \ / _ \____\ \ / / | '_ ` _ \
| |_| |_| | |_) |  __/_____\ V /| | | | | | |
 \__|\__,_|_.__/ \___|      \_/ |_|_| |_| |_|

```

**tube-vim** is a integrated command line environment that mainly designed for OS X. You can install it by **running a single command**:
```
bash <(curl -L https://raw.githubusercontent.com/tolinwei/tube-vim/master/install.sh)
```
**tube-vim** includes best practical Vim settings, bunch of Vim plugins managed by **[junegunn/vim-plug](https://github.com/junegunn/vim-plug)**, and decent color scheme **[gruvbox](https://github.com/morhetz/gruvbox)** ([gruvbox-terminal](https://github.com/flipxfx/gruvbox-terminal) & [gruvbox-generalized](https://github.com/morhetz/gruvbox-generalized) for Terminal & iTerm2).

**tube-vim** also installs Z shell `zsh`'s wrapper **oh-my-zsh** ([Github](https://github.com/robbyrussell/oh-my-zsh) | [Official size](http://ohmyz.sh/)) as the replacement of most system's default `bash`. You can switch to it easily due to its full compatibility with `bash`.

As a supplement, **[tmux](http://tmux.github.io/)**, which is a terminal multiplexer, will be installed to accerate your operation (OS X only). If you feel `screen` better than `tmux`, a configuration for the former one is also provided to help you manage the sessions.

<a href="https://github.com/tolinwei/tube-vim/wiki/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3" target="_blank">
简体中文文档正在编辑中</a>

## Preview
<img src="https://raw.githubusercontent.com/tolinwei/dev-config/master/preview/gruvbox-java.png" width="800">
<img src="https://raw.githubusercontent.com/tolinwei/dev-config/master/preview/gruvbox-vimrc.png" width="800">


## Installation

### For OS X
1. (Optional) Install **[iTerm2](https://iterm2.com/index.html)** ([direct link](https://iterm2.com/downloads/stable/iTerm2_v2_0.zip)) as Terminal replacement, check out more features [here](https://iterm2.com/features.html)

2. Run the following command to install **tube-vim**
     ```
     bash <(curl -L https://raw.githubusercontent.com/tolinwei/tube-vim/master/install.sh)
     ```
3. Change the color scheme in **Preferences...&nbsp;&nbsp;&nbsp;&nbsp;⌘,** of **iTerm2** or **Terminal** depends on which one you're using.
     + <a href="https://github.com/tolinwei/tube-vim/wiki/How-to-change-color-scheme-for-iTerm2-&-Terminal.app" target="_blank">
How to change color scheme for iTerm2 & Terminal.app</a>

4. Modified the following lines in your `~/.bashrc` to correct git commits info if you're using `git` and have no existing `~/.bashrc` before installation
     ```
     git config --global user.name "<put-your-name-here>"
     git config --global user.email "<put-your-email-here>"
     ```

### For Linux

**tube-vim** provides a simplified<sup>*</sup> version for server side Linux, as it's always anoying to develop on a bare remote machine. Makie sure you have `git`, `wget` and Vim >= 7.4 installed (7.2 might have issue with [NERDTree](https://github.com/scrooloose/nerdtree)), then run the following command to set it up:
```
bash <(wget -O - https://raw.githubusercontent.com/tolinwei/tube-vim/master/install-linux.sh --no-check-certificate)
```

## Usage Guide

### Vim

- Type `vimtutor` in your shell emulator like **Terminal** or **iTerm2** to open the most rudimental yet intuitive tutorial of Vim
- [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)
- [Learn Vimscript the hard way](http://learnvimscriptthehardway.stevelosh.com/)
- [Practical Vim - Edit Text at the Speed of Though](http://media.pragprog.com/titles/dnvim/toc.pdf)

### [Vim Plugins and Usage Guide](https://github.com/tolinwei/tube-vim/wiki/Vim-Plugins-and-Usage-Guide)

###tmux

- [A tmux Crash Course](https://robots.thoughtbot.com/a-tmux-crash-course)
- [A tmux Primer](https://danielmiessler.com/study/tmux/)
- [tmux: Productive Mouse-Free Development](http://uploads.mitechie.com/books/tmux_p1_1.pdf)


## License

Copyright © [Wei Lin](http://www.linkedin.com/in/tolinwei). Distributed under the same terms as Vim itself. See `:help license`.

