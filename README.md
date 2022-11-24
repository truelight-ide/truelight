TrueLight is a zero config, IDE-like neovim distribution

### Features
- Zero config: TrueLight is feature-rich out of the box
- IDE-like experience

### Installation

TODO: provide a much better installation experience

#### Install fzf

```sh
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

#### Install truelight
For Unix/Linux:

```sh
git clone --depth=1 https://github.com/truelight-ide/truelight.git \
    "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/pack/truelight
```

For Windows:

```
git clone https://github.com/truelight-ide/truelight.git "$env:LOCALAPPDATA\nvim-data\site\pack\truelight"
```

Then add this line to your `init.lua`:

```
require('truelight')
```

### Roadmap
[Roadmap](https://github.com/orgs/truelight-ide/projects/1)

### Special thanks

truelight depends on following awesome projects:
- [savq/paq-nvim](https://github.com/savq/paq-nvim) for package management
- [neovi/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) for lsp configuration
- [gpanders/editorconfig.nvim](https://github.com/gpanders/editorconfig.nvim) for editorconfig support
- [ibhagwan/fzf-lua](https://github.com/ibhagwan/fzf-lua) for fzf integration
- [lunarvim/Onedarker.nvim](https://github.com/lunarvim/Onedarker.nvim) for onedarker colorscheme
