---
layout: post
title:  "Nighthold Trinket Theorycrafting"
categories: trinkets theorycrafting
hide: true
---

**Note:** If you're looking for how these trinkets fit into the larger context of existing trinkets, see
[Trinkets](/trinkets) instead.

**These numbers are outdated as of the hotfix on Jan 24, 2017.** See
[Questionably Epic's analysis](https://questionablyepic.com/nighthold-healer-trinkets-update/) for up-to-date numbers.
I've left the below info to not break links, but this page is outdated and is now hidden from the rest of the site.

Here's some theorycrafting about Nighthold trinkets:

- [Ephemeral Paradox][paradox] from Elisande. Only affects Healing Wave (that is, it procs off all heals, but only makes
  Healing Wave free/restore mana). According to Wowhead, this trinket has a proc rate set at &asymp;1.2 procs per
  minute. This gives a mana return of:
  
      1.2 * (3869 + 19800) = 28402 mana
  
  per minute. Over a 5-minute fight, that's 142k mana restored - about 2.5 chain heal casts - which you could use to heal
  3 million or so health. The extra mana is maybe a 2-4% bump in overall healing, and the static intellect makes this is a
  decent trinket, especially if you have mana issues sometimes. However, I would still prefer an int/stat stat stick, 
  as >1k mastery or crit will probably be more than 2% healing done in a fight.

  **Note:** Some info suggests that the datamined value for the procs per min (from Wowhead) may be higher than it actually
  is in game. Need to confirm, but if so that makes this trinket weaker than expected.

- [Etraeus' Celestial Map][map] from Star Augur Etraeus.  According to Wowhead, this trinket has approximately 2 procs
  per minute, leading to (2 &times; 8 sec / 60 sec) &asymp; 27% uptime. As a relatively low uptime proc trinket, the Map
  won't be all that great in raid, other than the fact that it has intellect as its stat (and since it's Nighthold gear,
  it will drop at a high item level). See the bottom of the [Trinkets](/trinkets) post about this trinket and
  [Heightened Senses][senses], which are very similar.

- [Perfectly Preserved Cake][cake] from Trilliax. This trinket is... interesting. A useful Wowhead comment tells us it
  has these properties:
    * The trinket is off GCD
    * The cake is placed instantly in front of you when you use it. It immediately affects yourself (maybe a bug)
      plus five other raid members within an 8 yard radius. No action or movement is required. If there are fewer
      than five other members, the cake persists for 20 seconds and will auto-apply to those who enter its radius
      (up to the cap).  See [this picture](/assets/cake-radius.jpg) to see where the trinket drops in relation to
      your character and how wide the radius of effect is. **Note:** The cake persists for a bit even after its
      charges are exhausted, so don't tell raid members to run to it if they see it, necessarily.

  So, this trinket (at 900 item level) places five 296k absorbs (= 1.48 mil total) every 2 minutes, or about 740k
  absorbs per minute on average. Not bad - [Vial of Nightmare Fog][vial], for example, does about the same absorbs per
  minute at similar ilevels.  Plus, with mastery as its stat, it fits our stat priority really well. **I think this
  trinket is probably better than [Vial of Nightmare Fog][vial] for similar item levels,** if used properly (which should not be
  that hard, given the information above). This is especially the case for Nighthold, which has several fights where the
  raid stacks.

  This trinket may be mechanically annoying to use, however...

- [Aluriel's Mirror][mirror] from Spellblade Aluriel. According to Wowhead, this trinket has approximately 3 procs per
  minute, giving a total healing of 321k healing per minute (in the form of a 12 sec HoT) plus the *chance* for some 58k
  AoE explosions. (Note: this is assuming 905 item level.) As far as heals per minute goes, this seems weak for a
  trinket, and combined with the haste stat, I think **this is the weakest trinket in Nighthold for us.** (Also, I
  suspect this trinket will have a high percentage of overhealing.)

[map]: http://www.wowhead.com/item=140803/etraeus-celestial-map&bonus=3518
[paradox]: http://www.wowhead.com/item=140805/ephemeral-paradox&bonus=3518
[cake]: http://www.wowhead.com/item=140793/perfectly-preserved-cake&bonus=3445
[mirror]: http://www.wowhead.com/item=140795/aluriels-mirror&bonus=3518
[vial]: http://www.wowhead.com/item=138222/vial-of-nightmare-fog&bonus=1806
[senses]: http://www.wowhead.com/item=139330/heightened-senses&bonus=1806
