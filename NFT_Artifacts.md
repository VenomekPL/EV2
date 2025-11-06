# Artifacts NFT

## Overview

Artifacts are non-purchasable, tradeable NFTs that function as specialized modifier trinkets in EV2. Implemented as ERC-998 composable NFTs, Artifacts are equipped into suit power slots to provide dynamic gameplay modifications. Artifacts work similarly to armor and relics in traditional looter-shooters—temporary bonuses and effects that are active only while equipped. Removing an Artifact immediately deactivates its effects, making Artifact selection crucial for mission optimization and playstyle specialization.

---

## Artifact System Overview

### ERC-998 Composable NFTs

Artifacts utilize ERC-998 standard for advanced functionality:

- **Composable Assets**: Artifacts are bound to suits while equipped
- **Detachable Modifications**: Remove artifact to disable effects
- **Persistent Ownership**: Artifacts remain player property when unequipped
- **On-Chain Verification**: All artifact properties and bindings recorded on blockchain
- **True Ownership**: Players control artifact transfers and trades
- **Flexible Slots**: Different artifact types fit different equipment slots

### Equipment Slot System

Each suit has multiple power slots for artifact equipping:

- **Slot Types**: Different slot categories for different artifact types
- **Limited Slots**: Suit power capacity constrains number of equipped artifacts
- **Slot Specialization**: Certain artifacts only fit specific slots
- **Flexibility**: Choose which artifacts to equip for current mission
- **Hot-Swapping**: Remove and equip different artifact combinations
- **Synergy Optimization**: Combine artifacts for powerful effect stacking

---

## Artifact Types & Slot Categories

### Slot Categories

*Specific slot names and quantities to be determined by development team*

Potential slot categories may include:

- **Power Core Slot**: Central performance modifications
- **Shield Module Slot**: Defensive capability enhancements
- **Reactor Slot**: Energy generation and management
- **Armor Plate Slot**: Structural reinforcement
- **Targeting System Slot**: Weapon and aiming optimization
- **Movement Module Slot**: Mobility and traversal enhancement
- **Auxiliary Slot**: Miscellaneous effect modifications
- **Special Ability Slot**: Unique powerful effects
- *Additional slots to be designed by development team*

### Artifact Rarity & Power

Like weapons and suits, artifacts spawn at different rarity tiers:

- **Common**: Basic modifications, accessible passive bonuses
- **Uncommon**: Improved effects and broader application
- **Rare**: Notable bonuses with specific specialization
- **Epic**: Powerful modifications enabling strong builds
- **Legendary**: Exceptional effects with rare stat combinations
- **Exotic**: Extremely rare artifacts with unique mechanics

---

## Artifact Modification Categories

### Defensive Artifacts

Protect and enhance suit durability:

#### Example Artifact Modifications

- **Reinforced Plating**: +15% armor value
- **Shield Regeneration**: Restore armor over time out of combat
- **Damage Reflection**: Reflect 5% of incoming damage back to attackers
- **Resistance Module**: +20% resistance to specific damage type (fire, electric, etc.)
- **Structural Integrity**: Reduce damage from environmental hazards
- **Knockback Resistance**: Reduce knockback from explosions
- **Status Effect Immunity**: Prevent specific status effects (stun, freeze, etc.)
- **Last Stand**: Temporary invulnerability when armor drops below 20%
- *Additional defensive artifacts to be designed by development team*

### Offensive Artifacts

Enhance combat performance and damage output:

#### Example Artifact Modifications

- **Damage Amplification**: +20% weapon damage
- **Critical Chance**: +15% critical hit chance
- **Critical Damage**: +50% damage on critical hits
- **Elemental Mastery**: +25% damage with status effect weapons
- **Armor Piercing**: +30% damage against armored targets
- **Headshot Bonus**: +40% damage on precise shots
- **Weakness Exploitation**: +50% damage to status-affected enemies
- **Kill Streak Bonus**: Increase damage +5% per consecutive kill (stacks up to 50%)
- *Additional offensive artifacts to be designed by development team*

### Utility Artifacts

Provide practical gameplay conveniences and advantages:

#### Example Artifact Modifications

- **Extended Ammo Capacity**: +30% magazine size
- **Faster Reload**: -25% reload time
- **Loot Magnet**: Increased loot pickup range
- **Experience Boost**: +20% XP from missions
- **Resource Efficiency**: Consumables last 25% longer
- **Equipment Proficiency**: Switch weapons 40% faster
- **Compass Navigation**: Mini-map reveals nearby loot
- **Cooldown Reduction**: Reduce ability cooldowns by 15%
- *Additional utility artifacts to be designed by development team*

### Mobility Artifacts

Enhance movement and traversal capabilities:

#### Example Artifact Modifications

