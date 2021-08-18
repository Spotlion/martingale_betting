# martingale_betting
Inspired by Gil Banuelos, who proposed a betting strategy that I'd wondered about in the past as well.

Imagine gambling on a coin flip, where you choose whatever bet size you'd like. Heads you win, tails you lose. The proposed strategy is as follows: start with a small bet. Every time a tails comes up, double the bet sizing. Every time a heads comes up, reset the bet sizing to the original amount. The idea behind this is that every time a heads comes up, the gambler wins an amount of money equal to the original small bet size, regardless of the number of tails that have come up beforehand.

Turns out this is already known as the martingale betting system (https://en.wikipedia.org/wiki/Martingale_(betting_system)). Each round of betting has an expected gain of exactly 0, and later rounds aren't informed by earlier rounds. The gambler can win a small amount of money with high probability, or lose vast amounts with low probability. The goal of this project is to explore this betting strategy, compare it with others, and see how viable it is.
