# Foundry-PF2e-WildShapeTokenChanging

This project is designed to facilitate automatically changing the token image when using one of the Wild Shape, or alternate form spells in Pathfinder 2e.

Quick Use:
Create a new "Item" in foundry
Right Click the item, and select "Import Data"
Choose the "fvtt-Item-changeshapeeffects.json" to import
This will rename the Item to "ChangeShapeEffects"
Apply this item to any actors which will be changing forms (ie Wild Order Druids).
It will show up as a Bonus Feat for the Actor.
Now when applying any of the 'form' spell effects, the token will automatically change images.

If you do not have an image in the defined location, the token will revert to the default for actors for the system.

In order to have the tokens show, you will need to create a personal library of token images for the various forms.

The values here use "art/tokens/WildShape/<form>.png".  (Path is relative to your Foundry User Data Directory)
You will need to point each Rule Element to an appropriate image file. 


Spell Forms Completed:
Pest Form
Animal Form
Dragon Form
Dinosaur Form

Polymorph Spell Rule Elements to be added:
Insect Form
Aerial Form
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
