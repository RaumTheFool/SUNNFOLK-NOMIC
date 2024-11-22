# SUNNFOLK NOMIC 1st RULESET 


### 1. RULES (R)

Each Rule is named with the following format: `[natural number]. [name]`. 
Should a Rule contradict another, the Rule named with the lowest number takes precedence. 
No two Rules have the same number or name. 


### 2. PLAYERS AND POINTS

A Player is someone who consents to being a Player and is recorded in #players along with their Point balance. 

A Player's Point balance is a whole number, initially 0. 
The first Player to reach 200 Points wins the game. 


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

- THE PROPOSAL PHASE 

An unedited message posted in #proposals during the PP, following the format below, is a Proposal;
```
PROPOSAL [natural number]

[Changes described here are applied to the game.]
```
A Proposal's number is 1 higher than the one preceding it. 

- THE VOTING PHASE 

A :thumbsup: or :thumbsdown: reaction on a Proposal is a Vote. 

- THE INTERPRETATION PHASE 

When checked by a @Bookkeeper during the IP, if a Proposal from the last PP has more :thumbsup: than :thumbsdown: Votes, it passes and its poster gains 5 Points. 


### 5. DECK OF CARDS 

The Deck contains a list of Cards. 
A Card follows the following format: 
```
[natural number]. [name]
/description of effects/
```
 
A Card's number is 1 higher than the preceding card and the lowest is 1. 
No two Cards have the same name. 


### 6. PLAYS AND HANDS

When a Player states their intent in #play to perform one of the Plays listed below, the Play's effects are executed. 
Should not all of its effects be executed, none are. 
If a Play's effect contradicts the effect of a Card it interacts with, the Card takes precedence. 
A Player's Hand is a list of Cards below their name in #hands. 

- Draw Card: 
Lose 5 Points. 
A natural number from 1 to [the number of the highest numbered Card] is randomly generated. 
The corresponding Card's name is added to your Hand. 

- Use Card: 
Specify a Card in your Hand. 
That Card's effect, as described in the Deck, is fulfilled, and it is removed from your Hand. 

- Transfer: 
Specify a number of Points or Cards in your Hand, which you lose and a player of your choice receives.


### 7. KLARK 

This is Klark. 
He counts as a Player for all intents and purposes. 
Klark likes flowers and HATES the rich. 
when this proposal resolves and at the end of every week (sunday 23:59) Klark steals 10 points from the player with the most points and gives it to the person with the least points. 
If multiple people share the last place the points are splittend evenly rounded down

