# tfp

A small terminal utility for quickly finding and opening projects using `fzf`.

## Dependencies

`tfp` requires [`fzf`](https://github.com/junegunn/fzf).

On Fedora:

```bash
sudo dnf install fzf
```

Verify that `fzf` is available:

```bash
command -v fzf
```

## Installation

Install `tfp` to `~/.local/bin`:

```bash
mkdir -p ~/.local/bin
install -m 755 tfp ~/.local/bin/tfp
```

Make sure `~/.local/bin` is in your `PATH`:

```bash
export PATH="$HOME/.local/bin:$PATH"
```

To make this permanent, add the following line to your shell configuration file:

```bash
export PATH="$HOME/.local/bin:$PATH"
```

For Bash, add it to `~/.bashrc`. For Zsh, add it to `~/.zshrc`.

## Usage

Run:

```bash
tfp
```

Use `fzf` to find and select the project you want to open.
