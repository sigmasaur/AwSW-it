# Italian translation of [AwSW](https://store.steampowered.com/app/571880/Angels_with_Scaly_Wings/)

## Status

Currently working on `Bryce`'s sections. Files done and up for review:

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
    adine2.rpy
    adine3.rpy
    adine4.rpy
    adine5.rpy

    anna1.rpy
    anna2.rpy
    anna3.rpy
    anna4.rpy
    anna5.rpy

    bryce1.rpy
    bryce2.rpy

A few remarks:

* Having considered the developer's opinion, and given the precedent of game Neo Cab, I opted to use [Inclusive Italian][1] to help addressing the player character with a neutral gender, which wouldn't be feasible otherwise, if not by questionable adaptation of some of the script. I took the liberty of updating `Ardnas.otf` with a few accented vowels, which were needed anyways, and `TitilliumWeb-*.ttf` as well with `ə` and `ɜ`, needed for such a neutral gender; they were all easily obtained from other symbols. Note that Inclusive Italian only applies to the actual in-game entries, i.e. practically from `chapter1.rpy` onwards.<br>On the other hand the `System`, as well as the `Administrator` in `chapter4.rpy`, are currently addressed with the male form for lack of a better alternative, but this is still subject to change. Also, `Emera` is addressed by all other characters with formal pronouns, as well as `Anna` by `Adine`, `Sebastian` by `Adine` and `Lorem`, and `Adine` by `Sebastian` in those few circumstances.

* I decided to use the characters' variables, which are defined in `images.rpy`, in place of their plain names where possible throughout the script, e.g. `Reza` → `[Rz]`, to reduce the risk of typos when translating.

* Sometimes, it may happen that a line matches exactly its translated counterpart. These lines don't get rendered correctly for some reason, and the only way I found to bypass the issue is to differentiate them by just putting a blank at the end.

* As a design choice, the developer eventually decided that no gameplay sequence would ever lead to both `Anna` and `Damion` surviving `Reza`'s break-in between `chapter2.rpy` and `chapter3.rpy`. However, dead branches are still found in the game, and therefore still made available for translation whenever any dialogue is involved. This dialogue is never triggered, but it should probably be at least taken into account when translating related branches.

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

### [`status.rpy`](italiantl/status.rpy)

