# lazydle

A lazy solution to being bored. A Wordle-style word guessing game — in English, French, and Spanish, switchable mid-game.

## Why

Regular Wordle clones only do one language. This one doesn't see why that should be a limitation — pick a word in English, get stuck, switch to French, come back later. No reason a word game has to pick a side.

## How to play

1. Open `index.html` in any browser — no install, no build step
2. Pick a language (EN / FR / ES) up top
3. Type a 5-letter word and hit Enter (or click the on-screen keyboard)
4. Sage green = right letter, right spot. Gold = right letter, wrong spot. Gray = not in the word.
5. Six tries. Switch languages anytime, even mid-game — your progress in each language is remembered separately.

## Tech

Single-file HTML/CSS/vanilla JS. No dependencies, no build tools, no frameworks. Just open the file.

## Ideas for later

- More words per language (currently 20 each, so it repeats fast)
- A daily word mode (same word for everyone, like the original Wordle)
- A streak counter / stats tracking
- More languages
