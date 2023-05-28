+++
title = "Mechanical Conventions"
description = "conventions for pickup groups"

weight = 2
+++

# Mechanical Conventions

These conventions represent my recommendations on how to handle various mechanical aspects of fights.
They're intended for use both by blind pickup groups and in standardized strategies.

These are not rules. They are recommendations. Guidelines. Don't treat them like rules.
Conventions exist largely because, in many cases, making *any* decision is more important than making any particular decision.
Getting everyone on the same page gets everyone progging faster, clearing more often, and having a better time.
But the conventions are having the opposite effect if they're ruining anyone's fun.
And specific fights will often demand that the conventions be deviated from.

The conventions _will_ change over time. In the early days, they will likely change frequently.

<!-- FIXME: Properly numbered headers? -->
## 1. The #1 marker goes in the north-east by default {#markers}

{{ image(alt="A diagram of markers showing #1 in the top-right corner.", src="markers.png", caption="Marker diagram") }}

The #1 marker is not consistently placed in North American parties.
Some groups place it in the north-west corner, others in the north-east.
On occasion, we even see groups that put numbers on the cardinals and letters on the intercardinals.

#1 in the NE is generally the most common worldwide, and also makes the markers more consistent:
both cardinal and intercardinal makers can be read clockwise from north, like an actual clock.
With #1 in the northwest, you would have to read clockwise starting from the northwest.

#1 in the northwest does make role pairs more natural, as DPS can rotate clockwise (see [below](#pairs)),
and in Japanese data centers this is the preference.
We have opted for consistency of the markers across all fights instead.

## 2. Tank the boss in the center facing north {#tank-north}

In fights where the tank can control the boss's position and/or facing, by default the boss should be lured to the middle of the arena and faced north.
After mechanics where the boss moves or turns, the main tank should typically return it to that position if possible.
This applies even after a tank swap, with the new main tank taking the north position.

The purpose of consistent boss facing is to let the melee DPS consistently and easily hit positionals, particularly during spreads.
On fights where the boss has a consistent preference to face in a direction other than north,
it may make more sense to tank it in that direction, which in turn may require the spread spots to be changed.

### 2a. `MT` and `OT` positions swap if needed to keep the boss facing north {#tank-swaps}

The terms "main tank" and "off-tank" are ambiguous with tank swaps.
The main tank could be either the player who had the `MT` position at the start of the fight, or the player who currently has aggro.

In general, it is simpler to have the `MT` position stay with the player who had it at the start of the fight.
But this means that, after a tank swap, the `OT` will be at the north position in order to keep the boss facing north.
Tanking the boss north takes priority.

So the `MT` and `OT` may have to swap positions for a mechanic, such as spread spots, to keep the boss facing north.
If there is no need for a swap, as often happens with light party stacks, the tanks retain their original positions.

If there's any confusion, tanks should hash things out on a mechanic-by-mechanic basis.

## 3. Party split priotities: G1/TH go N/W; G2/DPS go S/E {#split-priorities}

Many mechanics require half the party to go in one direction, half togo the other direction.

For these mechanics, group 1 will go north or west towards the purple and red markers, and group 2 will go south or east towards the blue and yellow markers.
For mechanics where the split is relative to a mechanic, group 1 should go left and group 2 should go right.
For soaks, the default soak positions are east and west, i.e. markers B and D.

Group 1 is either light party 1 or the tanks and healers, depending on the split required by the mechanic.
Group 2 is either light party 2 or the DPSs.

## 4. Pairs default to colour pairs (DPS rotate counterclockwise) {#pairs}

Many mechanics require players to pair up one tank with one DPS.
By default, this should be colour pairs: A with 1, B with 2, etc.

For some mechanics, there are large targeted AoEs that require everyone to be well spread out while also paired up.
For these mechanics, the default is to meet on the cardinal points with the letter markers.

This is the same as saying that the default is that DPS rotate counterclockwise from their spread spots.

We choose to do counterclockwise, rather than clockwise, to keep the [marker position](#markers) consistent.
