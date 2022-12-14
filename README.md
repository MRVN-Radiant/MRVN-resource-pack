# MRVN-resource-pack
Dev textures & entity models for making maps with MVRN-radiant


# Installation
Download this repo as `.zip` & copy the folders for each game into your MRVN-Radiant working folder(s)  
(the folder above `maps/` where MRVN-Radiant saves by default)


# Details
 * `models/` contains `.obj` models for spawnpoints and other entity models  
   Support for `.mdl` in MRVN-radiant coming soonTM
 * `shaders/tools.shader` is hand-crafted so MRVN-radiant can hide triggers etc. in the viewport
 * `textures/dev` provides some hl2 dev textures, you will need to convert to `.vmt` or `.rpak` to see these in-game  
 * `textures/models` holds textures for editor models
 * `textures/tools` holds a mix of source engine & titanfall tool textures  
   Tool textures should not appear in-game, they are used for special materials & triggers
 * `Northstar_example_mod.zip` extracts into `Titanfall2/R2Northstar/mods` & provides in-game textures  
   Requires [Northstar 1.11.0 or later](https://github.com/R2Northstar/Northstar/releases/) for `.vmt` & `.vtf` textures
   Otherwise you will need to put textures in either `.vpk` or `.rpak` files
   `.rpak` is recommended for public releases, `.vmt` should be easier for testing and quickly iterating
