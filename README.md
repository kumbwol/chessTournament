# Test task - Chess tournament

A chess tournament is held with 5 participants. Each player plays against everyone else. For each match, the winning player receives 2 points and the losing player receives none. In case of a draw, both players receive 1 point.

An example representation of the tournament results:

 `- A B C D E`<br/>
 `A 0 2 2 1 0`<br/>
 `B 0 0 1 2 0`<br/>
 `C 0 1 0 1 2`<br/>
 `D 1 0 1 0 2`<br/>
 `E 2 2 0 0 0`<br/>

Explanation:

 1. Player "A" does not play against herself. 
 2. "A" beats player "B", receiving 2 points. 
 3. "A" also beats player "C" receiving 2 points. 
 4. The result of the match between "A" and "D" is a draw. Both players receive 1 points. 
 5. "A" loses versus "E". She gets no points, while "E" receives 2.


## 1. Generate a tournament result in the format above. The result of any match is completely random, with equal probability between the three outcomes. Log it to the console.
Note, that if player "A" beats player "B", that also means player "B" has lost against player "A".
   
   
## 2. Log to the console the winner of the tournament, and the total points of the winner:

i.e.:<br/>
  `- A B C D E`<br/>
  `A 0 1 1 2 1`<br/>
  `B 1 0 2 2 2`<br/>
  `C 1 0 0 2 2`<br/>
  `D 0 0 0 0 2`<br/>
  `E 1 0 0 0 0`<br/>
  
  B has won with 7 points.
  
  ## 3. Bonus math: Who is the more successful player on average: 
  - Player X, who wins a match with 40% probability, draws with 30% and loses with 30% or
  - Player Y, who wins 25%, drwas 60% and loses 15% 
