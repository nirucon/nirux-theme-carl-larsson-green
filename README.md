# NIRUX Theme: Carl Larsson Green

A NIRUX suite theme pack based on the green Carl Larsson wallpaper.

- Theme ID: `niru-carl-larsson-green`
- Display name: **Niru Carl Larsson Green**
- Background: `#0e120c`
- Foreground: `#e3ddcb`
- Muted: `#a29c87`
- Border: `#35402d`
- Focus: `#8aa66a`
- Wallpaper: `nirux-wallpaper-carl-larsson-green-4k.png` (4K)

## Install

NIRUX must be installed and `niructl` must be in `PATH`.

```sh
./install.sh
niructl theme niru-carl-larsson-green
```

The installer uses `niructl theme-import`, so it validates the theme and
installs both the palette and wallpaper into the standard per-user locations.
No root access is required.

To replace an existing installation after a pack update:

```sh
./install.sh --replace
niructl theme niru-carl-larsson-green
```

## Uninstall

```sh
./uninstall.sh
```

## Compatibility

The theme is a user theme, so the suite discovers it without being added to any
built-in theme list. Components that follow the shared NIRUX theme pick it up:
NIRUWM, NIRUBAR, NIRU Launcher, NIRUNOTIFY, NIRULOCK, NIRUSCREENSAVER,
NIRUSHOT, NIRUPRES editor chrome, NIRUFLOW, NIRUORG and NIRUNOTE with
**Follow NIRUX**. NIRUPRES slide themes remain independent by design.
