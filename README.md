# Brass Rail Poker

A Texas Hold'em game built to teach poker while you play. It is a single `index.html` file with no build step and no dependencies.

## Features

- **Learn**: the 10 hand rankings with example cards and odds, 7 short lessons (how a hand plays, starting hands, position, outs and the rule of 2 and 4, pot odds, betting and bluffing), and an endless "Which hand wins?" quiz.
- **Practice with Coach Mae**: on each of your turns the coach names your hand and draws, counts outs, estimates your winning chance with Monte Carlo simulation, compares it with the pot odds, and recommends fold, check, call or raise, with a reason. After each hand she reviews what happened.
- **Vs AI**: 1 to 5 opponents at four levels: Easy, Medium, Hard and Poker Master. Poker Master tracks how often you fold or call and adjusts its bluffing.
- **Friends**: a host creates a table with a four-letter code and friends join with it.
- **Animations**: a dealer shuffles and deals, cards fly to each seat and flip, bets slide into the pot, and chips fly to the winner.

## Running it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Limitations outside claude.ai

The Friends tables and the coach's "Ask Mae" box use runtime features that only work when the page is opened as a Claude artifact on claude.ai. Opened anywhere else, Friends shows a notice and the Ask box stays hidden; Learn, Practice and Vs AI work fully.
