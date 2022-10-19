# Foundry-PF2e-WildShapeTokenChanging

This project is designed to facilitate automatically changing the token image when using one of the Wild Shape, or alternate form spells in Pathfinder 2e.

# Quick Use:
1. Create a new "Item" in foundry
2. Right Click the item, and select "Import Data"
3. Choose the "fvtt-Item-changeshapeeffects.json" to import
4. This will rename the Item to "ChangeShapeEffects"
5. Apply this item to any actors which will be changing forms (ie Wild Order Druids).
	- It will show up as a Bonus Feat for the Actor.

Now when applying any of the 'form' spell effects, the token will automatically change images.

If you do not have an image in the defined location, the token will revert to the default for actors for the system.

In order to have the tokens show, you will need to create a personal library of token images for the various forms.

The values here use "art/tokens/WildShape/{tokenname}.png".  (Path is relative to your Foundry User Data Directory)
You will need to point each Rule Element to an appropriate image file. 

# Updating the Item
If you import a new version of the "ChangeShapeEffects" item, you will need to remove the old version from any actors it's currently applied to.  Then add the new version to those actors.

---
Polymorph Spell Forms Completed:
Pest Form
Animal Form
Dragon Form
Dinosaur Form
Aerial Form
Insect Form

---
Polymorph Spell Rule Elements to be added:

Elephant Form
Elemental Form
Plant Form
Cosmic Form
Monstrosity Form
Angel Form
Demon Form
Fey Form
Devil Form
Daemon Form
Ooze Form
Aberrant Form
