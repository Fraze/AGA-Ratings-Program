# AGA-Ratings-Program
AGA Ratings Program

## What If...
What if you could instantly get an updated rating after your tournament? What if it were as simple as making an api call?

## Why
Might there be better ways to rate games? Maybe (*cough* Whole History Rating, Glicko-2 (OGS), etc *cough*). But many people specifically want to know their AGA rating. While the AGA owns their database of "members", it is possible to calculate for anyone an "unofficial" rating that would exactly match what the AGA would reward. However, where the AGA is resicted by various factors and considerations, the general public is not.

## The Math
Paul Matthews was one of the lead authors of the rating system. He published an "easy" to understand explanation of the system
Simple Version - https://github.com/amj/AGA-Ratings-Program/tree/myfork

Phil Waldron had a role I have not yet unearthed, but he has provided an detailed mathematical explanation of the system.
Detailed Version - https://www.usgo.org/sites/default/files/pdf/AGARatings-Math.pdf

## The Code
The code for the ratings were written by Jonathan Bresler of which this repositor is forked from. This is the code the AGA currently uses to calculate ratings.

Andrew Jackson has done some work on this. Particularily in updating the sigma value for how your rating decays over time so that people are able to advance more true to their actaul ability.
He has a forked version of this code here (https://github.com/amj/AGA-Ratings-Program/tree/myfork)

I also found online some code written by Philip Waldron. I think it is written in perl and it has some good notes in it
https://metacpan.org/source/REID/Games-Go-AGA-BayRate-0.119/lib/Games/Go/AGA/BayRate/Collection.pm#PGames::Go::AGA::BayRate::Collection

