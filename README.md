Bracket 3 Experimental: House Rules
Section 0: Baseline

All standard Bracket 3 rules still apply, including the 3 Game Changer maximum, no mass land denial, and no chaining extra turns. There are two exceptions. The guideline against winning before turn 6 is removed. The guideline against early-game 2-card combos is replaced by Rules 1–3 below. Where these rules conflict with official Bracket 3 guidance, these rules win. 

Section 00: Clarification on MLD and Extra Turns
The clarifications in section 00 are in addition to the official MLD and Extra Turn rules and do not replace all MLD/Extra Turn restrictions.
Extra Turns: If a spell or ability would provide 2+ turns instead only 1 of those turns is taken. If you are in an extra turn you may not take an additional consecutive turn.
Mass Land Denial: If a spell or ability would remove 2+ opponents lands or keep them tapped indefinitely (e.g., winter orb, back to basics), instead only 1 of those lands is removed. You may not remove more than 1 land per turn, if an ability does so that land is instead not removed and the land is treated as not removed for the purpose of any conditional effects that may occur.

Section A: Definitions

A1. Piece. A piece is any card the sequence requires, where the card is either:

in any zone other than your library when the sequence begins, or
moved out of your library during the sequence and then cast, activated, put onto the battlefield, or relied on for its abilities.

Further details:

Your commander counts as a piece.
A land counts as a piece if the sequence needs anything from it that a basic land couldn't provide. Examples: being a creature, a non-mana ability, extra mana, or being a specific named card.
Tokens are not pieces, but the card that creates them is a piece if the sequence needs those tokens.
Cards that are only drawn, milled, exiled, or revealed without being used are not pieces. For example, the cards Tainted Pact exiles are not pieces.

A2. Baseline Test. To check whether a set of cards forms a combination, assume all of the following:

Your side of the game contains only those cards, plus any number of basic lands of any types.
One starting event occurs if the sequence needs one to begin. Examples: one instance of life gain, damage, a creature dying, or a spell being cast.
Opponents take no actions and control nothing relevant.
Basic lands may pay any costs. For a loop, though, once the first iteration is complete, every later iteration must generate the resources it spends.

A3. Two-card combination. Two cards form a two-card combination if exactly those two pieces produce the outcome under the Baseline Test.

A4. Unbounded loop. An unbounded loop is a loop as described in MTR 4.4 that, under the Baseline Test, can be repeated an unlimited number of times. One full pass through the repeated sequence is one iteration.

A5. Restricted pair. A restricted pair is any two-card combination that forms an unbounded loop.

A6. Deterministic. An outcome is deterministic if it doesn't depend on random results, hidden information, or opponents' choices. Opponents' responses are ignored for this purpose.

A7. Sequence. A combanation of spells and/or abilities that resolve within the same turn.

Section B: Restrictions

Rule 1: Loop Limit (gameplay restriction).

Any loop that uses both cards of a restricted pair as pieces may be iterated at most once per turn.
This applies no matter what other cards are involved in the loop.
It applies whether or not the loop has a payoff or would win the game.
Each player's turn counts separately.
Both cards may be in your deck.

Rule 2: No Two-Card Library Draw (deckbuilding restriction). Your deck, including your commander, may not contain any two-card combination that deterministically lets you draw your entire library or an arbitrarily large number of cards. Check this with Rule 1 in effect.

Rule 3: No Two-Card Deterministic Win. You may not execute any two-card combination that deterministically does any of the following:

wins you the game,
makes all opponents lose, or
reduces every opponent to a losing condition (0 life, 10 poison, 21 commander damage, or drawing from an empty library) or
mills your library, or
draws your library, or any combination that would be a two-card combination if cards moved from your library during the sequence were not counted as pieces.

Check this with Rule 1 in effect. A loop that would only win by repeating is governed by Rule 1, not Rule 3.

Section C: Disputes

C1. If a dispute comes up mid-game, the play stands. Rule on it after the game for future games.

C2. Keep a written log of every ruling. Rulings act as precedent.

Reference Examples
Thassa's Oracle + Tainted Pact: banned by Rule 3.
Kiki-Jiki + Zealous Conscripts: a restricted pair. Legal, but only one iteration per turn under Rule 1, so it makes one hasty token.
Kiki-Jiki + Zealous Conscripts + Bloom Tender + Deadeye Navigator: limited to one iteration per turn under Rule 1, because the loop uses both cards of a restricted pair. The extra pieces don't change that.
Sanguine Bond + Exquisite Blood: a restricted pair, limited to one iteration per turn.
Basalt Monolith + Rings of Brighthearth: a restricted pair. Basics pay to start it, and each iteration then nets mana. Adding a mana sink as a third card doesn't lift the limit.
Deadeye Navigator + Peregrine Drake: a restricted pair. Each flicker costs 2, and Drake untaps 5 basics, so every iteration pays for itself.
Isochron Scepter + Dramatic Reversal: not a two-card combination. It needs nonland mana rocks, and Dramatic Reversal can't untap basic lands, so it is unrestricted.
Dryad Arbor + bestowed Springheart Nantuko: not an unbounded loop. Each iteration costs {1}{G} that the loop doesn't generate, so it stops once your basics run out.
Dryad Arbor + Springheart Nantuko + Badgermole Cub + a haste source: unrestricted. Dryad Arbor counts as a piece because basic lands aren't creatures, so this is four pieces, and no pair among them loops on its own.
Tutors: Searching for multiple cards with a same card can trigger rule 3 deterministic win sequence. If these cards are searched for and used in the same turn they can trigger rule 3. Some examples include using survival of the fittest 3 times to search for 3 creatures that combine to win the game, or having defense of the heart triggered plus another creature from your hand, or tooth and nail entwined + 1 creature in play. In general, 1 tutor can use only 1 combo piece per turn.