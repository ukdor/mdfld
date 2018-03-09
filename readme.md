# orgfld

Atom's built-in folding commands use line indentation level to deduce the structure of the editor buffer. This works for most programming languages, but doesn't work for markdown documents.

This package reimplements the default editor fold commands, but uses heading levels instead of indentation levels.

Commands:

```
Windows Keymap
mdfld:unfold-all                ctrl-alt-] or ctrl-alt-0
mdfld:fold-current-row          ctrl-alt-[
mdfld:fold-at-heading-level-1   ctrl-alt-1
mdfld:fold-at-heading-level-2   ctrl-alt-2
mdfld:fold-at-heading-level-3   ctrl-alt-3
mdfld:fold-at-heading-level-4   ctrl-alt-4
mdfld:fold-at-heading-level-5   ctrl-alt-5
mdfld:fold-at-heading-level-6   ctrl-alt-6
```

Demo:

<img src="demo.gif" width=400>

## See also

* [mdfld](https://atom.io/packages/mfld) - Great implementation that is based on heading with "#" character
* [org-mode](https://atom.io/packages/org-mode) - Grammar for org-mode (.org) files
