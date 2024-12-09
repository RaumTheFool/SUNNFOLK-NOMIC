# SUNNFOLK NOMIC 1st RULESET 


## 0. THE GAME 

The Sunnfolk Nomic is a game of nomic as proposed by Peter Suber in 1982. 
It is played by students at a folk high school. 
The game is tracked on GitHub and played in a Discord server. 



## 1. RULES (R)

Each Rule is named with the following format: `[natural number]. [name]`. 
Should a Rule contradict another, the Rule named with the lowest number takes precedence. 
No two Rules have the same number or name. 

__DEFINITIONS:__
- **Definition**: Required way to interpret Rules. 
- **Convention**: Encouraged way to write Rules. 
- **Interpret**: Implement a game change. 
- **Resolve**: Be interpreted. 
- **Amend**: Change Rules. 
- **Append**: Add to end. 
- **Insert**: Add to list, pushing the following points forward. 
- **Clause**: Subset of Ruleset. 
- **Redundant**: Unnecessary as already stated. 
- **Contradiction**: Two clauses that are simultaneously legal and illegal. 
- **Precedent**: More important in a contradiction, aka. "trump".

__CONVENTIONS:__ 
- Text in (parentheses) provides an abbreviation. 
- Text in \*italics* describes an event or game change. 
- Text in /slash brackets/ is flair and has no legal effect. 
- Text in \`\`\`code blocks\`\`\`/\`code blocks` provides a format or quote. 
- Text in [square brackets] is a placeholder.
- Text in **bold** refers to a header. 



## 2. PLAYERS 
Klark is a @Player /who likes flowers and HATES the rich/. 
A @Player meets the following criteria: 
- Is a @Mutinee or @Devotee, unless they are Klark or a @Bookkeeper. 
- Is recorded in #players. 
- Has a Pea balance in #players. 
- Has a Klark Coin (KC) balance in #players. 

A @Player's Peas and KC balance are whole numbers and initially 0. 



## 3. WINNING 
A @Mutinee wins when they reach 100 Peas. 
A @Bookkeeper wins when they reach 250 Peas. 
@Devotees win when Klark reaches 500 Peas. 
If no winner(s) is/are determined within December 24., the game ends. 



## 4. BOOKKEEPING 

A clause is true when a @Bookkeeper interprets it. 
All means of changing the Rules are defined within this Rule. 

The game cycles through three Phases: 
1. The Proposal Phase (PP), 
2. The Voting Phase (VP), and 
3. The Interpretation Phase (IP) 

Each Phase begins at 07:00 and ends at 23:00. 
Void Time is a period without a Phase, during which the Rules are inactive unless stated otherwise. 

- **THE PROPOSAL PHASE**: 

The first @Bookkeeper to post "PP" in #bookkeeping gains 5 Peas. 
A message which is posted in #proposals during the PP and not edited outside the PP, following the format below, is a Proposal;
```
PROPOSAL [natural number]

[effects]
```
A Proposal's number is 1 higher than the one preceding it, initially 1. 

- **THE VOTING PHASE**: 

The first @Bookkeeper to post "VP" in #bookkeeping gains 5 Peas. 
A :thumbsup: or :thumbsdown: reaction on a Proposal is a Vote. 

- **THE INTERPRETATION PHASE**: 

If a Proposal from the previous PP has more :thumbsup: than :thumbsdown: Votes, it passes and its poster gains 10 Peas. 
Proposals that mention Klark require a ratio of 75👍/25👎 or more to pass. 
A random Player gains 10 Klark Coins and another who has more than 0 loses up to 10 Klark Coins.
A @Bookkeeper provides their ChatGPT with the following prompt: 
```
Follow the Rules, assume the role of Klark and write a Proposal per R **BOOKKEEPING**; 

[The Ruleset] 
```
Its response has the header **KLARK'S PROPOSAL** and is a Proposal that passes immediately without Vote. 
The first @Bookkeeper to interpret all changes and post "IP" in #bookkeeping gains 5 Peas. 

