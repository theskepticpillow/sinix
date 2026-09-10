~/.config/macchina/themes/
# macchina themes -(md-entry!)
=====================================

Self-explanatory, Macchina themes allow you to customize the rust-written fetch program.

# 1: Applying Themes

Open your main macchina.toml file with your favorite text editor.

For example, lets use nano.
```bash
> nano ~/.config/macchina/macchina.toml
```

Uncomment the `theme = "Sodium"` line and replace `Sodium` with `Beryllium`.

```toml
theme = "Beryllium
```

How this actually works is that macchina reads theme files from .config/macchina/themes/, then **uses the content in the theme files
in the main config file.**

You can make your own theme and customize existing ones if you know macchina's TOML syntax.

# 2: Troubleshooting

### Theme doesn't work, or the output doesnt change.

Ensure your file is in the themes folder.

It's common that you may not even have the themes folder.

Create it:
```bash
> mkdir -p ~/.config/macchina/themes/
```

Put your theme file there:

```bash
> cp your-file.toml ~/.config/macchina/themes/
```

And set the theme in macchina.toml:

```toml
theme = "your-file"
```

You may see the new output, and this should be permanent.

> [!NOTE]
> If you do this in the root account, it will NOT appear in the normal user account.
---------------------------------------------------------------------------------------
