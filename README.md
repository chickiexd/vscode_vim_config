# VS Code Vim Configuration Profile

Welcome to my VS Code Vim Configuration Profile repository! This repo contains my personal configuration for using Vim within Visual Studio Code. It's tailored for developers who love the efficiency of Vim and wish to integrate similar workflows into VS Code.

Including some keybinds of [kickstarter](https://github.com/nvim-lua/kickstart.nvim), [ThePrimagen](https://github.com/ThePrimeagen/init.lua), [Melkey](https://github.com/Melkeydev/vscode_bindings)

## Overview

This setup aims to bring the best of Vim into the flexible and powerful environment of VS Code, offering a seamless experience for those accustomed to Vim's keybindings. The configurations provided here include:

- `keybindings.json`: Custom keybindings to mimic Vim's shortcuts.
- `settings.json`: Various settings to customize the editor's behavior, also including shortcuts.

## Cheat-Sheet

### Misc Keybindings

- **Toggle Zen-Mode**: `<Ctrl+z>` ➜ `workench.action.toggleZenMode`

### Insert Mode Keybindings

- **Exit Insert Mode**: `jj` ➜ `<Esc>`
- **Move Right and Insert**: `<Ctrl+l>` ➜ `<Esc>`, `l`, `a`

### Normal Mode Keybindings (Non-Recursive)

- **Comment Line**: `leader c` ➜ `editor.action.commentLine`
- **Save File**: `leader w` ➜ `:w!`
- **Quit**: `leader q` ➜ `:q!`
- **Save and Quit**: `leader x` ➜ `:x!`
- **Focus Left Group**: `leader h` ➜ `workbench.action.focusLeftGroup`
- **Focus Below Group**: `leader j` ➜ `workbench.action.focusBelowGroup`
- **Focus Above Group**: `leader k` ➜ `workbench.action.focusAboveGroup`
- **Focus Right Group**: `leader l` ➜ `workbench.action.focusRightGroup`
- **Split Window**: `leader %` ➜ `:split`
- **Vertical Split Window**: `leader v` ➜ `:vsplit`
- **Next Buffer**: `<Shift+l>` ➜ `:bnext`
- **Previous Buffer**: `<Shift+h>` ➜ `:bprevious`
- **Delete Line**: `leader d` ➜ `dd`
- **Move Down Fast**: `J` ➜ `5j`
- **Move Up Fast**: `K` ➜ `5k`
- **Join Lines**: `<Leader>J` ➜ `J`
- **Show Command Palette**: `<Leader><Leader>p` ➜ `workbench.action.showCommands`
- **Go to Symbol**: `<Leader>t` ➜ `workbench.action.gotoSymbol`
- **Scroll Down Half Page**: `<Ctrl+d>` ➜ `<Ctrl+d>`, `zz`
- **Scroll Up Half Page**: `<Ctrl+u>` ➜ `<Ctrl+u>`, `zz`
- **Next Find Match**: `n` ➜ `n`, `zz`, `zz`, `v`
- **Previous Find Match**: `N` ➜ `N`, `zz`, `zz`, `v`
- **Previous Marker**: `[d` ➜ `editor.action.marker.prev`
- **Next Marker**: `]d` ➜ `editor.action.marker.next`
- **Quick Fix**: `leader .` ➜ `editor.action.quickFix`
- **Quick Open**: `leader f` ➜ `workbench.action.quickOpen`
- **Find in Files**: `leader sf` ➜ `workbench.action.findInFiles`
- **Format Document**: `leader p` ➜ `editor.action.formatDocument`
- **Run Python File**: `<leader><leader>r` ➜ `python.execInTerminal-icon`

### Visual Mode Keybindings

- **Paste Over without Yanking**: `<Leader>p` ➜ `"_dP`
- **Outdent Lines**: `<` ➜ `editor.action.outdentLines`
- **Indent Lines**: `>` ➜ `editor.action.indentLines`
- **Move Lines Down**: `J` ➜ `editor.action.moveLinesDownAction`
- **Move Lines Up**: `K` ➜ `editor.action.moveLinesUpAction`
- **Comment Line**: `leader c` ➜ `editor.action.commentLine`

### Code Navigation and Editing Keybindings

- **Select Next Suggestion**: `Ctrl+j` ➜ `selectNextSuggestion` (when suggestions are visible)
- **Select Previous Suggestion**: `Ctrl+k` ➜ `selectPrevSuggestion` (when suggestions are visible)
- **Select Next Code Action**: `Ctrl+j` ➜ `selectNextCodeAction` (when code action menu is visible)
- **Select Previous Code Action**: `Ctrl+k` ➜ `selectPrevCodeAction` (when code action menu is visible)
- **Add Selection to Next Find Match**: `Alt+d` ➜ `editor.action.addSelectionToNextFindMatch`

### Terminal Keybindings

- **Focus Next Terminal**: `Ctrl+Shift+j` ➜ `workbench.action.terminal.focusNext`
- **Focus Previous Terminal**: `Ctrl+Shift+k` ➜ `workbench.action.terminal.focusPrevious`
- **Toggle Panel**: `Ctrl+Shift+h` ➜ `workbench.action.togglePanel`
- **New Terminal**: `Ctrl+Shift+n` ➜ `workbench.action.terminal.new`
- **Kill Terminal**: `Ctrl+Shift+w` ➜ `workbench.action.terminal.kill`

### File Explorer and Search Keybindings

- **Open/Close Files Explorer**: `Ctrl+e` ➜ `workbench.files.action.focusFilesExplorer` `workbench.action.focusActiveEditorGroup`
- **New File in Explorer**: `n` ➜ `explorer.newFile`
- **Rename File in Explorer**: `r` ➜ `renameFile`
- **New Folder in Explorer**: `Shift+n` ➜ `explorer.newFolder`
- **Delete File in Explorer**: `d` ➜ `deleteFile`
- **Open/Close Search**: `Ctrl+f` ➜ `workbench.view.search` `workbench.action.focusActiveEditorGroup` 
- **Focus Next Search Result**: `Ctrl+j` ➜ `search.action.focusNextSearchResult`
- **Focus Previous Search Result**: `Ctrl+k` ➜ `search.action.focusPreviousSearchResult`