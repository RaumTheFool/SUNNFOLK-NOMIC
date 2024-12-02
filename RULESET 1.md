# SUNNFOLK NOMIC 1st RULESET 


### 1. RULES (R)

Each Rule is named with the following format: `[natural number]. [name]`. 
Should a Rule contradict another, the Rule named with the lowest number takes precedence. 
No two Rules have the same number or name. 

- Text in (parentheses) provides an abbreviation. 
- Text in \*italics* describes an event. 
- Text in /slash brackets/ has no legal effect. 
- Text in \`\`\`code blocks\`\`\`/\`code blocks` provides a format or quote. 
- Text in [square brackets] is a placeholder.


### 2. PLAYERS AND POINTS

A Player is someone who consents to being a Player and is recorded in #players along with their Point balance. 

A Player's Point balance is a whole number, initially 0. 
The first Player to reach 200 Points wins the game. 
Klark needs 500 Points to win. 
Klark Mutinees need 100 Points to win. 
Klark Devotees win if klark wins, and cannot win any other way.


### 3. BOOKKEEPERS AND ELECTIONS 

A @Bookkeeper enforces the Rules. 
From the moment a Player calls for an Election in #play, Players have 12 hours to reply to it with the name of one Player. 
Given their explicit consent, the Player whose name was iterated most frequently through this process becomes the new @Bookkeeper and the former loses said role. 
Should a @Bookkeeper meet the win condition per Rule "PLAYERS AND POINTS", they do not win. 


### 4. PROPOSALS (P)

The game alternates between three Phases: 
1. The Proposal Phase (PP), 
2. The Voting Phase (VP), and 
3. The Interpretation Phase (IP) 

Each Phase begins at 07:00 and ends at 23:00. The game is paused in-between Phases, which is called Void Time. 

- **THE PROPOSAL PHASE**: 
An unedited message posted in #proposals during the PP, following the format below, is a Proposal;
```
PROPOSAL [natural number]

[Changes described here are applied to the game.]
```
A Proposal's number is 1 higher than the one preceding it. 
An edited message is considered a Proposal if Bookkeepers deem it to have been edited in good faith.

- **THE VOTING PHASE**: 
A :thumbsup: or :thumbsdown: reaction on a Proposal is a Vote. 

- **THE INTERPRETATION PHASE**: 
When checked by a @Bookkeeper during the IP, if a Proposal from the last PP has more :thumbsup: than :thumbsdown: Votes, it passes and its poster gains 5 Points.

Proposals that affect Klark primarily, or that directly mention Klark, require a ratio of 75👍/25👎 or more to pass.


### 5. DECK OF CARDS 

The Deck contains a list of Cards. 
A Card follows the following format: 
```
[natural number]. [name]
/description of effects/
```
 
A Card's number is 1 higher than the preceding card and the lowest is 1. 
No two Cards have the same name. 

Players cannot gain more Cards if they have reached their max hand size
All players have a max hand size of 5. Klark Devotees have a max hand size of 3.

If a Klark Mutinee has one or more cards held in hand with Klark in the title, they lose those cards and gain 10 points per card lost. If they draw a card with Klark in the title, they do not obtain it and may roll again for free.


### 6. PLAYS AND HANDS

When a Player states their intent in #play to perform one of the Plays listed below, which they have performed 0 times this Phase, the Play's effects are executed. 
Should not all of its effects be executed, none are. 
If a Play's effect contradicts the effect of a Card it interacts with, the Card takes precedence. 
A Player's Hand is a list of Cards below their name in #hands. 

- **Draw Card**: 
Lose 5 Points. 
A natural number from 1 to [the number of the highest numbered Card] is randomly generated. 
The corresponding Card's name is added to your Hand.
This cannot be done if you have less than 5 points.
Klark Mutinees gain the opportunity to perform an additional draw, still costing 5 points, if their previous card was played to affect Klark.

- **Use Card**: 
Specify a Card in your Hand. 
That Card's effect, as described in the Deck, is fulfilled, and it is removed from your Hand. 

- **Transfer**: 
Specify a number of Points or Cards in your Hand, which you lose and a player of your choice receives.

- **Transact**: 
Specify a number of Points and/or Cards you wish to sell from your Hand, or buy from another Player's Hand. If, within the current Phase, another Player has responded by specifying a number of Points and/or Cards in their Hand, and you have consented to the Transaction, 
\- You receive, and they lose, what they specified, and 
\- They receive, and you lose, what you specified. 


### 7. KLARK 

Klark is a Player. /He likes flowers and HATES the rich./ 
Every IP, the Player with the fewest Points gains 10 and the Player with the most loses 10. 
Ties are resolved randomly.

Every player has a Klark Affection (KA) score that starts at 0. 
If you give Points to Klark his affection for you increases. 1 Point = 1 KA.
At the end of the game, 1 random Player with the highest KA score marries Klark. <3 
Simultaneously, 1 random Player with the lowest KA score becomes Klark's nemesis. 

### 8. TRIP TRAP

If you document yourself and two or more players taking a walk outside with a picture, all of you earn five points each. 
The picture must be posted in the play chat along with the names of the players who went along on the trip. 
This counts as a play. A player can only claim five points per day from this play.