* At line 20-216: *good*/*bad* → *positive*/*negative*, as *bad* \[<i>cattivo</i>\] is more commonly understood as *mean* or *evil*. An alternative would be *friendly*/*hostile*.

### [`help.rpy`](italiantl/help.rpy)

* At line 13: Used `space` tags in place of plain spaces to obtain a better alignment at a target resolution of 1920 x 1080, hope it's ok. There has to be a better way though.

### [`chapter1.rpy`](italiantl/chapter1.rpy)

* At line 385, 408: *to skip seen messages* → *to skip messages*, as it depends on the user's preference.
* At line 431: Corrected simple past tense *were under consideration* to past perfect, as we're supposedly talking of the period before the solar flare; the current translation is nonetheless rather flexible in this sense.
* At line 431, 452, 471, 648, 1640: Corrected simple dash to em-dash.
* At line 436, 2738, 2837, 2934: Corrected uppercase letter to lowercase after colon.
* At line 463: Unfolded *8* → *eight*, for elegance.
* At line 1084, 2109, 2176, 2753, 3118, 3352: Slightly pruned to fit fewer lines.
* At line 1358: Corrected two-dots ellipsis to three-dots.
* At line 1751: Used if-statement to further distinguish between food types by linguistic necessity.
* At line 1861: *or even* → *such as*, as bacteria are unicellular.
* At line 2348-2352, 2389-2395, 2410-2415: Assumed the authors' gender by linguistic necessity.
* At line 2351, 2395: Consider changing *dragon* in accordance with line 472, as dragons probably wouldn't refer to themselves as such, at least in the literature.
* At line 2371: Removed extra space after ellipsis.
* At line 2728, 2747, 3609: Adapted to preserve a pun; reverse translation:
  * At line 2728: *I'd have a foot on the ground.* (Can also be read as *I'd have a pied-à-terre*.)
  * At line 2747: *There's a lot of them.*
  * At line 3609: *Achoo- I mean, excellent.*
* At line 2737: Slightly adapted *isn't it fascinating* to add an obvious pun without loss of meaning.
* At line 3068: *PDAs* → *PDA*, to match numerous lines throughout the script; also note the following:
  * No more than one PDA unit is ever interacted with or referred to at one time, except when talking about the PDAs as a whole.
  * Neither the number of PDA units to be delivered, nor actually given to the player character before the portal is rendered out of order, is ever addressed.
  * Even though `Reza` was given a PDA of his own as per line 452, it was before the trade was even set up, so it shouldn't count towards the PDAs to be delivered.
* At line 3197: Corrected *are the likely cause* → *is the likely cause*.
* At line 3226: Unfolded *RIP* → *rest in peace*, as keeping it folded would make an obscure reference in Italian, thus bringing to light elegance concerns.
* At line 3245, 3347: Rendered *legs* as *paws*.
* At line 3712: Assumed *sorry* is addressed to `Sebastian`.

### [`chapter2.rpy`](italiantl/chapter2.rpy)

* At line 523, 1278, 3228, 3312, 3712, 3792, 4226: Corrected simple dash to em-dash.
* At line 572, 958, 1056, 1816, 1826, 1830, 3510, 3680: Corrected uppercase letter to lowercase after colon.
* At line 649: Rendered *legs* as *paws*.
* At line 791: Used if-statement in place of lines 797/801. Using those lines produces either a bad translation, or a good adaptation but hard to pick up again at line 916, if not with another adaptation. (Note that the user should be aware that the intended gender agreement is syntactic, as semantic agreement of *that* \[<i>quell-</i>\] with the player character would have been rendered with the inclusive gender instead \[<i>-ə</i>\].)
* At line 1036, 1148, 3771: Slightly pruned to fit fewer lines.
* At line 1191, 1221: Added parentheses to match resp. lines 4093, 4141 of [`chapter1.rpy`](#chapter1rpy).
* At line 1420-1438: Note that these lines also trigger if the user left at lines 75, 142 of [`bryce1.rpy`](#bryce1rpy), thus having never encountered `Zhong` at the bar.
* At line 1607: Added brackets to match line 2301 of [`chapter1.rpy`](#chapter1rpy).
* At line 1623: *melon bread* → *melon-flavored bread*, to preserve the pun by linguistic necessity.
* At line 2423, 3824: Adapted to preserve a pun; reverse translation:
  * At line 2423: A playful exclamation of surprise.
  * At line 3824: This had to be changed completely: *You'd be a perfect dragon investigator... short of a tail.* Any improvement is welcome. (Note that in theory, `Zhong`'s name might still be unknown to the user.)

### [`chapter3.rpy`](italiantl/chapter3.rpy)

* At line 823, 825, 835, 847, 882, 988, 996, 1219, 1278, 1139, 1478: *PDAs* → *PDA*; see line 3068 of [`chapter1.rpy`](#chapter1rpy).
* At line 849, 884: Split in multiple parts to fit fewer lines.
* At line 860, 2439: Corrected uppercase letter to lowercase after colon.
* At line 1264-1266: Corrected future tenses to conditional, as we're supposedly talking of the yet speculative case where the player character doesn't go through the portal as per `Emera`'s resolve.
* At line 1346: Unfolded *10* → *ten*, for elegance.
* At line 1346: *Hiroshima* → *atomic*, for elegance, not to mention we're supposedly addressing `Bryce` and `Emera`, who can't possibly know about it; the resulting expression reads better without loss of meaning.
* At line 1383: Unfolded *15%* → *fifteen percent*, for elegance.
* At line 1476, 3366, 4338: Corrected simple dash to em-dash.
* At line 1482: Corrected *under consideration* → *into consideration*.
* At line 1946: Corrected uppercase letter of *Chief* to lowercase, to match numerous lines throughout the script where `Bryce` is not addressed directly.
* At line 2144: *inch* → *centimeter*, as Italians prefer the metric system and the resulting expression reads better.
* At line 2467: *list of* → *note with*, to avoid repeating too many same prepositions and to match lines 713, 1149 of [`chapter1.rpy`](#chapter1rpy).
* At line 3054: Consider changing ellipsis with simple dash.
* At line 3098: Slightly pruned to fit fewer lines.
* At line 3639: *pockets* → *pocket*, to match line 2312.
* At line 3751: Adapted to preserve a pun; reverse translation: *I'm stunned.*
* At line 3862-3866: Note that these lines also trigger if `Zhong` was already encountered in [`bryce1.rpy`](#bryce1rpy), where he addresses the player character by name. The user is then prompted to ask `Zhong` about him knowing the player character, resulting in the two speaking the same dialogue. Currently, the only affected sequences are where the user leaves at lines 694, 1176 of [`bryce1.rpy`](#bryce1rpy) or plays through, and doesn't interrogate `Zhong` in [`chapter2.rpy`](#chapter2rpy).
* At line 4046-4064: Note that the larger, orange dragon should be a female, as mentioned by `Zhong` at line 3907; the current translation doesn't use this information, nonetheless.

### [`chapter4.rpy`](italiantl/chapter4.rpy)

* At line 762, 922, 4375, 4382: Corrected uppercase letter to lowercase after colon.
* At line 898, 2716, 3560, 3790, 4369, 4436, 4472, 4478, 4592, 4628: Corrected simple dash to em-dash.
* At line 1094: Used if-statement to distinguish whether `Anna` survives or not, and corrected present tenses to simple past in the latter case.
* At line 1368-1736: The following is a simplified flow chart to help keeping track of which dialogue spoken by the system refers to which case. `INV` is the number of investigation points on this run. **`CHEAT`**, **`SAVED`** are persistent pseudo-variables starting resp. from `0`, `FALSE`. Note that **`CHEAT`** may jump from `0` to `2` but never decrease, and **`SAVED`** may never fall back to `FALSE`.<details><summary></summary><p align="center">![bryce_death](bryce_death.png)</p></details>
  * At line 1676-1736: Note that these lines also trigger if `Bryce` has been saved at least once after dying, then just died again and the user tries to cheat for the *first* time, resulting in a possibly unintended behavior (see e.g. line 1696).
* At line 1708: Slightly pruned to fit fewer lines.
* At line 1812: Note that in theory, dragons don't know what a car is.
* At line 2035, 2836, 2873, 2909, 2946: *PDAs* → *PDA*; see line 3068 of [`chapter1.rpy`](#chapter1rpy).
* At line 2411: `Shake` function doesn't seem to trigger.
* At line 3236, 3315, 3468, 3698: Rendered *leg* as *paw*.
* At line 3285-3289, 3379-3383, 3438-3442, 3511-3515, 3742-3746: Adapted to preserve a pun; reverse translation: *Exceptional.*
* At line 3568, 3627, 3798, 3857: Assumed *who* is referred to `Adine`.
* At line 4345, 4353: Unfolded *65* → *sixty-five*, for elegance.
* At line 4365: About *aligning \[the portals\] across the time axis*, note that `Izumi` would still have had to bypass the anti-time travel safeguards for her to be able to return, assuming the portals in the present were still operational.
* At line 4367: *that meant that* → *moreover*, as there's no real logical implication between line 4365 and this line.
* At line 4432, 4614: Unfolded *AI* → *artificial intelligence*, for elegance.
* At line 4462: Unfolded *10km* → *ten kilometers*, for elegance.
* At line 4468: Unfolded *75%* → *seventy-five percent*, for elegance.
* At line 4468-4472: Slightly adapted to exchange the two units, as Italians way prefer the metric system. Does this qualify as improper localization?
* At line 4500: Corrected *don't think that he would<s>n't</s> hesitate*.
* At line 4556: Split in multiple parts to fit fewer lines.
* At line 4556: *connected* → *linked*, to avoid repeating *the connection \[...\] is not connected*.
* At line 4592: Corrected lowercase letter of *earth* to uppercase.

### [`chapter5.rpy`](italiantl/chapter5.rpy)

* At line 584, 913: Corrected simple dash to em-dash.
* At line 646: *inch* → *centimeter*; see line 2144 of [`chapter4.rpy`](#chapter4rpy).
* At line 913: Changed parentheses with brackets to match line 385 of [`chapter1.rpy`](#chapter1rpy).

### [`chapter5evilending.rpy`](italiantl/chapter5evilending.rpy)

* At line 11, 19, 33, 71, 473, 545: Corrected simple dash to em-dash.
* At line 25, 517, 845: Corrected uppercase letter to lowercase after colon.
* At line 347, 371: *generators* → *generator*, to match lines 4520, 4590 of [`chapter4.rpy`](#chapter4rpy).
  * Note that *the building still having electricity* despite `Reza` having gotten its generator, which was supposed to be *also powering the portal*, is explained by `Reza` himself at line 449, revealing the presence of a backup. At the same line, however, `Reza` claims he *could even get the backup generator as well*, suggesting that the portal is really powered by other means. Whether this is truly the case is never addressed.
* At line 565: Assumed *it* is referred to *the solution* at line 563.
* At line 638: Consider adding parentheses to render the monologue a proper soliloquy.
* At line 733-741: Unfolded *10* → *ten*, for elegance.

### [`adine1.rpy`](italiantl/adine1.rpy)

* At line 39: *containers* → *container*, to match `cgadine2.png` and line 129.
* At line 61-67: Note that these lines also trigger if the user managed to save `Bryce` and returned the eggs to the hatchery, thus having already encountered `Adine` before the actual meeting.
* At line 286, 785: Corrected uppercase letter to lowercase after colon.
* At line 307: Rendered *children* as *cubs*.
* At line 468, 520, 929: Corrected simple dash to em-dash.

### [`adine2.rpy`](italiantl/adine2.rpy)

* At line 53-55: See lines 61-67 of [`adine1.rpy`](#adine1rpy).
* At line 215: Rendered *children* as *cubs*.
* At line 346: Removed extra space before full stop.
* At line 569, 617, 668, 753: Corrected uppercase letter to lowercase after colon.
* At line 1053: Slightly pruned to fit fewer lines.

### [`adine3.rpy`](italiantl/adine3.rpy)

* At line 51-53: See lines 61-67 of [`adine1.rpy`](#adine1rpy).
* At line 257, 264: Consider renaming variable from `mp.time` to `mp.tan`, although it's never used.
* At line 405, 407, 417, 419: Rendered *leg*(*s*) as *paw*(*s*).
* At line 771: Kept the English name for *Freefall*, for coherence with the other names.
* At line 883: Enclosed *hawk* with italics tags.
* At line 1035: Split in multiple parts to fit fewer lines.
* At line 1278, 1282: *pockets* → *pocket*, to match line 2312 of [`chapter3.rpy`](#chapter3rpy).

### [`adine4.rpy`](italiantl/adine4.rpy)

* At line 289: Corrected two-dots ellipsis to three-dots.
* At line 377: Corrected *in the outskirts* → *on the outskirts*.
* At line 627, 665: Unfolded *TV* → *television*, for elegance.
* At line 651: Corrected simple dash to em-dash.
* At line 863: Rendered *child*(*ren*) as *cub*(*s*).
* At line 877: Rendered *leg* as *paw*.
* At line 907: *inches* → *centimeters*; see line 2144 of [`chapter4.rpy`](#chapter4rpy).

### [`adine5.rpy`](italiantl/adine5.rpy)

* At line 83: *the mysterious person I met* → *the Administrator*, to improve the resulting readability and to match line 541 of [`chapter5.rpy`](#chapter5rpy).
* At line 146-244: Note that according to the player character at line 146, `Reza`'s *got six bullets* in his gun, which is the same number of bullets that can be heard being fired up until line 244. Whether they actually notice or not is never addressed; either way the player character eventually surrenders as per `Adine`'s plea at line 279.
* At line 574, 578: Removed extra space before dash.
* At line 838: Corrected simple dash to em-dash.
* At line 856: Preserved uppercase letter after ellipsis.

### [`anna1.rpy`](italiantl/anna1.rpy)

* At line 306: *English language* → *our language*.
* At line 309-311: Adapted to preserve a pun; reverse translation:
  * At line 309: *\[...\] I'm pretty good with the languages \[...\].* (Can also be read as *I'm pretty good with the tongues.*)
  * At line 311: This had to be changed completely: *Especially with mine.* Any improvement is welcome. (Note that *cunning* is often translated as *skilled* when a pun is involved, resulting in a duplicate of line 309.)
* At line 732, 938: Rendered *children* as *cubs*.
* At line 801: Unfolded *20* → *twenty*, for elegance.
* At line 803, 888, 965: Note that wrong answers to `Anna`'s questions seem to be undo-able.
* At line 932: Corrected uppercase letter to lowercase after colon.
* At line 963, 965: Unfolded *#1* → *one*, for elegance.
* At line 963, 965: Unfolded *#2* → *two*, for elegance.
* At line 963, 965, 978, 989: Unfolded *#3* → *three*/*third*, for elegance.
* At line 1018: Corrected *approximate <s>acceleration</s> speed*.
* At line 1029: Corrected *lighter* → *less dense*.

