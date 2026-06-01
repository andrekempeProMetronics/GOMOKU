# GOMOKU
Gomoku game vs. Computer or 2 players - ZERO internet required
Lazy Holiday Production, will update from time to time.
Most effort went into making the AI a realistic opponent
- 

******* QUICK CONFIGURE
- choose 2 players or vs. AI first
- choose your oponent:
There are 3 different play modes, that will provide a different type of opponent.

1. Simple — Minimax algorithm: plays deterministically and tactically—given the same position, it always makes the same move. It responds well to direct threats but lacks a strategic plan. Use this if you want to get the basic logic

2. Master — The algo randomly selects from 8 authentic opening sequences (the first 6–7 moves taken from master games), followed by a strong Minimax engine. Every game begins differently. Use this, if you want to study strategy of masters.

  3. Creative — MCTS with a time budget. MCTS plays statistically and strategically—it thinks in terms of probabilities rather than fixed evaluations. This creates several noticeable differences:
  It plays more variably—the same opening leads to different games because the simulations involve a degree of randomness.
  It develops long-term structures—MCTS recognizes that certain board configurations statistically lead to victory, even if the immediate tactical advantage is not yet apparent.
  It makes more human-like errors—sometimes it overlooks a direct threat because the simulations happened to turn out unfavorably in that specific instance. This makes its gameplay feel less mechanical.
  It grows stronger over time—a larger time budget results in stronger play. You could even implement a difficulty slider that simply adjusts the time budget: 200ms for Easy, 1000ms for Hard. Use this if you want to play with most diversity.

Strength is adjustable via the Quick/Strong toggle. 
Quick/Strong — Applies to both Master and Creative modes:
Quick = 300ms (fluid)
Strong = 1000ms (stronger—particularly noticeable with MCTS)

******* HOW TO PlAY
- You are the black player, try to put 5 Stones in a row
- The edge positions can be occupied as well

- You will start the game, put your first stone
- AI or your oponent will put his next stone
- no time limit, but AI should answer within seconds
- the last stone carries a red dot
- The user who should put the next stone is displayed
- once any user has completed 5 in a row, its highlited. game is over
- press NEW to start the next game
- the looser owns the 1 put
- Enjoy

<img width="1315" height="1792" alt="image" src="https://github.com/user-attachments/assets/ed461fe5-2526-4eaa-9132-f71cf6452529" />
<img width="1323" height="1730" alt="image" src="https://github.com/user-attachments/assets/3cecba89-64c2-40bf-9299-61ecced337c3" />

******* Tested on edge and firefox
on ipad and iphone
