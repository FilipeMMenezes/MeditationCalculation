This is my take of a coding challenge in boot.dev

Meditate
In Fantasy Quest, player characters have spells and abilities that cost mana to cast. Characters can meditate to regenerate mana by converting energy directly into mana. Energy potions can be used to instantly regain energy.

Assignment
Complete the meditate function using a while loop. It takes mana, max_mana, energy and energy_potions integers.

While meditating, a character converts 1 energy into 3 mana — their mana cannot exceed their max mana — for each iteration of the loop.
mana cannot exceed the max_mana.
If they have any energy_potions when they run out of energy, they will use 1 energy potion to gain 50 energy and continue meditating.
A character will stop meditating if either:
Their mana reaches the max_mana, or
They run out of energy and energy_potions.
Return the mana and remaining energy and energy_potions when the character stops meditating.