### [`anna2.rpy`](italiantl/anna2.rpy)

* At line 219, 760: Corrected uppercase letter to lowercase after colon.
* At line 219: Unfolded *2* → *two*, for elegance.
* At line 369: Consider changing variable `chap2facres2` with `chap2facres`; see also line 1889 of [`chapter2.rpy`](#chapter2rpy).
* At line 383-385: Used if-statements to distinguish whether `Damion` survives or not, and corrected present tenses to simple past in the latter case. Currently, the only affected sequence is where the user has already seen `Anna`'s good ending, then just played [`chapter3.rpy`](#chapter3rpy) after playing [`anna1.rpy`](#anna1rpy) and asking `Damion` about his research in [`chapter2.rpy`](#chapter2rpy); see also line 369.
* At line 428, 436: Unfolded *90%* → *ninety percent*, for elegance.
* At line 430: Unfolded *50%* → *fifty percent*, for elegance.
* At line 432: Unfolded *99.9%* → *(not) one permill*, *95-97%* → *(not) three-five percent*, for elegance.
* At line 937: Interpreted *you and another of your species'* as *you and \[the members of\] any species other than yours* and then lifted it from member- to species-level.
* At line 979: Assumed the first *you* is referred to the player character, the second to the human race.
* At line 995: Corrected *burst into flame<b>s</b>*.
* At line 1106: Rendered *man* as *(male) dragon*.
* At line 1172: Corrected simple dash to em-dash.
* At line 1211: Unfolded *100%* → *one hundred percent*, for elegance.

### [`anna3.rpy`](italiantl/anna3.rpy)

* At line 622: Used if-statement to distinguish color names based on whether their first character is a vowel or not, by linguistic necessity.
* At line 704: Corrected *why do them* → *why do it*.
* At line 926: Corrected uppercase letter to lowercase after colon.
* At line 1268: Used if-statement to distinguish whether `Damion` survives or not, and corrected present tenses to simple past in the latter case. Currently, all sequences are affected.

### [`anna4.rpy`](italiantl/anna4.rpy)

* At line 435: Corrected *<s>that</s> you could cure me*.
* At line 474: Corrected uppercase letter of *Council* to lowercase, to match numerous lines throughout the script.
* At line 509: Assumed *you* is referred to the player character.
* At line 511: Consider changing *my last straw*.
* At line 599: Corrected *dont* → *don't*.
* At line 617: Removed extra space before question mark.
* At line 675: Corrected simple dash to em-dash.
* At line 792: Where did `Anna` say *[she doesn't] really know anyone else*?

### [`anna5.rpy`](italiantl/anna5.rpy)

* At line 87: see line 83 of [`adine5.rpy`](#adine5rpy).
* At line 341, 343, 435, 710, 859: Corrected simple dash to em-dash.
* At line 415: Corrected uppercase letter to lowercase after colon.
* At line 439: Slightly pruned to fit fewer lines.
* At line 742: Rendered *leg* as *paw*.

### [`bryce1.rpy`](italiantl/bryce1.rpy)

* At line 44: Corrected simple dash to em-dash.
* At line 57: Corrected lowercase first letter to uppercase.
* At line 311: Note that this line also prompts if the user interrogated `Zhong` in [`chapter2.rpy`](#chapter2rpy) or [`chapter3.rpy`](#chapter3rpy), resulting in him and the player character speaking the same dialogue.
* At line 352: Assumed *you* is referred to the police department.
* At line 353: Corrected uppercase letter to lowercase after colon.
* At line 939-1259: Slightly relaxed the use of subjunctive forms in the dialogue spoken by `Bryce` and the player character, to match their altered state.

### [`bryce2.rpy`](italiantl/bryce2.rpy)

* At line 70-78, 507, 513-553, 1079-1081, 1153-1157: Note that these lines also trigger under unexpected conditions. For ease of notation, let:<details><summary></summary>
<code>A1</code> The user left at lines 421, 484, 568 of <a href="#bryce1rpy"><code>bryce1.rpy</code></a> before playing <a href="#chapter2rpy"><code>chapter2.rpy</code></a>.</br>
<code>A2</code> The user left at lines 75, 142, 694 of <a href="#bryce1rpy"><code>bryce1.rpy</code></a>, then interrogated <code>Zhong</code> in <a href="#chapter2rpy"><code>chapter2.rpy</code></a>.</br>
<code>A3</code> The user left at line 1176 of <a href="#bryce1rpy"><code>bryce1.rpy</code></a>, then interrogated <code>Zhong</code> in <a href="#chapter2rpy"><code>chapter2.rpy</code></a> and apologized to him.</br>
<code>B1</code> The user played through <a href="#bryce1rpy"><code>bryce1.rpy</code></a> and put <code>Bryce</code> in a <code>bad</code> mood, then interrogated <code>Zhong</code> in <a href="#chapter2rpy"><code>chapter2.rpy</code></a>.</br>
<code>B2</code> The user played through <a href="#bryce1rpy"><code>bryce1.rpy</code></a> and put <code>Bryce</code> in a <code>neutral</code> mood.</br>
<code>B3</code> The user played through <a href="#bryce1rpy"><code>bryce1.rpy</code></a> and put <code>Bryce</code> in a <code>good</code> mood.</details>
  * At line 70-78: The player character never got to see `Bryce`'s apartment in [`bryce1.rpy`](#bryce1rpy), or did get to see his apartment but they never agreed to *pretend the whole thing never happened*; affected sequences: `A3` in the former case, `B1` in the latter; used if-statement to correct `A3` by `pass`ing.
  * At line 507, 513-553: The `Administrator` and `Maverick` were already encountered in [`chapter4.rpy`](#chapter4rpy), where:<ul><li>At line 507: The player character learns that the former is not `Reza`;</li><li>At line 513-553: `Bryce` and the player character learn of *what [the latter]'s been up to*;</li></ul>
  affected sequences: `A1-3`, `B1-2`, or `B3` after playing [`chapter3.rpy`](#chapter3rpy), then the user managed to save `Bryce` in [`chapter4.rpy`](#chapter4rpy).
  * At line 1079-1081: The player character never got drunk in [`bryce1.rpy`](#bryce1rpy); affected sequences: `A1-2`.
  * At line 1153-1157: `Bryce` never said *there's more to \[him\] than getting drunk*; affected sequences: `A1-3` or `B1-2`.
* At line 357, 395, 592, 1169: Corrected simple dash to em-dash.
* At line 395: Unfolded *100%* → *one hundred percent*, for elegance.
* At line 428, 430, 465, 848: Rendered *leg*(*s*) as *paw*(*s*).
* At line 878, 911: Assumed *you* is referred to the player character.
* At line 880: Assumed *you* is referred to the human race.
* At line 1057: Rendered *child* as *cub*.
* At line 1059: Where did `Bryce` and the player character say *no getting drunk this time*?

## Other remarks

* At line 929 of [`adine1.rpy`](#adine1rpy): On *prendere e* V, see F. Masini, S. Mattiola, G. Vecchi, [*La costruzione* "prendere e *V*" *nell'italiano contemporaneo*](https://www.societadilinguisticaitaliana.net/wp-content/uploads/2019/08/007_Masini_Mattiola_Vecchi_Atti_SLI_LII_Berna.pdf), 2019.
