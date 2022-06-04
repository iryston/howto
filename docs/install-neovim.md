# Install Neovim

## macOS / OS X

### Pre-built archives

The [Releases](https://github.com/neovim/neovim/releases) page provides pre-built binaries for macOS 10.11+.

```bash
curl -LO https://github.com/neovim/neovim/releases/download/stable/nvim-macos.tar.gz
tar xzf nvim-macos.tar.gz
./nvim-osx64/bin/nvim
```

### [Homebrew](https://brew.sh) on macOS or Linux

```bash
brew install neovim
```

Or install the development version of Nvim:

```bash
brew install --HEAD neovim
```

To update the development version of Nvim:

```bash
brew reinstall neovim
```

### Python support

Python (:python) support is installable via the pip

```bash
python3 -m pip install --user --upgrade pynvim
```
