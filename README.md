# Italian translation of [AwSW](https://store.steampowered.com/app/571880/Angels_with_Scaly_Wings/)

## Status

Currently working on `Adine`'s sections. Files done and up for review:

    common.rpy
    dv.rpy
    
    screens.rpy
    status.rpy
    help.rpy
    images.rpy
    script.rpy

    chapter1.rpy
    chapter2.rpy
    chapter3.rpy
    chapter4.rpy
    chapter5.rpy
    chapter5evilending.rpy

    adine1.rpy

A few remarks:

* Having considered the developer's opinion, and given the precedent of game Neo Cab, I opted to use [Inclusive Italian][1] to help addressing the player character with a neutral gender, which wouldn't be feasible otherwise, if not by questionable adaptation of some of the script. I took the liberty of updating `Ardnas.otf` with a few accented vowels, which were needed anyways, and `TitilliumWeb-*.ttf` as well with `ə` and `ɜ`, needed for such a neutral gender; they were all easily obtained from other symbols. Note that Inclusive Italian only applies to the actual in-game entries, i.e. practically from `chapter1.rpy` onwards.<br>On the other hand the `System`, as well as the `Administrator` in `chapter4.rpy`, are currently addressed with the male form for lack of a better alternative, but this is still subject to change.

* I decided to use the characters' variables, which are defined in `images.rpy`, in place of their plain names where possible throughout the script, e.g. `Reza` → `[Rz]`. Also, `Emera` is addressed by any other character with formal pronouns, as well as `Sebastian` by `Adine` and `Lorem`, and `Adine` by `Sebastian` in those few circumstances.

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
* At line 431: Corrected simple past tense *were under consideration* to past perfect, as we're supposedly talking of the period before the solar flare; the current translation is nonetheless rather flexible in this sense.
* At line 431, 452, 471, 648, 1640: Corrected simple dash to em-dash.
* At line 436, 2837: Corrected colon to dot to preserve the uppercase letter.
* At line 463: *8* → *eight*, for elegance.
* At line 1084, 2109, 2176, 2753, 3118, 3352: Slightly pruned to fit fewer lines.
* At line 1358: Corrected number of dots from two to three.
* At line 1751: Used if-statement to further distinguish between food types by linguistic necessity.
* At line 1861: *or even* → *such as*, as bacteria are unicellular.
* At line 2348-2352, 2389-2395, 2410-2415: Assumed the authors' gender by linguistic necessity.
* At line 2351, 2395: Consider changing *dragon* in accordance with line 472, as dragons probably wouldn't refer to themselves as such, at least in the literature.
* At line 2728, 2747, 3609: Adapted to preserve a pun; reverse translation:
  * At line 2728: *I'd have a foot on the ground.* (Can also be read as *I'd have a pied-à-terre.*)
  * At line 2747: *There's a lot of them.*
  * At line 3609: *Achoo- I mean, excellent.*
* At line 2737: Slightly adapted *isn't it fascinating* to add an obvious pun without loss of meaning.
* At line 2738, 2934: Corrected uppercase letter to lowercase.
* At line 3068: *PDAs* → *PDA*.
* At line 3226: The actual translation in DE:HR would be just *condolences*; consider unfolding *RIP*.
* At line 3712: Assumed *sorry* is addressed to `Sebastian`.

### chapter2.rpy

* At line 523, 1278, 3228, 3312, 3712, 3792, 4226: Corrected simple dash to em-dash.
* At line 572, 958, 1056, 1816, 1826, 1830: Corrected uppercase letter to lowercase.
* At line 3510, 3680: Corrected colon to dot to preserve the uppercase letter.
* At line 791: Used if-statement in place of lines 797/801. Using those lines produces either a bad translation, or a good adaptation but hard to pick up again at line 916, if not with another adaptation. (Note that the user should be aware enough that the intended concordance of genders is syntactic, as semantic concordance of *that* \[<i>quell-</i>\] with the subject would have been rendered with the inclusive gender instead \[<i>-ə</i>\].)
* At line 1036, 1148, 3771: Slightly pruned to fit fewer lines.
* At line 1191, 1221: Added parentheses to match resp. lines 4093, 4141 of `chapter1.rpy`.
* At line 1607: Added brackets to match line 2301 of `chapter1.rpy`.
* At line 1623: *melon bread* → *melon-flavored bread*, to preserve the pun by linguistic necessity.
* At line 2423, 3824: Adapted to preserve a pun; reverse translation:
  * At line 2423: A playful exclamation of surprise.
  * At line 3824: This one just had to be changed completely: *You'd be a perfect dragon investigator... short of a tail.* Any improvement is welcome. (Note that in theory, `Zhong`'s name might still be unknown to the user.)

### chapter3.rpy

