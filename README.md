# glow.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview markdown files with [glow](https://github.com/charmbracelet/glow). To install, clone the repo inside your `~/.config/yazi/plugins/`:

```bash
git clone https://github.com/Reledia/glow.yazi.git
```

then include it in your `yazi.toml` to use it:

```toml
[plugin]
prepend_previewers = [
  { name = "*.md", exec = "glow" },
]
```

Make sure you have [glow](https://github.com/charmbracelet/glow) installed, and can be found in `PATH`.
