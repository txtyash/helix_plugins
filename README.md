# Helix Plugins(unofficial)

How it works:

- This repo's purpose is to have a list of the most desired helix plugins.
- You could suggest preexisting plugins from editors such as vscode, emacs,
  vim, etc. or you could describe your new plugin idea & give it a name.
- In case you do not understand a specific plugin's purpose from just it's
  name then please refer to the "plugin description" right below or just
  click on the plugin name.

# Plugins and Plugin Ideas

1.  [ colorizer ](#colorizer)
1.  [ ghosttext ](#GhostText)
1.  [ helix-remote-development ](#helix-remote-development)
1.  [ magit ](#magit)
1.  [ org-mode ](#org-mode)
1.  [ shade ](#shade)
1.  [ table-mode ](#table-mode)
1.  [ tabout ](#tabout)
1.  [ vim-move ](#vim-move)

# Plugin/Idea Description

### Colorizer:

- Description: Color previewer in files
- Issues: None
- References: <https://github.com/norcalli/nvim-colorizer.lua>
- Implementation: Builtin

### GhostText:

- Description: Use your text editor in the browser
- Issues: helix-editor/helix/issues/3339
- References: <https://ghosttext.fregante.com/>
- Implementation:

### helix-remote-development

- Description: Seamlessly edit code from ssh host machine
- Issues: helix-editor/helix/issues/3721, #2
- References: <https://code.visualstudio.com/docs/remote/remote-overview>
- Implementation: Plugin

### magit:

- Description: Magit is an interface to the version control system Git,
  implemented as an Emacs package.
- Issues: helix-editor/helix/issues/227
- References: <https://github.com/magit/magit>
- Implementation:

### org-mode:

- Description: A GNU Emacs major mode for keeping notes.
- Issues: helix-editor/helix/issues/2825
- References: <https://orgmode.org/>
- Implementation: Plugin

### shade:

- Description: Dim your inactive windows, making it easier to see the active
  window at a glance.
- Issues: None
- References: <https://github.com/sunjon/Shade.nvim>
- Implementation: Builtin

### table-mode:

- Description: Automatic table creator & formatter allowing one to create neat tables as you type.
- Issues: helix-editor/helix/issues/2819
- References: <https://github.com/dhruvasagar/vim-table-mode>
- Implementation: Plugin

### tabout:

- Description: [Tabbing out from parentheses, quotes, and similar contexts.](https://github.com/helix-editor/helix/issues/1587#issue-1115976332)
- Issues: <https://github.com/helix-editor/helix/issues/1587>
- References: <https://github.com/abecodes/tabout.nvim>
- Implementation: Builtin

### vim-move:

- Description: This is a plugin for vim to move lines.
- Issues: helix-editor/helix/issues/2245
- References: <https://github.com/matze/vim-move>
- Implementation: Plugin

# Contributing

Users can contribute by either opening an issue or making a PR. Just make sure
to follow the below format for issues and pull requests:

Format:

```markdown
### plugin-name

- Description: Description of the plugin.
- Issues: Links to any issues about this in the helix repo or this repo(comma
  separated). Leave empty if it's a new idea.
- References: Links to any references like preexisting plugins, etc. Leave
  empty if it's a new idea.
- Implementation: Plugin/Builtin
```

## Issues:

- Check the list to prevent duplicates.
- If it's a new idea then give it a short descriptive name.
- Add the information according to the format.

## Pull Requests:

- Rules similar to rules for issues follow here.
- Follow alphabetical order while changing the list.
- Names should be lowercase.
