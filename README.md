# rxKata
A simple exercise to get our feet wet with ReactiveX 

Inspired by https://github.com/varokas/kata-rx/wiki/Kata-RX-Consensus, we actualized a bit to 2016 the problem.

Write a program to take output from 100 voters. Each of them waits randomly between 1-5 seconds, and returns randomly one of the following Strings (currently active candidates from https://ballotpedia.org/Presidential_candidates,_2016): 

- Hillary Clinton
- Roque De La Fuente
- Bernie Sanders
- Ted Cruz
- John Kasich
- Marco Rubio
- Donald Trump (or if you prefer, return Donald Drumpf) 

Once we collected the votes, print out the number of votes each candidate got. If a candidate got 0 you don't have to print it. 
