# Conventions

We do our best to follow [Hyphen-ated's Conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md). Below are additions and deviations.

## Good Touch Play

If you're holding a subset cards such that if every card in this subset is useful (not trash), then at least one of your held cards is playable, you will play the left most card of this subset held on the first turn after which your teammates have had a chance to correct this.

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

## Cascading Self-Prompt/Finesse vs. Self-Bluff

Our convention permits a cascading self-prompt or self-finesse. For example:

![Cascading Self-Finesse](/images/cascading_self_finesse.png)

Assuming empty stacks, Matt gets clued about one 3. He sees that it is not playable and nobody else has any cards that will make progress towards a 3. Matt plays his finesse spot, which is the red 1. The 3 is not yet playable, nor does anyone have a 2, so Matt will cascade the finesse to his slot 2.

However, there may be a case where the cascade "diverges". For example:

![Cascading Self-Lie](/images/cascading_self_lie.png)

Assuming a similar scenario above, Matt gets the clue about one 3 and plays his slot 1 in the finesse spot. On his next turn, he assumes that his "cascaded" finesse spot (now slot 2) is the yellow 2, since that's what would be needed to connect the previous play to the clued card. However, it is actually a yellow 1. At this point, we say that the cascade "diverges", because Matt played a red 1 and a yellow 1, which make progress towards different 3's. Matt should no longer cascade any further (i.e. stop playing finesse cards). In this example, it just so happens that he could keep playing and it would work out nicely. However, the cards will usually not line up so nicely, an and we'd need a clue to correct if Matt decided to keep playing.
