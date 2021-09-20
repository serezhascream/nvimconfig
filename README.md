# Neovim configs
My configuration files for neovim

## To set up configuration

1. Clone repo as bare repo

```bash
git clone --bare git@github.com:serezhascream/nvimconfig.git .nvimconfig
```

2. Create alias for managing nvim configuration

```bash
alias nconf="/usr/bin/git --git-dir=$HOME/.nvimconfig --git-tree=$HOME/%path-to-configuration%"
```

Here, %path-to-configuration% is where neovim configuration should store.

3. Install Vundle and install plugins with :PluginInstall in nvim
