# theme

Dracula.

docs: [Vim • Dracula Theme](https://draculatheme.com/vim)


# Install

1. 将本仓库中的 vim/ 目录（包含 .vimrc、.vim-plugin-config 等）复制到新电脑的 ~/.vim/ 或 ~/.config/nvim/（若用 Neovim）。

2. 安装 Vim 及插件管理器

	- 安装 Vim 8+ 或 Neovim。

	- 安装 vim-plug（本配置使用）：

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

3. 安装插件

启动 Vim，执行：

```text
:PlugInstall
```

等待所有插件下载完成。

4. 安装外部依赖

coc.nvim 需要 Node.js：参考 https://nodejs.org/en/download/

然后在 Vim 内执行 :CocInstall coc-json coc-clangd (sudo apt install clangd) 等按需安装语言服务。


# Vim 9

Some plugin need Vim 9.

see: https://zhuanlan.zhihu.com/p/550341865

