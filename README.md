# Conventions

We do our best to follow [Hyphen-ated's Conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md). Below are additions and deviations.

## Good Touch Play

If you're holding a subset cards such that if every card in this subset is useful (not trash), then at least one of your held cards is playable, you will play the left most card of this subset on the first turn after which your teammates have had a chance to correct this.

### Example

- In a normal variant game, on the stacks there is a blue 2
- Matt gives Aly a clue about four blue cards in slots 1, 2, 3, and 4
- Ryan discards
- Aly plays her slot 1 which turned out to be a blue 3

On the next turn Aly is expected to play her slot 2 card, then on the following turn she's expected to play her slot 3.

### What does it mean to have had a chance to correct the move?

Did a turn pass where a teammate of yours could have given you a clue without letting a teammate dump a critical card?

## Rainbow Prompt 

When you receive a color play clue on a newly clued card that turns out to be rainbow, and this clue also touches cards that you were holding that aren't confirmed rainbow, play the leftmost of these cards on the next turn.

### Example

- On the stacks is a green 2
- Aly has a rainbow 1 in slot 1 and a green 3 in slot 4. Slot 4 has previously been clued as a green card.
- Ryan gives Aly a clue about 2 green cards.
- Matt discards
- Aly plays her slot 1 and discovers it's a rainbow 1. At this point she thinks to herself, I wonder why Ryan chose green? She then realizes that he was also trying to get he to play he green 3 in slot 4, so she correctly labels this card as `rainbow 2 or green 3`.

## Elimination Assumptions

[This section](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#discard-elimination--elimination-notes--the-elimination-blind-play)
talks about what assumptions a player can make after discarding an important card (anything playable or a needed 2). In the linked conventions,
the player who discards should assume that one of their cards is a duplicate of the card they discarded. Our conventions differ in that we
assume that the card in the now chop is this card.

### Example

- On the stacks is a green 2
- Ryan discards a green 3
- On Ryan's next turn, he correctly plays the chop as the green 3.

### Example

- On the stacks is a green 2
- Ryan discards a green 3
- On Ryan's next turn, he correctly plays the chop as the red 1.
- On Ryan's next turn, he correctly plays the chop as the green 3.

### Example

- On the stacks is a green 2
- Ryan has green 3, blue 4, green 3 in slots 3, 4, and 5 respectively
- Ryan discards a green 3
- Matt now tells Ryan about one 4 in his chop. Good thing he did, or else Ryan would've incorrectly played this card.
Ryan now shifts his thinking to assuming that his green 3 is in slot 4 (one over from the chop).
- On Ryan's next turn, he correctly plays green 3 from slot 4.

### Example

- Nothing on the stacks
- Ryan discards green 2 and picks up a green 1
- Ryan assumes his now chop is a green 2, or else his teammates never would've let him discard a 2.
- Aly clues Ryan about one 1
- Matt discards
- Ryan plays the green 1. Seeing that his 1 is gree, Ryan resolves to play his chop card which he previously labeled as the green 2 on the next turn.

