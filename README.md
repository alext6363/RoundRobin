# RoundRobin
Generating a randomised round robin with emphasis on minimising bench time per team/player

# Spec from friend

I want a piece of software for generating a randomised round robin.

So I'd give it a number of players between 12 and 24, a number of courts between 2 and 4, and a number of rounds to generate.

For each round it would place 4 players randomly on a court (2v2) until all courts are full. All remaining players who can't fit on a court would be on the bench for that round.

This much I've been able to do with ChatGPT and Python myself.

The key here is I want to minimise the number of times everyone sits on the bench, and important everyone has to sit on the bench and equal number of times (or as close to as possible) and I want to avoid a person sitting on the bench two rounds in a row. Lastly ideally it would be great if you weren't teamed with the same teammate too often and definitely not two games in a row
So the output would be:

Round 1
   Court 1
     Jordan & Ellen Vs Alex & Vincent
   Court 2
      Same idea
So on so on
   Bench
     Unlucky lad 1, 2 and 3
