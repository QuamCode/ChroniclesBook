# 📠 How it all works out...

### Custom Weapons 🗡

**Rapiers** (light)

* 🟢 Very high attack speed
* 🟢 High armor penetration
* 🟢 High immunity reduction
* 🔴 No knockback
* 🔴 Very low damage

**Daggers** (light)

* 🟢 High attack speed
* 🟢 High critical strike chance
* 🔴 Low attack reach

**Maces** (light)

* 🟢 Stun chance
* 🟠 Deals (slightly lower) bludgeoning damage (good against armored targets)

**Greataxes** (heavy)

* 🟢 Very high damage
* 🟢 High critical strike chance
* 🔴 Very low attack speed

**Warhammers** (heavy)

* 🟢 Stun chance
* 🟠 Deals high bludgeoning damage
* 🟠 High knockback

**Spears** (heavy)

* 🟢 High attack reach
* 🟢 Deals increased damage the faster you approach the target while attacking
* 🔴 Low damage for a heavy weapon

### Luck 🍀

Each point of luck you have grants you _1 re-roll_ with most things related to RNG for a favorable outcome.\
For example, if you fail a 20% chance to critically hit, you get another 20% chance to do it again!\
The opposite, however, is also true. Where negative luck means if you succeed you get 1 re-roll in favor of a negative outcome.

| -2 Luck       | -1 Luck     | Base Chance | 1 Luck | 2 Luck |
| ------------- | ----------- | ----------- | ------ | ------ |
| _**0.0125%**_ | _**0.25%**_ | 5%          | 9.7%   | 14.2%  |
| _**0.1%**_    | _**1%**_    | 10%         | 19%    | 27.1%  |
| _**0.33%**_   | _**2.25%**_ | 15%         | 27.7%  | 38.5%  |
| _**0.8%**_    | _**4%**_    | 20%         | 36%    | 48.8%  |
| _**2.7%**_    | _**9%**_    | 30%         | 51%    | 65.7%  |
| _**6.4%**_    | _**16%**_   | 40%         | 64%    | 74.4%  |
| _**12.5%**_   | _**25%**_   | 50%         | 75%    | 87.5%  |
| _**21.6%**_   | _**36%**_   | 60%         | 84%    | 93.6%  |
| _**34.4%**_   | _**49%**_   | 70%         | 91%    | 97.3%  |
| _**51.2%**_   | _**64%**_   | 80%         | 96%    | 99.2%  |
| _**72.9%**_   | _**81%**_   | 90%         | 99%    | 99.9%  |

For negative luck, the chance for success is (chanceluck )\
For positive luck, the chance for success if (1 - (1 - chance)luck )

