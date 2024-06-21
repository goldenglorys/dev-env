Cheat sheet with the keymaps and shortcuts from the Neovim setup above, along with some general Vim commands that might be useful.

# Neovim Cheat Sheet

## General Keymaps

| Keymap | Action |
|--------|--------|
| `<leader>` | Space key |
| `jk` | Exit insert mode |
| `<leader>nh` | Clear search highlights |
| `<leader>+` | Increment number |
| `<leader>-` | Decrement number |

## Window Management

| Keymap | Action |
|--------|--------|
| `<leader>sv` | Split window vertically |
| `<leader>sh` | Split window horizontally |
| `<leader>se` | Make splits equal size |
| `<leader>sx` | Close current split |

## Tab Management

| Keymap | Action |
|--------|--------|
| `<leader>to` | Open new tab |
| `<leader>tx` | Close current tab |
| `<leader>tn` | Go to next tab |
| `<leader>tp` | Go to previous tab |
| `<leader>tf` | Open current buffer in new tab |

## File Explorer (nvim-tree)

| Keymap | Action |
|--------|--------|
| `<leader>ee` | Toggle file explorer |
| `<leader>ef` | Toggle file explorer on current file |
| `<leader>ec` | Collapse file explorer |
| `<leader>er` | Refresh file explorer |

## Telescope

| Keymap | Action |
|--------|--------|
| `<leader>ff` | Fuzzy find files in cwd |
| `<leader>fr` | Fuzzy find recent files |
| `<leader>fs` | Find string in cwd |
| `<leader>fc` | Find string under cursor in cwd |
| `<leader>ft` | Find todos |

## LSP

| Keymap | Action |
|--------|--------|
| `gR` | Show LSP references |
| `gD` | Go to declaration |
| `gd` | Show LSP definitions |
| `gi` | Show LSP implementations |
| `gt` | Show LSP type definitions |
| `<leader>ca` | See available code actions |
| `<leader>rn` | Smart rename |
| `<leader>D` | Show buffer diagnostics |
| `<leader>d` | Show line diagnostics |
| `[d` | Go to previous diagnostic |
| `]d` | Go to next diagnostic |
| `K` | Show documentation for what is under cursor |
| `<leader>rs` | Restart LSP |

## Formatting

| Keymap | Action |
|--------|--------|
| `<leader>mp` | Format file or range (in visual mode) |

## Linting

| Keymap | Action |
|--------|--------|
| `<leader>l` | Trigger linting for current file |

## Comments

| Keymap | Action |
|--------|--------|
| `gcc` | Comment/uncomment current line |
| `gc` | Comment/uncomment selection (in visual mode) |

## Git (Gitsigns)

| Keymap | Action |
|--------|--------|
| `]h` | Next hunk |
| `[h` | Previous hunk |
| `<leader>hs` | Stage hunk |
| `<leader>hr` | Reset hunk |
| `<leader>hS` | Stage buffer |
| `<leader>hR` | Reset buffer |
| `<leader>hu` | Undo stage hunk |
| `<leader>hp` | Preview hunk |
| `<leader>hb` | Blame line |
| `<leader>hB` | Toggle line blame |
| `<leader>hd` | Diff this |
| `<leader>hD` | Diff this ~ |

## LazyGit

| Keymap | Action |
|--------|--------|
| `<leader>lg` | Open LazyGit |

## Trouble

| Keymap | Action |
|--------|--------|
| `<leader>xx` | Open/close trouble list |
| `<leader>xw` | Open trouble workspace diagnostics |
| `<leader>xd` | Open trouble document diagnostics |
| `<leader>xq` | Open trouble quickfix list |
| `<leader>xl` | Open trouble location list |
| `<leader>xt` | Open todos in trouble |

## General Vim Commands

| Command | Action |
|---------|--------|
| `:w` | Save file |
| `:q` | Quit |
| `:wq` | Save and quit |
| `:q!` | Quit without saving |
| `dd` | Delete line |
| `yy` | Yank (copy) line |
| `p` | Paste after cursor |
| `P` | Paste before cursor |
| `u` | Undo |
| `Ctrl+r` | Redo |
| `/pattern` | Search for pattern |
| `n` | Go to next search result |
| `N` | Go to previous search result |
| `:s/old/new/g` | Replace 'old' with 'new' in current line |
| `:%s/old/new/g` | Replace 'old' with 'new' in entire file |



Remember that `<leader>` is set to the Space key in this configuration. This cheat sheet covers the main keymaps and shortcuts from the setup above, along with some general Vim commands that are always useful to know.
