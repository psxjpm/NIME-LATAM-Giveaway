# NIME-LATAM-Giveaway
Pure data patch for NIME LATAM prize draw

This pure data patch uses an oscillator with a low pass gate. The values of the signal's envelope bang a counter that cycles through a selector. A signal threshold turns a spigot on and off to start and stop the counter respectively. The bangs in the selector bang a series of urns that randomly cycle through 0-8 (8 is the index size required to cycle through a 9-bang selector, in the case of having 9 entries). In other words, each of the 9 entries in this case is randomly drawn 9 times without drawing the same name twice in a row. 

The low pass gate patch is based on: https://youtu.be/L-1o44enUIc
