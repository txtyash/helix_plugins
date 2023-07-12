# Helix Plugins(unofficial)

How it works:

*   This repo's purpose is to have a list of the most desired helix plugins.
*   You could suggest preexisting plugins from editors such as vscode, emacs,
    vim, etc. or you could describe your new plugin idea & give it a name.
*   In case you do not understand a specific plugin's purpose from just it's
    name then please refer to the "plugin description" right below or just
    click on the plugin name.

## Plugins and Plugin Ideas

1. [ codestats ](#code-stats)
1. [ colorizer ](#colorizer)
1. [ easymotion ](#easy-motion)
1. [ ghosttext ](#ghost-text)
1. [ helix-remote-development ](#helix-remote-development)
1. [ jupyter ](#jupyter)
1. [ magit ](#magit)
1. [ mucomplete ](#mucomplete)
1. [ org-mode ](#org-mode)
1. [ table-mode ](#table-mode)
1. [ tabout ](#tabout)
1. [ vim-move ](#vim-move)
1. [ wakatime ](#wakatime)

## Plugin/Idea Description

### Code Stats:

*   Description: Generate statistics from your programming.
*   Issues/Discussions: N/A
*   References: <https://codestats.net/api-docs>, <https://codestats.net/plugins>
*   Implementation: Plugin

### Colorizer:

*   Description: Color previewer in files
*   Issues/Discussions: None
*   References: <https://github.com/norcalli/nvim-colorizer.lua>
*   Implementation: Built-in

### Easy Motion:

*   Description: Simpler way to use motions by highlighting choices
*   Issues/Discussions: zim0369/helix\_plugins/issues/7
*   References: <https://github.com/easymotion/vim-easymotion>
*   Implementation: Plugin

### Ghost Text:

*   Description: Use your text editor in the browser
*   Issues/Discussions: helix-editor/helix/issues/3339
*   References: <https://ghosttext.fregante.com/>
*   Implementation: Plugin

### Helix Remote Development

*   Description: Seamlessly edit code from ssh host machine
*   Issues/Discussions: helix-editor/helix/issues/3721, zim0369/helix\_plugins/issues/2
*   References: <https://code.visualstudio.com/docs/remote/remote-overview>
*   Implementation: Plugin

### Jupyter:

*   Description: Two-way integration between Helix and Jupyter. Should allow for interactive plotting (maybe by integrating with JupyterLab).
*   Issues/Discussions: <https://github.com/helix-editor/helix/issues/2806>
*   References: <https://github.com/jupyter-vim/jupyter-vim>
*   Implementation: Plugin

### Magit:

*   Description: Magit is an interface to the version control system Git,
    implemented as an Emacs package.
*   Issues/Discussions: helix-editor/helix/issues/227
*   References: <https://github.com/magit/magit>
*   Implementation: Plugin

### MUcomplete:

*   Description: Autocompletion
*   Issues/Discussions: helix-editor/helix/issues/1063, helix-editor/helix#901, helix-editor/helix#1015
*   References: <https://github.com/lifepillar/vim-mucomplete>
*   Implementation: Built-in

### Org Mode:

*   Description: A GNU Emacs major mode for keeping notes.
*   Issues/Discussions: helix-editor/helix/issues/2825
*   References: <https://orgmode.org/>
*   Implementation: Plugin

### Table Mode:

*   Description: Automatic table creator & formatter allowing one to create neat tables as you type.
*   Issues/Discussions: helix-editor/helix/issues/2819
*   References: <https://github.com/dhruvasagar/vim-table-mode>
*   Implementation: Plugin

### Tabout:

*   Description: [Tabbing out from parentheses, quotes, and similar contexts.](https://github.com/helix-editor/helix/issues/1587#issue-1115976332)
*   Issues/Discussions: <https://github.com/helix-editor/helix/issues/1587>
*   References: <https://github.com/abecodes/tabout.nvim>
*   Implementation: Built-in

### Vim Move:

*   Description: This is a plugin for vim to move lines.
*   Issues/Discussions: helix-editor/helix/issues/2245
*   References: <https://github.com/matze/vim-move>
*   Implementation: Plugin

### Wakatime:

*   Description: Code stats right from your editor
*   Issues/Discussions: helix-editor/helix/discussions/3477, zim0369/helix\_plugins/issues/6
*   References: <https://wakatime.com/help/creating-plugin>
*   Implementation: Plugin

## Contributing

Users can contribute by either opening an issue or making a PR. Just make sure
to follow the below format for issues and pull requests:

### Format:

```markdown
### Plugin Name
  * Description: Description of the plugin.
  * Issues/Discussions: Links to any issues/discussions about this in the helix repo or this repo(comma
    separated). Leave empty if it's a new idea.
  * References: Links to any references like preexisting plugins, etc. Leave
    empty if it's a new idea.
  * Implementation: Plugin/Built-in
```

### Issues:

*   Check the list to prevent duplicates.
*   If it's a new idea then give it a short descriptive name.
*   Add the information according to the format.

### Pull Requests:

*   Rules similar to rules for issues follow here.
*   Follow alphabetical order while changing the list.
*   Names should be lowercase.
