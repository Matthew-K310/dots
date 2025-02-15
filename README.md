# dots

This is my configuration for all the utilities that I use every day on my Mac.

## The .zshrc file must be in the root directory and your shell must be zsh for Homebrew, Oh My Posh, and other plugins to work!

To set zsh as default shell:
```chsh -s $(which zsh)```

Restart your terminal for the changes to take effect

[!note] All config folders must be in the .config directory of the machine

Requirements

- Git
- Homebrew 

Install Homebrew:
```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

- Yazi file manager

Config location: ~/.config/yazi

Install Yazi:
```brew install yazi ffmpeg sevenzip jq poppler fd ripgrep fzf zoxide imagemagick font-symbols-only-nerd-font```

- Neovim (the greatest text editor)

Config location: ~/.config/nvim

Install Neovim:
```brew install neovim```

- Tmux terminal multiplexer

Config location: ~/.config/tmux

Install Tmux:
```brew install tmux```

- Oh My Posh shell prompt styling

Config location: ~/.config/ohmyposh

Install Oh My Posh:
```brew install jandedobbeleer/oh-my-posh/oh-my-posh```

- Ghostty terminal (my primary)

Config location: ~/.config/ghostty

Install Ghostty:
```brew install --cask ghostty```

- kitty terminal (my secondary)

Config location: ~/.config/kitty

Install kitty:
```brew install kitty```

- SketchyBar status bar

Config location: ~/.config/sketchybar

Install SketchyBar:
```brew tap FelixKratz/formulae```
```brew install sketchybar```

To start SketchyBar with Homebrew:
```brew services start sketchybar```

- Aerospace tiling window manager

Config location: ~/.config/aerospace

Install Aerospace:
```brew install --cask nikitabobko/tap/aerospace```

- JankyBorders window borders

Config location: ~/.config/borders

Install JankyBorders:
```brew tap FelixKratz/formulae```
```brew install borders```

Start JankyBorders with Homebrew:
```brew services start borders```

Some of the packages built in to the config include:

- zoxide - easier cd
- fzf - fuzzily find files
- oil.nvim - text buffer style file browser
- yazi.nvim - the best file browser
- harpoon.nvim - quickly jump between saved files
- telescope.nvim - search for files
- obsidian.nvim (disabled by default due to machine specific file paths) - integrates with Obsidian.md
- alpha.nvim - the coolest homescreen ever