- **Flight Speed**: +30% maximum flight velocity
- **Maneuverability**: +25% agility and turning speed
- **Dash Distance**: Dash abilities cover 40% more ground
- **Jump Height**: +50% vertical jump capability
- **Hover Duration**: Extend hover time by 5 seconds
- **Sprint Speed**: +35% running speed
- **Fall Damage Reduction**: Reduce fall damage by 50%
- **Air Control**: Maintain better control while airborne
- *Additional mobility artifacts to be designed by development team*

### Support Artifacts

Enable team assistance and social benefits:

#### Example Artifact Modifications

- **Healing Aura**: Nearby allies regenerate 2% armor per second
- **Damage Buff Aura**: Allies nearby gain +15% damage
- **Revive Range**: Extend revive ability range by 50%
- **Shared Resources**: Nearby allies gain 20% ammo efficiency
- **Team XP Share**: Allies gain 10% bonus XP from your kills
- **Buff Duration**: Extend buff effects to nearby allies by 5 seconds
- **Support Focus**: Gain bonus XP for assisting teammates
- **Rally Call**: Teammates gain +25% movement speed for 10 seconds (cooldown: 30s)
- *Additional support artifacts to be designed by development team*

### Specialist Artifacts

Unique niche modifications for specific playstyles:

#### Example Artifact Modifications

- **Stealth Enhancement**: Reduce detection radius by 40%
- **Thermal Signature**: Reduce heat detection by 50%
- **Hive Attunement**: +40% damage specifically vs Hive creatures
- **Machine Slayer**: +35% effectiveness against robotic enemies
- **Environmental Mastery**: Blend into specific environments
- **Tactical Network**: Reveal enemy positions to teammates
- **Resource Scavenging**: Find additional crafting materials
- **Rare Loot Enhancement**: Triple rare loot drop chance
- *Additional specialist artifacts to be designed by development team*

---

## Artifact Synergies & Builds

### Slot Synergy

Different artifact combinations unlock powerful effects:

#### Example Synergy: "The Tank Destroyer"

- **Power Core Slot**: Armor Piercing (+30% armor-piercing damage)
- **Targeting System Slot**: Weakness Exploitation (+50% vs status-affected)
- **Reactor Slot**: Damage Amplification (+20% all damage)
- **Synergy Effect**: Combine for 100%+ damage vs armored, status-affected enemies
- **Result**: Specialized anti-tank build devastating for boss fights

#### Example Synergy: "The Support Guardian"

- **Power Core Slot**: Team Heal (regenerate nearby allies)
- **Shield Module Slot**: Healing Aura (passive ally regeneration)
- **Armor Plate Slot**: Reinforced Plating (absorb damage for team)
- **Special Ability Slot**: Rally Call (emergency team boost)
- **Result**: Unkillable support pilot enabling squad persistence

#### Example Synergy: "The Ghost Operative"

- **Movement Module Slot**: Flight Speed (+30%)
- **Targeting System Slot**: Stealth Enhancement (reduce detection)
- **Auxiliary Slot**: Thermal Signature (reduce heat detection)
- **Special Ability Slot**: Equipment Proficiency (faster switching)
- **Result**: Invisible infiltrator capable of surgical strikes

### Pilot-Artifact Chemistry

Artifacts synergize with pilot feats:

- Pilots with "Tough" feat gain extra value from defensive artifacts
- Precision specialist pilots amplify offensive artifact bonuses
- Support pilots enable team artifacts to shine
- Different pilot/artifact combinations create unique playstyles

### Suit-Artifact Compatibility

Different suits favor different artifacts:

- Tank suits maximize value from armor-focused artifacts
- Scout suits excel with mobility artifacts
- Support suits amplify team-oriented artifacts
- Specialist suits unlock niche artifact combinations

---

## Artifact Acquisition

### Gameplay Drops

Artifacts earned through combat and exploration:

- **Enemy Drops**: Defeated enemies drop artifact blueprints
- **Boss Rewards**: Challenging encounters grant powerful artifacts
- **Loot Chests**: Hidden containers contain rare artifacts
- **Event Rewards**: Limited-time events distribute exclusive artifacts
- **Challenge Completion**: Difficult tasks unlock special artifacts
- **Dungeons/Raids**: Cooperative missions reward top-tier artifacts

### Artifact Blueprints

Like weapons, most artifacts drop as blueprints:

- **Blueprint Collection**: Combine with materials to craft NFT
- **Rarity Variation**: Blueprints spawn at different rarity tiers
- **Duplicate Drops**: Same blueprint found multiple times
- **Crafting Process**: Convert to NFT using [In-Game_Currency_Rewards](In-Game_Currency_Rewards.md)
- **Account-Bound Initially**: Become tradeable after minting

### Secondary Market Trading

For details on artifact trading, valuation, and pricing dynamics, see [Second-Hand Economy](Second-Hand Economy.md).

