# Costume Party

Suppose you're attending a Marvel costume party. There are 10 people invited, and
the host has specified that everyone should choose from one of the following 10 
costumes:

* Spiderman
* Black Panther
* Scarlet Witch
* Iron Man
* Black Widow
* The Wasp
* Thanos
* Gamora
* Groot
* Captain Marvel

Unfortunately, you arrive early (well, on time, but you know, BYU standard time).
As guests arrive, you grow nervous that someone will be wearing your same costume.
As the number of guests grows, what's the probability that someone is wearing your
same costume? Be sure to assess the monte carlo error of your estimate.

1. Write a function with the following parameters:
  `n`: the number of people at the party (not counting yourself).
  `n_reps`: the number of times to run the simulation.
This function should return a numeric vector (or data.frame) of length 3
containing an estimate of the probability that someone is wearing your same
costume for the given value of n along with the upper and lower bounds of your
confidence interval.

2. Use the function defined above to calculate the likelihood that your costume
will be duplicated as each guest arrives at the party.

3. Create a plot that shows the probability of someone sharing your costume as guests
arrive at the party, along with your upper and lower bounds.
