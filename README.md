# CFP's build of st

## Applied patches:
- [alpha](https://st.suckless.org/patches/alpha/)
- [anygeometry](https://st.suckless.org/patches/anygeometry/))
- [anysize](https://st.suckless.org/patches/anysize/)
- [blinking cursor](https://st.suckless.org/patches/blinking_cursor/)
- [bold is not bright](https://st.suckless.org/patches/bold-is-not-bright/)
- [charoffset](https://st.suckless.org/patches/charoffsets/)
- [clipboard](https://st.suckless.org/patches/clipboard/)
- [fullscreen](https://st.suckless.org/patches/fullscreen/)
- [gruvbox](https://st.suckless.org/patches/gruvbox/)
- [newterm](https://st.suckless.org/patches/newterm/)
- [scrollback](https://st.suckless.org/patches/scrollback/)
- [xresources](https://st.suckless.org/patches/xresources/)

## Requirements:
Xlib header files. On Arch-based systems:

```bash
# pacman -S libx11
```

## Installation:
Edit config.mk and config.h and run:

```bash
# make clean install
```
