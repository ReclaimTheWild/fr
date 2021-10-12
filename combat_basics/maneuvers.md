---
layout: default
title: Maneuvers
permalink: /combat_basics/maneuvers
parent: Combat Basics
nav_order: 7
---

# Maneuvers
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Maneuvers are actions that don’t directly harm foes, but can still give you a strategic advantage. **All Maneuvers cost no Magic or Stamina to perform, and can be performed while Cursed.** Maneuvers are Standard Actions, unless otherwise stated.

When a Maneuver’s Roll lists multiple Traits, the creature rolling adds up the sum of the listed Traits, and adds a 2d6 roll to that for their final total. This roll is also impacted by anything that affects a “Roll To-Hit.”

## Combat Maneuvers

Combat Maneuvers have a range of Melee, unless otherwise noted.

### Disarm
**Roll**: Accuracy and Combat v. Vitality  
**Effect**: Select one item that the target currently has in their hands or on their belt (but not in their Pack). They drop this item in a random square adjacent to them.

### Grapple
**Roll**: Agility and Athletics v. Vitality  
**Use Requirement**: One empty hand (for foes smaller than you), or two empty hands (for foes your size). You cannot grapple foes larger than you.  
**Effect**: You grapple the target until the end of your next turn. While grappled, the foe is Distracted by you and Halted. When you move, your foe moves with you; each square you enter costs an additional Movement. You must repeat this Trait check at the beginning of every turn (as a Free Action); if you do not, or you fail it, the target is released. If the grappled target is Pushed away from you, or they use their Standard action to try and escape, you must repeat this check to maintain your grapple.

### Hobble
**Roll**: Combat and Guile v. Vitality  
**Effect**: The target is Slowed until the end of their next turn.  

### Low Blow
**Roll**: Athletics and Combat v. Vitality  
**Effect**: The target is put Off-Balance.

### Pickpocket
**Roll**: Accuracy and Agility v. Concentration  
**Use Requirement**: At least one empty hand  
**Effect**: Take an item – or stack of items - from the target's Belt or Pack (but not their hands). You must have enough empty hands to hold it. (To do this unnoticed, first [Sneak]({{ "/playing_the_game/movement#sneaking" | absolute_url }}) up to the target.)  
**Special**: -4 to your roll if the foe is in combat or moving erratically.

### Push
**Roll**: Athletics and Intimidate v. Vitality  
**Effect**: The target is pushed 1 square away from you. If the target is mounted, they are also dismounted and knocked Prone.

### Sand Attack
**Roll**: Accuracy and Guile v. Vitality  
**Effect**: The target is Blinded until the end of their next turn.

### Trip
**Roll**: Agility and Insight v. Vitality  
**Effect**: The target is Knocked Prone.

## Social Maneuvers

All Social Maneuvers require you and the target be able to either see and/or hear one another.

### Coordinate
**Roll**: Command & Perception v. Concentration  
**Effect**: Select one ally you can see and communicate with. That ally now has a Knack for their next To-Hit roll against that foe. (This does not allow them to make a second attack against another foe with Techniques or Spells, but does allow a second Basic Attack or Maneuver against another foe.)

### Flirt
**Roll**: Guile and Influence v. Concentration  
**Effect**: The target cannot target you with attacks, nor intentionally cause harm to you, until the end of their next Turn.

### Menace
**Roll**: Command & Intimidate v. Concentration  
**Effect**: The target is Cursed until the end of their next turn.

### Predict
**Roll**: Insight & Perception v. Concentration  
**Effect**: You learn what the opponent is thinking of doing next, at that moment. If they intend to attack you, and follow through on that intention before the end of their next turn, you will be Hard to Hit with that attack. If you use an existing Reaction to reduce their attack’s damage, you Resist the damage 2 more Ranks. Note that “yelling out what the foe intends to do” may make it change its mind, if it is an intelligent foe that can understand your words.

### Taunt
**Roll**: Influence and Insight v. Concentration  
**Effect**: The target is Distracted by you until the end of their next turn.

## Miscellaneous Maneuvers

Miscellaneous Maneuvers may have unique rules, rolls, or ranges. Be sure to read them carefully!

### Compel Surrender
**Roll**: Command, Influence, and Intimidate v. (10 + Rank + Discipline + Fortitude)  
**Range**: Auditory / Visual; cannot target Heroes  
**Effect**: The target willingly gives up. They may lay down their arms, let themselves be taken prisoner, or walk away from the battle.  
**Special**: The foe’s DC to resist takes a -2 penalty for each of these circumstances:
- Foe is in Peril
- Foe believes they have little-to-no chance to win the fight
- Foe believes you will be merciful
- Foe is of Rational intelligence

Minibosses gain +2 to their DC to resist 
Compelling Surrender; Bosses gain +4. 
Other penalties or bonuses may also apply, 
at GM discretion.

### Intercept
**Roll**: Agility and Perception v. Concentration  
**Use Requirement**: An ally is the target of an attack, and is within your Movement range.  
*Reaction*  
**Effect**: You move to the ally’s square, push the ally one square (in the direction of your choice), and take their place – and suffer the attack. You cannot use Reactions against this attack, and it automatically hits you. Any effects that occur on a subsequent To-Hit check as part of that attack also automatically hit you, as well.

### Learn Lore
**Roll**: Special (See Below)  
**Range**: Auditory / Visual  
*Minor Action*  
**Effect**: You learn information about the foe, based on your roll and the Rank of the target foe, per the table below.

You may gain additional information about that particular foe or that foe’s species, also based on the roll result. Consult the foe’s entry in the Bestiary for this information.

**Special**: You may attempt this Maneuver only once per type of foe in a given battle. You may be allowed a second attempt if new information comes to light during the battle.

**Special, Roll**: The Trait used to make this roll depends on the foe’s origins.

**Arcana**: Arcane Foes made of magic, energy, or other ephemeral things. Also covers undead foes. Examples: Bubbles, Ghini, Phantom Ganon, Redead.  
**Civilization**: Sentient, humanoid foes, such as soldiers, bandits, or rival Heroes. Examples: Garo, Vaati, Yiga assassins.  
**Mechanics**: Automata, robots, statues, and Ancient-built foes. Examples: Beamos, Dark Train, Gimos, Guardians.  
**Nature**: Natural-born foes, such as plants and animals. Includes sub-sentient humanoid monsters. Examples: Bokoblin, Deku Baba, Gohma, Wolfos.

| Rank 0 | Rank 1 | Rank 2 | Rank 3 | Rank 4 | Rank 5 | Obtained Information |
|--------|--------|--------|--------|--------|--------|----------------------|
| 0      | 2      | 4      | 6      | 8      | 10     | Name, Rank, Description
| 2      | 4      | 6      | 8      | 10     | 12     | Typical Habitat & Diet, Intelligence, Typical Behavior |
| 4      | 6      | 8      | 10     | 12     | 14     | Tactics, Properties, Weapons, Passive Abilities |
| 6      | 8      | 10     | 12     | 14     | 16     | Resistances, Vulnerabilities, Immunities, and Weak Points |
| 8      | 10     | 12     | 14     | 16     | 18     | Full information on foe’s Attacks, Spells, Techniques |
| 10     | 12     | 14     | 16     | 18     | 20     | Trait scores, hidden tricks, any remaining secrets |
{: .rtw-table .centered-bold .small-rank-columns }