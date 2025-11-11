# In-Game Currency & Rewards

## Overview

This page documents the non-blockchain reward systems that form the backbone of EV2's economy. Most loot earned through gameplay is account-bound and non-blockchain, creating a dual-economy system where players convert tradeable resources into blockchain NFTs through crafting and minting processes.

---

## Currency System

### Relic Fragments

Primary currency for blockchain asset acquisition:

- **What It Is**: Crystalline resource harvested from defeated enemies and environmental sources
- **Primary Use**: Required to mint weapon blueprints into blockchain NFTs
- **How to Earn**: Drop from enemies, found in loot chests, mission completion rewards
- **Account-Bound**: Cannot be traded directly (prevents gold selling)
- **Stackable**: Accumulate without limit
- **Weekly Caps**: *Optional mechanic to be determined by development team*

### Other Tech Currencies

Additional specialized resources:

- **Power Cells**: Energy-type currency used for jetpacks
- **Alloy Credits**: Crafting materials for armor enhancements
- **Circuit Tokens**: Used for weapon modification unlocks
- **Catalyst Essence**: Currency for special ability enhancements
- **Archive Points**: Reputation/prestige currency for cosmetics
- *Specific uses to be determined by development team*

### Currency Management

- **Account Storage**: All currencies stored server-side on PlayFab
- **Inventory Display**: View all currencies in unified interface
- **Transaction History**: Track spending and earnings on-chain (optional)
- **Seasonal Reset**: Some currencies may reset each season
- **Weekly Allowances**: Optional soft caps on earning to prevent farming exploitation

---

## Loot Categories

### Blueprint Drops

Weapon and equipment blueprints are primary combat loot:

- **Most Common Drop**: Majority of enemy loot is blueprints
- **Rarity Variation**: Blueprints spawn at different rarity tiers (common to exotic)
- **Weapon Type Variety**: Different enemies drop different weapon part blueprints
- **Duplicate Drops**: Same blueprint found multiple times
- **Purpose**: Craft into weapons through [NFT_Weapons](NFT_Weapons.md) crafting system
- **Blueprint Storage**: Stackable inventory, unlimited quantities

### Crafting Materials

Resources required for weapon and armor crafting:

- **Component Fragments**: Basic building blocks from defeated enemies
- **Rare Alloys**: Higher quality materials from tough encounters
- **Exotic Minerals**: Rare crafting materials from boss drops
- **Elemental Essences**: Special materials for status effect upgrades
- **Catalyst Compounds**: Materials for transformative modifiers
- **Accumulation**: Collected and stored in inventory
- **Conversion**: Trade materials directly for crafting recipes

### Ammunition (Generic Categories)

Ammo drops as consumable account-bound items:

- **Primary Ammo**: Standard rounds for most weapons
- **Specialist Ammo**: Specialized ammunition for advanced weapons
- **Heavy Ammo**: Ammunition for high-powered weaponry
- **Energy Battery**: Fuel for jetpack
- **Restock Frequency**: Regularly drop from enemies to maintain supply
- **Inventory Limits**: Soft caps encourage usage rather than hoarding

### Consumable Items

Single-use items that provide temporary benefits:

- **Med Kits**: Restore suit health (small, medium, large variants)
- **Weapon Enhancers**: Temporary damage boost to all weapons
- **Movement Stimulants**: Temporary speed and agility boost
- **Defensive Stimulants**: Temporary armor increase
- **Specialty Consumables**: Mission-specific advantages
- **Single-Use**: Consumed when activated, must be re-earned

### Experience & Progression Items

Account-wide progression boosters:

- **Leveling Multipliers**: Temporary multiplier to all XP sources
- **Duration-Based**: Active for a specific time period
- **Stackable**: Multiple boosters can combine effects
- **Earned or Purchased**: Available through gameplay or cosmetic shop

### Cosmetic Materials

Resources for visual customization:

- **Color Dyes**: Used to customize [NFT_Chroma_Skins](NFT_Chroma_Skins.md)
- **Pattern Templates**: Apply designs to equipment
- **Visual Effects**: Particle effects for weapons and suits (epic, legendary, exotic)
- **Emote Blueprints**: Animation sets for player characters
- **Victory Poses**: Special animations for match completion
- **Spray Decals**: Deployable cosmetic markings
- **Purely Visual**: No gameplay impact

### Reputation & Currency

Social and community progression:

- **Guild Contribution Points**: Contribute toward [NFT_Guild_Tokens](NFT_Guild_Tokens.md) progression
- **Event Tokens**: Temporary currency during special events
- **Ranked Points**: Accumulate for competitive progression
- **Community Standing**: Influence with factions or organizations
- **Achievement Badges**: Cosmetic recognition system
- **Leaderboard Position**: Status indicator of player performance


## Enemy Drop System

### Drop Mechanics

How loot is awarded from defeated enemies:

- **Guaranteed Drops**: Every enemy guarantees some loot
- **Tiered System**: Stronger enemies grant better loot
- **Random Selection**: Loot type randomized from possible drops
- **Rarity Variance**: Rarity of blueprints randomized
- **Special Drops**: Rare chance for exotic blueprints
- **Environmental Variation**: Different areas favor different loot types
- **Boss Guarantees**: Boss enemies guarantee rare drops

