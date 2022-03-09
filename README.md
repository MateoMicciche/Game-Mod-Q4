# IT266 Quake 4 Mod - KF2 Inspired Wave Survival Mod

1. [Description](#Description)
1. [Deliverables](#Deliverables)
1. [Changes](#Changes)
3. [Testing](#Testing)

## Description
This KF2 inspired mod is a mod in which the player chooses between three unique classes and tries to 
survive for as long as they can agaisnt waves of enemies. From killing enemies, players can earn xp and cash,
allowing them to become stronger by earning perks and buying new weapons and armor.

## Deliverables
Below are the deliverables for this mod:
- Enemies Spawn in Waves
- Three classes to choose from (Gunslinger, Demolitionist, Beserker)
- Player earns xp and levels up to unlock perks (3 for each class)
- Ingame shop where player can buy ammo, armor, and guns
- Enemies drop currency that players can pick up

## Changes
#### Enemies Spawn in waves (Every other 20 seconds)
#### Players now pick out of three of the classes to spawn in as (Gunslinger, Demolitionist, Beserker) (Perks detailed in Testing)
##### - Gunslinger has 75 health and 50 shield (Most mobile)
##### - Demolitionist has 125 health and 75 shield (Average)
##### - Beserker has 150 health and 75 shield (Slowest moving)
#### Player spawns in on one map (hub1)
#### Buy menu can be accessed ingame to purchase items
#### Money is gathered by killing enemeies and picking up the item "dosh"
#### Player can level up can unlock perks by killing enemies
#### Main menu, HUD, buymenu, and wristcomm have been modified for use of mod
#### Help menu can be found where credits used to be (can also be accessed ingame by pressing TAB)

## Testing
Below explains how to test each deliverable:

### Enemies spawn in waves
Launch into the map, wait around 20 seconds and the first wave will begin to spawn. This will occur every other 20 seconds,
as there is about 20 seconds of peace (optimal time to utilize the shop) and 20 seconds of enemies spawning.

### Three classes to choose from (Gunslinger, Demolitionist, Beserker)
On game startup, click on 'Survival', then choose a difficulty, and the game screen will present the three classes to choose from.
Choose one of the classes and launch the game to see the class in action. To see each class quickly, you can either quit the level
and go back to the main menu, or on death, click restart and it will bring the player back to the main menu screen. Classes can only be chosen
before match startup.

### Player earns xp and levels up to unlock perks (3 for each class)
There are three classes, each with three perks that unlock at player levels 5, 10, and 15. 
To test the perks, hit level 15 or set player level to 15 by typing
this command into the console: 'setLevel 15'. All perks will be active for the respective class chosen.
Below are the perks for each class:
#### Gunslinger (Mobile damage dealer)
- Level 5: Weapons reload faster (excluding Lightning and Dark Matter gun)
- Level 10: Player deals 20% more damage on headshots
- Level 15: For each kill, the players speed permanently increases by 5% to a max of 40%
#### Demolitionist (Zones with Explosives)
- Level 5: Player gains resistance to explosive splash damage (Rocket and Grenade Launchers)
- Level 10: Explosive damage splash range is increased by 20% (Rocket and Grenade Launchers)
- Level 15: Explosive weapons now shoot a spread of explosions (Rocket and Grenade Launchers)
#### Beserker (Tank)
- Level 5: Shield get converted to health, max health is now increased by max shield
- Level 10: For every kill, the player gains 5 health back
- Level 15: Melee damage taken is reduced by 40% (Vomit from Slimy Transfers still deals same damage)

### Ingame shop where player can buy ammo, armor, guns
Make sure to bind the 'buymenu' to a key in the settings menu.
Once in a game, hit the key binded to the buymenu, and the menu to purchase items will popup.
Once opened, the player's mouse will turn into a cursor and the player will be able to interact with the menu.
Click on the item you want, and if you have enough currency, the item will appear in your inventory. You will know an item is purchased if
the dosh counter at the bottom of the menu decreases in count. If you do not have enough dosh, then you cannot buy the items.

### Enemies drop currency that players can pick up
Very simple to test, kill an enemy and the currency will drop. It looks like an armor shard, walk over it and on the lower left of your screen,
you should see that the currency 'dosh' has been acquired. To double check that you acquired it, you can open up the buymenu and check the dosh counter
and see if it increased. Currently, each enemy drops 100 dosh.
