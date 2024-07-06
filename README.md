# RVGL Launcher Flatpak

This unofficial repository provides automatic builds of a Flatpak package for the [RVGL Launcher](https://re-volt.gitlab.io/rvgl-launcher/).

## Installation

```bash
$ flatpak install --user --noninteractive https://mickael9.github.io/rvgl-flatpak/rvgl.flatpakref
```

## Notes

- Anything downloaded from the launcher lives inside `~/.var/app/org.rvgl.rvmm`
- Automatic updates of the launcher itself are disabled
- `rvmm://` custom protocol handler is registered
