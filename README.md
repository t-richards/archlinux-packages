# archlinux-packages

A set of custom packages for Arch Linux.

## Notes

All packages must build in a clean chroot.

```bash
pkgctl build
```

Update the `.SRCINFO` alongside any changes to the `PKGBUILD`.

```bash
makepkg --printsrcinfo > .SRCINFO
```

Check for new versions.

```
pkgctl version check