To see which stats are affected by luck, check the [stats](https://github.com/Athlaeos/ValhallaMMO/wiki/Stats) page

Due to how much effect it has on various parts of the game, Luck is one of the most powerful stats to get

***

### Bleeding 🩸

Bleeding is a status effect that may be inflicted. It has a **Chance to inflict**, **Duration**, and **Tick Damage**.\
When bleeding is inflicted it deals **Tick Damage** amount of damage every 40 ticks. Bleeding damage ignores armor.

When bleeding is inflicted while a target is already bleeding, the duration is refreshed and the tick rate speeds up by 5 ticks, up to 4 times.\
So if bleeding is inflicted 5 times in a short enough time, the victim will bleed twice as fast.

***

### Mob Stats 🧟‍♂️

**Radiant Damage**\
Can be seen as "Smite" damage, though the Smite enchantment does not deal radiant damage.\
Deals 2x damage against undead and 1.5x damage to nether mobs, but 0x damage to everything else.

**Necrotic Damage**\
The "Wither" debuff now deals necrotic damage.\
Deals 1x damage against everything, except 0.5x damage to nether mobs and 0x damage to undead.

**Scaling**\
Spawned mobs scale with the level of the average of all surrounding players. They're given a level up to 5 levels away from the local average.\
Mobs gain increased stats based on their given level.\


| Stat              | Scaling                  | Description                                                      |
| ----------------- | ------------------------ | ---------------------------------------------------------------- |
| Armor             | `0.2 * level`            | <p>10 armor every 50 levels<br></p>                              |
| Damage            | `-0.2 + (0.023 * level)` | <p>-30% damage initially, increases up to +200% at lv100<br></p> |
| Health            | `-0.3 + (0.033 * level)` | <p>-30% health initially, increases up to +300% at lv100<br></p> |
| Armor Penetration | `0.005 * level`          | <p>up to 50% armor penetration at lv100<br></p>                  |
| Crit Chance       | `0.005 * level`          | <p>up to 50% crit chance at lv100<br></p>                        |
| Crit Damage       | `0.5`                    | critical hits by mobs do 50% more damage                         |

Additional Scaling's

| Mob Type                                  | Stat                                                                                                                                 | Scaling                                                                                                               | Description                                                                                                                                                                  |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Zombie<br>(and related)</p>            | <p>Fire Resistance<br>Poison Resistance<br>Bleeding Resistance</p>                                                                   | <p><code>-0.5</code><br><code>0.5</code><br><code>0.5</code></p>                                                      | <p>+50% Fire Damage Taken<br>-50%Poison Damage Taken<br>-50% Bleeding Damage Taken</p>                                                                                       |
| <p>Drowned<br>(inherits Zombie stats)</p> | Fire Resistance                                                                                                                      | `0`                                                                                                                   | No weakness to fire                                                                                                                                                          |
| <p>Husk<br>(inherits Zombie stats)</p>    | Fire Resistance                                                                                                                      | `0.3`                                                                                                                 | -30% Fire Damage Taken                                                                                                                                                       |
| Skeleton                                  | <p>Fire Resistance<br>Melee Resistance<br>Explosion Resistance<br>Falling Resistance<br>Poison Resistance<br>Bleeding Resistance</p> | <p><code>-1</code><br><code>-0.5</code><br><code>-1</code><br><code>-1</code><br><code>1</code><br><code>1</code></p> | <p>+100% Fire Damage Taken<br>+50% Melee Damage Taken<br>+100% Explosion Damage Taken<br>+100% Fall Damage Taken<br>Immune to Poison Damage<br>Immune to Bleeding Damage</p> |
| Wither Skeleton                           | <p>Poison Resistance<br>Bleeding Resistance</p>                                                                                      | <p><code>1</code><br><code>1</code></p>                                                                               | <p>Immune to Poison Damage<br>Immune to Bleeding Damage</p>                                                                                                                  |
| Spider                                    | Poison Resistance                                                                                                                    | `0.5`                                                                                                                 | -50% Poison Damage Taken                                                                                                                                                     |
| Cave Spider                               | <p>Poison Resistance<br>Melee Resistance</p>                                                                                         | <p><code>1</code><br><code>-0.5</code></p>                                                                            | <p>Immune to Poison Damage<br>+50% Melee Damage Taken</p>                                                                                                                    |

In exchange, leveled mobs drop extra EXP orbs according to `0.02 * level` (+200% dropped EXP orbs at lv100)

***

### Damage 💥

Damage taken is defined by the following formula

```
damageTaken * (1 - typeResistance) * (1 - trueResistance)
```

Where typeResistance is whatever your total resistance stat is versus the specific damage type, and trueResistance being your generic damage resistance stat.\
\
If this damage happens to be physical, the following multiplier is applied again:

```
resistedDamage * max(0.1, (15 / (15 + armor)) - (toughness * 0.15))
```

Physical damage are all reduced by armor, but some sources may be more effective against armor than others.\
If a source has, for example, 50% armor efficiency that means you'll be taking damage from that source as if you were wearing half as much armor.\
\
Physical damage sources are:

* Projectile
* Falling blocks (anvil)
* Bludgeoning (at 70% armor efficiency)
* Melee Attacks
* Sweeping Attacks
* Explosions (at 70% armor efficiency)
* Contact (cacti)
* Falling
* Lava (at 50% armor efficiency)

In simpler terms, every 15 armor the player has increases their _effective_ HP by 100%.

Effective HP being the amount of raw damage you can take before death.\
If you have 10 hearts of health and have 10 armor, that means you can take 20 hearts of health in damage before dying. 20 armor would make that 30 health, 30 armor 40 health, etc. Each 15 armor is an extra HP bar worth of damage you can take.

Damage is further reduced by toughness, a flat 0.15 damage reduction for each point of toughness you have. That means that with 10 armor toughness, 4 damage is reduced to 2.5. That makes armor toughness especially effective against low damage hits, but rather ineffective against high damage hits.

Armor can be reduced by enemy armor penetration. This can be flat penetration or % penetration, flat penetration reducing your armor by a static amount and % penetration reducing your armor by a fraction of itself. 5 flat penetration would reduce your 10 armor to 5, and 10% penetration would reduce 10 armor to 9.

Armor cannot reduce damage taken to below 10% of the original damage taken, so there is an armor cap of 150 armor (ignoring toughness)

The damage you take after all those calculations is then further reduced by your aforementioned resistances.
