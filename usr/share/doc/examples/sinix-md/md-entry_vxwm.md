/usr/share/sinix/vxwm/
# vxwm -(md-entry!)
===============================

`VXWM (Versatile X Window Manager)` is a fork of `dwm (Dynamic Window Manager)` that adds
infinite tags, which means your desktop is treated like infinite canvas.

It is relatively lightweight and many people consider it better than `dwm` itself.

# 1: Installation

VXWM requires some compilation dependencies;
install them with one command:

```bash
> sudo pacman -S base-devel libx11 libxft libxinerama fontconfig git make
```

After the installation completes, compile the program:

```bash
> cd /usr/share/sinix/vxwm/
> make
> sudo make clean install
```

# 2: Customization

Like `dwm,` you have to edit it's source code then recompile the program.
if you need to recompile after making changes in its config.h, run this:

```bash
> sudo make clean install
```

What this command does is to clean the current install and recompile the program, 
so reinstalling.
