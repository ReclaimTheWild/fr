---
layout: default
title: Attacking 101
permalink: /combat_basics/attacking_101
parent: Combat Basics
nav_order: 2
---

# Attacking 101
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Landing the Blow

When you attack a foe using a weapon, you will be asked to “Roll To-Hit”. **A roll To-Hit is 2d6 + Accuracy + Weapon Bonus.**

Rolls To-Hit do not exist in a vacuum, though – they must then be compared to the target’s Concentration, Evasion, or Vitality, as specified by the attack’s text. (Evasion may be used in place of Concentration or Vitality, unless the defender is Off-Balance.)

If your To-Hit roll equals or exceeds the opponent’s score, then the attack or effect hits; otherwise, it misses.

A missed attack acts essentially as if it never happened – no damage is dealt, no durability is lost, no effects are enacted upon the target or the user. (If the attack cost Magic or Stamina, however, then that cost is still spent.) If an attack’s Effect misses, then the attack still deals damage, but does not inflict that additional effect.

If you roll a 12 on your 2d6 when rolling To-Hit with a Basic Attack, it is a Critical Hit. (See the [Critical Hits]({{ "/combat_basics/attacking_101#critical-hits" | absolute_url }}) section for more information.) There are enchantments that can increase this range – if you have a +1 to your Critical Hit range, then a roll of 11 or 12 on your 2d6 would be a Critical Hit.

**Spells and Techniques automatically hit, except when other circumstances say otherwise** (such as being Distracted or Blinded). Spells and Techniques can still be mitigated by Reactions.

When a Spell or Technique hits a foe, it may have additional effects that can occur if you succeed at a roll To-Hit, against the foe’s Concentration or Vitality (noted in the Spell or Technique’s Effect section). These checks only decide if the additional effect occurs; failing this check does not change whether or not the target suffers damage from the Spell or Technique.

If the Spell or Technique misses for any reason, then you do not even roll to see if any additional effects land – they, too, miss.

Spells and Techniques are never made Critical Hits due to rolls To-Hit, although other circumstances can make a Spell or Technique be a Critical Hit.

Note that, for unarmed attacks, you have a Weapon Accuracy bonus of 5 – but no damage bonus from an equipped weapon (as you don’t have one!). 

If an Attack targets multiple foes, you must roll all To-Hit checks once for each foe. This applies for Basic Attacks, as well as Spells and Techniques that require To-Hit checks.

## Attack Ranges

**Blast X**: A Blast is a square, X squares to a side, which has one side or corner touching the user.

{% include floating/image_center src="../assets/images/attack_ranges/blast2.png" description="Blast 2" custom_width="30" %}

{% include floating/image_center src="../assets/images/attack_ranges/blast3.png" description="Blast 3" custom_width="30" %}

**Burst X**: A Burst is a ring that surrounds the user, X squares deep.

{% include floating/image_center src="../assets/images/attack_ranges/burst1.png" description="Burst 1" custom_width="30" %}

**Cone X**: A cone that extends out from the user. Every square it moves out, it also gets wider: If moving in a cardinal direction, it gets two squares wider (so a Cone 3 would be 1, 3, then 5 squares); in a diagonal direction, it gets one square wider (so a Cone 3 would be 1, 2, then 3 squares).

{% include floating/image_center src="../assets/images/attack_ranges/cone2.png" description="Cone 2" custom_width="30" %}

{% include floating/image_center src="../assets/images/attack_ranges/cone3.png" description="Cone 3" custom_width="30" %}

{% include floating/image_center src="../assets/images/attack_ranges/cone3diag.png" description="Cone 3, diagonal" custom_width="30" %}

**Line X**: The attack goes in a straight line from the user, proceeding X many squares (counting diagonals 1-2-1). The attack affects *all* targets in this line, passing through combatants, but not through solid objects.

{% include floating/image_center src="../assets/images/attack_ranges/line4.png" description="Line 4, horizontal" custom_width="30" %}

{% include floating/image_center src="../assets/images/attack_ranges/line4diag.png" description="Line 4, diagonal" custom_width="30" %}

**Melee**: The attack can affect one target, cardinally or diagonally adjacent to the user. The user must be able to physically reach out and touch the target, with either their hands or their chosen weapon, to perform a Melee attack.

