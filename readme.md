# Splight Of Hand

A quality of life script for the Spy

This script allows you to change your disguise's weapon at the same time as you do. This means you can make your disguise switch weapon much, much faster than would ever be possible otherwise.
What's more - It's completely automatic*! It activates itself whenever you disguise, and deactivates when you lose that disguise.
This will give you a bit more believability when trying to blend in with the enemy team!

## Installation
This config is designed to be put in your spy.cfg file, located at \Steam\steamapps\common\Team Fortress 2\tf\cfg

## Bindings
I had to bind actions to certain keys, so if you use custom bindings, you'll need to change the following:

1 = Revolver
2 = Sapper
3 = Knife
4 = Disguise kit
mouse1 = Attack
mwheelup = Go "Up" in the weapon list. From top to bottom: Primary > Melee > Secondary > Primary > Melee...
mwheeldown = The opposite of the above command.

"5" sets "disguisecheck" to "false" until you hold the disguise kit again. This basically turns off the automated weapon switching until then.
This binding should be used after each death to ensure disguisecheck isn't still set to true. If it is, the first time you switch your weapon in your next life, you'll also disguise, which you might not want to do, but it shouldn't be that bad.

[Here's](https://www.youtube.com/watch?v=cK1XyFY2IQg) a complementary video that demonstrates the script in action, and explains my reasoning behind making this:

## Limitations
*By automatic I mean it requires no set up besides putting the code in. As mentioned above, you should try to get in to the habit of pressing "5" after you die, just to be safe.

I did try to code in support for quick switching (q by default), however after many hours and anomalous errors, I couldn't find a solution right now.
Quick switching will still work, but if you do it between your sapper and something else, it might cause something unexpected.

You should make a reset.cfg file! As far as I know this shouldn't impact other classes, but it's a good idea to clear up all of my weird bindings and the like in case they end up conflicting with something else.
A reset.cfg file runs every time you change class, before your class.cfg file runs. This is mostly use to reset bindings back to what you had prior to playing that class. If you don't know what to put in your reset.cfg, you can likely just place exec config.cfg in your reset.cfg.
