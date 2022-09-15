# Helix Plugins(unofficial)

How it works:

*   This repo's purpose is to have a list of the most desired helix plugins.
*   You could suggest preexisting plugins from editors such as vscode, emacs,
    vim, etc. or you could describe your new plugin idea & give it a name.
*   In case you do not understand a specific plugin's purpose from just it's
    name then please refer to the "plugin description" right below or just
    click on the plugin name.

# Plugins and Plugin Ideas

1.  [ vim-move ](#vim-move)
2.  [ magit ](#magit)
3.  [ helix-remote-development ](#helix-remote-development)

# Plugin/Idea Description

### magit:

*   Description: Magit is an interface to the version control system Git,
    implemented as an Emacs package.
*   Issues: <https://github.com/helix-editor/helix/issues/227>
*   References: <https://github.com/magit/magit>
*   Implementation:

### vim-move:

*   Description: This is a plugin for vim to move lines.
*   Issues: <https://github.com/helix-editor/helix/issues/2245>
*   References: <https://github.com/matze/vim-move>
*   Implementation: Plugin

### helix-remote-development

*   Description: Seamlessly edit code from ssh host machine
*   Issues: <https://github.com/helix-editor/helix/issues/3721>, #2
*   References: <https://code.visualstudio.com/docs/remote/remote-overview>
*   Implementation: Plugin

# Contributing

Users can contribute by either opening an issue or making a PR. Just make sure
to follow these rules for issues and pull requests:

## Issues:

*   Make an issue only if a plugin similar to your description is not available
    in the list.
*   If you have a new idea for a plugin then please give it a short
    descriptive name.
*   Format:

```markdown
### plugin-name

+ Description: Description of the plugin.
+ Issues: Links to any issues about this in the helix repo or this repo(comma
  separated). Leave empty if it's a new idea.
+ References: Links to any references like preexisting plugins, etc. Leave
  empty if it's a new idea.
+ Implementation: Plugin/Builtin
```

## Pull Requests:

*   Rules similar to rules for issues follow here.
*   Arrange plugins in alphabetical order.
*   Don't forcefully start names with early alphabets.
