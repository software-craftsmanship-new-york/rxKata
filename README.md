# rxKata

> Inspired by https://github.com/varokas/kata-rx/wiki/Kata-RX-Consensus, we actualized a bit to 2016 the problem.

Write a program to take output from 100 voters. Each of them waits randomly between 1-5 seconds, and returns randomly one of the following Strings (currently active candidates from https://ballotpedia.org/Presidential_candidates,_2016): 

- Hillary Clinton
- Roque De La Fuente
- Bernie Sanders
- Ted Cruz
- John Kasich
- Marco Rubio
- Donald Trump (or if you prefer, return Donald Drumpf) 

Once we collected the votes, print out the number of votes each candidate got. If a candidate got 0 you don't have to print it. 


## Format

> Inspired by https://github.com/zdsbs/reactive-programming-exercise

**Rules**

- You are excused of writing tests today. Exceptionally. We will prepare a separate session on testing Rx. Enjoy! 
- Be prepared to share your learnings, that will make the session fun! 
- Form teams of 3! (not 4, not 2)
- Draw, design, read, learn first! Chop up the work! 
- Take babysteps, iterate! 
- **Plan**: 2 x (45 mins session + 10 mins retro)


**Recommended iterations** 

1. [optional] If you know threads well, implement it first without Rx!  

2. Implement with a dozen votes first with a blocking Observable (just use a list) and print the individual votes 

3. Implement the vote counting query on top of it

4. Make the Observable parallel with Schedulers

