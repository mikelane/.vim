# .vim

Get an awesomeized vim setup with minimal fuss!

### Installation

1. The first step you'll need to do is to upgrade to vim version 8. On a Mac (and linux systems with linuxbrew installed), this is as easy as using brew to install or update vim. For other systems, google is your friend here.
2. Once you get vim 8 installed, you'll need to clone this repo from your root directory recursively to get the submodules.

```bash
git clone --recurse-submodules -j8 git@github.com:mikelane/.vim.git
```

3. You might have to restart your terminal. But once you do, you'll have vim all set up with some great plugins and an excellent vimrc.

### Adding plugins

1. Find the github clone of the plugin that you want to add. I recommend checking out https://vimawesome.com/ for plugins.
2. Change into your `.vim` directory. On Mac/*nix:

```bash
cd ~/.vim
```

3. Add the submodule

```bash
git submodule add https://github.com/<name>/<plugin-name> pack/plugins/start/<plugin-name>
```

### Updating plugins

1. Change into your `.vim` directory.
2. Update the submodules:

```bash
git submodule update --remote --rebase
```

### More information

- https://shapeshed.com/vim-packages/
- https://git-scm.com/book/en/v2/Git-Tools-Submodules

