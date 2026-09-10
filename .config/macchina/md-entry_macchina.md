~/.config/macchina/
# macchina -(md-entry!)
=========================================

`macchina` is an alternative to `fastfetch` written in Rust.

It is very customizable and easier to configure.

# 1: Installation

While being a rust program (rust is a compiled language), `macchina` is in the
official Arch Linux repos!

```bash
> sudo pacman -S macchina
```

After installed, create a .config folder so you can configure it:

```bash
> mkdir -p ~/.config/macchina/
```

`macchina` is configured using TOML. if you know TOML or macchina's TOML syntax, you can write a config.

But for the sake of user experience, you can clone this repository you are right now and copy the default sinix configs.

```bash
> git clone https://github.com/theskepticpillow/sinix
> cd sinix
> cp -r .config/macchina/* ~/.config/macchina/
> sudo cp -r root/.config/macchina/ /root/.config/
> cd ..
> rm -rf sinix/
```

# 2: Customization

Check out ![our page for macchina themes.](https://github.com/theskepticpillow/sinix/tree/main/.config/macchina/md-entry_macchinathemes.md)

-----------------------------------------------------------------------------------
