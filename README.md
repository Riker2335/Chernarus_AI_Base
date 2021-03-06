# Chernarus AI Base DMS Static Mission

This is a large AI base objects &amp; static DMS mission in the north of Chernarus. This is simply a mission file and objects file for the DMS mission system used by ARMA 3 Exile. Mods used to create this are the CUP core,CUP maps, CUP Terrains, CWA components, Apex and Extended Base Mod. You will need these on the server to be able to show all the components of the mission. If you don't have them on the server, the mission should work but some components in the base will be missing.

This mission was created for a militarised server and has 2 roaming vehicles with the possibility of a Gorgon or armed Ifrit/Hunter/Strider as those armed roaming vehicles. The AI vehicles that can be used by the mission are editable in an array at the top of the mission config.
Easy difficulty is configured for testing purposes by default and not intended for server deployment as it only has a small number of AI and a lot of loot. Medium difficulty is intended for small groups of 2-3, difficult for groups of 4 and hardcore as 5+ or just some very persistent smaller groups.

5 loot crates are configured;

1. General items
2. Sniper Rifles
3. Building Supplies
4. Medical supplies
5. Special items (laser designators, rockets & launchers etc.)

Crates 1 and 3 utilise the DMS lists for general items and building items. Crates 2, 4 and 5 utilise arrays within the mission file and are fully customisable. If you want something to have a higher chance of spawning in these crates, simply put more of that item in the array. You can also adjust the amount of loot in each crate if you want to make one particularly generous or another quite light in the difficulty setup section.

# Installation Instructions
1. Copy the ai_base_chernarus.sqf file to a3_dms.pbo's /missions/static folder
2. Open config.sqf in a3_dms.pbo, find the DMS_StaticMissionTypes section and append ["AI_Base_Chernarus",1] to the list
3. Save and close config.sqf
4. re-pack a3_dms.pbo with all the changes and ensure it is placed in the /@ExileServer/Addons folder to launch at server startup.
5. copy the content from AI_Base_Objects.sqf into your initserver.sqf file inside your mission file.
6. Repack your mission file and upload to the server

Enjoy a new static mission for Chernarus!

# Optional Install Instructions
These 2 lines provide some preconfigured CUP vehicles and weapons for the mission file if you use those mods on your server.
1. If you have CUP Weapons, uncomment the "#define USE_CUP_WEAPONS 1" line
2. If you have CUP Vehicles, uncomment the "#define USE_CUP_VEHICLES 1" line
