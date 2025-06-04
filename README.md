# WizardDuel

It's called wizard duel.
The goal is for a player to hit the opponent with a spell, and the mechanics work like rock paper scissors: players put something down at the same time.
Each player starts with 1 mana, and mana is depleted by casting a spell.
Here are the mechanics:

Players tap twice on their lap (on the web there can be a 3-2-1 countdown), then choose to either:
1. Draw Mana (W for player 1, Up arrow for player 2)
2. Cast Spell (D for player 1, Left arrow for player 2)
3. Block Spell (S for player 1, Down arrow for player 2)
4. If the player has drawn to have a total of 4 mana, they can use a Kamehameha Blast (A for player 1, Right arrow for player 2).

Logistics: Each countdown is followed by a short window for player decisions (key presses).
If no key press is logged for a player, or an illegal key is pressed, the player defaults to a Block.
If two players cast a spell at the same time, the spells "cancel out" and the game continues.

The game is over when one player casts a spell at their opponent while the opponent is drawing mana.
A Kamehameha Wave defeats any opposing action, including the block and a standard spell cast.
