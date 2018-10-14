# gilded-rose-tech-test

Makers week 10 mock tech test - Gilded Rose Refactoring Kata

Full instructions for this project can be found [here](https://github.com/emilybache/GildedRose-Refactoring-Kata)

First, an introduction to the current system:

    - All items have a SellIn value which denotes the number of days we have to sell the item
    - All items have a Quality value which denotes how valuable the item is
    - At the end of each day our system lowers both values for every item

```
	- Once the sell by date has passed, Quality degrades twice as fast

	- The Quality of an item is never negative

	- "Aged Brie" actually increases in Quality the older it gets

	- The Quality of an item is never more than 50

	- "Sulfuras", being a legendary item, never has to be sold or decreases in Quality

	- "Backstage passes", like aged brie, increases in Quality as its SellIn value approaches;
	Quality increases by 2 when there are 10 days or less and by 3 when there are 5 days or less but
	Quality drops to 0 after the concert

We have recently signed a supplier of conjured items. This requires an update to our system:

	- "Conjured" items degrade in Quality twice as fast as normal items

Feel free to make any changes to the UpdateQuality method and add any new code as long as everything
still works correctly. However, do not alter the Item class or Items property as those belong to the
goblin in the corner who will insta-rage and one-shot you as he doesn't believe in shared code
ownership (you can make the UpdateQuality method and Items property static if you like, we'll cover
for you).

Just for clarification, an item can never have its Quality increase above 50, however "Sulfuras" is a
legendary item and as such its Quality is 80 and it never alters.
```
