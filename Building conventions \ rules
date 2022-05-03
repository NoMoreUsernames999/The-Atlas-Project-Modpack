##This file covers some guidelines and limitations of the structure mods which must be followed for building.

1) Recurrent complex does not support redstone states (powered redstone will spawn as unpowered until toggled again). 
   I am 70% sure that CofH world's nbt structure spawning does, however they are limited to 48x48x48 blocks (haven't tested the redstone with cofh yet, will update when I do). 
   If your structure relies on active redstone, either make it no larger than the aforementioned size, or make a player trigger to reset the network and "fix" it when they enter (not recommended. Will not always work). 
   *Redstone can still be used*. You just can't have active redstone.

2) Recurrent complex is technically limited to 48 cubic blocks as well, since larger structures take longer to generate. 
   If you plan on making a build that is bigger than 48 blocks on either of the 3 axis, you **must** have approval first as there will be a limited number of structures this size. 

3) Recurrent complex supports most regular modded blocks, and has rotation support for some of them. Any blocks that do not support RecC, or do but don't have rotation support, are listed below. 
   If you don't know how to use recurrent complex, then you can just learn how to export a structure and then submit the file and I'll handle the rest. 
   At minimum you should know how to export and import (you can check the mod wiki, it has a short page on this): https://minecraft-recurrent-complex.fandom.com/wiki/Guide:_Building_a_Structure
   Note that when selecting a structure, the second selection must be at the opposite diagonal corner so it forms a box. 
   
4) The name of your structure should follow this naming convention to make it easier to sort. There will eventually be hundreds if not thousands of structure files and this will save everyone a massive headache. 
   Naming scheme is: <DimensionsName><Category><StructureName>. Category is the type of structure, e.g any military type structure should be "military" and any generic ruined civilian structures should be "civilian" and so on. 
   This naming should be one word, and while it can contain upper case, CANNOT contain any sort of special characters. 

Side note: Because of dynamic block ID, you should not use world edit to export and import structures between worlds unless it contains 100% vanilla blocks (export/import in the same world works fine). 
Especially with Chisel, they will turn into random broken bs. Use recurrent complex to export/ import between worlds.



####List of blocks that do not support rotation. 
If your structure contains any of the following, you MUST have rotation and mirroring disabled for that structure. 
Keep in mind this means it will always generate with the same orientation. Before submitting any structure, you MUST test it by importing it at 90 degree rotation to see if anything breaks. 
If in a test world, make backups. This will typically corrupt the world if a block isn't supported. I recommend testing import rotation in new worlds. This list will be updated as I find blocks that cause issues: 

AVP blast doors. 
AVP machine blocks.
HBM multiblock doors. 
All RS gauges and switches.


####List of blocks that do not support Recurrent complex. These CANNOT BE USED in ANY structures:** 

HBM doors as follows: 
Water door.
QE containment door. 
Round airlock.
Sliding seal door. 
Sliding blast door. 
Vault tech blast door (Sort of. The only block you can click to open it is the bottom middle. As long as it is accessible it can be used).
