TrueLight is a zero config, IDE-like neovim distribution

### Features
- Zero config: TrueLight is feature-rich out of the box
- IDE-like experience

### Installation

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
