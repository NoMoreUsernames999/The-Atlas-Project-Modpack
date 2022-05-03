# The-Expanse-Modpack
**Repository for the dev team of The Expanse Modpack. Also for bug reports.** 
See the to-do list at the bottom. 


===============================================

**Remember to make any new txt files you create plain text! Json, .book, cfg, etc must all be plain text files!**

So, I would like to start off by saying, for those that haven't used GitHub before, you must check the documentaion linked in the Discord. 
It is relatively short and explains how to upload files, request your files be merged into the "accepted" files (called a pull request), and how to download individual files for clientside testing. 
Also as a reminder, **never submit/ commit files directly to the main branch or someone elses.** Submit your files by adding them to another branch. The option is at the bottom of the page after you upload your files. 

The *Main* branch is by default blocked from direct commits, but other peoples branches are not (branches are like seperate directories you can merge files between, and allows editing of files without messing with the main branch until you are ready to submit for approval).
Remember to make sure you check which branch and file path you are currently on before uploading.   

===============================================


## LostBooks:


For writers of the team. This is where all .book files go. **Make sure you read the format.txt file** for useful formatting tips and to learn the limitations of the LostBooks mod. 

All contributers will be credited in the authors file in the primary directory of LostBooks, but if you want to be credited for specific works you upload, it is up to you to do so. 
To do this, download the current authors.txt file (check GitHub references channel for how), and then add the name of any books you submit under the section for your username, using one line per book (you can commit changes to authors.txt as many times as is needed to list your contributions). 
If the authors.txt file in the Main branch has been edited since you copied it, you will be asked to resolve conflicts before you can commit your version of the file. Simply click on the resolve conflicts button and move some stuff around (don't mess up the formatting or move other peoples lines). Don't forget to remove the text inserted by GitHub marking the moved lines. 

As for books themselves, they are split into two folders/ categories: *common*, and *unique*. Any books in the common folder can be dropped multiple times, based on chance. Books in the unique folder will only drop **once per player, per world.** So determine the purpose of your book before choosing which folder to submit to. 
Things like news paper articles, "non-special" short stories, or things you would expect to find multiple times should all go in common. Something like a lab report dropped by a zombie, or any journals, should go in unique. Logically only one copy of these would exist. 
As far as the length of .book files go, you should limit them to under 1000 words, and they should never exceed 2000. If your book is longer than this, you must introduce soem kind of scene break, torn of section that is continued in the next volume, etc. Book files that are all volumes or parts of a single book should go in a folder inside common or unique, e.g *LostBooks/common/theMarsIncident* (folder name must not contain numerics!). 
This helps reduce clutter, but do note that this does sort of change the drop chance. E.g when a book from the common folder is dropped, they are all rolled dependent on their weight. Folders however are considered one book. If the roll lands on that folder, a second roll is then determined to decide which book in the folder is dropped. 

*You should follow the naming conventions laid out in format.txt, and should avoid using numbers in the name of the file. When uploading your files, add a description to the commit notes of what the book is about, whether is whitelisted for certain mobs, and any relevant lore it pulls from or adds to (to avoid contradictions from differnet authors).* 

The last thing you can do with your books, is control their drop conditions using a .txt file and giving it a name identical to the .book file that it is changing values for. The .txt file must be in the same directory as the .book file it's paired with. Things like how often the book drops relative to the others and which mobs they can drop from can be modified using these text files. For example; if a book is specific to a planet and should not be obtainable until reaching it, you can make it drop only from mobs on that planet (if it is an uninhabited planet then you can specify in your commit notes when you upload that the book must be added to a structure loot table). 
Note that weight values that are extremely low, like 1, will cause the book to likely never be seen. Check the DropSettings text file in the LostBooks folder for a more detailed explenation of how to do this, and **do not use weights higher than 100.**  


## Flan: 


If you have experience editing flan packs, then you know what this is for. If you have not been assigned to this folder, don't touch it. It's rather complicated and will be mostly handled by me. 


## Scripts: 


For all the script files. **FILES UPLOADED HERE MUST END WITH THE EXTENDED .zs.txt EXTENSION OR THEY WON'T BE APPROVED!** You will have to change the extention to just .zs when you download the file for client use. 
If you are adding a new script file that doesn't already exist, each mod or major function should have its own file. E.g any removals or modifications to Minecraft recipes should go in Minecraft.zs, Thermal expansion in Thermal.zs, etc. For mods like Advanced Rocketry, it may be necessary to seperate its machine recipes into seperate files for each one. Never mix recipes with other script functions, these should each go in their own file (compatSkills, JEI edits, etc). 
For things that aren't obvious like non recipe scripts, loops, or other functions; remember to add in file comments to make sure other devs reading your scripts know what does what. 
*Footnote: Where possible, use recipes.remove(<ID>) instead of typing out the full recipe with all its compenents. This abbreviation works in most cases and makes things more readable. Only use the longer removal script that specifies the recipe items if this doesn't work (sometimes it doesn't).*


## Config: 


Obviously where configs go. Make sure to keep file names and file paths if they exist in a subfolder. Do not make edits unless you know what you're doing, and have been assigned. All other mod editing exists in this folder unless otherwise specified. 
If merging conflicts during a pull request, **make sure you keep correct file formatting. Json files are extremely touchy about incorrect formats. Pay close attention while doing conflict resolution. Make sure you check the commit notes to see what was changed.** 
All commits **must** have a description in the notes of what they changed. This is required for any commites that modify files, but is especially important with configs.   

## TO-DO list 
  
  When you pick something on the list to do, if it is something that can only be done by a single person at a time, state so in the Discord to notify people that someone is working on the task so that people don't waste time doing the same thing twice. When you pick or finish something from the to-do list, go to the projects tab and move the note card of that task to the appropriate collumn. Please to do this as it helps organize, and organized projects move faster. You can use the below list to see what has been finished at a quick glance, or go to the organization project in the projects tab at the top of the page for more specific info.

Current to-do list, Updated as development progresses:

- [ ] Disable all HBM weapon and explosive recipes that use the assembler. 
- [ ] Finalize Mars and Earth building style. 
- [ ] Fill in energy consumption spreadsheet. 
- [ ] Finalize planet designs, names, and progression order. 
- [ ] Finish resourcepack. 
- [ ] Build starting planet. 
- [ ] Finish music file conversions. 

