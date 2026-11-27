# Credits

Everything the downloadable packs of **Shoot and Destroy** contain, and who made it.
The packs are the release assets of this repository (see [README.md](README.md)), the
way the licence of each part works is in [LICENSE.md](LICENSE.md).

Paths below are the files' paths **inside the packs** (the game's own virtual paths).
The tables are the ones the project keeps with its source (its `CREDITS.md`), cut to what the
packs hold. Mentions of `tools/...` are the scripts in the project's source that make a file.

| Pack | Holds | Credited below |
| --- | --- | --- |
| `models.zip` | `kv6/`, `ours/kv6/`, `menu/Raindance.ngmap` | the OpenSpades free pack, GameBanana, made for this game |
| `images.zip` | `png/`, `ours/png/` | Kenney, game-icons.net, the flags atlas, GameBanana, made for this game |
| `sounds.zip` | `wav/aos/`, `wav/ours/`, `wav/menu/` | the OpenSpades free pack, GameBanana, made for this game |
| `music.zip` | `music/*.ogg` | Suno |
| `voice-<lang>.zip` | `wav/voice/` | the radio voices |

## The flags atlas

`png/ui/flags.png` (the scoreboard's flags) is BetterSpades'
(the project this client is forked from, credited in README.md).

## Board game icons and the crosshair (Kenney, CC0)

The maps' base and intel icons, the pings' and quick chat's markers (sword,
shield, wall, mine, fire, bow, flag, gate, skull, a flag for a plain ping),
the king of the hill's crown and the crosshair are from Kenney's
[Board Game Icons](https://kenney.nl/assets/board-game-icons) 1.1 and
[Crosshair Pack](https://kenney.nl/assets/crosshair-pack) (`crosshair-081`),
Creative Commons Zero (public domain, no credit needed; given anyway), made
into the game's files by `tools/make_board_icons.py`.

## Icons from game-icons.net (CC BY 3.0)

The GUI and HUD icons (ammo, health, the minimap's and the markers' pictures,
arrows, the check, the menus' small icons) are glyphs of https://game-icons.net,
Creative Commons Attribution 3.0 (https://creativecommons.org/licenses/by/3.0/),
rendered white with a dark outline by `tools/make_gameicons.py` (the frames,
the knob, the joystick's base, the menu's tile and the medic's cross are
drawn there, no source). Authors and icons used:

- Delapouite: brick-wall (https://game-icons.net/1x1/delapouite/brick-wall.html)
- Delapouite: briefcase (https://game-icons.net/1x1/delapouite/briefcase.html)
- Delapouite: camping-tent (https://game-icons.net/1x1/delapouite/camping-tent.html)
- Delapouite: cave-entrance (https://game-icons.net/1x1/delapouite/cave-entrance.html)
- Delapouite: check-mark (https://game-icons.net/1x1/delapouite/check-mark.html)
- Delapouite: cube (https://game-icons.net/1x1/delapouite/cube.html)
- Delapouite: dynamite (https://game-icons.net/1x1/delapouite/dynamite.html)
- Delapouite: entry-door (https://game-icons.net/1x1/delapouite/entry-door.html)
- Delapouite: first-aid-kit (https://game-icons.net/1x1/delapouite/first-aid-kit.html)
- Delapouite: flag-objective (https://game-icons.net/1x1/delapouite/flag-objective.html)
- Delapouite: machine-gun-magazine (https://game-icons.net/1x1/delapouite/machine-gun-magazine.html)
- Delapouite: person (https://game-icons.net/1x1/delapouite/person.html)
- Delapouite: plain-arrow (https://game-icons.net/1x1/delapouite/plain-arrow.html)
- Delapouite: shotgun-rounds (https://game-icons.net/1x1/delapouite/shotgun-rounds.html)
- Delapouite: walkie-talkie (https://game-icons.net/1x1/delapouite/walkie-talkie.html)
- Lorc: bullets (https://game-icons.net/1x1/lorc/bullets.html)
- Lorc: crossed-swords (https://game-icons.net/1x1/lorc/crossed-swords.html)
- Lorc: cycle (https://game-icons.net/1x1/lorc/cycle.html)
- Lorc: grenade (https://game-icons.net/1x1/lorc/grenade.html)
- Lorc: hazard-sign (https://game-icons.net/1x1/lorc/hazard-sign.html)
- Lorc: hourglass (https://game-icons.net/1x1/lorc/hourglass.html)
- Lorc: land-mine (https://game-icons.net/1x1/lorc/land-mine.html)
- sbed: shield (https://game-icons.net/1x1/sbed/shield.html)
- Skoll: machine-gun (https://game-icons.net/1x1/skoll/machine-gun.html)

## Models from the OpenSpades free asset pack (CC0)

The block, grenade and spade, the tent, the SMG, the shotgun and the three
casings are the CC0
models of [openspades-free-pak](https://github.com/DeathByDenim/openspades-free-pak)
(commit 1e6b287, April 2023): "all models have been created from scratch using
Voxelshop by Jarno van der Kolk and are licensed under CC0" (its
`License/Credits-pak001-Free.md`). Packaged by DeathByDenim. They are in
`kv6/` under the names the game loads, voxel for
voxel; `tools/adopt_free_models.py` only moves each pivot to where the
replaced model's stood, so the game places them as before:

| Game file | The pack's file |
| --- | --- |
| `block`, `grenade` (tinted green here: the pack's is grey), `spade` | `Weapons/Block/Block`, `Weapons/Grenade/Grenade`, `Weapons/Spade/Spade` |
| `cp` (the tent) | `MapObjects/CheckPoint` |
| `smg`, `shotgun` | `Weapons/SMG/Weapon`, `Weapons/Shotgun/Weapon` |
| `semicasing`, `smgcasing`, `shotguncasing` | `Weapons/Rifle/Casing`, `Weapons/SMG/Casing`, `Weapons/Shotgun/Casing` |

The supply crates (`crate_ammo.kv6`, `crate_health.kv6`) and the parachute are
drawn by us (`tools/make_crates.py`).
The tracers (`semitracer`, `smgtracer`, `shotguntracer`) and the machine gun with
its tripod (`mg`, `mgbase`) are drawn by us too (`tools/make_tracers.py`,
`tools/make_mg.py`): no source art.

## Sounds from the OpenSpades free asset pack

Most of the game's sounds (`wav/aos/`) are made from
the sounds of [openspades-free-pak](https://github.com/DeathByDenim/openspades-free-pak)
(commit 1e6b287): "all sounds have been obtained from Public Domain resources"
(its `License/Credits-pak001-Free.md`), CC0 or **CC-BY, which asks for the
credit below**. Each is decoded, mixed to mono, brought to the level of the
sound it replaces and encoded as OGG Vorbis by `tools/free_sounds/run.sh`
(`map.txt` says which file makes which sound).

| Game file | The pack's file (`Sounds/`) | Licence | Credit | Source |
| --- | --- | --- | --- | --- |
| `wav/aos/bounce.ogg` | `Weapons/Grenade/Bounce` | CC-BY 3.0 | dklon | <https://opengameart.org/content/body-hitting-ground> |
| `wav/aos/build.ogg` | `Weapons/Block/Build` | CC0 | SieuAmThanh | <https://freesound.org/people/SieuAmThanh/sounds/530812/> |
| `wav/aos/cock.ogg` | `Weapons/Shotgun/Cock` | CC-BY 3.0 | Mike Koenig (Soundbible) | <https://opengameart.org/content/shotgun-shoot-reload> |
| `wav/aos/debris.ogg` | `Weapons/Grenade/Debris` | CC0 | Blender Foundation | <https://opengameart.org/content/tree-falling-yo-frankie> |
| `wav/aos/empty.ogg` | `Weapons/DryFire` | CC0 | rubberduck | <https://opengameart.org/content/100-cc0-metal-and-wood-sfx> |
| `wav/aos/explode.ogg` | `Weapons/Grenade/Explode1` | CC-BY 3.0 | Michel Baradari | <https://opengameart.org/content/2-high-quality-explosions> |
| `wav/aos/fallhurt.ogg` | `Player/FallHurt` | CC-BY 4.0 | Hansjörg Malthaner | <https://opengameart.org/content/cracking-sounds> |
| `wav/aos/footstep1.ogg` | `Player/Footstep1` | CC-BY 3.0 | congusbongus | <https://opengameart.org/content/footsteps-on-different-surfaces> |
| `wav/aos/footstep2.ogg` | `Player/Footstep2` | CC-BY 3.0 | congusbongus | <https://opengameart.org/content/footsteps-on-different-surfaces> |
| `wav/aos/footstep3.ogg` | `Player/Footstep3` | CC-BY 3.0 | congusbongus | <https://opengameart.org/content/footsteps-on-different-surfaces> |
| `wav/aos/footstep4.ogg` | `Player/Footstep4` | CC-BY 3.0 | congusbongus | <https://opengameart.org/content/footsteps-on-different-surfaces> |
| `wav/aos/grenadebounce.ogg` | `Weapons/Grenade/Bounce` | CC-BY 3.0 | dklon | <https://opengameart.org/content/body-hitting-ground> |
| `wav/aos/hitground.ogg` | `Weapons/Impacts/Block` | CC0 | rubberduck | <https://opengameart.org/content/100-cc0-metal-and-wood-sfx> |
| `wav/aos/hitplayer.ogg` | `Weapons/Impacts/Flesh1` | CC0 | magnuswaker | <https://freesound.org/people/magnuswaker/sounds/522091/> |
| `wav/aos/impact.ogg` | `Weapons/Impacts/Ricochet1` | CC0 | cedarstudios | <https://freesound.org/people/cedarstudios/sounds/148827/> |
| `wav/aos/jump.ogg` | `Player/Jump` | CC-BY 3.0 | Vinrax | <https://opengameart.org/content/cloth-swing-sounds> |
| `wav/aos/land.ogg` | `Player/Land` | CC0 | MentalSanityOff | <https://opengameart.org/content/jump-landing-sound> |
| `wav/aos/lose.ogg` | `Feedback/Lose` | CC0 | Umplix | <https://opengameart.org/content/game-over-8> |
| `wav/aos/pin.ogg` | `Weapons/Grenade/Fire` | CC0 | OwlishMedia | <https://opengameart.org/content/87-clickety-clips> |
| `wav/aos/semireload.ogg` | `Weapons/Rifle/Reload` | CC0 | zer0_sol | <https://opengameart.org/content/handgun-reload-sound-effect> |
| `wav/aos/semishoot.ogg` | `Weapons/Rifle/Fire` | CC0 | Ben Jaszczak, et al. | <https://opengameart.org/content/the-free-firearm-sound-library> |
| `wav/aos/shotgunreload.ogg` | `Weapons/Shotgun/Reload` | CC-BY 3.0 | Mike Koenig (Soundbible) | <https://opengameart.org/content/shotgun-shoot-reload> |
| `wav/aos/shotgunshoot.ogg` | `Weapons/Shotgun/Fire` | CC-BY 3.0 | Mike Koenig (Soundbible) | <https://opengameart.org/content/shotgun-shoot-reload> |
| `wav/aos/smgreload.ogg` | `Weapons/SMG/Reload` | CC0 | LFA | <https://opengameart.org/content/equipment-clicks-iii> |
| `wav/aos/smgshoot.ogg` | `Weapons/SMG/V2Local1` | CC0 | Ben Jaszczak, et al. | <https://opengameart.org/content/the-free-firearm-sound-library> |
| `wav/aos/switch.ogg` | `Weapons/Switch` | CC0 | LFA | <https://opengameart.org/content/equipment-clicks-iii> |
| `wav/aos/wade1.ogg` | `Player/Wade1` | CC-BY 3.0 | Motion_S | <https://freesound.org/people/Motion_S/sounds/221764/> |
| `wav/aos/wade2.ogg` | `Player/Wade2` | CC-BY 3.0 | Motion_S | <https://freesound.org/people/Motion_S/sounds/221764/> |
| `wav/aos/wade3.ogg` | `Player/Wade3` | CC-BY 3.0 | Motion_S | <https://freesound.org/people/Motion_S/sounds/221764/> |
| `wav/aos/wade4.ogg` | `Player/Wade4` | CC-BY 3.0 | Motion_S | <https://freesound.org/people/Motion_S/sounds/221764/> |
| `wav/aos/waterexplode.ogg` | `Weapons/Grenade/WaterExplode` | CC0 | qubodup | <https://opengameart.org/content/tiny-naval-battle-sounds-set> |
| `wav/aos/waterjump.ogg` | `Player/WaterJump` | CC-BY 3.0 | Michel Baradari | <https://opengameart.org/content/water-splashes> |
| `wav/aos/waterland.ogg` | `Player/WaterLand` | CC-BY 3.0 | Michel Baradari | <https://opengameart.org/content/water-splashes> |
| `wav/aos/whack.ogg` | `Weapons/Spade/HitPlayer` | CC0 | bart | <https://opengameart.org/content/33-metal-clang-sounds-cast-iron-pans> |
| `wav/aos/woosh.ogg` | `Weapons/Spade/Miss` | CC0 | Iwan Gabovitch | <https://opengameart.org/content/swish-bamboo-stick-weapon-swhoshes> |

## Sounds made for this game, the second set

`beep1`, `beep2`, `chat`, `death`, `horn`, `pickup`, `intro`, `chopper`,
`chopper1` and `choppernear` (`wav/aos/`) are synthesised by
`tools/make_sounds_aos.py` from the instruments of `make_sounds_ng.py`: no
recording and no other game's sound.

## Music (Suno)

`music/menu.ogg`, `music/loading.ogg` and `music/victory.ogg` were generated
with Suno (model v6, created on 2026-11-15: ids
`c84e9b9c-8ce8-4399-b5ae-480b3753f9ad`, `cc236878-f7c5-4bf7-80c0-d064083dd51e`
and `91976ebc-00b6-4b79-b876-16958813b051`), then edited here: levels set,
the menu's and the victory's ends faded out (they were cut mid-music), OGG
Vorbis, stereo, 44.1 kHz. The files as downloaded, with Suno's provenance
metadata (C2PA), are kept by the project outside the repository
(`original-assets/suno/`). The rights come from Suno's terms of the date and
the plan the account was on when they were created and downloaded (Suno's
terms of September 2026: commercial use needs a paid plan and a permitted
download): **plan: to be filled in by the account's owner.** Steam asks to be
told about AI generated music; so may other stores.

## Models from GameBanana

These voxel models were made by Ace of Spades modders and published on
[GameBanana](https://gamebanana.com/games/4637). They are in
`` as they came in the downloaded archive, renamed
to the part names the game loads.

| Used as | Files in `` | Mod (GameBanana) | Credits |
| --- | --- | --- | --- |
| Commando's body, and the default body of every player (`kv6/player{head,torso,torsoc,arms,leg,legc}.kv6` are copies of these) | `kv6/commando/*.kv6` | [Commado Deuce](https://gamebanana.com/mods/170835) (2013) | Ascent (model and texture), [Foxxy.](https://gamebanana.com/members/1285881) (submitter) |
| Marksman's body | `kv6/marksman/*.kv6` | [Marksman Redux](https://gamebanana.com/mods/170857) (2013) | Ascent (model and texture), [Foxxy.](https://gamebanana.com/members/1285881) (submitter) |
| Miner's body | `kv6/miner/*.kv6` | [Miner Deuce](https://gamebanana.com/mods/170805) (2013) | Ascent (model and texture), an unnamed author (dead model), [Foxxy.](https://gamebanana.com/members/1285881) (submitter) |
| Arena suits (rifle, SMG, shotgun) | `kv6/weaponskin/<gun>/*.kv6` | [Special Action Force](https://gamebanana.com/mods/170862) (2018), its CAMO variant: Assault for the rifle, Scout for the SMG, Shotgun for the shotgun | [Foxxy.](https://gamebanana.com/members/1285881) (model), [DaLemon](https://gamebanana.com/members/1456656) (screenshots) |
| Commando's rocket launcher | `kv6/rocketlauncher.kv6` | [COMMANDO's RPG](https://gamebanana.com/mods/170398) (2013), the "No Arms" model | [Death_AoS](https://gamebanana.com/members/1331382) (modeler) |
| Sentry gun | `kv6/sentry/base.kv6`, `kv6/sentry/head.kv6` | TF2 Lv1 Sentry for Ace of Spades (2014), cut in two by `tools/make_sentry_tf2.py` | 1shot1kill |
| The classes' melee tool (every class but the Miner, who keeps the spade) | `kv6/pickaxe.kv6` | [Pickaxe](https://gamebanana.com/mods/171019) (`pickaxe_4.rar`, 2012, its `spade.kv6`; CC BY-NC-ND 4.0) | MZ4 (model), [Foxxy.](https://gamebanana.com/members/1285881) (submitter) |
| The corpse of every player but a zombie (a tombstone in the team's colour) | `kv6/playerdead.kv6` | a `playerdead.kv6` from the [Build and Shoot forums](https://www.buildandshoot.com/forums/viewtopic.php?f=11&t=13788) (`playerdead.rar`, 2016) | Kuunikal |
| The intel (CTF's flag) | `kv6/intel.kv6` | [Tf2-Like Intel](https://gamebanana.com/mods/171053) (`tf2-like_intel_2.rar`, 2014; CC BY-NC-ND 4.0) | DeadFly (model), [NeoManiac](https://gamebanana.com/members/1354343) (submitter) |
| Marksman's rifle and its scope | `kv6/sniper.kv6`, `png/sniper.png` | [SNIPER AWP](https://gamebanana.com/mods/171101) (`sinper.rar`, 2013; it has no sound) | [NEGAS](https://gamebanana.com/members/1358981) |
| The revolver, a sidearm the classes share | `kv6/revolver.kv6`, `png/revolver.png`, `wav/ours/revolvershoot.wav`, `wav/ours/revolverreload.wav` | [Freeman Tech Double Action Super](https://gamebanana.com/mods/170279) (2013), its .357 Magnum version | [The Freeman](https://gamebanana.com/members/1293412) (models, iron sights), teh strelok (reload and .357 firing sounds), DJPON3 (.38 firing sounds) |
| The rifle (the Carbine Rifle), the three guns' sights and the Marksman's sniper's shot and reload (the SMG and shotgun models are the free pack's, above; the TF2 ones are kept in `ours/kv6/`, not loaded) | `kv6/semi.kv6`, `png/{semi,smg,shotgun}.png`, `wav/ours/{snipershoot,sniperreload}.wav` | TF2 Beta Weapons (GameBanana, Ace of Spades mods): the Carbine Rifle, the Sawnoff Shotgun, the SMG's Unsupressed variant, and the Concept Sniper Rifle's two sounds (`semishoot.wav`, `semireload.wav` there) | The Freeman (models, iron sights), Brenex (sights), Navaro and Mateoski (sounds), after Valve Software's Team Fortress 2 concept art |

The class skins' and the arena suits' own `playerdead.kv6` are not used:
every body falls as the one tombstone above.

The zombie's body (`kv6/zombie/*.kv6`: head, torso, leg and arms) is made
for this game, by us: the idea came from the classic Ace of Spades zombie
skins, the model is our own remake. `tools/make_zombie_skin.py` recolours
it, takes the uniform off it, tears the clothes, and cuts and joins the
arms.

## Made for this game

The sounds in `wav/ours/` made by `tools/make_sounds.py` (the jetpack, the weather, the rocket, the
sentry, the drill, casings, stingers, the map), `tools/make_sounds_ng.py`
(the feedback events: hit, headshot, kill, aim, screenshot) and
`tools/make_sounds_ps2.py` (the zombie's claw and groan), the menus' sounds
in `wav/menu/` made by `tools/make_sounds_x360.py`, the icons made
by `tools/make_icons.py` and `tools/make_app_icons.py`, and the Rocketeer's
suit, built in code from the default body (`client/src/model.c`). The kill
feed icons (`png/killfeed/`) come from OpenSpades' `ngspades` branch (see
README.md).

The game's logo, `png/splash_logo.png` (the home page's and the Discord art's),
is the NEXGEN SPADES logo (2026-11-26): the lettering is drawn from the outlines
of two fonts, Edo by Vic Fieger (NEXGEN) and Pic0 by Domenico Mazza (SPADES), and
everything else (the block-built letters, the extrusion, the flying blocks and the
block carrying the spade) is drawn by a script in the private `ngspades/brand`
repository, which also holds the variants, the social media art and the
READMEs' banners. The fonts are not shipped; the owner decided to use them in
the logo.

## The radio voices

The announcer's lines (`wav/voice/<key>.ogg` for English, `wav/voice/<folder>/<key>.ogg`
for the other fifteen languages: pt-BR, es, ru, de, tr, pl, it, fr, nl, da, sv, fi, no, ms,
sw) are **synthesised** for this game, by the project's own scripts (`tools/make_voices*.py`
in the game's repository), and are not recordings of a person.

- The model is [Chatterbox Multilingual](https://github.com/resemble-ai/chatterbox)
  by Resemble AI (MIT licence), run through MLX on a Mac. Brazilian Portuguese uses the
  `ResembleAI/Chatterbox-Multilingual-pt-br` model. **Check each model card's licence when
  you reuse the model**: it is named here, not re-licensed.
- Every language and variant is one speaker, "the commander". Its reference voice and the
  golden sample (`gen_enemy_one_to_win`) come from clips generated with Google Flow; the
  rights are those of Google Flow's terms of the date.
- The wordings are ours. Each take is filtered into a radio sound (band-pass,
  compression, squelch, static) and encoded as 16 kHz mono OGG Vorbis.

## Not in the packs

The game's fonts, its translations and its configuration stay in the game's own files (the
"base"), not here, and are credited in the game's CREDITS.md. The NEXGEN SPADES logo
(`png/splash_logo.png`) is lettered from the outlines of two fonts, Edo by Vic Fieger and
Pic0 by Domenico Mazza: the fonts themselves are not shipped.
