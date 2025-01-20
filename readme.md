# About

I'm constantly working on improving my development environment, and I'll be adding more tools and tweaks as I go along on my journey to create the perfect setup.

[Referenced from] (https://www.josean.com/posts/how-to-setup-neovim-2024)

# ALL THE KEYBINDINGS

**General Keymaps**

- **`jk`**: Exit insert mode.
- **`<leader>nh`**: Clear search highlights.
- **`<leader>+`**: Increment number.
- **`<leader>-`**: Decrement number.

**Window Management**

- **`<leader>sv`**: Split window vertically.
- **`<leader>sh`**: Split window horizontally.
- **`<leader>se`**: Make split windows equal size.
- **`<leader>sx`**: Close current split.

**Tab Management**

- **`<leader>to`**: Open new tab.
- **`<leader>tx`**: Close current tab.
- **`<leader>tn`**: Go to next tab.
- **`<leader>tp`**: Go to previous tab.
- **`<leader>tf`**: Move current buffer to new tab.

**File Explorer (nvim-tree)**

- **`<leader>ee`**: Toggle file explorer.
- **`<leader>ef`**: Toggle file explorer on current file.
- **`<leader>ec`**: Collapse file explorer.
- **`<leader>er`**: Refresh file explorer.

**Telescope Fuzzy Finder**

- **`<leader>ff`**: Fuzzy find files in the current working directory.
- **`<leader>fr`**: Fuzzy find recent files.
- **`<leader>fs`**: Find string in current working directory.
- **`<leader>fc`**: Find string under cursor in current working directory.
- **`<leader>ft`**: Find todos.

**Trouble**

- **`<leader>xw`**: Open trouble workspace diagnostics.
- **`<leader>xd`**: Open trouble document diagnostics.
- **`<leader>xq`**: Open trouble quickfix list.
- **`<leader>xl`**: Open trouble location list.
- **`<leader>xt`**: Open todos in trouble.

**Automated Session Manager**

- **`<leader>wr`**: Restore session for current working directory.
- **`<leader>ws`**: Save session for current working directory.

**vim-maximizer**

- **`<leader>sm`**: Maximize/minimize a split.

**Linting**

- **`<leader>l`**: Trigger linting for current file.

**Gitsigns**

- **`]h`**: Next Hunk.
- **`[h`**: Previous Hunk.
- **`<leader>hs`**: Stage hunk.
- **`<leader>hr`**: Reset hunk.
- **`<leader>hS`**: Stage buffer.
- **`<leader>hR`**: Reset buffer.
- **`<leader>hu`**: Undo stage hunk.
- **`<leader>hp`**: Preview hunk.
- **`<leader>hb`**: Blame line.
- **`<leader>hB`**: Toggle line blame.
- **`<leader>hd`**: Diff this.
- **`<leader>hD`**: Diff this ~.
- **`ih`**: Gitsigns select hunk.

**Lazygit**

- **`<leader>lg`**: Open lazygit.

**LSP (Language Server Protocol)**

- **`gR`**: Show LSP references.
- **`gD`**: Go to declaration.
- **`gd`**: Show LSP definitions.
- **`gi`**: Show LSP implementations.
- **`gt`**: Show LSP type definitions.
- **`<leader>ca`**: See available code actions.
- **`<leader>rn`**: Smart rename.
- **`<leader>D`**: Show buffer diagnostics.
- **`<leader>d`**: Show line diagnostics.
- **`[d`**: Go to previous diagnostic.
- **`]d`**: Go to next diagnostic.
- **`K`**: Show documentation for what is under cursor.
- **`<leader>rs`**: Restart LSP.

**Formatting**

- **`<leader>mp`**: Format file or range (in visual mode).

**Commenting**

- **`gcc`**: Comment a single line.
- **`gc`**: Comment multiple lines (after selecting in visual mode).

**Other**

- **`s` followed by a motion**: Substitute text with previously copied text.
- **`ss`**: Substitute line.
- **`S`**: Substitute to end of line.

**Note:**

- The **`<leader>`** key is set to **space** in this configuration.
- Some keybindings are specific to certain modes, such as "n" for normal mode, "i" for insert mode, and "v" for visual mode.
- Some keybindings are set up using the `vim.keymap.set` function, which is used for setting up keymaps in Neovim.
- The keybindings for telescope, trouble, gitsigns, and lazygit are set up using the `keymap.set` function.
- The commenting functionality is provided by the `Comment.nvim` plugin, which uses `gc` as the base keybinding.

These keybindings are designed to make navigating, editing, and managing your code more efficient and intuitive within Neovim.
