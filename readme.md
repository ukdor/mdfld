# orgfld

The source `mdfld` package implements folding in markdown files based on the heading character `#` (hash symbol).

This package reimplements the `mdfld` package using the asterisk `*` as the heading instead of the hash `#`.

Additionally, Windows friendly key mapping is added via CTRL-ALT-key combinations when the grammars `GitHub Markdown (gfm)` or `Org-mode Syntax (org-mode)` are in use by the file.

Windows Keymap:
```
mdfld:unfold-all                ctrl-alt-] or ctrl-alt-0
mdfld:fold-current-row          ctrl-alt-[
mdfld:fold-at-heading-level-1   ctrl-alt-1
mdfld:fold-at-heading-level-2   ctrl-alt-2
mdfld:fold-at-heading-level-3   ctrl-alt-3
mdfld:fold-at-heading-level-4   ctrl-alt-4
mdfld:fold-at-heading-level-5   ctrl-alt-5
mdfld:fold-at-heading-level-6   ctrl-alt-6
```

Demo (from mdfld):
(Works using * instead of #)

<img src="demo.gif" width=400>

## See also

* [mdfld](https://atom.io/packages/mfld) - Great implementation that is based on heading with "#" character
* [org-mode](https://atom.io/packages/org-mode) - Grammar for org-mode (.org) files