* At line 823, 825, 835, 847, 882, 988, 996, 1219, 1278, 1139, 1478: *PDAs* → *PDA*.
* At line 849, 884: Split in multiple parts to fit fewer lines.
* At line 860, 2439: Corrected uppercase letter to lowercase.
* At line 1264-1266: Corrected future tenses to conditional, as we're supposedly talking of the yet speculative case where the player character doesn't go through the portal as per `Emera`'s resolve.
* At line 1346: *10* → *ten*, for elegance.
* At line 1346: *Hiroshima* → *atomic*, for elegance; moreover, the resulting expression reads better without any real loss of meaning, not to mention that we're supposedly addressing `Bryce` and `Emera`, who can't possibly know about it.
* At line 1383: *15%* → *fifteen percent*, for elegance.
* At line 1476, 3366, 4338: Corrected simple dash to em-dash.
* At line 2144: *inch* → *centimeter*, as Italians prefer the metric system and the resulting expression reads better.
* At line 2457: Corrected colon to dot to preserve the uppercase letter.
* At line 2467: *list of* → *note with*, to avoid repeating too many same prepositions and to match lines 713, 1149 of `chapter1.rpy`.
* At line 3098: Slightly pruned to fit fewer lines.
* At line 3639: *pockets* → *pocket*, to match line 2312.
* At line 3751: Adapted to preserve a pun; reverse translation: *I'm stunned.*
* At line 4046-4064: Note that the larger, orange dragon should be a female, as mentioned by `Zhong` at line 3907; the current translation doesn't use this information, nonetheless.

### chapter4.rpy

* At line 762, 922: Corrected uppercase letter to lowercase.
* At line 898, 2716, 3560, 3790, 4369, 4436, 4472, 4478, 4592, 4628: Corrected simple dash to em-dash.
* At line 1094: Used if-statement to distinguish whether `Anna` survives or not, and corrected present tenses to simple past in the latter case.
* At line 1368-1736: The following is a simplified flow chart to help keeping track of which section spoken by the system refers to which case. `INV` is the number of investigation points on this run. **`CHEAT`**, **`SAVED`** are persistent variables starting resp. from `0`, `FALSE`. Note that **`CHEAT`** may jump from `0` to `2` but may never decrease, and **`SAVED`** may never fall back to `FALSE`.<details><summary></summary><p align="center">![bryce_death](bryce_death.png)</p></details>
  * At line 1676-1736: Note that these lines also trigger if `Bryce` was saved at least once after dying, then just died again and the user tries to cheat for the *first* time, even though apparently this is unintended behavior (see e.g. line 1696).
* At line 1708, 4592: Slightly pruned to fit fewer lines.
* At line 1812: Note that in theory, dragons don't know what a car is.
* At line 2035, 2836, 2873, 2909, 2946: *PDAs* → *PDA*.
* At line 2411: `Shake` function doesn't seem to trigger.
* At line 3285-3289, 3379-3383, 3438-3442, 3511-3515, 3742-3746: Adapted to preserve a pun; reverse translation: *Exceptional.*
* At line 3568, 3627, 3798, 3857: Assumed *who* is referred to `Adine`.
* At line 4345, 4353: *65* → *sixty-five*, for elegance.
* At line 4365: About *aligning \[the portals\] across the time axis*, note that `Izumi` would still have had to bypass the anti-time travel safeguards for her to be able to return, assuming the portals in the present were still operational.
* At line 4367: *that meant that* → *moreover*, as there's no real logical implication between line 4365 and this line.
* At line 4375, 4382: Corrected colon to dot to preserve the uppercase letter.
* At line 4432, 4614: *AI* → *artificial intelligence*, for elegance.
* At line 4462: *10km* → *ten kilometers*, for elegance.
* At line 4468, *75%* → *seventy-five percent*, for elegance.
* At line 4468-4472: Slightly adapted to exchange the two units, as Italians way prefer the metric system. Does this qualify as improper localization?
* At line 4500: Corrected *don't think that he would<s>n't</s> hesitate*.
* At line 4556: Split in multiple parts to fit fewer lines.
* At line 4556: *connected* → *linked*, to avoid repeating *the connection \[...\] is not connected*.

### chapter5.rpy

* At line 584, 913: Corrected simple dash to em-dash.
* At line 646: *inch* → *centimeter*; see line 2144 of `chapter4.rpy`.
* At line 913: Changed parentheses with brackets to match line 385 of `chapter1.rpy`.

### chapter5evilending.rpy

* At line 11, 19, 33, 71, 473, 545: Corrected simple dash to em-dash.
* At line 25: Corrected colon to dot to preserve the uppercase letter.
* At line 347, 371: *generators* → *generator*, to match lines 4520, 4590 of `chapter4.rpy`.
  * Note that *the building still having electricity* despite `Reza` having gotten its generator, which was supposed to be *also powering the portal*, is explained by `Reza` himself at line 449, revealing the presence of a backup. At the same line, however, `Reza` claims he *could even get the backup generator as well*, suggesting that the portal is really powered by other means. Whether this is truly the case is never addressed.
* At line 517, 845: Corrected uppercase letter to lowercase.
* At line 565: Assumed *it* is referred to *the solution* at line 563.
* At line 638: Consider adding parentheses to render the monologue a proper soliloquy.
* At line 733-741: *10* → *ten*, for elegance.

### adine1.rpy

* At line 39: *containers* → *container*, to match `cgadine2.png` and line 129.
* At line 61-67: Note that these lines also trigger if the user managed to save `Bryce` and returned the eggs to the hatchery, having already encountered `Adine` before the actual meeting.
* At line 286, 785: Corrected uppercase letter to lowercase.
* At line 307: Rendered *children* as *cubs*.
* At line 468, 520, 929: Corrected simple dash to em-dash.
