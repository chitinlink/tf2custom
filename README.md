TF2 Custom Files Backup
=======================

This is a backup and file history of my custom files for TF2.

## Installation

These files all go in `Team Fortress 2/tf/custom`.

1. Optionally clean up your TF2 settings by following [these instructions][mastercomfig-clean]
2. Follow the [mastercomfig installation instructions][mastercomfig]. You want to download:
    * Any preset (Some settings overriden by [modules.cfg](/configs/cfg/overrides/modules.cfg))
    * Null-Cancelling Movement
    * Flat Mouse
    * No Tutorial
3. Optionally follow the [mastercomfig OS optimization guide][mastercomfig-optimization]
4. Download and extract this repo
5. Download the files under ["External files"](#external-files)
6. You're done. Install a hud maybe?
    * [comfig huds](https://mastercomfig.com/huds/1/)
    * [TF2Huds.dev](https://tf2huds.dev/)

## Files

|                                   | Source                               | Description
| :-:                               | :-:                                  | :-
| [`configs`](/config/cfg/)         | Me                                   | TF2 configuration files authored by me. Note that I [use mastercomfig][mastercomfig-customization].
| [`hitsound`](/hitsound/sound/ui/) | Me                                   | My hit/kill sounds. Check the [folder](/hitsound/sound/ui/) for info.
| [`my_maps`](/my_maps/maps/)       | Me                                   | This is where I keep important maps. Check the [readme](/my_maps/maps) for more information.
| [`weapons`](/weapons/)            | [Mastercomfig][credits-mastercomfig] | Custom crosshairs, no shell ejection, no muzzle flash, no tracers, and reduced explosion effects.
| `nullsound.vpk`                   | Me                                   | Adds a file named `null.wav` to `sound/vo/`, fixing an annoying error message in tr_walkway_rc2.

## External files

Some of these are more important than the others, as you can probably guess.

|                              | Source                       | Description
| :-:                          | :-:                          | :-
| Conscientious Objector Fix   | [Gamebanana][source-sign]    | Fixes the sign to be easier to see.
| Team Colored Blueprints      | [Gamebanana][source-bp]      | Colors Engineer blueprints according to your team color.
| Halloween Festive Sapper     | [Gamebanana][source-sapper]  | Halloween-themed skin for the Festive Sapper.
| Bucket Lightwarp             | [Gamebanana][source-bucket]  | This is my favorite lightwarp for TF2.
| Plunger over Sun-on-a-Stick  | [Gamebanana][source-plunger] | Plunger skin for the Sun-on-a-Stick.
| Nintendo DS over PDA         | [Gamebanana][source-dspda]   | Nintendo DS skin for the PDA.
| Blunt over Concheror         | [Gamebanana][source-weed]    | Makes the Concheror horn into a weed blunt.
| Tara                         | [Gamebanana][source-tara]    | Replaces most miniguns with Twilight Sparkle.
| Quake axe over Escape Plan   | [Gamebanana][source-qaxe]    | Quake 1 Axe skin for the Escape Plan.

## Credits

* [mastercomfig][credits-mastercomfig]     — The performance config I use. Many many thanks for making this easier
* [Team Fortress Wiki][credits-tf2wiki]    — [Scripting basics][credits-tf2wiki-scripting], and a lot of other useful information
* [Valve Developer Community][credits-vdc] — a lot of technical information about TF2
* [TFTV Forums][credits-tftv]              — competitive and technical information about TF2, including the [no explosion smoke script][source-nosmoke]
* povohat                                  — [null-cancelling movement script][credits-nullcancel] <small>(Currently I use the mastercomfig VPK)</small>
* Jamien                                   — [regen.cfg](configs/cfg/regen.cfg), originally posted [here][credits-regen]
* Dr. Device                               — for the [auto-disguise script for spy][credits-autodisguise]
* CupOfTea/Rythyrix                        — for a bind that [activates uber ASAP][credits-instauber] on medic
* NiteCyper                                — for the [panic button][credits-panic], a bind that spins you real fast
* [Chris Down][credits-chrisdown]          — for his medic config which I have determined is the earliest example of the ["medic radar"][credits-chrisdown-radar]
* Nem                                      — for [GCFScape][credits-gcfscape], which helps reveal files hidden away in TF2's .vpk package files

## Attribution

If you use anything mine and post it elsewhere, a simple link to this page is enough credit.

[mastercomfig]:               https://docs.mastercomfig.com/latest/setup/install
[mastercomfig-clean]:         https://docs.mastercomfig.com/latest/setup/clean_up/
[mastercomfig-optimization]:  https://docs.mastercomfig.com/latest/os/
[mastercomfig-customization]: https://docs.mastercomfig.com/latest/customization/custom_configs/

[source-crosshairs]:          https://cfg.tf/tools/crosshairs/
[source-nosmoke]:             http://www.teamfortress.tv/25647/no-explosion-smoke-script
[source-bucket]:              https://gamebanana.com/mods/205374
[source-sign]:                https://gamebanana.com/mods/426147
[source-bp]:                  https://gamebanana.com/mods/434750
[source-sapper]:              https://gamebanana.com/mods/403966
[source-plunger]:             https://gamebanana.com/mods/317015
[source-dspda]:               https://gamebanana.com/mods/479185
[source-weed]:                https://gamebanana.com/mods/475545
[source-tara]:                https://gamebanana.com/mods/404105
[source-qaxe]:                https://gamebanana.com/mods/205029

[credits-tf2wiki]:            https://wiki.teamfortress.com/
[credits-tf2wiki-scripting]:  https://wiki.teamfortress.com/wiki/Scripting
[credits-vdc]:                https://developer.valvesoftware.com/
[credits-tftv]:               https://www.teamfortress.tv/forums
[credits-mastercomfig]:       https://mastercomfig.com
[credits-nullcancel]:         https://web.archive.org/web/20191124005113/http://ozfortress.com/showpost.php?p=624355
[credits-regen]:              https://web.archive.org/web/20130313024621/http://forums.tf2jump.com/index.php?topic=566.0
[credits-autodisguise]:       https://web.archive.org/web/20150404074844/http://tf2wiki.net/wiki/spy_scripts#Toggle_Auto_Disguise_on_attack
[credits-instauber]:          https://web.archive.org/web/20150321060517/http://tf2wiki.net/wiki/Medic_scripts#InstaUber
[credits-panic]:              https://web.archive.org/web/20150327135717/http://tf2wiki.net:80/wiki/Pyro_scripts#Pyro_Panic_Button
[credits-chrisdown]:          https://chrisdown.name/tf2/
[credits-chrisdown-radar]:    https://github.com/tf2configs/tf2configs/blob/master/medic#L42
[credits-gcfscape]:           https://nemstools.github.io/pages/GCFScape.html
[credits-gcfscape-dl]:        https://nemstools.github.io/pages/GCFScape-Download.html
