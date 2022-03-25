# zmk_sweep
Custom ZMK firmware for Sweep keyboard

I created a 34 key layout with a Colmak-DH base that works in both QMK and ZMK with the features available early January 2022. It is based on the work of manna_harbour and their proven [Miryoku layout](https://github.com/manna-harbour/miryoku) with some modifications that made it better for me. Since ZMK master didn't support mouse keys at the time, the Mouse layer is removed. The Media and Button layers are also removed which has the benefit of going to base plus four layers, which matches the number of thumb keys on 34 key boards. Not having to combo thumb keys improved usability in my opinion.

Existing muscle memory for space and the number pad on the right hand led to choosing the Flipped Miryoku variant as the starting point. I chose the Inverted-T arrow key option since my left hand has good muscle memory on that setup from PC games. Also since my thumbs home on the thumb keys farther away from the alphas, I chose to modify the arrangement to place Space and Backspace on the appropriate for me thumb keys. Combos were added on W+F for Esc (left-hand), and U+Y for Backspace (right-hand) to handle the missing base layer thumb keys which varies from the handed-ness of the Flipped Miryoku layout, but matches the handed-ness of the keys in a standard layout.

For me it is easy to hit the bottom row index key while a same hand thumb key is held, so that key is used on layers for some useful to me items like period on the Number layer, Windows screenshot, and Mute. I put Esc on the Symbol and Number layers for easy VI commands, but find myself using the W+F combo more.

NOTE: In practice I've found the Symbol layer doesn't work over Remote Desktop, so when you use RDP, you'll want to use the Number layer and Shift instead.

![KLE Pic](https://github.com/vpzed/zmk_sweep/blob/master/vpziryoku-2.png)

In the layout diagram a red thumb key indicates that key is held.
