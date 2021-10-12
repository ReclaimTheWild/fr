---
layout: default
title: Creating New Attacks
permalink: /creating_monsters/creating_new_attacks
parent: Creating Monsters
nav_order: 16
---

# Creating New Attacks
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

In some cases, you may want to create a new Technique, Spell, or other special attacks for your monstrous creations to use.

First, consider if an existing attack could simply be tweaked to serve a new purpose. You can change an attack’s Element, inflicted Status, or from a Spell to a Technique (or vice-versa) with little worry.

If that won’t do, however, you can get a feel for the balance of a new attack like so:
- Start with the number of targets the attack would usually hit when using [Abstract Combat Ranges]({{ "/combat_basics/attacking_101#abstract-combat-ranges" | absolute_url }}).
- Then, multiply by the attack’s damage multiplier. If it’s a Weapon + Combat attack, multiply by 1; if it’s Weapon + (3 x Combat), you multiply by 3, etc.
- If the attack has additional beneficial effects, such as inflicting a status effect, multiply by 1.25. If it has a downside or can only be used in some circumstances, multiply by 0.9. If both, then do nothing.
- Finally, divide by Magic or Stamina cost.

Ideally, your result will be about 0.33 – this indicates that your new attack is (probably) balanced. If your result is less than that, then your attack might be too weak or costly. If the number is higher, it may be too powerful.

## Concentration or Vitality?

When an attack has a secondary effect, that effect often targets either Concentration or Vitality. But which one should you use?

**Concentration** is used to defend against attacks that require quick thinking, keeping your cool, or might distract or mislead you.

**Vitality** is used to defend against attacks where you have to grit your teeth, stand your ground, or tough it out.

## Elements and Associated Ephemera

Below is a table of common pairings of Elements, their Vulnerability, Gems, Terrain, and Statuses.

| Element | Gemstone | Vulnerability | Common Status Effects        | Terrain                |
|---------|----------|---------------|------------------------------|------------------------|
| Dark    | Onyx     | Light         | Blinded, Sick Mire, Pit      | Mire, Pit              |
| Earth   | Emerald  | Ice           | Knock Prone, Sand-Covered    | Sand                   |
| Fire    | Ruby     | Water         | Burning, Oil-Soaked, On Fire | Brushfire, Lava, Oiled |
| Ice     | Sapphire | Fire          | Frozen, Halted, Slowed       | Ice, Snow              |
| Light   | Diamond  | Dark          | Cursed, Hard to Hit, Invisible | Tall Grass           |
| Shock   | Topaz    | Earth         | Electrified, Off-Balance     | Electrified            |
| Water   | Opal     | Shock         | Rusted, Soaked               | Water                  |
{: .rtw-table }

