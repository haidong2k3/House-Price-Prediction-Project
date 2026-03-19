# Basic Homebrew Syntax

## Download
- go to homebrew webpage
- copy link -> paste to terminal
- follow the instruction in terminal
- check: 'brew --version' or 'which brew'

## How it works
- Tất cả nằm trong: /opt/homebrew/
- Structure:
    - Cellar/ → nơi chứa package thật
    - bin/ → shortcut (symlink)
    - etc/ → config
    vd: khi chạy python '/opt/homebrew/bin/python3' → link tới Cellar

## Basic Syntax
- Pakage install: 'brew install <package>'
- Pakage uninstall: 'brew uninstall <package>'
- Help: 'brew help' or 'brew help <command>'
- Update + upgrade: 'brew update' -> 'brew upgrade'
- Search: 'brew search <package>'
- Packages List: 'brew list'
- Don rac: 'brew cleanup -n' -> 'brew cleanup'