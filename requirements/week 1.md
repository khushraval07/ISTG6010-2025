Battleship Software Design Portfolio

Part 1: Requirements Gathering via Interview

Interview Overview

In order to gain a better understanding of the rules, gaming mechanics, user expectations, and difficulties involved in creating a digital version of the game, a fictitious Battleship expert was interviewed.

Interview Questions and Answers

Q1: What is the main objective of Battleship?

A: The primary goal is to accurately predict your opponent's locations on a grid in order to sink all of their ships before they sink yours.

Q2: How is the game traditionally played?

A: Each player has two grids: one for tracking their opponent's estimates and another for positioning their ships. In order to attack, players alternately call coordinates.

Q3: What are the key components of the game?

A: Hit/miss monitoring, turn-based gameplay, grids, and ships of different sizes.

Q4: What challenges do players face?

A: Recalling past actions, planning ship placement, and anticipating the actions of opponents.

Q5: What features would improve a digital version?

A: Hits and misses are automatically tracked, there is visual feedback, multiplayer support, and potentially AI opponents.

Q6: Should the game support single-player mode?

A: Indeed, when playing alone, an AI opponent is crucial.

Q7: What difficulty levels should AI include?

A: Easy (random moves), Medium (basic strategy), Hard (advanced prediction).

Q8: What type of interface is preferred?

A: A clean grid-based interface with clear visuals for ships, hits, and misses.

Q9: What are common frustrations in physical gameplay?

A: Slow gameplay and manual tracking problems.

Q10: Are there any additional features that could enhance engagement?

A: Animations, sound effects, score tracking, and replay choices

Key Insights:
Clear visual input is necessary for players.
Automation reduces errors.
AI is essential for single-player mode.
Simple, intuitive UI is critical.
The UI is grid-based and clearly labeled.
Controls are easy to understand.
Instructions are available for new players.

Part 2: User Stories & Acceptance Criteria

1. Ship Placement:
I want to set up ships as a player in order to begin the game.
Different ship sizes
No overlap
Within grid

2. Attack System:
I want to attack coordinates as a player in order to destroy ships.
One move per turn
Show hit/miss
No repeat moves

3. Visual Feedback:
I want to see hits and misses so I can monitor my growth as a player.
Clear markers
Instant updates

4. AI Opponent:
I want an AI as a player so I can play by myself.
Difficulty levels
Auto turns

5. Game Outcome:
As a player, I want to know the result.
Detect win/lose
Show result

6. Remaining Ships:
I want to view the remaining ships as a player.
Display count
Update after hits

7. User Interface:
As a player, I want a simple interface.
Clear grid
Easy controls

8. Sound & Effects:
As a player, I want sound and visuals.
Hit/miss sounds
Basic animations
Toggle option

Conclusion

An organized summary of the specifications for a Battleship software solution is given in this portfolio. 
Important gameplay components and user demands were identified through the interview, and the user stories translate those needs into specific development objectives. 
This provides a solid basis for upcoming design and execution.

