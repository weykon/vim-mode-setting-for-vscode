# vim-mode-setting-for-vscode

[](https://dev.to/ansonh/10-vs-code-vim-tricks-to-boost-your-productivity-1b0n#1-smart-relative-line)

```
{
  "vim.normalModeKeyBindings": [
    {
      "before": ["g", "p", "d"],
      "commands": ["editor.action.peekDefinition"]
    },
    {
      "before": ["g", "h"],
      "commands": ["editor.action.showDefinitionPreviewHover"]
    },
    {
      "before": ["g", "i"],
      "commands": ["editor.action.goToImplementation"]
    },
    {
      "before": ["g", "p", "i"],
      "commands": ["editor.action.peekImplementation"]
    },
    {
      "before": ["g", "q"],
      "commands": ["editor.action.quickFix"]
    },
    {
      "before": ["g", "r"],
      "commands": ["editor.action.referenceSearch.trigger"]
    },
    {
      "before": ["g", "t"],
      "commands": ["editor.action.goToTypeDefinition"]
    },
    {
      "before": ["g", "p", "t"],
      "commands": ["editor.action.peekTypeDefinition"]
    },
  ],
}

```