**Projectile X**: The attack can go up to X squares from you, but it cannot go through solid objects or other combatants. The attack can only affect one target, and stops after hitting the first.

{% include floating/image_center src="../assets/images/attack_ranges/proj8.png" description="Projectile 8" custom_width="30" %}

Note how the other two enemies cannot be hit by the attack: one is hiding behind a block, and the other is hiding behind their less-fortunate front-row friend.

A final note on Projectiles: if *any* foe is adjacent to you, then *all* foes are Hard to Hit with *any* Projectile attacks, no matter how near or far they are from you.

**Sweep X**: The attack cuts through X many squares immediately adjacent to the user. All squares must be cardinally adjacent to one another. The attack may not ‘double back’ on itself.

{% include floating/image_center src="../assets/images/attack_ranges/sweep2.png" description="Sweep 2" custom_width="30" %}

**Weapon**: The range of the attack is equal to the range of the weapon’s Basic Attack. If the weapon is capable of multiple types of Basic Attack, then you may choose which Basic Attack to base the attack’s range off of at the moment you make the attack.

**X Targets/Squares within Y Squares**: The attack can affect X many targets or squares, so long as each of those targets are all within Y squares of the attack’s user. 

The targets do not need to be adjacent to one another. The user does not need to have a direct line of sight on their targets, but they do need to know what square(s) they are in. Any other targets in range are unaffected. A target can only be affected once by this attack, even if they occupy multiple squares, unless they are a Swarm.

{% include floating/image_center src="../assets/images/attack_ranges/xtargetsinrange.png" description="Any three of the foes within the red squares could be hit by a “3 Targets in 8 Squares” attack." custom_width="50" %}

## Counting Diagonals

When counting squares for attack ranges, just as when counting squares for movement, count every second diagonal square as two (so, “1-2-1”).

## Attacking Foes behind Cover

A foe is behind cover if a line from any one corner of your square intersects a solid object on its way to any corner of the opponent’s square.

When attacking a foe who is behind cover, that foe is considered Hard to Hit. In some particularly tricky situations, they may be Extremely Hard to Hit.

## The Size of Creatures

While many of the allies and enemies Heroes meet on their journey will be of similar size to them, not all of them will be. Some may be quite tiny indeed, while others will tower over even the tallest of Heroes. Even among Heroes, there can be quite a difference between a small Fairy and a large Zora!

Consult the table below to see how big or small a given creature, object, or bit of terrain might be.

| Size (feet)  | Size Category | Squares |
|--------------|---------------|---------|
| Less than 1’ | Diminutive    | ⅛       |
| 1’ – 2’      | Tiny          | ¼       |
| 2’ – 4’      | Small         | ½       |
| 4’ – 8’      | Medium        | 1       |
| 8’ – 16’     | Large         | 2       |
| 16’ – 32’    | Huge          | 3       |
| 32’ – 64’    | Gigantic      | 4       |
| 64’ and up   | Colossal      | 6+      |
{: .rtw-table .fixed-columns .centered .half-width }

This means that even some Heroes might be Large (such as particularly tall Gerudo or Zora), or small (such as Deku Scrubs, Fairies, and Subrosians).

By default, a creature’s size merely describes how much room they take up in a corridor or on the battlefield – it does not, in and of itself, make them more or less deadly.

{% include floating/image_center src="../assets/images/attack_ranges/size_comparison.png" custom_width="50" %}

## Abstract Combat Ranges

In some campaigns, you might decide to forego mapping out the battlefield, and simply describe it – how it looks, where combatants are standing, and the terrain that surrounds them. In these cases, the Attack Ranges above change to accommodate the nature of Abstract Combat!