---

## Artifact Progression & Leveling

### Experience Accumulation

Artifacts gain experience while equipped:

- **Combat XP**: Equipped artifacts earn XP from combat activities
- **Mission Performance**: Completion and objectives grant artifact XP
- **On-Chain Recording**: All progression verified on blockchain
- **Permanent Growth**: Artifact level never resets
- **Usage-Based Scaling**: More active use = faster leveling

### Level-Based Enhancements

Artifacts improve as they level:

- **Effect Scaling**: Passive effects become stronger
- **Duration Extension**: Temporary effects last longer
- **Cooldown Reduction**: Activated abilities recharge faster
- **Potency Increase**: Bonuses increase in magnitude
- **Unlock New Tiers**: High-level artifacts unlock additional modifications

### Leveled Artifact Value

High-level artifacts command premium prices on secondary market:

- See [Second-Hand Economy](Second-Hand Economy.md) for artifact valuation details
- Fully leveled rare artifacts extremely sought-after
- Specific level/rarity combinations highly valuable
- Represents significant player investment in optimization

---

## Equipped vs Unequipped States

### Equipment Mechanics

- **Instantly Active**: Equip artifact to immediately activate benefits
- **Instantly Inactive**: Remove artifact to immediately deactivate benefits
- **Hot-Swapping**: Switch between different artifact combinations
- **No Downtime**: Equiping/unequipping takes negligible time
- **Mission Optimization**: Choose artifacts before each mission type

### Mission-Specific Loadouts

Players optimize artifact combinations for different content:

- **PvE Dungeons**: Equip defensive and utility artifacts
- **PvP Arenas**: Equip offensive and mobility artifacts
- **Boss Raids**: Equip specialized anti-boss artifacts
- **Support Role**: Equip team-assistance artifacts
- **Casual Exploration**: Mix for balanced playstyle

### Permanent Ownership

- Artifacts remain player property when unequipped
- Stored in inventory like weapons and suits
- Can be equipped to any compatible suit
- Tradeable on secondary market anytime
- No loss of progression from unequipping

---

## NFT Specifications

- **Asset Type**: Non-purchasable, tradeable NFT
- **Standard**: ERC-998 Composable NFT
- **Acquisition**: Earned through gameplay as blueprints, then crafted/minted
- **Blockchain Verified**: All artifact properties and modifications recorded on-chain
- **Equipment State**: On-chain record of which suit currently equips artifact
- **Leveling History**: Complete usage and progression history on blockchain
- **Resale**: Fully tradeable on secondary markets
- **Permanence**: Artifact data stored permanently on blockchain

---

## Economic Impact

### Continuous Engagement

- Multiple artifact types encourage collection
- Different artifacts for different missions
- Build optimization pursuit
- High-level artifact hunting
- Secondary market activity

### Artifact Grinding Incentive

- Artifacts core to endgame optimization
- Build crafting central to progression
- Artifact hunting rewarding long-term play
- Level grinding meaningful
- Synergy discovery engaging

### Secondary Market Sustainability

- Artifacts constantly crafted from blueprints
- High rarity artifacts always in demand
- Leveled artifacts very valuable
- Specific synergy combinations sought-after
- Vibrant marketplace from artifact economy

---

## Design Flexibility

### Artifact Slot Customization

Game developers can create custom slots:

- **Limited Creativity**: Suit architects define available slots
- **Balancing Tool**: Slot quantity balances artifact power
- **Specialization Options**: Unique slots enable niche strategies
- **Future Expansion**: New slots added with content updates
- *Specific slots to be designed by development team*

### Artifact Modification Range

Extensive modification possibilities:

- **Stat Bonuses**: Simple percentage increases to existing stats
- **New Mechanics**: Entirely new gameplay systems tied to artifacts
- **Synergy Effects**: Artifacts interact with pilot feats and suit abilities
- **Status Effects**: Grant powerful status modifications
- **Transformative**: Change fundamental suit behavior
- *Specific modifications determined by development team*

---

## Related Documentation

- [NFT_Mech_Suits](NFT_Mech_Suits.md) - Suits that equip artifacts
- [NFT_Mech_Pilots](NFT_Mech_Pilots.md) - Pilots utilizing artifact synergies
- [NFT_Weapons](NFT_Weapons.md) - Weapons used alongside artifact builds
- [In-Game_Currency_Rewards](In-Game_Currency_Rewards.md) - Artifact blueprint acquisition and NFT minting
- [Second-Hand Economy](Second-Hand Economy.md) - Artifact trading and rarity valuation
- [Blockchain_Integration](Blockchain_Integration.md) - Overall Web3 architecture

**Return to:** [Blockchain_Integration](Blockchain_Integration.md)

---

*Last Updated: November 6, 2025*


