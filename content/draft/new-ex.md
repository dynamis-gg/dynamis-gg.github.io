+++
title = "Extreme Trial New Player Guide (DRAFT)"
description = "Basics of Extreme Trials for new players"
+++

# Extreme Trial New Player Guide

Extreme trials are the first level of high-end combat content in FFXIV, and where most players start playing endgame.
If you are interested in playing Extreme trials but don't know how to begin, this guide is for you.

This guide assumes you are tackling current (most recently released) trials, which are always the most difficult.
Older trials are easier because of power creep.

## Preparation

To get started, you will need to unlock the Extreme trial in question.
This typically requires completing the quest containing the normal trial,
and then accepting a separate quest that unlocks the Extreme trial.

So far, all Endwalker trials have been in the MSQ rather than sidequests.
The Extreme Trials are all unlocked by talking to ~~YoshiP~~ the Wandering Minstrel at Old Sharlayan (x:12.7, y:14.3).

### Gear

You will need to be appropriately geared for the fight.

Full endgame gearing is beyond the scope of this guide, but at the very least, you should ensure that:

1. You meet the minimum item level for the trial.
2. You have filled all your gear's materia slots with the highest level materia available.

The minimum item level will not be enforced when entering the duty with a pre-made party, such as one formed on Party Finder,
so it is possible to play the trial without appropriate gear.
Please do not do this unless you know your team is willing to carry you.

As for materia, typically you want to meld for Critical Hit, Determination, and Direct Hit.
Healers may want to meld Piety to aid with mana management, particularly early after a trial's release.
Skill/Spell Speed and Tenacity materia are not good default options and should be avoided unless you have a particular reason to meld them.
Consult a job-specific gear guide for more information on melding.
Do not worry about overmelding for your first introduction to Extremes, unless you are having difficulty with [DPS checks][damage].

### Consumables {#consumables}

There are two kinds of consumables used in high-end content: food and potions, specifically tinctures.

Food increases [damage] and [keeps you alive][mitigation].
Because it helps mitigate damage, food should always be used, even when learning and practicing.
You should generally use high-quality food with a comparable item level to your gear.
Job-specific guides provide information on the best-in-slot food choice.

Tinctures, on the other hand, are used to enhance [burst] damage.
Because they are only used for damage and are more expensive, tinctures are typically used only when a clear is in sight.
Most jobs use tinctures in the opening burst window, but some will delay to the first 2-minute burst window because their opener is weak.
Extreme fights are not typically so strict as to require tincture use, but as with all burst optimisations, they do make the fight easier and more forgiving when used correctly.
When first learning Extremes, however, you may find it helpful to ignore tinctures at first.

### Finding Parties

In all North American data centers, parties for Extreme trials are generally assembled manually on Party Finder.
Raid Finder and Duty Finder are not used.
If you queue for an Extreme trial on Raid Finder or Duty Finder, expect a long wait.
If there are no parties currently forming for the trial you want to do, you can make your own.

Check out our [PF glossary](pf-glossary) for help understanding PF postings.

### Assigning Positions

Once a party is formed but before the fight even begins,
players will usually need to agree on what positions they will take for various mechanics.
The specific formations required vary from fight to fight based on the mechanics.

Two formations, however, are common to almost all fights: light party stacks and clock spreads.
In light party stacks, two players (usually the healers) are marked with stack markers and the players need to split into two groups of four to soak the stacks.
In clock spreads, each player has an AoE targeted on them and need to spread out.
They're called clock spreads because the players spread to positions on a circle around the boss, reminiscent of a clock.