**Burst**: Hits 2 targets for every 1 in the Range. For instance, a Burst 1 can hit up to 2 foes, and a Burst 2 can hit up to 4 foes. May hit 1 additional foe if all targeted foes are described as being close together (standing within arm's reach of one another).

**Blast, Cone, Line, or Sweep**: Hits 1 target, plus 1 additional target for every 2 in the Range beyond the first. For instance, a Cone 2 would hit just one foe, but a Cone 3 hits 2 foes. May hit 1 additional foe if all targeted foes are described as being close together (standing within arm's reach of one another).

**Melee, Projectile**: Hit 1 foe.

**X Targets/Squares within Y Squares**: Can hit X targets, if the user can identify their foe's locations accurately.

In addition, some foes might not be able to be hit alongside other foes, no matter the attack’s range. For instance, if a foe is up on a balcony, hiding behind cover, or if they’ve specifically separated themselves from the other foes, then they cannot be included in an attack with other foes.

Even moreso than in other situations, when it comes to Abstract Combat, the GM’s word is law! However, GMs are encouraged to allow players to include a tricky foe in a large-area attack if the player is able to come up with a clever, fun, or unique way to go about it.

## Damage

Most attacks will have their damage listed in the form of “Weapon + Trait”. “Weapon” refers to the Attack Power of the weapon used. The Trait is typically either Combat or Willpower, and it may be multiplied by 2, or even 3, for some deadlier attacks.

**As an example**: say you have a sword with an Attack Power of 5, your Combat Trait is 3, and you perform a Sneak Attack, for (Weapon + (2 x Combat)) damage. Multiply your Combat by 2, then add your Weapon’s Attack Power of 5, for a total of 11 damage. 

Once the damage output is calculated, subtract the target’s Defense. Then, apply the target’s Resistance to the attack, if any. Finally, apply any other factors. This final result is how much Health the target loses.

All attacks, if they land and their target is not immune to them, will do at least 1 damage.

## Critical Hits

When an attack is a Critical Hit, **add the Weapon’s Attack Power again** to the damage dealt by the attack. If multiple circumstances cause an attack to be a Critical Hit, then it’s still ‘just’ a Critical Hit.

An attack must *normally* be able to miss, to be eligible to be a Critical Hit. This excludes most Spells and Techniques (except those that enable additional Basic Attacks).

## Vulnerability

When you take damage of a type you have a Vulnerability to, add 4 damage and apply only half Resistance; the total damage can’t be reduced below 4. This only applies once per hit; hitting multiple Vulnerabilities in one attack still only deals 4 additional damage.

## Weapon Durability

Whenever a weapon is successfully used in any encounter, at the end of that encounter, the weapon takes 1 Durability damage. If the weapon is struck against anything out of combat, or otherwise put under stress, that use also incurs 1 Durability damage.

When a weapon’s Durability reaches 0, it shatters. This not only means it can no longer be used, but that it is entirely unrecoverable, and cannot even be salvaged for parts. Be careful – if you depend upon a single weapon, and that weapon breaks, you may find yourself in dire straits!

**In general, weapons cannot be repaired.**  
Wield your weapons wisely!

## Peril

When you are at less than 25% health – that is, when your Health is equal to or less than your Hearts score – you are in Peril. On its own, this does nothing but indicate that your character is severely wounded, winded, and worn-down. However, some Feats, Spells, and Techniques may only work on imperiled targets, or may have additional effects on targets in Peril, so be aware that you might be exceptionally vulnerable – or powerful! – while at low health.

## Falling in Battle

In combat, your Health measures how much punishment you can withstand. When a creature reaches 0 Health, they either perish, or simply fall Helpless – depending on the attacker’s whims. (If the attack cannot *have* whims, such as when you fall due to a mindless trap, then you fall Helpless.)

Heroes, however, do not fall quite so easily. When reduced to 0 Health, they always merely fall Helpless, rather than dying, regardless of their foe’s whims. Typically, foes will then turn to fight the remaining Heroes, leaving the Helpless Hero alone. 

While Helpless, a creature may still be blearily aware of their surroundings, but can take no actions, have no Guard Stats, and cannot move. At best, they can croak out a call for aid. Restoring any Health to a Helpless creature ends their Helpless state, though they may still need to stand up from being Knocked Prone.

Creatures that are Helpless (rather than merely sleeping or unaware) can be killed, but it must be done with an attack specifically directed at them, and only them. A Helpless foe will not be further harmed by an AoE that merely happens to catch them in the blast while hitting other targets. The attack can be of any suitable type or range, but it must target that Helpless creature, and **only** that Helpless creature.

Even Heroes can be finished off while Helpless by a follow-up attack. If this happens, their allies should strongly consider Intercepting the deadly blow.
