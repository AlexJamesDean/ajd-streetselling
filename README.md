# AJD StreetSelling – QBCore Street-Level Drug Selling System

**AJD StreetSelling** is a FiveM QBCore drug selling script that turns casual hand-offs into a dynamic street-level economy. NPC buyers, territory restrictions, heat and police escalation, and supply/demand modifiers create a system that reacts to player activity, time, weather, and gang presence.

This repository is for documentation, indexing, and SEO.  
The full source code is available through Tebex.

## Purchase Link

https://alexjamesdean.tebex.io/

---

# What AJD StreetSelling Does

AJD StreetSelling adds a configurable NPC drug dealing system for FiveM servers using QBCore or QBX. All behaviour is controlled through your configuration:

- QBCore-Optimized: Built for QBCore/QBX with AJD Bridge handling inventory and target interactions.
- NPC Buyer Logic: Buyers have configurable personalities, suspicion, loyalty, and negotiation options.
- Territory Zones: Define unlimited zones with item rules, bonuses, penalties, gang restrictions, and time-of-day checks.
- Heat Mechanics: Heat increases through activity and decreases over time, affecting police chance and prices based on your configuration.
- Police Integration: Dispatch alerts, evidence drops, and scalable detection based on heat and officer count.
- Economy Controls: Supply and demand multipliers, pricing variation, and loyalty bonuses.
- Exploit Prevention: Server-side validation, distance checks, cooldowns, rate limits, and logging.

Everything listed is directly configurable and included in the script.  
No additional behaviour is implied.

---

# Deep-Dive Overview

## NPC System
- Spawn chance and max lifetime settings.
- Configurable suspicion and loyalty behaviour.
- Optional negotiation.
- Optional bulk buyer variants.  
(All defined through config.lua.)

## Territory and Zones
Each zone includes:
- Allowed item lists
- Price multipliers
- Gang restrictions
- Heat modifiers
- Time-of-day rules
- Police requirements

## Heat and Police
These values are controlled by your configuration:
- Heat gain and decay
- Heat thresholds
- Police alert chance
- Evidence chance
- Online officer multiplier

## Economy Settings
- Base price variation
- Negotiation range
- Loyalty bonus ranges
- Territory modifiers
- Optional supply/demand adjustments

## Developer Tools
- Debug tools
- Webhook templates
- Logging templates
- Example configs
- Integration via AJD Bridge

---

# Scenarios Supported

- Gang roleplay with turf-based modifiers.
- Civilian side jobs in safer zones.
- High-risk narcotics with higher configured detection.
- Seasonal or time-based bonuses.
- Police roleplay using evidence and dispatch logs.

Every scenario above is determined entirely by your configuration.

---

# Default Numeric Values

- NPC spawn distance: 50 meters (adjustable)
- Resmon usage: under 0.02 ms with default settings
- Heat tiers: multiple configurable thresholds
- Detection formula: base chance + heat multiplier + online officers  
(All values come from the included configuration.)

---

# Included With Purchase

1. Full client, server, and UI source code (no escrow).
2. Config templates for NPCs, heat, police, and economy.
3. Vue-powered UI components.
4. Optional SQL schemas for logging, evidence, and progression.
5. Discord webhook samples.
6. Lifetime updates for the current major version.

---

# Comparison With Basic Selling Scripts

This comparison reflects the actual features included:

- NPC variations vs static ped interactions
- Territory rules vs global selling areas
- Heat and evidence vs basic police pings
- Price variation and loyalty bonuses vs fixed prices
- Logging and evidence vs minimal admin visibility

No unimplemented systems are referenced.

---

# Installation

1. Purchase using the link above.
2. Download from your Tebex receipt or dashboard.
3. Add the resource to your server.
4. Ensure `ajd-bridge` first, then `ajd-streetselling`.
5. (Optional) Import SQL for dedicated logging tables.
6. Configure zones, pricing, NPC behaviour, and heat in `config.lua`.

---

# FAQ

**Which frameworks are supported?**  
QBCore and QBX via AJD Bridge. ESX is not supported.

**Can heat or police be disabled?**  
Yes. All related systems can be toggled or adjusted.

**Can police participate?**  
Behaviour depends entirely on your job/gang/item checks.

**Does it work with ox_target or qb-target?**  
Yes. AJD Bridge supports both.

**Can I add custom items?**  
Yes. Add them to `Config.AllowedItems` and configure multipliers.

---

# Related AJD Scripts

- **AJD Crafting** – QBCore crafting framework  
- **AJD Scavenge** – QBCore scavenging and item collection system  
- **AJD StreetSelling** – NPC drug selling and territory control  

These internal links help GitHub indexing and do not imply shared features beyond what is stated.

---

# SEO Keywords

FiveM drug selling script, QBCore drug system, FiveM NPC selling, GTA V RP drugs, QBCore street economy, QBCore police alerts, FiveM selling zones, AJD StreetSelling, AJTheDev scripts, QBCore frameworks

---

This repository does not include the script itself.  
It exists for indexing, documentation, and SEO purposes only.

I fix the bugs other devs gaslight you about.
AI tools, FiveM systems, automation pipelines.
Build it, break it, resurrect it: 👉 https://AJThe.Dev
