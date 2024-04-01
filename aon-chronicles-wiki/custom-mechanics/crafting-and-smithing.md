# 🔨 Crafting & Smithing

Crafting any tool or piece of armor will grant it a **quality** value. This quality value is equal to your generic Smithing quality stat PLUS your Smithing quality stat for the material the item is made out of.

Each item has a "neutral" quality as well, it's not very important to know how it works but in a nutshell it defines the quality tooltip displayed on the item. This neutral quality is also used to define when an item's stats should be equal to vanilla stats.

| Material Type | Neutral Quality |
| ------------- | --------------- |
| Wood          | `50`            |
| Leather       | `50`            |
| Stone         | `80`            |
| Chainmail     | `80`            |
| Bows          | `80`            |
| Gold          | `110`           |
| Iron          | `110`           |
| Diamond       | `140`           |
| Prismarine    | `155`           |
| Netherite     | `170`           |
| Enderic       | `185`           |

The quality tooltip is determined based on how much the item's quality differs from its neutral quality. If a wooden pickaxe has 90 quality for example, it'll have +40 compared to its neutral quality. The table below shows which tooltip it will be given.

| Quality Difference | Tooltip   |
| ------------------ | --------- |
| -500               | Terrible  |
| -60                | Shoddy    |
| -30                | Decent    |
| 0                  | Good      |
| 30                 | Great     |
| 60                 | Flawless  |
| 90                 | Masterful |
| 120                | Fabled    |
| 150                | Peerless  |

The 90-quality wooden pickaxe would be "Great", because +40 is more than 30 but less than 60.\
For an item to be considered "Peerless" it needs to be at least 150 quality above its neutral quality, meaning that a Peerless wooden pickaxe is far less impressive than a Peerless netherite pickaxe as the wooden pickaxe only needs 200 quality whereas a netherite pickaxe needs 320.

### How to gain Smithing quality



Leveling up grants you `1.5` Smithing quality to your items, up to `150` at level 100.

The Smithing skill tree (see /skills) has perks each granting `+50` quality to a specific material.

The final perk of the Smithing skill tree grants you another `+50` to everything.

So leveling to 100 alone grants you a total of `250` Smithing quality, but there are ways to push past this.\
\


You can reset Smithing and enter NewGame+, granting you a permanent `+50` quality per loop, for a total of `+100` should you choose to do this twice.

Leveling Woodcutting eventually grants you access to Crystal Apples, which give you `+50` Smithing quality (among other things) for 30 seconds when eaten.

If EnchantsSquared happens to be installed, it adds the "Forgemaster" enchantment which (at max level 3) grants another `+50` Smithing quality.

That means you can accumulate a total of `450` Smithing quality assuming the default configuration. The plugin was balanced around 300 being the assumed max, so you can get some pretty overpowered stuff doing this.

### The impact of Smithing quality on items

The item's neutral quality as mentioned above is an indicator when your crafted items do not receive buffs or debuffs for their quality. The only exception to this is netherite, which will have the same scaling as diamond equipment.

| Stat                 | Scaling Description                             | Exceptions                                                                                                                             |
| -------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Armor                | 1-1.5x armor from `neutral`-300 quality         |                                                                                                                                        |
| Toughness            | 1-2x toughness from `neutral`-300 quality       |                                                                                                                                        |
| Attack Damage        | +0-4 damage from `neutral`-300 quality          | For rapiers this is +0-2 and for greataxes this is +0-6 instead. See [Custom Weapons](stats/how-it-all-works-out....md#custom-weapons) |
| Attack Speed         | +0-0.2 attack speed from `neutral`-300 quality  | For greataxes this is +0-0.1 instead, and rapiers have no attack speed scaling                                                         |
| Dig Speed            | +0-50% digging speed from `neutral`-300 quality |                                                                                                                                        |
| Bludgeoning Damage   | +0-3.5 damage from `neutral`-300 quality        | For warhammers this is +0-4 instead                                                                                                    |
| Knockback Resistance | 1-2x resistance from `neutral`-300 quality      |                                                                                                                                        |
