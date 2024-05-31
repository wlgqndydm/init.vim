# init.vim
a useful neovim config
一个好用的neovim 配置文件，拿来改改，加点料。

安装方法：

1.克隆此项目：

git clone --depth 1 https://github.com/wlgqndydm/init.vim.git ~/.config/nvim

2.安装packer：
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim

3.安装支持库，必须安装nodejs，且必须安装，先执行：
ubuntu:apt install nodejs

然后执行：
npm install -g pyright

如使用python，则执行：(可能无法发挥作用)
pip install pynvim 

    3.1个别发行版可能需使用包管理器安装：
    
    如opensusu，需使用zypper安装 python311-neovim，
    如termux，则需要运行：apt install python-nvim，
    否则可能出现找不到包或msgpack和greenlet库编译错误
 

4.安装lsp：
python:pip install pyright
