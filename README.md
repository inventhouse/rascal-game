Rascal
======
_A [Scoundrel] Variant_

Original by Zach Gage and Kurt Bieg  
This version and app by Benjamin Holt © 2025 MIT or CC-BY License

[Scoundrel] ([BGG]) is a brilliant dungeon-crawling [roguelike] solitaire card game concept, however it has some mechanics that make outcome depend on luck at least as much as player choices, which I don't care for.  I also feel like the concept all-but-demands an "inventory", so I developed this variant.

Aside, tweaking or outright re-working game rules like this is a lot of fun, I've included some tuning ideas below.

[Scoundrel]: http://stfj.net/art/2011/Scoundrel.pdf
[BGG]: https://boardgamegeek.com/boardgame/191095/scoundrel
[roguelike]: https://en.wikipedia.org/wiki/Roguelike

**[Play Rascal](play)**

Setup
-----
Start with a standard 52-card deck (jokers are not used), separate high red cards (J,Q,K,A ♦️/♥️); these can be used as the "life counter" by assigning 1-4 to J-A (1+2+3+4 = 10 x 2 suits = 20 life.)

When damage is taken turn the appropriate value of life points face down; when life points are restored, turn that value back face-up.  "Make change" as needed.

Life points can never go above 20; if they ever go below one, the game is lost.

Thoroughly shuffle remaining cards (2-A ♣️/♠️, 2-10 ♦️/♥️); this will be the "dungeon" where:
- ♣️/♠️ are monsters and do damage equal to their value (2-A = 2-14).
- ♦️ are shields which prevent damage based on their value, but degrade a point with each use.  You can have only one shield equipped a time.
- ♥️ are healing potions and restore life points up to their value, up to the starting life of 20, but only one potion per round ("room") is effective.

Layout is up to you and/or the space you are playing; you will need to have a place for the dungeon deck face-down, your life counter, four room cards face-up, a discard pile, an equipped shield stack, and an inventory item.  Here is one example:

```
              Room
Dungeon 🂠   🂶🃝🃑🂸   🂠 Discard

    Shield  🃄🂨   🃂  Inventory

         🂱🂠🂾🃎🂽🃍🂻🃋
              Life
```

Gameplay
--------
Play is a series of four card "rooms".

Upon "entering" a room, you may choose to fight or flee; if you flee, all four room cards are scooped up and added back to the bottom of the dungeon to come up again later.  You may not flee two rooms in a row.

If you fight, cards may be dealt with in any order, but only one at a time:
- ♦️ When equipping a shield, any previously held shield must be discarded.
- ♣️/♠️ Fighting a monster can be done with or without your equipped shield and damage is deducted from life points immediately.  Fighting with your shield deducts the shield's current value from the damage taken (face value minus the number of previously vanquished monsters) but degrades the shield by a point; place the monster on the shield card to help track its degraded value.  Fighting barehanded, you take the full damage and discard the monster.
- ♥️ Taking a healing potion restores life points immediately and is discarded; again, only one potion per room is restorative.

Shields or potions in the room may also simply be discarded.

When three of the room cards have been disposed of, you have the option to move on to the next room and the remaining card carries over.  Deal cards from the top of the dungeon back up to four.

You win when the dungeon is cleared.

Special Rules
-------------

### Inventory
You also have one inventory slot, however you cannot access it (either to store or retrieve/use an item) when any monsters are present; an item may be used directly from the inventory slot or, if there is space in the room, it can be dropped and treated as a room card.

### Repair
The 2♦️ can be used to repair up to two points of damage on your equipped shield; discard the 2♦️ and up to two monsters from your shield stack.

Balance
-------
As-designed, Rascal is pretty winnable; not every dungeon can be beaten, and mis-steps are often costly, but if you're making good choices about conserving resources, etc. you win a lot of the time.  That's how I like it.  There are also many ways you can tune the game; a few ideas follow.

### Pull Cards
The deck is already literally stacked against you; when you think about it, that means that pulling red cards (especially ♦️) will make it harder to win, moreso than removing black cards will make it easer.

On the flip-side, using another mechanism for a life-counter and adding a high-value red card would tilt the game significantly in your favor.

### Tweak Special Rules
Dropping the "repair" rule or even pulling the 2♦️ out of the deck would make the game harder; though it seems of minimal value (which is why I added the repair rule), it means one less monster in a room, which can make all the difference.

Dropping the inventory rule would force more discards of mid-value items.  Or, relaxing some of the inventory constraints could make it easier: allow swapping the equipped shield with one in inventory, access even if a monster is carrying over, or even access during combat.

### Other Tweaks
- Change the "fight or flee" rule
- Increase or decrease life points
- Alter shield degradation rate or process
- Add random elements, such as a die roll for which monster to fight
- Add a special, say, lightning bolt you can use once to slay a monster
