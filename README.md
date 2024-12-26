# tinted-delta

A Tinted Theming template for [delta] with [Base16] themes

### Using with Tinty

For usage with [Tinty]:

1. Add the following to `~/.config/tinted-theming/tinty/config.toml`:
```toml
[[items]]
path = "https://github.com/tinted-theming/tinted-delta"
name = "delta"
themes-dir = "configs"
hook = "cp -f %f ~/.config/tinted-theming/delta.gitconfig"
supported-systems = ["base16", "base24"]
```

2. `tinty apply ...` to apply the theme you like.

[delta]: https://github.com/dandavidson/delta
[Base16]: https://github.com/tinted-theming/home/blob/main/styling.md
[Tinty]: https://github.com/tinted-theming/tinty
