# AdvancementGrowth
Unofficial BlazeandCave Advancements addon that shrinks/grows the world border depending on the number of advancements the player has achieved.

This datapack requires BlazeandCave's Advancements Pack: https://www.planetminecraft.com/data-pack/blazeandcave-s-advancements-pack-1-12/

# Installation 
1. Download this datapack and the BlazeandCave's Advancements Pack (linked above).
2. Unzip the BlazeandCave's Advancements Pack.
3. Extract the AdvancementGrowth and bac_advancements folders into the "datapacks" folder of your Minecraft world.
4. Ensure both datapacks are enabled. This can be done with the "/datapack enable" command.
5. Locate where in your Minecraft world you like to be the center of the world border.
6. Run the command "/function adv_growth:init"
7. Enjoy!

# Config
The world border width is equal to the number of advancements you have achieved multiplied by growthFactor. growthFactor defaults to 3. You can change the growthFactor by running the command "/scoreboard players set @p growthFactor <insert number here>"
  
# Notes
Multiplayer support has not been tested. Use in multiplayer at your own risk.
