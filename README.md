# Barcelona for iTerm2 and ZSH
*Barcelona* is my personal color theme for ZSH, based on a fork of [Cobalt2](https://github.com/wesbos/Cobalt2-iterm) leveraging [Agnoster](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/agnoster.zsh-theme) as the foundation for the prompt layout of ZSH and [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh).

This theme is intended for my personal use only and therefore is an ongoing work-in-progress provided *as is*.

<img width="969" alt="Screenshot" src="https://cloud.githubusercontent.com/assets/1104146/9185601/7d40ff7c-3fbd-11e5-9144-f027f9d2f456.png">

## Installation

##### 1. Copy `barcelona.zsh-theme` into the `~/.oh-my-zsh/themes`

```shell
$ cp ./barcelona.zsh-theme ~/.oh-my-zsh/themes/
```
##### 2. Open up your ZSH preferences at `~/.zshrc` and change the theme variable to `ZSH_THEME="barcelona"`.

```shell
# Set name of the theme to load.
# Look in ~/.oh-my-zsh/themes/
# Optionally, if you set this to "random", it'll load a random theme each
# time that oh-my-zsh is loaded.
ZSH_THEME="barcelona"
```
##### 3. Should the Powerline Fonts are available already on your system please skip this step. Otherwise, download and install the [Powerline Fonts from its repo](https://github.com/powerline/fonts).

```bash
$ cd ..
$ git clone https://github.com/powerline/fonts.git powerline-fonts
$ cd powerline-fonts
$ ./install.sh
```
##### 4. In iTerm2 access the Preferences pane on the Profiles tab.
Under the Colors tab import the barcelona.itermcolors file via the *Load Presets* drop-down. Click then on the Text tab and change the font for each type (Regular and Non-ASCII) to '**Inconsolata for Powerline**' in order to properly display icons in your prompt.
##### 5. Type the following statement on the command line in order to refresh ZSH.

```bash
$ source ~/.zshrc
```

## ISC License

Copyright (c) 2015, Pablo Deeleman <deeleman@gmail.com>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