A message in #proposals with the header "EMERGENCY PROPOSAL" and a @Player ping is an Emergency Proposal (EP) if it was posted after the previous EP was resolved. 
It initiates a 12-hour period of Void Time where the only active clause is this paragraph. 
When Void Time ends, if the EP has a ratio of at least 75👍/0👎 reactions, it passes. 
Should a non-@Bookkeeper post an EP which does not pass, they cease to be a @Player. 



## 5. PLAYS 

When a @Player states their intent in #plays to perform one of the Plays listed below, which they have not performed this Phase, its effects are executed. 
If not all of its effects are executed, none are. 

- **Transfer**: 
Specify a number of Peas and/or Cards in your Hand, which you lose and a @Player of your choice receives.

- **Transact**: 
Specify a number of Peas and/or Cards you wish to sell from your Hand, or buy from another @Player's Hand. 
If, within the current Phase, another @Player has responded by specifying a number of Points and/or Cards in their Hand, and you have consented to the Transaction, 
\- You receive, and they lose, what they specified, and 
\- They receive, and you lose, what you specified. 

- **Re-Elect**: 
A message in #actions naming one or more @Bookkeepers and calling for a Re-Election, is a Re-Election. 
A 24-hour period of Void Time is initiated, during which the only active clause is this paragraph. 
A reply to a Re-Election with a number of @Player names equal to the number of @Bookkeepers mentioned is a Vote for the named @Players. 
When Void Time ends, the @Players with the most Votes replace the mentioned @Bookkeepers. 
If a @Bookkeeper does not state their choice between @Mutinee and @Devotee before they are replaced, they cease to be a @Player. 

- **Trip Trap**: 
Document yourself and one or more @Players taking a walk outside with a picture and their names. Each mentioned @Player gains 5 Peas. 



## 6. DECK OF CARDS

The Deck contains a list of Cards. 
A @Player's Hand is a list of Card names below their name in #players. 
A Card follows the following format: 
```
[natural number]. [name] 
[TYPE]
[effects]
```
A Card's number is 1 higher than the preceding card and the lowest is 1. 
No two Cards have the same name. 

During the VP, if a @Player states their intent to "draw a Card" in #plays, they lose 5 Peas, a random number from 1 to [the highest Card number] is generated, and the corresponding Card is added to their Hand. 
During the VP, if a @Player states their intent to "discard" a Card from their Hand, it is removed from their Hand. 
If a Mutinee, Bookkeeper or Devotee has respectively 5, 4 or 3 Cards, they cannot gain Cards. 
If not all of a Card's effects are executed, none are. 
If a Card's effect contradicts with a clause in the Ruleset, the Rules take precedence. 

The Card Types are: 

- **CONSUMABLE**: 
During the VP, if a @Player states their intent in #plays to "use" [a Consumable Card in their Hand], the Card is removed from their hand and its effects are executed. 

- **REACTION**: 
A Reaction is used like a Consumable, but in a reply to the use of a Consumable ("target Card") before its effects have resolved. 

- **PASSIVE**: 
The effect of a Passive Card is constantly active while in Hand. 

- **EVENT**: 
The effect of an Event Card is executed immediately when drawn, and the Card is not added to one's Hand. 



## 7. CHURCH OF KLARK (COK)

When a @Player Transfers Peas to Klark, they gain Klark Coins at a 1:1 exchange rate. 
During the PP, if a @Player states their intent in #plays to purchase a Klarkian Blessing they have not purchased this PP, they lose its required number of KC and its effects are executed. 

**KLARKIAN BLESSINGS**: 

- **Klarkian Grace** (5 KC): Gain 10 Peas. 
- **Klarkian Wrath** (10 KC): A Player of your choice loses 10 Peas. 
- **Klarkian Gift** (15 KC): Draw a Card without losing Peas. 

A Klarkian Blessing's price is divisible by 5. @Devotees get a 20% discount on Klarkian Blessings. 
