# LaTeX Snippets

This repository holds a personal collection of snippets I use to when writing LaTeX documents with Neovim.

## Prerequisites

- Install and setup [Vimtex](https://github.com/lervag/vimtex) (the LaTeX plugin)
- Install and setup [LuaSnip](https://github.com/L3MON4D3/LuaSnip) (the snippet engine)

## Setup

Assuming the prerequisites have been met, all that's needed now is a `snippets/` folder within your Neovim configuration path and some snippets.

```sh
# create snippets folder
mkdir ~/.config/nvim/snippets
```

And copy the `./tex.snippets` file to the `snippets/` folder that was just made. Now, the snippets are ready to be used in your LaTeX documents.