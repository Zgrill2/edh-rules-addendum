# Bracket 3 Experimental: House Rules

## Baseline

This is an addendum to Bracket 3. All official Bracket 3 rules still apply, including the 3 Game Changer maximum, except that the guideline against winning before turn 6 is removed. Rules 1–3 below clarify the official guidance on mass land denial, chaining extra turns, and early-game 2-card combos. Where a rule here conflicts with official Bracket 3 guidance, the rule here wins. All other official guidance stays in effect. These rules do not govern any additional deck building restrctions beyond the official bracket 3 rules, but instead only govern gameplay.

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

### 3.1 Pieces

A sequence is a combination of spells and/or abilities that resolve within the same turn. A piece is any card the sequence requires, where the card is either:

- in any zone other than your library when the sequence begins, or
- moved out of your library during the sequence and then cast, activated, put onto the battlefield, or relied on for its abilities.

Further details:

- Your commander counts as a piece.
- A land counts as a piece if the sequence needs anything from it that a basic land couldn't provide. Examples: being a creature, a non-mana ability, extra mana, or being a specific named card.
- Tokens are not pieces, but the card that creates them is a piece if the sequence needs those tokens.
- Cards that are only drawn, milled, exiled, or revealed without being used are not pieces. For example, the cards Tainted Pact exiles are not pieces.
- **Chained searches.** A search is chained if a card found by an earlier search in the same sequence is used to perform, pay for, or enable it. Examples: the found card searches, is sacrificed or discarded as a cost of the next search, or produces the mana for it. If a sequence contains a chained search, cards found by searches during that sequence are not pieces.

### 3.2 Baseline Test

To check whether a set of cards forms a combination, assume all of the following:

- Your side of the game contains only those cards, plus any number of basic lands of any types.
- One starting event occurs if the sequence needs one to begin. Examples: one instance of life gain, damage, a creature dying, or a spell being cast.
- Opponents take no actions and control nothing relevant.
- Basic lands may pay any costs to start the sequence. For a loop, though, once the first iteration is complete, every later iteration must generate everything it spends (mana, life, cards, permanents, and so on) from its pieces alone.

### 3.3 Two-Card Loop Restrictions

A two-card loop may be iterated at most once per turn.

A two-card loop is a loop as described in MTR 4.4 that exactly two pieces can repeat an unlimited number of times under the Baseline Test. One full pass through the repeated sequence is one iteration. A loop that a single piece can repeat by itself also counts for the purposes of 3.3.

- A loop with more than two pieces is still a two-card loop if, with the other pieces removed, two of its pieces would perform the same loop with the same targets.
- This applies whether or not the loop has a payoff or would win the game.
- This applies even if the loop is made of mandatory triggered abilities. After one iteration the loop stops, and any further triggered abilities from that loop are removed from the stack.
- Each player's turn counts separately.

### 3.4 Two-Card Deterministic Win Restrictions

Two cards form a two-card combination if exactly those two pieces produce the outcome under the Baseline Test. An outcome is deterministic if it doesn't depend on random results, hidden information, or opponents' choices. Opponents' responses are ignored for this purpose.

You may not execute any two-card combination that deterministically does any of the following:

- wins you the game,
- makes all opponents lose,
- reduces every opponent to a losing condition (0 life, 10 poison, 21 commander damage, or drawing from an empty library),
- mills or exiles your or your opponent's libraries, or
- draws your library.

This rule is for combos that win without looping, like Thassa's Oracle + Tainted Pact. If a combo wins by looping over and over, like Sanguine Bond + Exquisite Blood, see 3.3 Two-Card Loop Restrictions.

### Examples

**Loops**

- **Kiki-Jiki + Zealous Conscripts:** a two-card loop. Legal, but only one iteration per turn under 3.3, so it makes one hasty token.
- **Kiki-Jiki + Zealous Conscripts + Bloom Tender + Deadeye Navigator:** still a two-card loop, limited to one iteration per turn. With the extra pieces removed, Kiki-Jiki and Conscripts perform the same loop with the same targets.
- **Birds of Paradise + Freed from the Real:** a two-card loop. It does nothing by itself, but adding a payoff like Kinnan, Bonder Prodigy doesn't lift the limit.
- **Murderous Redcap + Gev, Scaled Scorch** (starting event: an opponent lost life this turn): a two-card loop. Redcap targets itself to die and persist.
- **Murderous Redcap + Gev + Ashnod's Altar, targeting opponents:** not a two-card loop. Without the Altar, Redcap can only keep looping by targeting itself, so the loop with the same targets needs all three pieces.
- **Sanguine Bond + Exquisite Blood:** a two-card loop, limited to one iteration per turn even though its triggers are mandatory.
- **Basalt Monolith + Rings of Brighthearth:** a two-card loop. Basics pay to start it, and each iteration then nets mana. Adding a mana sink as a third card doesn't lift the limit.
- **Deadeye Navigator + Peregrine Drake:** a two-card loop. Each flicker costs 2, and Drake untaps 5 basics, so every iteration pays for itself.
- **Isochron Scepter + Dramatic Reversal:** not a two-card loop. Dramatic Reversal can't untap basic lands, so later iterations can't pay for themselves. Adding Mana Vault makes a three-card loop, which is unrestricted.
- **Dryad Arbor + bestowed Springheart Nantuko:** not an unbounded loop. Each iteration costs {1}{G} that the loop doesn't generate, so it stops once your basics run out.
- **Dryad Arbor + Springheart Nantuko + Badgermole Cub + a haste source:** unrestricted. Dryad Arbor counts as a piece because basic lands aren't creatures, so this is four pieces, and no pair among them loops on its own.

**Deterministic outcomes and searches**

- **Thassa's Oracle + Tainted Pact:** may not be executed.
- **Inalla + Spellseeker:** may not be executed. Each Spellseeker copy searches for the cards that pay for the next copy, so the searches are chained and the cards they find aren't pieces. That leaves Inalla and Spellseeker.
- **Birthing Pod, Yisan, and Rocco lines:** chained when each found creature is sacrificed into, untaps, or otherwise enables the next search. Only the engine and the starting creature count as pieces.
- **Survival of the Fittest, discarding each found creature to find the next:** chained, because the found card is the next search's cost.
- **Survival of the Fittest, discarding three unrelated creatures to find three combo pieces:** not chained. Survival plus the three found creatures are four pieces.
- **Tooth and Nail (entwined) + one creature already on the battlefield:** not chained. Tooth and Nail, the two creatures it finds, and the creature on the battlefield are four pieces.
- **Defense of the Heart:** not chained. The creatures it finds count as pieces.
## Disputes

- **D1.** If a dispute comes up mid-game, the play stands. Rule on it after the game for future games.
- **D2.** Keep a written log of every ruling. Rulings act as precedent.
