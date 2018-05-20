1.Fork this repo

2.Pull and link your fork:

```
  git clone https://github.com/vlasikhin/.vim.git
```
3.`cd .vim`

4.`cp .vimrc ~/`

5.Download [vim-plug](https://github.com/junegunn/vim-plug)

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

6.Launch VIM (vim), ignore errors and call `:PlugUpgrade` (upgrades Plug manager to the latest version) and `:PlugUpdate` (updates/installs all the Plug-referenced plugins) commands. Plugins will be loaded on the next run.
It might be a good idea to run those commands once in a while to keep your tools up-to-date
