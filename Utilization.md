# Conky:

Conky is a free software desktop system monitor for the X Window System. It is available for Linux, FreeBSD, and OpenBSD.

---

# Installation steps:

## Arch Linux

```
$ pacman -S conky
```

## Debian

```
$ sudo apt install conky
```

## Fedora

```
$ sudo dnf install conky
```

## FreeBSD

```
# Conky is in ports in `sysutils/conky`.
$ cd /usr/ports/sysutils/conky
$ make install clean
```
```
# Alternatively, install the binary package.
$ pkg install conky
```

## Gentoo

```
$ emerge conky
```

## Nix

```
$ nix-env -i conky
```

This is the official [Conky Page.](https://github.com/brndnmtthws/conky)

---

# Change Conky Theme:

If you want to change your Conky theme, you need to follow these steps.

Open your file manager with root rights, you can do this with:

```
$ sudo nautilus
```

Now go under:
Other Locations/Computer/etc/conky/conky.conf

Now you can open this file.

You can now make a backup of Conky by copying the entire text of conky.conf into a new file of your choice, which you can keep in a safe place in case something goes wrong. You can use this file to undo everything.

Now you have to jump to [Conky.txt](https://github.com/HoferSimon/Conky/blob/main/Conky.txt) and copy all the text. Now you must first delete all the text that is in your conky.txt file, after you have done this you can paste the new text. Now you just need to save, and you can use your new theme.