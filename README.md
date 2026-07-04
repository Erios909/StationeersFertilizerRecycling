# Recycle Fertilizer to Biomass

Feed unwanted Fertilizer into the Recycler and get Biomass back.

## What it does

Adds a recycling recipe for Fertilizer. The Recycler breaks each Fertilizer unit down into 2 Biomass reagent, delivered as Reagent Mix. Pass the Reagent Mix through a Centrifuge or Combustion Centrifuge to receive Biomass items - exactly the same pipeline the base game uses when you recycle plants and food waste.

- 1 Fertilizer -> 2 Biomass (per stack unit; full stacks are processed unit by unit)
- Works with chute networks, stack feeding, and automation like any vanilla recycler recipe
- The Biomass you get back can be composted, burned into charcoal, or centrifuged as usual

## Balance

The Composter processes three organic items to produce one Fertilizer, so a 1:2 return is still lossy - you recover two thirds of what composting cost you. Recycling spare Fertilizer is a salvage path, not a duplication trick: no infinite-matter loop is possible.

## Compatibility

- Pure data mod: no DLL, no BepInEx, no LaunchPad required - loads on a completely vanilla game
- No base-game files are modified; the mod only adds one recycling recipe
- Safe to add or remove from a save at any time
- Multiplayer: install on the host or dedicated server (clients receive the results automatically)