### Drop Categories by Enemy Type

Different enemies prioritize different loot:

- **Standard Hive Creatures**: Common blueprints, primary ammo
- **Elite Hive Units**: Uncommon blueprints, specialist ammo
- **Boss Creatures**: Rare blueprints, exotic materials
- **Mini-Bosses**: Epic blueprints, rare crafting materials
- **Raid Bosses**: Legendary/Exotic blueprints, unique components

### Loot Chests & Containers

Strategic placement of valuable loot:

- **Hidden Chests**: Exploration rewards high-rarity items
- **Event Chests**: Limited-time content grants event currency
- **Vault Caches**: Dangerous areas contain better loot
- **Enemy Stashes**: Defeated enemy leader rewards
- **Environmental Decay**: Decaying Hive structures drop rare components
- **One-Time Opens**: Most chests single-use to prevent farming

---

## Currency Sinks (Economic Balance)

### Account-Bound Spending

Where players spend non-blockchain currency:

- **Weapon part Crafting**: Relic Fragments to mint blueprints
- **Skill Unlocks**: Circuit Tokens to advance weapon modifications
- **Cosmetic Shop**: Account-bound cosmetics purchasable with currency
- **Respawn Options**: Optional currency cost for immediate respawn
- **Convenience Features**: Various QoL improvements for currency

### Account-Bound Cosmetics

Cosmetics earned through gameplay (non-NFT):

- **Weapon part Skins**: Account-bound cosmetic variants
- **Pilot Customization**: Non-NFT appearance options
- **Emotes & Poses**: Animation set cosmetics
- **Trails & Effects**: Visual customization options
- **Non-Tradeable**: These remain permanently account-bound
- **Cheaper Than NFTs**: Accessible through normal play

### Cross-Currency Conversion

*Optional conversion mechanics to be determined:*

- Can blockchain currency convert to account-bound?
- Can account-bound currency convert to blockchain?
- What are conversion rates and limitations?
- Monthly caps or daily limits on conversions?

---

## Mission Rewards

### Completion Bonuses

Rewards for successful mission completion:

- **Base Reward**: Currency for mission completion
- **Performance Bonus**: Extra currency for high scores/objectives
- **Speed Bonus**: Additional rewards for quick completion
- **No-Death Bonus**: Perfect run completion bonus
- **Challenge Mode**: Increased rewards for harder difficulties
- **First-Clear Bonus**: Enhanced rewards on first playthrough

### Difficulty Scaling

Harder missions reward better:

- **Normal Difficulty**: Standard currency and rare blueprints
- **Hard Difficulty**: 1.5x currency, better blueprint rarity
- **Nightmare Difficulty**: 2x currency, epic blueprint rates
- **Mythic Difficulty**: 3x currency, legendary blueprints possible
- **Seasonal Challenges**: Limited-time ultra-hard missions with exotic rewards

---

## Season System (Optional)

### Seasonal Currency

*If implementing seasonal progression:*

- **Season Pass Currency**: Earned through battle pass progression
- **Seasonal Events**: Event-specific temporary currency
- **Season-Exclusive Rewards**: Limited-time cosmetics and cosmetics
- **Seasonal Reset**: Some or all currency resets each season
- **Carryover Options**: Certain currency carries to next season
- **Archive System**: Missed seasonal rewards available later

---

## Anti-Farming Measures

### Engagement Incentives

Encourage varied gameplay rather than repetition:

- **Objective Bonuses**: Completing objectives grants extra rewards
- **First-Clear Bonuses**: First time doing something = enhanced reward
- **Difficulty Progression**: Encourage attempting harder content
- **Event Participation**: Special event rewards incentivize variety
- **Community Events**: Server-wide goals create engagement spikes

---

## Blockchain Integration

### NFT Minting from Account-Bound Loot

- Account-bound drops convert to NFTs through player choice
- Minting irreversible but voluntary
- Players decide when to convert assets to blockchain
- Conversion through standardized crafting/minting interface
- Costs and requirements clearly stated before conversion

### Dual-Economy Benefits

- **Accessibility**: Account-bound items accessible to all players
- **Safety**: Only convert valuable assets to blockchain when ready
- **Experimentation**: Try weapons before committing to NFT
- **Progression**: Meaningful advancement through both systems
- **Long-Term Engagement**: Both economies provide engagement hooks

---

## Related Documentation

- [NFT_Weapons](NFT_Weapons.md) - Weapon component crafting system
- [EV2_Combat_Suits](EV2_Combat_Suits.md) - Suit progression and currency usage
- [NFT_Gear](NFT_Gear.md) - Gear piece acquisition and upgrades
- [Blockchain_Integration](Blockchain_Integration.md) - Overall Web3 architecture
- [Monetization_Schemas](Monetization_Schemas.md) - Economic design overview
- [README](README.md) - Overall game structure

**Return to:** [README](README.md)

---

*Last Updated: November 6, 2025*


