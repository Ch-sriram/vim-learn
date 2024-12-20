# Vim &mdash; My Learning & Resources <!-- omit in toc -->

- This repository contains my learnings and material from a Udemy course taught by [Jason Cannon](https://www.linkedin.com/in/jasonacannon/). The course can be found [here](https://www.udemy.com/course/vim-commands-cheat-sheet/).

## Table of Contents <!-- omit in toc -->

- [About `vim`](#about-vim)
- [Why use `vim`?](#why-use-vim)
- [Main Modes in `vim`](#main-modes-in-vim)
- [Creating a file \& editing using `vim`](#creating-a-file--editing-using-vim)

### About `vim`

- `vim` is an advanced text editor.
- `vim` = `vi` + `im`proved
- `vi` is short for *visual*
- In most modern systems, `vim` has replaced `vi`.

### Why use `vim`?

- Ubiquitous &mdash; installed in almost all of the systems, if not `vim`, at least `vi` exists.
- Extremely Powerful &mdash; `vim` is even more powerful than `nano`.
- Transferable Skills &mdash; most of the editors support `vim`-mode like Atom, Sublime Text, XCode, Notepad++, VSCode, etc.
- Cross-Platform &mdash; `vim` is available in Windows, macOS, and in all Linux Distros.
- `vim` is also available in a TUI / GUI mode where we can use `vim` with a mouse.
- Syntax Highlighting &mdash; by default, `vim` includes syntax highlighting for most popular languages and script. For unknown/new languages, `vim` plugins can be installed to enable the syntax highlighting.
- Commands are mneumonic based &mdash; `i` (insert), `d` (delete), `q` (quit), and `w` (write).
- `vim` is like a language: (`Action-Adjective-Object`, thinking in English, and abbreviating it is a `vim` command, is the actual action)
  - To "*delete 3 words*" -> `d3w` (after coming out of `insert` mode)
    - Action -> Delete, Adjective -> 3, Object -> Words
  - To *delete a word* -> `dw`
  - To *change the text of a word* -> `cw`
  - To *delete everything inside a quotation mark (')* -> `di'` (means: **delete inside quotation mark '**)

[:top:](#table-of-contents)

### Main Modes in `vim`

- Normal/Command Mode `Esc`
- Insert Mode `i`
- Line/CommandLine Mode (`:`)

[:top:](#table-of-contents)

### Creating a file & editing using `vim`

- Create a file using `vim`

  ```sh
  vim abc123
  ```

  `vim` will open in normal mode.

- Go to insert mode by pressing the `i` key, and type in some text.
- Go to normal mode by pressing the `Esc` key.
- Go to line mode by pressing the `:` key, and to save and quit the from `vim`, type in `wq`.
  - full command is: `:wq` (to force-quite, use a bang at the end `!`, then the command will be `:wq!`)
