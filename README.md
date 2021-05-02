# Italian translation of [AwSW](https://store.steampowered.com/app/571880/Angels_with_Scaly_Wings/)

## Status

Currently working on the main chapters. Files done and up for review:

    common.rpy
    dv.rpy
    screens.rpy
    status.rpy
    help.rpy
    images.rpy
    script.rpy
    chapter1.rpy

**Note**: Having considered the developer's opinion, and given the precedent of Neo Cab, I decided to use [Inclusive Italian][1] to help referring to the player character with a neutral gender, which wouldn't be possible otherwise, if not by questionable adaptation of some of the script. I took the liberty of updating `Ardnas.otf` with a few accented vowels, which were needed anyways, and `TitilliumWeb-*.ttf` as well with the 'ə' symbol, needed for such a neutral gender. Also note that Inclusive Italian only applies to the actual in-game entries, i.e. practically from `chapter1.rpy` onwards.

**Note**: Throughout the script, I also decided to use the characters' variables, defined in `images.rpy`, in place of their names where possible, e.g. `Reza` → `[Rz]`.

[1]:https://italianoinclusivo.it/

## How can I participate?

1. To start, have a look at the pinned threads in the dedicated [Steam sub-forum][2]; there you'll also find the Italian translation thread.
2. You can contact me either through [Steam][3] or [Discord][4], so that I can add you as a collaborator and we can discuss how to divide up the tasks, but in the meantime feel free to poke around to get an idea or even start working on the translation on your own.
3. If you don't feel like working on the actual translation, you can still provide a precious contribution by reviewing the already translated files and report errors/suggest improvements, either by contacting me directly or by posting on the [discussions][5] here.
4. Should you need contextual reference while translating/reviewing, you can find the game's relevant source code in this [Onedrive folder][6], together with other stuff like images containing text that needs to be translated, too.

I should probably mention that this is intended to be an 'official' translation until proven otherwise, so if you want to give your contribution then you agree to transfer all rights on said translation to the developer (except maybe for the attribution right, but it remains at their discretion) so that it may be included in the game without legal issues.

[2]:https://steamcommunity.com/groups/awswtranslators/discussions/
[3]:https://steamcommunity.com/profiles/76561199007249524/
[4]:https://discord.com/users/638007218670796832/
[5]:https://github.com/sigmasaur/AwSW-it/discussions/
[6]:https://1drv.ms/u/s!AizmqTe1iFZrhYt-GIuCq4MLa9Ki2A?e=46qKmV

## Notes

The following are mostly to the benefit of the developer and translators.

### status.rpy

* At line 20-216: *good*/*bad* → *positive*/*negative*, as *bad* \[<i>cattivo</i>\] is more commonly understood as *mean* or *evil*. An alternative would be *friendly*/*hostile*.

### help.rpy

* At line 13: Used `space` tags in place of plain spaces to obtain a better alignment at a target resolution of 1920 x 1080, hope it's ok. There has to be a better way though.

### chapter1.rpy

* At line 385, 408: *to skip seen messages* → *to skip messages*, as it depends on the user's preference.
* At line 431: *were in consideration* → *had been in consideration*, as we're supposedly talking of the period before the solar flare.
* At line 436, 2837: Corrected colon to dot to preserve the capital letter.
* At line 463: *8* → *eight*, for elegance.
* At line 1358: Corrected number of dots from two to three.
* At line 2109, 2176, 2395, 2735, 3352: Slightly pruned to fit fewer lines.
* At line 2348-2352, 2389-2395, 2410-2415: Assumed the author's gender by necessity.
* At line 2737: Slightly adapted *isn't it fascinating* to add an obvious pun without loss of meaning.
* At line 2747: Slightly adapted to strengthen the pun, but it might still be too weak.
* At line 3068: *PDAs* → *PDA*.
* At line 3226: *RIP* → *rest in peace*, for elegance.
* At line 3352: Slightly adapted to match line 3344 so that they both fit line 3367, and precisely lines 3384/3391.
* At line 3609: Slightly adapted to preserve a pun.
