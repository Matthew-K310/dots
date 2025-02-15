# dots

This is my configuration for all the utilities that I use every day on my Mac.

Requirements

- Git
- Homebrew 

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

- Yazi file manager

```brew install yazi ffmpeg sevenzip jq poppler fd ripgrep fzf zoxide imagemagick font-symbols-only-nerd-font```

- Neovim

```brew install neovim```

- Tmux

```brew install tmux```

Some of the packages built in to the config include:

- zoxide - easier cd
- fzf - fuzzily find files
- oil.nvim - text buffer style file browser
- yazi.nvim - the best file browser
- harpoon.nvim - quickly jump between saved files
- telescope.nvim - search for files
- obsidian.nvim (disabled by default due to machine specific file paths) - integrates with Obsidian.md
- alpha.nvim - the coolest homescreen ever
