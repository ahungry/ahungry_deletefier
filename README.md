# Ahungry Deletefier

BG:EE/BG2:EE/EET mod - Removes many items from
creatures/stores/areas - basically tries to 'downgrade' any special
item types into their base form given some probability.

# NOTE

Beta quality, I need to do some play throughs with this mod!

WARNING: You will NOT be able to complete certain quests as expected
with this mod.  Accepting that will (perhaps) add some replayability -
or let CLUAConsole be your friend for items you feel you should have
received (use NearInfinity or EEKeeper on another saved game to find
the item codes).

What percent of items would you like to have disappear (creatures,
stores, and areas)?

```
   0   = no items deleted (why are you installing this mod again?)
   50  = half of all items are deleted
   100 = all items are deleted that aren't script creations/random npc loot (probably a bad idea!)
```

Hint: On a megamod (200+ mods) I enjoy 90 to 95 - it makes gear
acquisition exciting again.

## Install

I would recommend installing this last, or at least after all mods
that update/add files in override/


```
weinstall ahungry_deletefier
```

Or to install specific parts non-interactively (*nix based at least...):

```
echo -ne '90\n90\n90\n' | weinstall ahungry_deletefier --force-install 1 1000 2000 3000 4000
```

Would install (at 90% deletion percent) the stores component (2000),
the area component (3000) and the creature component (4000).

## Uninstall

```
weinstall ahungry_deletefier --uninstall
```

# TODO

Build up list of deletables and non-deletables.

https://www.gibberlings3.net/forums/topic/35993-ahungrys-deletefier-make-rare-items-rare-again-restore-that-lost-excitement/
