# ngspades/assets

Downloadable asset packs for **Shoot and Destroy** (the ngspades reference
client). The game downloads them at start-up; they are not meant to be fetched
by hand, but the files are public like everything else in this organization.

The repository holds no files of its own: **the packs are release assets**.

| Pack | What is in it |
| --- | --- |
| `voice-<lang>.zip` | The radio announcer's voice lines in one language (`en`, `pt-BR`, `es`, `ru`, `de`, `tr`, `pl`, `it`, `fr`, `nl`, `da`, `sv`, `fi`, `no`, `ms`, `sw`). |
| `music.zip` | The game's soundtrack. |
| `manifest.json` | Every pack with its size, SHA-256 and download URL. The client reads this first and checks each pack against it. |

The latest manifest is always at
`https://github.com/ngspades/assets/releases/latest/download/manifest.json`.

Each release (`assets-v<N>`) is complete: a new one carries every pack, and the
manifest points at its own tag. Packs are plain ZIP files (stored, no
compression) holding the game's own virtual paths (`wav/voice/<lang>/<key>.ogg`,
`music/<track>.ogg`).

## Credits and licence

The radio voices are synthesised for the project (see the game's CREDITS.md in
[ngspades/shoot-and-destroy](https://github.com/ngspades/shoot-and-destroy)).
The soundtrack is credited there as well. The game's code is GPL-3.0.
