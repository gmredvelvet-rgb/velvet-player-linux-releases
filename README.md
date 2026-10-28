# Velvet Player Linux downloads

[Download Velvet Player Linux 0.1.6 Preview](https://github.com/gmredvelvet-rgb/velvet-player-linux-releases/releases/tag/v0.1.6-preview.1).

For Linux x86_64, system Steam and Proton. Supports composited X11 and KDE Plasma Wayland through XWayland, including Nobara and Steam Deck Desktop Mode. Keep your KDE Wayland desktop; Velvet and TaleSpire use XWayland windows.

## New in 0.1.6

Adds a local custom weapon library: import rigid GLB files, or convert FBX through locally installed Blender, adjust the grip and select each model per character/item. Files live in TaleSpire/BepInEx/plugins/VelvetFieldKit/CustomAssets/Weapons and survive updates. No repackaging is needed per model. Requires the GM to serve Canvas Bridge 1.0.10 or newer.

Includes first/third-person cameras, original hands and weapons, equipped/raised PF2e shields, Foundry-triggered attacks, spell VFX, auras, per-character vision/Fog of War, linked loot and the per-character weapon appearance selector. This player uses its own TaleSpire through Proton. No stream, video capture, WebRTC or second instance is included. The GM must serve the compatible updated Foundry interface.

## Updating an older launcher blocked on Nobara

If the old launcher reports Native Wayland is not supported before it shows Update, close Velvet and download [Actualizar-Velvet-Linux.sh](https://github.com/gmredvelvet-rgb/velvet-player-linux-releases/releases/download/v0.1.6-preview.1/Actualizar-Velvet-Linux.sh). In the download folder run:

    sh Actualizar-Velvet-Linux.sh

Run it as your normal user, without sudo. It uses the updater already installed with Velvet 0.1.1/0.1.2/0.1.3/0.1.4: signed metadata, verified download, installation and automatic restart, preserving settings and mini packs. No desktop change, system Node or manual reinstall is required. If you only used a portable copy and have no installed version, use the full archive and ./install.sh once instead.

## Normal installation and updates

If the launcher opens, use **Check for updates → Update & restart**. For a first installation, download the versioned tar.gz and matching sha256, verify, extract, then run ./install.sh without sudo. Close TaleSpire before the next Play to update native plugins.

This is a player-only launcher: use the GM's HTTPS Foundry address and your normal player account. No Velvet invitation, access key, GitHub account or desktop keyring is required. The GM needs Canvas Bridge 1.0.9 or a compatible newer version and Foundry Rolls Bridge 1.3.1 for the current PF2e critical/compound dice and actor-search fixes.

See the release's NOBARA_KDE.md guide. Automated tests include real KWin Wayland/rootless XWayland, actual Chromium launcher UI, docking/restoration/normal close and PF2e/D&D area workflows with simulated games. Actual Nobara/Plasma 6 + GPU + Steam/Proton multiplayer remains pending. Native Wayland game windows, other Wayland compositors, Gaming Mode, Flatpak Steam and controller-only operation remain outside the preview.

The linux-preview release stores signed update metadata; use the versioned release above for downloads. Never share Foundry credentials or local bridge tokens.
