# zig.vim

File detection and syntax highlighting for the
[zig](http://ziglang.org/) programming language.

## Installation

 * Use Vim 8 or newer
 * `mkdir -p ~/.vim/pack/plugins/start/`
 * `cd ~/.vim/pack/plugins/start/`
 * `git clone https://github.com/ziglang/zig.vim`

## Configuration

Automatic formatting on save is enabled by default. To disable this, add the
following to your vimrc:

```
let g:zig_fmt_autosave = 0
```
