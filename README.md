# docx.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview MS Word
(.docx) files with [docx2txt](https://docx2txt.sourceforge.net/).

This plugin is a only minimal changed copy of [glow.yazi](https://github.com/Reledia/glow.yazi).

To install, clone the repo inside your `~/.config/yazi/plugins/`

`~/.config/yazi/plugins/`:

```bash
git clone https://github.com:cschult/docx.yazi.git
```

or install with ya:

```bash
ya pack --add cschult/docx
```

then include it in your `yazi.toml` to use:

```toml
[plugin]
prepend_previewers = [
  { mime = "application/vnd.openxmlformats-officedocument.wordprocessingml.document", run = "docx" },
]
```
