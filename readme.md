# Dotfiles

My personal dotfiles managed using [GNU Stow](https://www.gnu.org/software/stow/).

## Structure

Each config is organized in its own directory. Stow will symlink them into the appropriate location in your home directory.


## Usage

Clone the repo:

```sh
git clone https://github.com/yourusername/dotfiles.git
cd dotfiles
```

```sh
stow gitconfig
stow nvim
stow tmux
```



