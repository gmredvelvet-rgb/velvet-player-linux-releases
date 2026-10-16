# Velvet Player Linux downloads

[Download Velvet Player Linux 0.1.2 Preview](https://github.com/gmredvelvet-rgb/velvet-player-linux-releases/releases/tag/v0.1.2-preview.1).
This repository contains release packages and public update metadata; source is maintained separately.

Players enter without a Velvet access key, invitation code, Patreon sign-in or unlocked desktop
keyring. Choose **I am a player**, enter your GM's Foundry HTTPS address and sign in with your normal
Foundry player account. Existing invited players migrate automatically. Foundry and TaleSpire still
enforce their own account and miniature permissions. This is a player-only launcher.

For Linux x86_64 PCs using an X11 desktop and Steam Deck Desktop Mode. Native Steam and Proton are
required for TaleSpire Full or Guest Edition. Wayland, Gaming Mode and Flatpak Steam are outside
this preview. Real game and hardware validation is ongoing.

Download the `.tar.gz` and matching `.sha256`, verify and extract them on Linux, then run
`./install.sh` without sudo. Open **Velvet Player Linux** from the applications menu. Use the included
README for the Proton launch option and Symbiote setup.

Installed 0.1.1 clients can use **Check for updates → Update & restart**. Updates retain signed
metadata, size and SHA256 verification. No GitHub account or token is needed. The `linux-preview`
release stores signed channel metadata; use the versioned release for the installation archive.

The GM should update the Foundry module to 0.4.33 for PF2e roll/target and image fixes served by the
GM's Foundry server. The Linux player launcher does not install or host the GM's Foundry module.

Never share Foundry credentials or local bridge tokens when reporting a problem.
