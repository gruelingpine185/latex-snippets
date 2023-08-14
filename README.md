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

And copy the `tex.snippets` file to the `snippets/` folder that was just made. Now, the snippets are ready to be used in your LaTeX documents.

```sh
# copy snippets to snippets/ folder
curl -o ~/.config/nvim/snippets/tex.snippets https://github.com/gruelingpine185/latex-snippets/main/tex.snippets?raw=true
```

## Snippets

### Structure

| Snippet | Description |
| ------- | ----------- |
| bd | Create begin/end document |
| beg | Create custom begin/end environment |
| dc | Create documentclass |
| dca | Create documentclass with article type |

### Includes

| Snippet | Description |
| ------- | ----------- |
| use | Use package |
| Use | Use package with options |

## Contributions

As mentioned, this repo holds personal snippets, however, if I find use with suggested snippets, I'll be sure to add them. With that aside, if bugs or typos are encountered, feel free to make an issue or fix it with a Pull Request.
