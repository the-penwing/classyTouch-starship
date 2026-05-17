# THIS REPO IS NO LONGER MAINTAINED

I am still actively working on this prompt.
However it is only getting updated in my [dotfiles](https://github.com/the-penwing/nixos-config).
Managing 2 repos for the same file just isnt worth it for me anymore.

# Gruvbox Clean Starship Prompt

[Starship](https://starship.rs/) prompt inspired by a oh-my-zsh theme called classyTouch

## Current Features

- Username and Hostname
  - Green for standard users
  - Red for root users
- Git Status
- Git Branch
- Current Directory
- Baked in Gruvbox theming
- [WIP] Language Support
  - Currently just python, if I have time more will be added
  - Named Virtual Enviroment
  - Version
- Success Notifcation
  - Red Full Prompt on Success
  - Orange Shorter Prompt on Fail
- Maybe More that I've forgotten

![photo](screenshot.png)

## Requirements

- Starship
- A Nerdfont selected and enabled in the terminal (a starship requirement but listing it here regardless)

## Installation

Just download the ``starship.toml`` file and place in ``~/.config``
After you have placed the file in the aforementioned directory, just reload your shell!!

---

If you run into any issues, have any questions or concerns or want more features, feel free to let me know.
