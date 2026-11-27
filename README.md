# ngspades/assets

Downloadable asset packs for **Shoot and Destroy** (the ngspades reference
client). The game downloads them at start-up; they are not meant to be fetched
by hand, but the files are public like everything else in this organization.

The repository holds no files of its own: **the packs are release assets**.

| Pack | What is in it |
| --- | --- |
| `voice-<lang>.zip` | The radio announcer's voice lines in one language (`en`, `pt-BR`, `es`, `ru`, `de`, `tr`, `pl`, `it`, `fr`, `nl`, `da`, `sv`, `fi`, `no`, `ms`, `sw`). |
| `models.zip` | **Required.** Every 3D model the game draws (`kv6/`: bodies, class and weapon skins, guns, sentry, crates, zombie, `ours/kv6/`) and the home page's world (`menu/`). |
| `images.zip` | **Required.** Every picture (`png/`: HUD, icons, textures, `png/aos/`, `png/ui/`, `ours/png/`). |
| `sounds.zip` | **Required.** Every sound effect (`wav/aos`, `wav/ours`, `wav/menu`), without the radio voices. |
| `music.zip` | The game's soundtrack (optional). |
| `manifest.json` | Every pack with its size, SHA-256 and download URL. The client reads this first and checks each pack against it. |

The latest manifest is always at
`https://github.com/ngspades/assets/releases/latest/download/manifest.json`.

The game cannot start without `models`, `images` and `sounds` (`"required": true`
in the manifest): its first-run screen downloads them once. The music and the
voices are optional and arrive in the background.

Each release (`assets-v<N>`) is complete: a new one carries every pack, and the
manifest points at its own tag. Packs are plain ZIP files (stored, no
compression) holding the game's own virtual paths (`wav/voice/<lang>/<key>.ogg`,
`music/<track>.ogg`, `kv6/<model>.kv6`, `png/<picture>.png`, `wav/aos/<sound>.ogg`).

## Credits and licence

The packs mix the project's own work with third-party work under its own licence.
Who made what, and under which licence, is in [CREDITS.md](CREDITS.md), and how the
licences work together is in [LICENSE.md](LICENSE.md): **read both before reusing a file
outside the game** (some models allow no commercial use). The radio voices are synthesised
for the project. The game's code is GPL-3.0 ([ngspades/shoot-and-destroy](https://github.com/ngspades/shoot-and-destroy)).
