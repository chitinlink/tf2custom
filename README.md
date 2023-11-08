tf2-backup
==========

This is a backup of my custom files for TF2. Last updated November 2023 (mastercomfig 9.10.2)

## Installation

These files all go in `Team Fortress 2/tf/custom`.

1. Optionally clean up your TF2 settings by following [these instructions][mastercomfig-clean]
2. Follow the [mastercomfig installation instructions][mastercomfig]. You want to download:
    * A preset
    * Null-Cancelling Movement
    * Flat Mouse
    * No Tutorial
3. Optionally follow the [mastercomfig OS optimization guide][mastercomfig-optimization]
4. Download and extract this repo
5. Download the files under ["External files"](#external-files)

## Files

|                 | Source                                       | Description
| :-:             | :-:                                          | :-
| `configs`       | Me                                           | TF2 configuration files authored by me.
| `hitsound`      | Me                                           | My hit/kill sounds. Check the [folder](/hitsound/sound/ui/) for info
| `my_maps`       | Me                                           | This is where I keep important maps. Check the [readme](/my_maps/maps) for more information.
| `nullsound.vpk` | Me                                           | Adds a file named `null.wav` to `sound/vo/`, fixing an annoying error message in tr_walkway_rc2
| `crosshairs`    | [CFG.tf][source-crosshairs]                  | Weapon-specific crosshairs.
| `nosmoke.vpk`   | [Teamfortress.tv][source-nosmoke] (original) | Switches the rocket explosion effect to the sapper destruction effect for less clutter. Does not work with the Cow Mangler.

## External files 

|                              | Source                      | Description
| :-:                          | :-:                         | :-
| A Simple Critical Hit Effect | [Gamebanana][source-crit]   | Changes the critical hit text from "CRITICAL HIT!!!" to "CRIT!"
| Bucket Lightwarp             | [Gamebanana][source-bucket] | This is my favorite lightwarp for TF2.

## Credits

* [Team Fortress Wiki][credits-tf2wiki]                        — [Scripting basics][credits-tf2wiki-scripting], and a lot of other useful information
* [Valve Developer Community][credits-vdc]                     — a lot of technical information about TF2
* [mastercomfig][credits-mastercomfig]                         — The performance config I use. Many many thanks for making this easier
* povohat                                                      — [null-cancelling movement script][credits-nullcancel] <small>(Currently I use the mastercomfig VPK)</small>
* Jamien                                                       — [regen.cfg](configs/cfg/regen.cfg), originally posted [here][credits-regen]
* Dr. Device                                                   — for the [auto-disguise script for spy][credits-autodisguise]
* CupOfTea/Rythyrix                                            — for a bind that [activates uber ASAP][credits-instauber] on medic
* NiteCyper                                                    — for the [panic button][credits-panic], a bind that spins you real fast
* [Chris Down][credits-chrisdown]                              — for his medic config which I have determined is the earliest example of the ["medic radar"][credits-chrisdown-radar]
* Nem                                                          — for [GCFScape][credits-gcfscape] ([Download][credits-gcfscape-dl]), which helps reveal files hidden away in TF2's .vpk package files

## Attribution

If you use anything mine and post it elsewhere, a simple link to this page is enough credit.

[mastercomfig]:              https://docs.mastercomfig.com/latest/setup/install/
[mastercomfig-clean]:        https://docs.mastercomfig.com/latest/setup/clean_up/
[mastercomfig-optimization]: https://docs.mastercomfig.com/latest/os/

[source-nosmoke]:            http://www.teamfortress.tv/25647/no-explosion-smoke-script
[source-bucket]:             https://gamebanana.com/skins/145214
[source-crit]:               https://gamebanana.com/effects/4759
[source-crosshairs]:         https://cfg.tf/tools/crosshairs/
[source-uvisfix]:            https://github.com/agrastiOs/Ultimate-TF2-Visual-Fix-Pack

[credits-tf2wiki]:           https://wiki.teamfortress.com/
[credits-tf2wiki-scripting]: https://wiki.teamfortress.com/wiki/Scripting
[credits-vdc]:               https://developer.valvesoftware.com/
[credits-mastercomfig]:      https://mastercomfig.com
[credits-nullcancel]:        https://web.archive.org/web/20191124005113/http://ozfortress.com/showpost.php?p=624355
[credits-regen]:             https://web.archive.org/web/20130313024621/http://forums.tf2jump.com/index.php?topic=566.0
[credits-autodisguise]:      https://web.archive.org/web/20150404074844/http://tf2wiki.net/wiki/spy_scripts#Toggle_Auto_Disguise_on_attack
[credits-instauber]:         https://web.archive.org/web/20150321060517/http://tf2wiki.net/wiki/Medic_scripts#InstaUber
[credits-panic]:             https://web.archive.org/web/20150327135717/http://tf2wiki.net:80/wiki/Pyro_scripts#Pyro_Panic_Button
[credits-chrisdown]:         https://chrisdown.name/tf2/
[credits-chrisdown-radar]:   https://github.com/tf2configs/tf2configs/blob/master/medic#L42
[credits-gcfscape]:          https://nemstools.github.io/pages/GCFScape.html
[credits-gcfscape-dl]:       https://nemstools.github.io/pages/GCFScape-Download.html
