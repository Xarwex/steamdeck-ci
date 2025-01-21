# Steam Deck NixOS binary cache

This repository contains workflows to build custom packages from
[Jovian-NixOS](https://github.com/Jovian-Experiments/Jovian-NixOS) and push them
to a binary cache on a regular basis.

A complete NixOS system is built, including Valve's kernel and Mesa forks among
other things.

## Revisions

The following revisions are built on a daily basis. Note that these may
not always succeed.

### Nixpkgs

- `nixos-unstable-small`
- `nixos-unstable`

### Jovian-NixOS

- `development`