Pick-up groups using macros typically lay out formations [in a fight macro or following a default position](/etiquette#positions).
The abbreviations used for positions are as follows:

| Abbreviation | Meaning                                    |
| :----------: | :----------------------------------------- |
| `MT`         | Main tank                                  |
| `OT`         | Off-tank (also known as "side tank" in JP) |
| `H1`         | Healer 1, usually the pure healer          |
| `H2`         | Healer 2, usually the barrier healer       |
| `M1`         | Melee DPS 1                                |
| `M2`         | Melee DPS 2 or flex DPS                    |
| `R1`         | Ranged DPS 1, usually ranged physical      |
| `R2`         | Ranged DPS 2, usually caster               |

## Playing the Fight

There are many ways in which the mechanics of Extreme trials are a step up in difficulty from normal fights.
We try to lay out some of the major points, first covering aspects common to all roles, then role-specific aspects for tanks and healers.
Some of these points apply equally to normal fights, but are included here because normal fights are typically forgiving enough that you may not have picked them up by now.

### DPS & Enrage {#dps}

Most normal fights can go on as long as the party needs to defeat the boss, subject only to the duty timer.
Starting with Extreme trials, however, fights have fixed timers, usually in the range of 7 to 11 minutes.
If the party is unable to defeat the boss in time, then the boss will "enrage" and wipe the party.
Thus, the party's overall DPS must exceed a certain minimum over the course of the fight in order to clear.
This is called a "DPS check".

In some fights, the boss will summon one or more adds that must be killed within a time limit.
These are also DPS checks, but are usually less strict than the fight's overall DPS check.

Doing damage to the boss is typically not required apart from DPS checks and for tanks to maintain aggro.
Therefore, in many fights, if you prefer you can learn or practice by focusing the mechanics and only attacking when strictly necessary.
Once you are making it a substantial portion through the fight, you should focus on adding in your DPS and optimizing it.

Specific tips for maximizing your DPS follow.
In Extreme fights, you will probably not need to use all of them to pass the DPS check,
and you certainly won't need to do everything perfectly.
At the same time, you will not be able to be carried by other players. 

#### Always be Casting {#abc}

The *most important* rule for maximising DPS is ABC: Always Be Casting.

You should get in the habit of *always* having your global cooldown (for weaponskills/spells) rolling, and using your damaging abilities as soon as they come off cooldown unless you are saving up for [burst].

Specific optimizations to make maximal use of your job's abilities and the burst window typically pale in comparison to what you get out of simply keeping up a steady output of damage.

A corollary of ABC is DD: Don't Die.
Being resurrected with anything other than a limit break gives you a nasty damage down debuff.
But even if you're resurrected by LB3, during the time you are dead, you're not casting.
So not dying will do wonders for your DPS.

#### Burst Windows {#burst}

Most jobs, other than healers, now follow a consistent pattern of having major actions on a 1- or 2-minute cooldown.
These include both actions that deal a lot of damage, and actions that increase damage, often for the entire party.
In particular, party buffs are usually on a 2-minute cooldown.

You generally want to pack in as much damage as you can into the buffs,
so generally if you have resources (such as a job gauge) that you can spend gradually,
you want to save those for the burst window.
Even if your job has no damage buff to align to, such as samurai, you idealy want to align your gauge spending with other party members' party buffs.

Extreme trials are not so strict on DPS that optimising burst windows is required for success.
However, even if they are not strictly required, they make the fight more forgiving of other mistakes,
and getting used to optimising your burst windows will help immensely if you go on to Savage.

#### Testing your DPS with Stone, Sea, Sky

Stone, Sea, Sky is an in-game facility that lets you test your DPS against dummies calibrated for specific high-end bosses.
While SSS is not a very accurate simulator for a fight, it is an excellent first-pass check.
If you cannot pass the SSS challenge for a given fight, then you should not expect to clear the DPS check unless you are carried by an overgeared party.

### Mechanics

Extreme and harder fights typically put much more work on the players to anticipate and avoid the boss's attacks, and punish mistakes more harsly than normal trials.
In many cases, to learn to do an Extreme trial successfully, one should study the normal version of the fight carefully.
It will typically reveal information needed for the Extreme fight.
For instance, if the normal version of the trial has the boss do a particular animation and a clearly telegraphed AoE indicator,
in the Extreme version of the trial you may only have the animation, and not the AoE telegraph, as warning for the attack.

#### Tells

In normal fights, attacks are usually telegraphed either with a specific targeting marker over a player, or with an AoE marker that appears on the ground.
These telegraphs give players time to anticipate and react to the attack.

Extreme and harder fights may use any of the following kinds of tells instead of obvious telegraphs:

*  The boss may execute one of multiple attacks depending on the name of the spell on its cast bar.
*  The boss may execute one of multiple attacks depending on its wind-up animation.
*  The boss may perform a set-up cast in one of several variations, and later do an attack based on which variation was set up. Sometimes, but not always, the boss will get a buff to serve as a reminder of which variation is active.
*  The boss may give one or more players debuffs, and later perform an attack targeting the debuffed player(s) without otherwise giving warning.

For buffs and debuffs, it is always a good idea to hover over them and read the tooltip in order to get information about what they do.
If you cannot read a tooltip fast enough, ask a party member for help.

#### Snapshots {#snapshots}

Because Extreme trials give you less time to avoid mechanics, it is very important to understand how snapshotting works.
Most attacks "lock in" their target whenever the targeting marker or AoE telegraph disappears.
For these attacks, once the marker or telegraph disappears, you can safely walk into the attack animation without taking any damage.
Conversely, if you were in the area of effect when the telegraph disappeared,
you will take damage even if you are nowhere near the attack animation.

In Extreme trials, bosses will often have attacks that only flash their AoE very briefly, without giving any time to dodge.
These flashes are not warnings like normal AoE telegraphs.
They exist only so you can understand the exact extent and snapshot timing of the attack.
Unavoidable attacks often snapshot at the end of the castbar.

There are two important ways to make use of snapshots during fights.
First, all damage reduction and nullification is also computed as of the snapshot.
This means that [mitigation] and [knockback resistance] must be applied before the snapshot.
Second, paying attention to snapshots will help you move more quickly after an attack,
which is particularly valuable when there are multiple in rapid succession.
There are also advanced techniques for snapshot abuse, if you're the sort of player who likes that kind of thing.

Note that some attacks are multi-hit or have unusual snapshots.
Trial and error may be needed to work out exactly how a mechanic's snapshot works.

#### Vulnerability {#vuln}

As in normal fights, the typical penalty in an Extreme for getting hit by an avoidable attack is a vuln debuff that increases damage taken from subsequent attacks.

Extreme fights also introduce damage-type specific vulnerability debuffs such as "Magic Vulnerability Up" or "Wind Resistance Down".
These debuffs are often unavoidable, used to enforce correct execution of certain mechanics.
They usually are extremely powerful debuffs but, apart from [tank swaps][tankbusters], are usually very short-lived.

As an example, a prototypical light party stack mechanic begins by placing stack markers over both healers.
The players must stack with the healers to spread the damage out and allow the healers to survive the attack.
Any player hit by the attack, however, will receive a debuff matching the type of the attack, say, Magic Vulnerability Up.

Thus, if a player is hit by both attacks at the same time,
the vulnerability debuff from whichever one is processed first will be applied to the damage to the second,
and this will almost certainly be lethal, even to a tank.
So in order to survive the mechanic, the party must split into two separate stacks, rather than all stacking together.

### Damage & Mitigation {#damage}

Starting with Extreme trials, bosses will begin to output unavoidable damage at a rate that genuinely threatens the party.
The damage is often high enough that healers will struggle to keep up.
This is especially true if the healers have to spend time and mana resurrecting other players, or if players have taken vuln stacks from mistakes.
Ranged DPS are particularly squishy and vulnerable to dying to unavoidable damage,
especially magic damage for ranged physical and physical damage for casters.

To ease burden on the healers and help cover for mistakes, all players must contribute by eating appropriate [food] and mitigating icoming damage.
All non-healer jobs have at least one action that mitigates damage to the party:

*  Tanks have Reprisal, which inflicts a debuff on nearby enemies reducing their damage by 10%.
*  Melee DPS have Feint, which inflicts a debuff reducing physical damage by 10% and magical damage by 5%.
*  Ranged magical DPS have Addle, which inflicts a debuff reducing magical damage by 10% and physical damage by 5%.
*  Ranged physical DPS each have a job-specific party-wide buff that reduces incoming damage by 10%. These buffs do not stack with each other.

Almost all buffs and debuffs for damage mitigation stack, except that the ranged DPS barriers do not stack and neither do multiple copies of the same ability.
It is also generally more effective to spread mitigation out, with one or two mitigations per attack, rather than dumping it all onto one attack.

Extreme trails generally do not have so much damage that the party must plan out exactly when each mitigation will be used.
So while you should try to make active use of your mitigation against raidwide attacks, do not worry too much about being perfect.
The most valuable thing you can do is try to use mitigation consistently in each pull so that other party members can adjust to what you are doing.
If you are frequently using your mitigation at the same time as your role partner, however, or the party is regularly dying to raidwides,
it may be a good idea to coordinate with your party.

### Knockback Resistance {#kbr}

As with normal fights, many Extreme trials have knockback mechanics that will kill the player if they are not resolved correctly.
Most such knockbacks can be ignored using your knockback resistance (KBR): Arm's Length (for physical jobs) or Surecast (for casters).

Extreme trials will generally not require the use of KBR, so whether to use it is a personal choice.
You may prefer to dodge or ride the knockback if it makes other mechanics easier,
or you may prefer to use KBR if it lets you maintain uptime.
If you decide to use KBR, be sure to use it before the attack [snapshot][snapshots].

### Tanks

Tanks have a few additional concerns specific to their role in holding aggro.

#### Boss Positioning

By convention, as much as possible, the boss should be kept [in the center facing north](tank-north) unless otherwise required by the fight.
Apart from repositioning the boss for a mechanic or to get it back to center, though,
the boss should be moved as little as possible.

Moving the boss makes it harder to consistently execute mechanics and, for melee DPS, makes it harder to execute positionals correctly.

A corollary of this is that tanks should not fight for aggro, as that will cause the boss to spin.
The off-tank should disable their tank stance as needed to ensure they are not going to surpass the main tank for top aggro unintentionally.

#### Tankbusters & Tank Swaps {#tankbusters}

Many Extreme trials have mandatory tank swaps.
Usually this is done by having a tankbuster inflict a [vuln] that will make a follow-up attack into a guaranteed lethal hit.
The off-tank must take aggro so that they are hit by the follow-up instead of the main tank.
Involuntary tank swaps will also occur if the main tank dies.

The off-tank should take aggro by using Provoke and by ensuring they have their tank stance on.
The correct time to Provoke is usually during the cast bar of the tankbuster, before the first hit.
The main tank must ensure that they do not steal aggro back accidentally as well.
Therefore, the main tank must either drop their tank stance or use Shirk to pass additional aggro to the off-tank.
Using a tank's ranged attack for the extra aggro is a last resort.

Even when tankbusters do not have tank swaps, in Extreme and harder fights, they hit much harder.
Tanks should use at least one, ideally two, mitigation ability for all tankbusters.

### Healers

The job of a healer in end-game content includes both dealing damage and keeping the party alive.
Your primary strategy should be to try to use off-GCD abilities to heal when needed, and GCD spells primarily for attacking.

Keeping the party alive is your first priority, however, so use GCD abilities as much as you feel needed to do so.
As you learn a fight and become more comfortable with your cohealer,
you can reduce the number of GCD heals and focus them on damage.

[boss positioning]: /conventions#tank-north
[mitigation]: #damage
[knockback resistance]: #kbr
[vuln]: #vuln
[damage]: #dps
[food]: #consumables
[tankbusters]: #tankbusters
[snapshots]: #snapshots
