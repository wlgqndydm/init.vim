# init.vim
a useful neovim config
一个好用的neovim 配置文件，拿来改改，加点料。
安装方法：
1.克隆此项目

git clone --depth 1 https://github.com/Nalleyer/init.vim.git ~/.config/nvim

2.安装packer：

git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim

3.安装支持库，如使用python，则执行：(个别发行版可能需使用包管理器安装，如opensusu需使用zypper安装 python311-neovim )

pip install pynvim 

4.安装lsp：

python:pip install pyright
