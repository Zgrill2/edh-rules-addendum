# Bracket 3 Experimental: House Rules

## Baseline

This is an addendum to Bracket 3. All official Bracket 3 rules still apply, including the 3 Game Changer maximum, except that the guideline against winning before turn 6 is removed. Rules 1–3 below clarify the official guidance on mass land denial, chaining extra turns, and early-game 2-card combos. Where a rule here conflicts with official Bracket 3 guidance, the rule here wins. All other official guidance stays in effect.

## Rule 1: Mass Land Denial

This rule only governs opponents' lands. You may do whatever you want to your own lands.

- **1.1** No more than one land owned and controlled by an opponent may leave the battlefield each turn as a result of spells and abilities you control.
- **1.2** If more would leave, the controller of the spell or ability chooses which one leaves. If one has already left this turn, none leave. Lands that don't leave stay on the battlefield and are treated as never having left for any effect that checks.
- **1.3** Cards that keep lands tapped or change what mana lands produce (e.g., Winter Orb, Blood Moon, Back to Basics) are still not allowed, as in official Bracket 3.

Examples:

- **Terastodon targeting one land from each of three opponents:** only one is destroyed, and its controller gets the only Elephant.
- **Terastodon targeting three of your own lands:** all three are destroyed.

## Rule 2: Extra Turns

- **2.1** If you would take an extra turn immediately after an extra turn of yours, that turn is skipped instead. If a spell or ability would give you 2+ extra turns in a row, you take the first and skip the rest.
- **2.2** Extra turns that aren't back to back are fine. For example, Lighthouse Chronologist gives you an extra turn after each opponent's turn, which is allowed.

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

A combination of spells and/or abilities that resolve within the same turn.

### 3.8 Loop Limit (gameplay restriction)

- Any loop that uses both cards of a restricted pair as pieces may be iterated at most once per turn.
- This applies no matter what other cards are involved in the loop.
- It applies whether or not the loop has a payoff or would win the game.
- Each player's turn counts separately.
- Both cards may be in your deck.
- This applies even if the loop is made of mandatory triggered abilities. After one iteration the loop stops, and any further triggered abilities from that loop are removed from the stack.

### 3.9 No Two-Card Deterministic Win

You may not execute any two-card combination that deterministically does any of the following:

- wins you the game,
- makes all opponents lose, or
- reduces every opponent to a losing condition (0 life, 10 poison, 21 commander damage, or drawing from an empty library) or
- mills your library, or
- draws your library, or any combination that would be a two-card combination if cards moved from your library during the sequence were not counted as pieces.

Check this with 3.8 in effect. A loop that would only win by repeating is governed by 3.8, not 3.9.

### Examples

- **Thassa's Oracle + Tainted Pact:** may not be executed.
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
