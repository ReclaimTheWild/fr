---
layout: default
title: Packs & Pouches
permalink: /equipment_crafting/packs_pouches
parent: Equipment & Crafting
nav_order: 7
---

# Packs & Pouches
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

Heroes carry their inventory in a Pack. A better Pack can increase the number of Tools, Weapons, Armors, and Ammunition you can carry. Without a Pack, a Hero can only carry what items they can keep equipped in their hands and on their body. Any items a Hero has equipped do not count towards their Pack’s limits.

Packs are made with Cloth and Monster Parts. **When upgrading an existing Pouch, the materials price can be paid for only in Cloth or Monster Part materials, at any ratio** – all Cloth, all Monster Parts, or a mixture of the two.

## Starting Pack

All heroes start with a basic Pack. It has the following pouches, each with a number of slots already available:

| Pouch Type  | Starting Slots |
|-------------|----------------|
| Weapons     | 5              |
| Consumables | 5              |
| Armor       | 3              |
| Tools       | 3              |
| Ammo Pouch  | 1              |
{: .rtw-table .fixed-columns .centered-bold .half-width }

Heroes can store infinite Materials and Rupees in their pack.

If a Hero is wearing a piece of equipment (such as having an Armor or Weapon equipped), it does not count against their inventory capacity.

If an item doesn’t fit into any of the categories above, it is considered a Key Item. A Hero’s pack can store infinitely many Key Items.

## Ammunition and the Ammo Pouch

While the Ammo Pouch starts with only a single slot, don’t fret – any amount of a single type of ammunition counts as a single ‘slot’. This means that the starting Ammo Pouch can hold 10 Arrows, 100 Bombs, or 1,000 Fire Arrows. However, 1 Arrow and 1 Fire Arrow will not be able to both fit in that single slot in the Ammo Pouch – you would need two slots, one for each type of Ammunition.

## Upgrading a Pouch

Whenever heroes are able to craft, the Pouches in their Packs can be upgraded by paying Materials. The cost depends on how many slots the Pouch already has.

The *number* of Materials required is equal to (Number of slots the pouch currently has, modulo 5, plus 1). In layman’s terms, this means that going from 4 slots to 5 in a pouch costs 5 materials, going from 5 to 6 costs 1 material, and going from 9 to 10 slots also costs 5.

The *Rank* of Materials required is equal to (Number of slots the pouch currently has, divided by 5, rounded down to the nearest whole number). This means that every 5 slots, the Rank of material required to upgrade the pouch goes up by 1 – so going from 4 slots to 5 requires only Rank 0 Materials, but going from 9 to 10 slots requires Rank 1 materials. 

Upgrading a Pouch does *not* require access to a Forge. A Pouch cannot have more than 30 slots to it

| SLOTS | <span>#</span> MATS | RANK of MATS |
|-------|--------|--------------|
| 1     | 1      | 0            |
| 2     | 2      | 0            |
| 3     | 3      | 0            |
| 4     | 4      | 0            |
| 5     | 5      | 0            |
| 6     | 1      | 1            |
| 7     | 2      | 1            |
| 8     | 3      | 1            |
| 9     | 4      | 1            |
| 10    | 5      | 1            |
| 11    | 1      | 2            |
| 12    | 2      | 2            |
| 13    | 3      | 2            |
| 14    | 4      | 2            |
| 15    | 5      | 2            |
| 16    | 1      | 3            |
| 17    | 2      | 3            |
| 18    | 3      | 3            |
| 19    | 4      | 3            |
| 20    | 5      | 3            |
| 21    | 1      | 4            |
| 22    | 2      | 4            |
| 23    | 3      | 4            |
| 24    | 4      | 4            |
| 25    | 5      | 4            |
| 26    | 1      | 5            |
| 27    | 2      | 5            |
| 28    | 3      | 5            |
| 29    | 4      | 5            |
| 30    | 5      | 5            |
{: .rtw-table .centered-bold .fixed-columns .half-width }

*Cost of Upgrading a Pouch, in Cloth and/or Monster Part materials*
{: .centered }

## Creating a Pack

While all Heroes start with a Pack, they may on occasion need to create a new Pack. For instance, if they wash ashore on a deserted island, and their Pack (and its contents) were lost at sea.

They might do this if they wish to provide a Companion (such as their trusted steed) a way to carry additional inventory for them – as a Companion does not begin with a Pack, and thus has no way to carry large amounts of items for a Hero.

A new, *utterly pouch-less* Pack may be created by consuming 5 Materials (either Cloth or Monster Parts). This *does* require access to a Forge. This new Pack, unlike a Hero’s starting Pack, starts with no slots of any kind, and must be upgraded (per the above table) in order to carry anything.

Note that you cannot use additional Packs for additional inventory space on your Hero’s person – a creature may only carry one Pack. You cannot store Packs within Packs.

## Overflow Inventory

Finally, Heroes can carry a few additional items, above and beyond what their Pack can handle. They can carry a number of extra Weapons, Armor, Consumables, Tools, or stacks of Ammunition, equal to their Athletics score. These items may be in any of the above categories, mixed and matched as desired.

Beyond that limit, though, a Hero simply cannot carry more things. If a Hero’s Weapons pouch is full, and their Overflow Inventory is full, then they simply cannot carry another weapon without first disposing of one they’re already carrying.

Using your Overflow Inventory is just like using your Pack: placing an item in it, or taking an item out of it, is a Minor Action.

