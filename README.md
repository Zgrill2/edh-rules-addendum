# Bracket 3 Experimental: House Rules

## Baseline

All standard Bracket 3 rules still apply, including the 3 Game Changer maximum, no mass land denial, and no chaining extra turns. There are two exceptions. The guideline against winning before turn 6 is removed. The guideline against early-game 2-card combos is replaced by Rule 3 below. Where these rules conflict with official Bracket 3 guidance, these rules win.

The clarifications in Rules 1 and 2 are in addition to the official MLD and Extra Turn rules and do not replace all MLD/Extra Turn restrictions.

## Rule 1: Mass Land Denial

If a spell or ability would remove 2+ opponents lands or keep them tapped indefinitely (e.g., winter orb, back to basics), instead only 1 of those lands is removed. You may not remove more than 1 land per turn, if an ability does so that land is instead not removed and the land is treated as not removed for the purpose of any conditional effects that may occur.

## Rule 2: Extra Turns

If a spell or ability would provide 2+ turns instead only 1 of those turns is taken. If you are in an extra turn you may not take an additional consecutive turn.

## Rule 3: Combos

### 3.1 Piece

A piece is any card the sequence requires, where the card is either:

- in any zone other than your library when the sequence begins, or
- moved out of your library during the sequence and then cast, activated, put onto the battlefield, or relied on for its abilities.

Further details:

- Your commander counts as a piece.
- A land counts as a piece if the sequence needs anything from it that a basic land couldn't provide. Examples: being a creature, a non-mana ability, extra mana, or being a specific named card.
- Tokens are not pieces, but the card that creates them is a piece if the sequence needs those tokens.
- Cards that are only drawn, milled, exiled, or revealed without being used are not pieces. For example, the cards Tainted Pact exiles are not pieces.

### 3.2 Baseline Test

To check whether a set of cards forms a combination, assume all of the following:

- Your side of the game contains only those cards, plus any number of basic lands of any types.
- One starting event occurs if the sequence needs one to begin. Examples: one instance of life gain, damage, a creature dying, or a spell being cast.
- Opponents take no actions and control nothing relevant.
- Basic lands may pay any costs. For a loop, though, once the first iteration is complete, every later iteration must generate the resources it spends.

### 3.3 Two-card combination

Two cards form a two-card combination if exactly those two pieces produce the outcome under the Baseline Test.

### 3.4 Unbounded loop

An unbounded loop is a loop as described in MTR 4.4 that, under the Baseline Test, can be repeated an unlimited number of times. One full pass through the repeated sequence is one iteration.

### 3.5 Restricted pair

A restricted pair is any two-card combination that forms an unbounded loop.

### 3.6 Deterministic

An outcome is deterministic if it doesn't depend on random results, hidden information, or opponents' choices. Opponents' responses are ignored for this purpose.

### 3.7 Sequence

A combanation of spells and/or abilities that resolve within the same turn.

### 3.8 Loop Limit (gameplay restriction)

- Any loop that uses both cards of a restricted pair as pieces may be iterated at most once per turn.
- This applies no matter what other cards are involved in the loop.
- It applies whether or not the loop has a payoff or would win the game.
- Each player's turn counts separately.
- Both cards may be in your deck.

### 3.9 No Two-Card Deterministic Win

You may not execute any two-card combination that deterministically does any of the following:

- wins you the game,
- makes all opponents lose, or
- reduces every opponent to a losing condition (0 life, 10 poison, 21 commander damage, or drawing from an empty library) or
- mills your library, or
- draws your library, or any combination that would be a two-card combination if cards moved from your library during the sequence were not counted as pieces.

Check this with 3.8 in effect. A loop that would only win by repeating is governed by 3.8, not 3.9.

### Examples

- **Thassa's Oracle + Tainted Pact:** banned by 3.9.
- **Kiki-Jiki + Zealous Conscripts:** a restricted pair. Legal, but only one iteration per turn under 3.8, so it makes one hasty token.
- **Kiki-Jiki + Zealous Conscripts + Bloom Tender + Deadeye Navigator:** limited to one iteration per turn under 3.8, because the loop uses both cards of a restricted pair. The extra pieces don't change that.
- **Sanguine Bond + Exquisite Blood:** a restricted pair, limited to one iteration per turn.
- **Basalt Monolith + Rings of Brighthearth:** a restricted pair. Basics pay to start it, and each iteration then nets mana. Adding a mana sink as a third card doesn't lift the limit.
- **Deadeye Navigator + Peregrine Drake:** a restricted pair. Each flicker costs 2, and Drake untaps 5 basics, so every iteration pays for itself.
- **Isochron Scepter + Dramatic Reversal:** not a two-card combination. It needs nonland mana rocks, and Dramatic Reversal can't untap basic lands, so it is unrestricted.
- **Dryad Arbor + bestowed Springheart Nantuko:** not an unbounded loop. Each iteration costs {1}{G} that the loop doesn't generate, so it stops once your basics run out.
- **Dryad Arbor + Springheart Nantuko + Badgermole Cub + a haste source:** unrestricted. Dryad Arbor counts as a piece because basic lands aren't creatures, so this is four pieces, and no pair among them loops on its own.
- **Tutors:** Searching for multiple cards with a same card can trigger 3.9 deterministic win sequence. If these cards are searched for and used in the same turn they can trigger 3.9. Some examples include using survival of the fittest 3 times to search for 3 creatures that combine to win the game, or having defense of the heart triggered plus another creature from your hand, or tooth and nail entwined + 1 creature in play. In general, 1 tutor can use only 1 combo piece per turn.

## Disputes

- **D1.** If a dispute comes up mid-game, the play stands. Rule on it after the game for future games.
- **D2.** Keep a written log of every ruling. Rulings act as precedent.
