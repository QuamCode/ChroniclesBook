# ⭐ Stats

### Armor 🛡

| Stat                        | Type   | Default | Description                                                                                                                                                           |
| --------------------------- | ------ | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Weightless Armor            | Value  | `0.0`   | Reduces damage from physical sources, not affected by Light/Heavy Armor skills. See [Armor](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#damage-) |
| Light Armor                 | Value  | `0.0`   | Reduces damage from physical sources, affected by Light Armor skill alone. See [Armor](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#damage-)      |
| Heavy Armor                 | Value  | `0.0`   | Reduces damage from physical sources, affected by Heavy Armor skill alone. See [Armor](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#damage-)      |
| Toughness                   | Value  | `0.0`   | Reduces damage from physical sources by 0.15 damage per point                                                                                                         |
| Armor Penetration           | Value  | `0.0`   | Offensive stat, your attacks deal damage as if your opponent has reduced armor. e.g. `5.0` Armor Penetration would reduce `10.0` Armor to `5.0` Armor                 |
| Armor Penetration (%)       | Scalar | `0.0`   | Offensive stat, your attacks deal damage as if your opponent has reduced armor. e.g. `0.5`(50%) Armor Penetration would reduce `20.0` Armor to `10.0` Armor           |
| Light Armor Penetration     | Value  | `0.0`   | Offensive stat, identical to Armor Penetration except it only works against Light Armor                                                                               |
| Light Armor Penetration (%) | Scalar | `0.0`   | Offensive stat, identical to Armor Penetration (%) except it only works against Light Armor                                                                           |
| Heavy Armor Penetration     | Value  | `0.0`   | Offensive stat, identical to Armor Penetration except it only works against Heavy Armor                                                                               |
| Heavy Armor Penetration (%) | Scalar | `0.0`   | Offensive stat, identical to Armor Penetration (%) except it only works against Heavy Armor                                                                           |

### Vanilla Attributes 🌎

| Stat                   | Type   | Default | Description                                                                                                                                            |
| ---------------------- | ------ | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Health                 | Value  | `0.0`   | Additional max HP                                                                                                                                      |
| Health Multiplier      | Scalar | `1.0`   | Additional multiplier on max HP (after health stat added)                                                                                              |
| Movement Speed         | Scalar | `1.0`   | Your movement speed                                                                                                                                    |
| Knockback Resistance   | Scalar | `0.0`   | Knockback taken from attacks                                                                                                                           |
| Attack Damage Bonus    | Value  | `1.0`   | Your default melee attack damage (even including fists)                                                                                                |
| Attack Speed           | Scalar | `1.0`   | Your melee attack speed                                                                                                                                |
| Luck                   | Value  | `0.0`   | Increases your luck, which influences loot drops and RNG mechanics. See [Luck](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#luck-) |
| Block Reach            | Value  | `5.0`   |                                                                                                                                                        |
| Step Height            | Value  | `0.5`   |                                                                                                                                                        |
| Scale                  | Scalar | `1.0`   |                                                                                                                                                        |
| Gravity                | Scalar | `1.0`   |                                                                                                                                                        |
| Safe Falling Distance  | Value  | `3.0`   | (1.20.5+) How far you'd need to fall to start taking fall damage                                                                                       |
| Fall Damage Multiplier | Scalar | `1.0`   | (1.20.5+) Virtually identical to Fall Damage Resistance except it doesn't affect kinetic damage from elytra collisions. Affects fall damage you take   |

### Damage 💥

| Stat                     | Type   | Default | Description                                                                                                                                                                                                |
| ------------------------ | ------ | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Damage Dealt             | Scalar | `1.0`   | Damage multiplier, both melee and ranged                                                                                                                                                                   |
| Melee Damage Dealt       | Scalar | `1.0`   | Melee damage multiplier                                                                                                                                                                                    |
| Ranged Damage Dealt      | Scalar | `1.0`   | Ranged damage multiplier                                                                                                                                                                                   |
| Unarmed Damage Dealt     | Scalar | `1.0`   | Damage multiplier when not wielding any weapon                                                                                                                                                             |
| Thrust Damage            | Scalar | `0.0`   | Damage multiplier based on velocity. `0.3`(30%) thrust damage will grant roughly 30% extra damage if the damager moves towards the target at sprint-jumping speed, and twice as much at twice the velocity |
| Light Armor Damage       | Scalar | `0.0`   | Damage multiplier for each piece of light armor the target is wearing                                                                                                                                      |
| Heavy Armor Damage       | Scalar | `0.0`   | Damage multiplier for each piece of heavy armor the target is wearing                                                                                                                                      |
| Fire Damage Bonus        | Value  | `0.0`   | Extra points of fire damage dealt                                                                                                                                                                          |
| Explosion Damage Bonus   | Value  | `0.0`   | Extra points of explosion damage dealt                                                                                                                                                                     |
| Poison Damage Bonus      | Value  | `0.0`   | Extra points of poison damage dealt                                                                                                                                                                        |
| Magic Damage Bonus       | Value  | `0.0`   | Extra points of magic damage dealt                                                                                                                                                                         |
| Lightning Damage Bonus   | Value  | `0.0`   | Extra points of lightning damage dealt                                                                                                                                                                     |
| Freezing Damage Bonus    | Value  | `0.0`   | Extra points of freezing damage dealt                                                                                                                                                                      |
| Radiant Damage Bonus     | Value  | `0.0`   | Extra points of radiant damage dealt                                                                                                                                                                       |
| Necrotic Damage Bonus    | Value  | `0.0`   | Extra points of necrotic damage dealt                                                                                                                                                                      |
| Bludgeoning Damage Bonus | Value  | `0.0`   | Extra points of bludgeoning damage dealt                                                                                                                                                                   |
| Fire Damage Dealt        | Scalar | `1.0`   | Fire damage multiplier                                                                                                                                                                                     |
| Explosion Damage Dealt   | Scalar | `1.0`   | Explosion damage multiplier                                                                                                                                                                                |
| Poison Damage Dealt      | Scalar | `1.0`   | Poison damage multiplier                                                                                                                                                                                   |
| Magic Damage Dealt       | Scalar | `1.0`   | Magic damage multiplier                                                                                                                                                                                    |
| Lightning Damage Dealt   | Scalar | `1.0`   | Lightning damage multiplier                                                                                                                                                                                |
| Freezing Damage Dealt    | Scalar | `1.0`   | Freezing damage multiplier                                                                                                                                                                                 |
| Radiant Damage Dealt     | Scalar | `1.0`   | Radiant damage multiplier                                                                                                                                                                                  |
| Necrotic Damage Dealt    | Scalar | `1.0`   | Necrotic damage multiplier                                                                                                                                                                                 |
| Bludgeoning Damage Dealt | Scalar | `1.0`   | Bludgeoning damage multiplier                                                                                                                                                                              |

### Combat ⚔



| Stat                       | Type       | Default   | Description                                                                                                                                                        |
| -------------------------- | ---------- | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Power Attack Damage        | Scalar     | `1.5`     | Damage multiplier when melee-attacking while falling (also known as Vanilla Crit)                                                                                  |
| Power Attack Radius        | Value      | `0.0`     | Radius in which power attack damage is spread to surrounding entities                                                                                              |
| Power Attack Splash Damage | Scalar     | `0.0`     | Fraction of power attack damage dealt to surrounding entities in the radius                                                                                        |
| Attack Reach               | Value      | `3.0`     | Melee attack reach                                                                                                                                                 |
| Attack Reach Multiplier    | Scalar     | `1.0`     | Melee attack reach multiplier                                                                                                                                      |
| Ranged Inaccuracy          | Value      | `10.0`    | Ranged inaccuracy value while shooting, each point of inaccuracy is roughly 2.7 degrees of spread                                                                  |
| Ranged Velocity            | Scalar     | `1.0`     | Velocity multiplier on shot projectiles                                                                                                                            |
| Knockback                  | Scalar     | `1.0`     | Knockback multiplier on attacks                                                                                                                                    |
| Immunity Frames            | Value      | `10.0`    | Immunity frames received after taking damage                                                                                                                       |
| Immunity Frame Multiplier  | Scalar     | `1.0`     | Immunity frame multiplier after taking damage                                                                                                                      |
| Bleed Chance               | Chance     | `0%`      | 🍀 (Affected by luck!) Chance to inflict bleeding. See [Bleeding](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#bleeding-)                      |
| Bleed Damage               | Value      | `2.0`     | Bleed damage per tick of bleeding                                                                                                                                  |
| Bleed Duration             | Game Ticks | `80` (2s) | Duration of bleeding                                                                                                                                               |
| Dodge Chance               | Chance     | `0%`      | Chance to avoid melee or ranged damage completely                                                                                                                  |
| Reflect Chance             | Chance     | `0%`      | 🍀 Chance to reflect damage back to the attacker                                                                                                                   |
| Reflect Damage             | Scalar     | `0.0`     | Fraction of damage reflected to the attacker if Reflect Chance procs                                                                                               |
| Dismount Chance            | Chance     | `0%`      | 🍀 Chance to forcefully dismount the victim if they are riding something                                                                                           |
| Stun Chance                | Chance     | `0%`      | 🍀 Chance to stun the victim entity. A stunned entity cannot be stunned again for 5 seconds afterwards                                                             |
| Stun Duration              | Game Ticks | `20` (1s) | Duration of stuns                                                                                                                                                  |
| Crossbow Magazine          | Value      | `3`       | Amount of times a crossbow can be instantly loaded up should "ammo preservation chance" proc many times in a row, afterwards it needs to be reloaded once manually |
| Shield Disarming           | Game Ticks | `0` (0s)  | Shield disabling duration after hitting                                                                                                                            |
| Life Steal                 | Scalar     | `0.0`     | The fraction of damage dealt converted to healing for the attacker                                                                                                 |

### Parry 🤺

| Stat                             | Type       | Default                         | Description                                                                                                                                                                                                |
| -------------------------------- | ---------- | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Parry Active Duration            | Game Ticks | `0` (0s)                        | Duration after activating "parry" for which the defender can successfully parry an attack. See [Light Weapons](https://github.com/Athlaeos/ValhallaMMO/wiki/Skills-&-Leveling-%F0%9F%94%BA#light-weapons-) |
| Parry Vulnerable Duration        | Game Ticks | `0` (0s)                        | Duration after activating "parry" for which the defender will be vulnerable to enemy attacks. Parry active duration takes priority over vulnerable duration.                                               |
| Parry Enemy Debuff Duration      | Game Ticks | `0` (0s)                        | The duration the attacking party will be debuffed for if parry deflects one of their melee attacks                                                                                                         |
| Parry Self Debuff Duration       | Game Ticks | `0` (0s)                        | The duration the defending party will be debuffed for if the enemy hits them during the Parry Vulnerable Duration while Parry Active Duration is expired                                                   |
| Parry Damage Reduction           | Scalar     | `1.0`                           | The damage multiplier taken when a defending party successfully parries an attack                                                                                                                          |
| Parry Cooldown                   | Game Ticks | <p><code>-1</code><br>(N/A)</p> | The cooldown of an attempted/failed parry                                                                                                                                                                  |
| Parry Success Cooldown Reduction | Game Ticks | `0` (0s)                        | How much a defending party's parry cooldown will be reduced if they successfully parry an attack                                                                                                           |

### Damage Resistances ⚜

| Stat                   | Type   | Default                                                                                           | Description                                                                                                                                                                                     |
| ---------------------- | ------ | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Damage Resistance      | Scalar | `0.0`                                                                                             | General damage resistance, lowers(or increases) damage taken from nearly all sources. Damage resistance will not mitigated VOID, SONIC\_BOOM, STARVATION, WORLD\_BORDER, or SUICIDE type damage |
| Melee Resistance       | Scalar | `0.0`                                                                                             | Damage reduction from melee attacks                                                                                                                                                             |
| Projectile Resistance  | Scalar | `0.0`                                                                                             | Damage reduction from projectiles                                                                                                                                                               |
| Bludgeoning Resistance | Scalar | `0.0`                                                                                             | Damage reduction from bludgeoning attacks                                                                                                                                                       |
| Fire Resistance        | Scalar | `0.0`                                                                                             | Damage reduction from fire                                                                                                                                                                      |
| Explosion Resistance   | Scalar | `0.0`                                                                                             | Damage reduction from explosions                                                                                                                                                                |
| Magic Resistance       | Scalar | `0.0`                                                                                             | Damage reduction from magic attacks                                                                                                                                                             |
| Poison Resistance      | Scalar | `0.0`                                                                                             | Damage reduction from poison                                                                                                                                                                    |
| Freezing Resistance    | Scalar | `0.0`                                                                                             | Damage reduction from freezing                                                                                                                                                                  |
| Lightning Resistance   | Scalar | `0.0`                                                                                             | Damage reduction from lightning                                                                                                                                                                 |
| Necrotic Resistance    | Scalar | See [Stats](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#mob-stats-%EF%B8%8F) | Damage reduction from necrotic damage                                                                                                                                                           |
| Radiant Resistance     | Scalar | See [Stats](https://github.com/Athlaeos/ValhallaMMO/wiki/Mechanics-%E2%9A%99#mob-stats-%EF%B8%8F) | Damage reduction from radiant damage                                                                                                                                                            |
| Crit Chance Resistance | Scalar | `0.0`                                                                                             | Reduces enemy Crit Chance by the given amount. If you have 0.5 crit resistance and the enemy has 50% crit chance, they will have 25% crit chance when attacking you                             |
| Crit Damage Resistance | Scalar | `0.0`                                                                                             | Reduces enemy Crit Damage by the given amount. If you have 0.5 crit damage resistance and the enemy has 100% crit damage, they will have 50% crit damage when attacking you                     |

### Utility ⛏

| Stat                         | Type          | Default | Description                                                                                                                                                                                                                                             |
| ---------------------------- | ------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Healing                      | Scalar        | `1.0`   | Multiplies any healing gained                                                                                                                                                                                                                           |
| Hunger Consumption Reduction | Chance/Scalar | `0.0`   | 🍀 If positive, acts as a chance to not spend hunger whenever you get hungrier. If negative, acts as a multiplier for the hunger you lost                                                                                                               |
| Cooldown Reduction           | Scalar        | `0.0`   | Reduces cooldowns for active abilities (such as Parry, Tree Capitator, Rage, etc.)                                                                                                                                                                      |
| Crafting Speed               | Scalar        | `0.0`   | Speeds up crafting for the "immersive" recipe type. The Lite configuration will not have any of these recipes, and so this stat does nothing. `time = baseTime * (1 / 1 + value)`                                                                       |
| Cooking Speed                | Scalar        | `0.0`   | Speeds up cooking of furnaces, blast furnaces, smokers, campfires, and cauldrons. `time = baseTime * (1 / 1 + value)`                                                                                                                                   |
| Ammo Consumption Reduction   | Chance        | `0.0`   | 🍀 Chance to not spend ammo. On crossbows it instantly reloads the crossbow                                                                                                                                                                             |
| Durability                   | Scalar        | `0.0`   | Effectively adds a chance to not spend durability similarly to how Unbreaking works, `chance = 1 / 1 + value`                                                                                                                                           |
| Entity Drops                 | Scalar        | `1.0`   | Multiplies mob drops                                                                                                                                                                                                                                    |
| Entity Luck                  | Value         | `0.0`   | Acts as luck specifically for custom mob drops that are affected by luck                                                                                                                                                                                |
| Jump Height                  | Scalar        | `1.0`   | Acts as a multiplier for jump height. It is known that this tends to act a little strangely, there is not much I can do against this as it is lag-related, but with 1.20.5 adding a jump height attribute this should be a lot smoother in that version |
| Multi-Jumps                  | Value         | `0`     | Allows jumping multiple times in mid-air, requires double-tapping spacebar to jump. If you have not spent all your jumps before landing, you will not take fall damage                                                                                  |
| Sneak Speed                  | Scalar        | `1.0`   | Multiplies sneak speed                                                                                                                                                                                                                                  |
| Sprint Speed                 | Scalar        | `1.0`   | Multiplies sprinting speed                                                                                                                                                                                                                              |
| Dig Speed                    | Scalar        | `1.0`   | Multiplies block breaking speed                                                                                                                                                                                                                         |
| Fishing Luck                 | Value         | `0.0`   | Increases luck while fishing                                                                                                                                                                                                                            |
| Fishing Speed                | Scalar        | `0.0`   | Speeds up fishing. `speed = baseSpeed * (1 / 1 + value)`                                                                                                                                                                                                |
| Explosion Power              | Scalar        | `1.0`   | Acts as a multiplier on TNT explosions lit off by you                                                                                                                                                                                                   |

### Food 🥩

| Stat            | Type   | Default | Description                         |
| --------------- | ------ | ------- | ----------------------------------- |
| Vegetable Bonus | Scalar | `1.0`   | Multiplies food value of vegetables |
| Seasoning Bonus | Scalar | `1.0`   | Multiplies food value of seasonings |
| Alcoholic Bonus | Scalar | `1.0`   | I think you get it                  |
| Beverage Bonus  | Scalar | `1.0`   |                                     |
| Spoiled Bonus   | Scalar | `1.0`   |                                     |
| Seafood Bonus   | Scalar | `1.0`   |                                     |
| Magical Bonus   | Scalar | `1.0`   |                                     |
| Sweet Bonus     | Scalar | `1.0`   |                                     |
| Grain Bonus     | Scalar | `1.0`   |                                     |
| Fruit Bonus     | Scalar | `1.0`   |                                     |
| Nut Bonus       | Scalar | `1.0`   |                                     |
| Dairy Bonus     | Scalar | `1.0`   |                                     |
| Fat Bonus       | Scalar | `1.0`   |                                     |

### Smithing 🔨

| Stat                   | Type   | Default | Description                                                                              |
| ---------------------- | ------ | ------- | ---------------------------------------------------------------------------------------- |
| General Quality        | Value  | `0.0`   | Increases the quality of all your crafted tools and armor                                |
| Wood Quality           | Value  | `0.0`   | Increases the quality of your wooden tools                                               |
| Leather Quality        | Value  | `0.0`   | Increases the quality of your leather armor                                              |
| Stone Quality          | Value  | `0.0`   | I think you, again, get it                                                               |
| Chainmail Quality      | Value  | `0.0`   |                                                                                          |
| Gold Quality           | Value  | `0.0`   |                                                                                          |
| Iron Quality           | Value  | `0.0`   |                                                                                          |
| Diamond Quality        | Value  | `0.0`   |                                                                                          |
| Netherite Quality      | Value  | `0.0`   |                                                                                          |
| Bow Quality            | Value  | `0.0`   |                                                                                          |
| Crossbow Quality       | Value  | `0.0`   |                                                                                          |
| Prismarine Quality     | Value  | `0.0`   | Increases the quality of items deemed made of prismarine, which usually is just Tridents |
| Enderic Quality        | Value  | `0.0`   | Increases the quality of items deemed enderic, which usually is just Elytras             |
| General Quality        | Value  | `0.0`   | Increases the quality of all your crafted tools and armor                                |
| Wood Quality (%)       | Scalar | `1.0`   | Multiplies your wood crafting skill                                                      |
| Leather Quality (%)    | Scalar | `1.0`   | Multiplies your leather crafting skill                                                   |
| Stone Quality (%)      | Scalar | `1.0`   | Yeeaaa yegeddit                                                                          |
| Chainmail Quality (%)  | Scalar | `1.0`   |                                                                                          |
| Gold Quality (%)       | Scalar | `1.0`   |                                                                                          |
| Iron Quality (%)       | Scalar | `1.0`   |                                                                                          |
| Diamond Quality (%)    | Scalar | `1.0`   |                                                                                          |
| Netherite Quality (%)  | Scalar | `1.0`   |                                                                                          |
| Bow Quality (%)        | Scalar | `1.0`   |                                                                                          |
| Crossbow Quality (%)   | Scalar | `1.0`   |                                                                                          |
| Prismarine Quality (%) | Scalar | `1.0`   |                                                                                          |
| Enderic Quality (%)    | Scalar | `1.0`   |                                                                                          |
| General EXP            | Scalar | `1.0`   | Multiplies Smithing Skill EXP                                                            |
| Wood EXP               | Scalar | `1.0`   | Multiplies Smithing Skill EXP gained when crafting wooden items                          |
| Leather EXP            | Scalar | `1.0`   | Multiplies Smithing Skill EXP gained when crafting leather items                         |
| Stone EXP              | Scalar | `0.5`   | myeah                                                                                    |
| Chainmail EXP          | Scalar | `0.5`   |                                                                                          |
| Gold EXP               | Scalar | `0.25`  |                                                                                          |
| Iron EXP               | Scalar | `0.25`  |                                                                                          |
| Diamond EXP            | Scalar | `0.15`  |                                                                                          |
| Netherite EXP          | Scalar | `0.1`   |                                                                                          |
| Bow EXP                | Scalar | `1.0`   |                                                                                          |
| Crossbow EXP           | Scalar | `1.0`   |                                                                                          |
| Prismarine EXP         | Scalar | `1.0`   |                                                                                          |
| Enderic EXP            | Scalar | `1.0`   |                                                                                          |

### Alchemy ⚗

| Stat                             | Type   | Default | Description                                                                                                                                                                   |
| -------------------------------- | ------ | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| General Quality                  | Value  | `0.0`   | Increases the quality of all your brewed potions and poisons                                                                                                                  |
| Poison Quality                   | Value  | `0.0`   | Increases the quality of all your brewed poisons                                                                                                                              |
| Potion Quality                   | Value  | `0.0`   | Increases the quality of all your brewed (beneficial) potions                                                                                                                 |
| General Quality (%)              | Scalar | `1.0`   | Multiplies the quality of all your brewed potions and poisons                                                                                                                 |
| Poison Quality (%)               | Scalar | `1.0`   | Multiplies the quality of all your brewed poisons                                                                                                                             |
| Potion Quality (%)               | Scalar | `1.0`   | Multiplies the quality of all your brewed (beneficial) potions                                                                                                                |
| Brewing Speed                    | Scalar | `0.0`   | Speeds up brewing, \`speed = baseSpeed \* (1 / 1 + value)                                                                                                                     |
| Ingredient Consumption Reduction | Chance | `0%`    | 🍀 Grants a chance to not spend an ingredient while brewing. Saved ingredients are ejected from the top of the brewing stand                                                  |
| Potion Consumption Reduction     | Chance | `0%`    | 🍀 Grants a chance to not spend a drunk or thrown potion                                                                                                                      |
| Throwing Force                   | Scalar | `0.0`   | Acts as a multiplier for thrown object velocity. Also affects snowballs, eggs, ender pearls, etc.                                                                             |
| Splash Intensity                 | Value  | `0.0`   | Acts as a minimum strength value for splash potions. Normally potion intensity goes down quickly with distance, this stat will put a minimum intensity regardless of distance |
| Lingering Duration               | Scalar | `0.0`   | Acts as a multiplier for the duration a lingering potion will stay on the ground                                                                                              |
| Lingering Radius                 | Scalar | `0.0`   | Acts as a multiplier for the radius of a lingering potion. Radius also increases how many times a lingering potion's can be absorbed by nearby entities                       |
| Alchemy EXP                      | Scalar | `1.0`   | Multiplies Alchemy Skill EXP                                                                                                                                                  |

### Enchanting 🎇

| Stat                            | Type   | Default | Description                                                                                                                  |
| ------------------------------- | ------ | ------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Enchanting Quality              | Value  | `0.0`   | Increases your enchanting ability                                                                                            |
| Enchanting Quality (%)          | Scalar | `1.0`   | Multiplies your enchanting ability                                                                                           |
| Anvil Quality                   | Value  | `0.0`   | Increases your anvil combining ability. Follows the same rule as enchantment scalings                                        |
| Anvil Quality (%)               | Scalar | `1.0`   | Multiplies your anvil combining ability                                                                                      |
| Enchanting Amplification Chance | Chance | `100%`  | Determines the chance for each individual enchantment on an item to be enhanced/debuffed by your (lack of) enchanting skill  |
| Lapis Consumption Reduction     | Chance | `0%`    | 🍀 Your chance to not spend lapis lazuli during enchanting                                                                   |
| EXP Orb Multiplier              | Scalar | `0.7`   | Multiplies vanilla EXP orbs obtained. EXP orbs from the grindstone are not amplified                                         |
| EXP Orb Refund Chance           | Chance | `100%`  | Chance to have EXP orbs refunded during the enchantment process                                                              |
| EXP Orb Refund Amount           | Scalar | `0.0`   | Amount of EXP orbs refunded after enchanting something. A multiplier applied on however much EXP you spent during enchanting |
| Enchanting EXP                  | Scalar | `1.0`   | Multiplies Enchanting Skill EXP                                                                                              |

### Farming 🌾

| Stat           | Type   | Default | Description                                                          |
| -------------- | ------ | ------- | -------------------------------------------------------------------- |
| Butchery Drops | Scalar | `1.0`   | Multiplies butchery drops                                            |
| Farming Drops  | Scalar | `1.0`   | Multiplies farming drops                                             |
| Farming Luck   | Value  | `0.0`   | Additional luck for custom farming drops if they're affected by luck |
| Farming EXP    | Scalar | `1.0`   | Multiplies Farming Skill EXP                                         |

### Mining ⛏

| Stat           | Type   | Default | Description                                                           |
| -------------- | ------ | ------- | --------------------------------------------------------------------- |
| Mining Drops   | Scalar | `0.7`   | Multiplies mining drops                                               |
| Mining Luck    | Value  | `0.0`   | Additional luck for custom mining drops if they're affected by luck   |
| Blasting Drops | Scalar | `1.0`   | Multiplies drops for blocks broken by TNT                             |
| Blasting Luck  | Value  | `0.0`   | Additional luck for custom blasting drops if they're affected by luck |
| Mining EXP     | Scalar | `1.0`   | Multiplies Mining Skill EXP                                           |

### Digging ⚒

| Stat             | Type   | Default | Description                                                                                                         |
| ---------------- | ------ | ------- | ------------------------------------------------------------------------------------------------------------------- |
| Digging Drops    | Scalar | `1.0`   | Multiplies digging drops                                                                                            |
| Digging Luck     | Value  | `0.0`   | Additional luck for custom digging drops, granting a rare chance to drop metal nuggets, diamonds, bones, and others |
| Archaeology Luck | Value  | `0.0`   | Additional luck for custom archaeology drops if they're affected by luck                                            |
| Digging EXP      | Scalar | `1.0`   | Multiplies Digging Skill EXP                                                                                        |

### Woodcutting 🪓

| Stat              | Type   | Default | Description                                                                                                                            |
| ----------------- | ------ | ------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Woodcutting Drops | Scalar | `1.0`   | Multiplies woodcutting drops                                                                                                           |
| Woodcutting Luch  | Value  | `0.0`   | Additional luck for custom woodcutting drops, which currently just means you sometimes get golden apples or crystal apples from leaves |
| Woodcutting EXP   | Scalar | `1.0`   | Multiplies Woodcutting Skill EXP                                                                                                       |

### Fishing 🎣

| Stat        | Type   | Default | Description                  |
| ----------- | ------ | ------- | ---------------------------- |
| Fishing EXP | Scalar | `1.0`   | Multiplies Fishing Skill EXP |

### Archery 🏹

| Stat        | Type   | Default | Description                  |
| ----------- | ------ | ------- | ---------------------------- |
| Archery EXP | Scalar | `1.0`   | Multiplies Archery Skill EXP |

### Light Armor ⚔

| Stat            | Type   | Default | Description                      |
| --------------- | ------ | ------- | -------------------------------- |
| Light Armor EXP | Scalar | `1.0`   | Multiplies Light Armor Skill EXP |

### Heavy Armor ⚒

| Stat            | Type   | Default | Description                      |
| --------------- | ------ | ------- | -------------------------------- |
| Heavy Armor EXP | Scalar | `1.0`   | Multiplies Heavy Armor Skill EXP |

### Light Weapons ⚔

| Stat              | Type   | Default | Description                        |
| ----------------- | ------ | ------- | ---------------------------------- |
| Light Weapons EXP | Scalar | `1.0`   | Multiplies Light Weapons Skill EXP |

### Heavy Weapons ⚒

| Stat              | Type   | Default | Description                        |
| ----------------- | ------ | ------- | ---------------------------------- |
| Heavy Weapons EXP | Scalar | `1.0`   | Multiplies Heavy Weapons Skill EXP |
