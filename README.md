# ilhamjaya08's nvim-config

This neovim configuration using template from [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

### For Windows (PowerShell) 

#### First, make a backup of your current nvim and shared folder

```pwsh
Rename-Item -Path $env:LOCALAPPDATA\nvim -NewName $env:LOCALAPPDATA\nvim.bak
Rename-Item -Path $env:LOCALAPPDATA\nvim-data -NewName $env:LOCALAPPDATA\nvim-data.bak
```
#### Next, Clone the repository

```pwsh
git clone --depth 1 https://github.com/ilhamjaya08/nvim-config $env:LOCALAPPDATA\nvim
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
nvim
```

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Next, Clone the repository

```shell
git clone --depth 1 https://github.com/ilhamjaya08/nvim-config ~/.config/nvim
rm -rf ~/.config/nvim/.git
nvim
```

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
