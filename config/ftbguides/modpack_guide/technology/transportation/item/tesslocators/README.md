# Item Tesslocators

![Basic Item Tesslocator](item:tesslocator:basic\_item\_tesslocator)
Item Tesslocators allow you to quickly move items over extremely short distances.
![They can only move items 1 block away](tesslocator.png)

Item Tesslocators will move 1 stack every 0.8 seconds, cycling through each slot of the inventory it is placed on. This is extremely useful for when items are being inserted and extracted from the same inventory at the same time, so it moves every slot instead of just the first couple.

It works with Itemducts too! You may have to right click the Itemduct with a Crescent Hammer to connect it.
![](itemducts.png)

You can have more than two Tesslocators in a single block space. If no filters are used, items will try to split equally.
![The Tesslocator at the top is set to Output](multiple.png)

Place Tesslocators in the same block space on each block you want to interact with. Open it's GUI to change the settings.
![](gui.png)

The center button allows you to change between input, output, and input/output modes. Items will move from output-mode inventories into input-mode inventories.

The left slots are filters you can set by inserting items or Item Filters to whitelist what items can come in or out.

You can insert Glowstone into the first slot on the right to make it work faster, up to 8 times to make it work once per tick.

You can insert Diamonds into the second slot on the right to make it move more stacks at once, up to 3 to make it send 4 stacks at a time.
