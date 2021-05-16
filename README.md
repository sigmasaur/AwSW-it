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
    chapter2.rpy

A few remarks:

* Having considered the developer's opinion, and given the precedent of game Neo Cab, I opted to use [Inclusive Italian][1] to help addressing the player character with a neutral gender, which wouldn't be feasible otherwise, if not by questionable adaptation of some of the script. I took the liberty of updating `Ardnas.otf` with a few accented vowels, which were needed anyways, and `TitilliumWeb-*.ttf` as well with `ə` and `ɜ`, needed for such a neutral gender; they were all easily obtained from other symbols. Note that Inclusive Italian only applies to the actual in-game entries, i.e. practically from `chapter1.rpy` onwards.

* I decided to use the characters' variables, which are defined in `images.rpy`, in place of their plain names where possible throughout the script, e.g. `Reza` → `[Rz]`. Also, `Emera` is addressed with formal pronouns.

* Sometimes, it can happen that a line matches exactly its translated counterpart. These lines don't get rendered correctly for some reason, and the only way I found to bypass the issue is to differentiate them by just putting a blank at the end.

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
* At line 431: *were in consideration* → *had been in consideration*, as we're supposedly talking of the period before the solar flare; the current translation is nonetheless rather flexible in this sense.
* At line 431, 452, 471, 648, 1640: Corrected simple dash to em-dash.
* At line 436, 2837: Corrected colon to dot to preserve the uppercase letter.
* At line 463: *8* → *eight*, for elegance.
* At line 1358: Corrected number of dots from two to three.
* At line 1751: Used if-statement to further distinguish between food types by linguistic necessity.
* At line 2348-2352, 2389-2395, 2410-2415: Assumed the authors' gender by linguistic necessity.
* At line 2728, 2747, 3609: Adapted to preserve a pun; reverse translation:
  * At line 2728: *I'd have a foot on the ground.* (Can also be read as *I'd have a pied-à-terre.*)
  * At line 2747: *There's a lot of them.*
  * At line 3609: *Achoo- I mean, excellent.*
* At line 2737: Slightly adapted *isn't it fascinating* to add an obvious pun without loss of meaning.
* At line 2753, 3352: Slightly pruned to fit fewer lines.
* At line 3068: *PDAs* → *PDA*.
* At line 3226: The actual translation in DE:HR would be just *condolences*; I'm still unsure whether to unfold *RIP* or not.

### chapter2.rpy

* At line 523, 1278, 3228, 3312, 3712, 3792, 4226: Corrected simple dash to em-dash.
* At line 572, 3510, 3680: Corrected colon to dot to preserve the uppercase letter.
* At line 791: Used if-statement in place of lines 797/801. Using those lines produces either a bad translation, or a good adaptation but hard to pick up again at line 916, if not with another adaptation. (Note that the user should be aware enough that the intended concordance of genders is syntactic, as semantic concordance of *that* \[<i>quell-</i>\] with the subject would have been rendered with the inclusive gender instead \[<i>-ə</i>\].)
* At line 958, 1056, 1816, 1826, 1830: Corrected uppercase letter to lowercase.
* At line 1036, 1148: Slightly pruned to fit fewer lines.
* At line 1191, 1221: Added parentheses to match resp. lines 4093, 4141 of `chapter1.rpy`.
* At line 1607: Added brackets to match line 2301 of `chapter1.rpy`.
* At line 1623: *melon bread* → *melon-flavored bread*, to preserve the pun by linguistic necessity.
* At line 2423, 3824: Adapted to preserve a pun; reverse translation:
  * At line 2423: A playful exclamation of surprise.
  * At line 3824: This one just had to be changed completely: *You'd be a perfect dragon investigator... short of a tail.* Any improvement is welcome. (Note that in theory, `Zhong`'s name might still be unknown to the user.)
