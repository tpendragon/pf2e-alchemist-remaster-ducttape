# PF2e Alchemist Remaster Duct Tape

A module to slap together some functionality until the PF2e system is updated to support the Alchmist remaster.

## Known issues

- The first time you use the Quick Alchemy macro (qaCraftAttack();) it will take a minute to load the screen.

## How to use
**Quick Alchemy:** Either import the Quick Alchemy macro from the compendium "Alchemist Duct Tape Macros", or create your own macro with the following code: `qaCraftAttack();`

**Powerful Alchemy:** This will work automatically on infused item creation, any exiting infused items will need to be re-crafted.

## Features

**Quick Alchemy:** funcion that will consume 1 Versatile Vile, and craft an item from your formulas. A dialog box will appear with two drop downs. The first will list formulas for items of type weapon (bombs), and will have a "Craft and Attack" button which will craft the item then open the dialog box for the attack actions. You must have a target selected first. The second dropdown will list consumable items that you have the formula for and have a "Craft" button. All items created with this will have the "Infused" trait. 
A macro will be included in the compendium. 

![Quick Alchemy macro example](https://i.ibb.co/db2vs2W/quick-alchemy-macro.gif)

(update) I added the option to just craft an item, in that case it will add to inventory, consume a versatile vial (unless crafting a versitile vial), and then add a chat card with a link to use that item. 

**Powerful Alchemy:** Will detect when an infused item is created, and if the actor has Powerful Alchemy feat, will update the descrtiption to reflect the Actor's Class DC. 

## Requests

This is still sort of a work in progress, and by no means a full release. I have made changes that affect my players the most at the moment. I expect when the Alchemist Player Core 2 changes are implemented in the PF2e system this module will be obsolete. 

In the meantime if you have a request for a work around fix for an Alchemist feature, please submit one in the [Issues Page](https://github.com/thejoester/pf2e-alchemist-remaster-ducttape/issues). 
