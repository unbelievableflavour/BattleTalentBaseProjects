## Battle Talent - Base Projects

Hi and welcome. Above you will find a collection of some clean example projects to use for creating Battle Talent mods. Hope it helps!

Dont forget to change YOURPREFIX_ to your own prefix throughout the project.

### Code changes

Only actual CODE changes that are needed per project are the following:

Step 1 - Entry.txt
In `Setup\Scripts\Entry.txt` edit ```print("Loading YOURPREFIX_PROJECTNAME")``` 

Step 2 - Entry.txt
In `Setup\Scripts\WeaponModDemo.txt` edit ```AddStoreItemTemplate("YOURPREFIX_PROJECTNAME", nil, "Weapon name", "A description about the weapon.")``` 
