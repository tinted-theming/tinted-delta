# tinted-delta

A Tinted Theming template for [delta] with [Base16] themes

### Using with Tinty

For usage with [Tinty]:

1. Add this line to your `.gitconfig`. This assumes you have already set up [delta] as your Git pager/diff-tool under the
   name `delta`:

   ```gitconfig
   [include]
       path = ~/.local/share/tinted-theming/tinty/tinted-delta-configs-file.gitconfig
   ```

2. Add the following to `~/.config/tinted-theming/tinty/config.toml`:
    ```toml
    [[items]]
    path = "https://github.com/tinted-theming/tinted-delta"
    name = "tinted-delta"
    themes-dir = "configs"
    supported-systems = ["base16", "base24"]
    ```

3. `tinty apply ...` to apply the theme you like.

[delta]: https://github.com/dandavidson/delta
[Base16]: https://github.com/tinted-theming/home/blob/main/styling.md
[Tinty]: https://github.com/tinted-theming/tinty
