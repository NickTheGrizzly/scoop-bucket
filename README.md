# NickTheGrizzly's Scoop bucket

[Scoop](https://scoop.sh) bucket for [Beam Mod Manager](https://beammodmanager.com/), a free mod
manager for BeamNG.drive and BeamMP.

```powershell
scoop bucket add nickthegrizzly https://github.com/NickTheGrizzly/scoop-bucket
scoop install nickthegrizzly/beam-mod-manager
```

This installs the **portable** build straight from the official
[GitHub release](https://github.com/NickTheGrizzly/beam-mod-manager-releases/releases), checked
against the SHA-256 published there and at https://beammodmanager.com/security. `scoop update`
picks up new versions automatically: a scheduled workflow in this repo updates the manifest when a
new release is published.

Your library, settings and Mod Storage live outside the Scoop app folder, so they survive updates
and uninstalls.

Other ways to install: the [website](https://beammodmanager.com/), `winget install
NickTheGrizzly.BeamModManager`, or Chocolatey (`beam-mod-manager`, in moderation).

The bucket files are public domain (see LICENSE). Beam Mod Manager itself is freeware under its own
[terms](https://beammodmanager.com/terms).
