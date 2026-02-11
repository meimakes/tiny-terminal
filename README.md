# tiny-terminal

A fake terminal where kids can type anything and get fun, safe responses. Single HTML file, no dependencies, runs offline.

<img width="946" height="519" alt="image" src="https://github.com/user-attachments/assets/a957eac1-a42c-44b5-96a0-21b5253b4b34" />

## Problem

Most "learn to type" apps are boring drills or require accounts and installations. Toddlers and pre-readers need something that rewards every keypress — real words AND keyboard smashing — without frustration or failure states.

## Solution

A browser-based terminal that responds to everything a child types:

- **Animals** — ASCII art + sounds for 20 animals (cat, dog, shark, dinosaur, lobster...)
- **Vehicles** — trucks, airplanes, rockets, excavators, cranes, bulldozers...
- **Colors** — type a color, see emoji things that are that color
- **Letters** — type any letter, see it big with its alphabet animal
- **Numbers** — type a number, see that many emoji. Big numbers (1000+) get a count-up animation
- **Keyboard smashing** — always fun. Emoji explosions, creatures built from typed letters, rainbow spells
- **Challenges** — after a few gibberish entries, a picture prompt appears ("what animal is this?") to nudge toward real words

Nothing is ever an error. Every keypress is a win.

## Usage

Open `index.html` in any browser. That's it.

Works on desktop and mobile. Supports light and dark mode (follows system preference).

## Features

- Zero dependencies, zero build step, zero server
- 20 animals with ASCII art
- 12 vehicles with ASCII art
- 10 colors with emoji collections
- Full alphabet with animal associations
- Number visualization (1-10: emoji rows, 11-999: scaled display, 1000+: count-up animation)
- Keyboard smash detection with 5 varied response types
- Picture challenges that nudge toward real words
- Jokes, magic words, dance party, rainbow mode
- Dark mode + light mode (prefers-color-scheme)
- ASCII art "hello!" welcome with random emoji on each load

## Design Philosophy

- Every input gets a positive response
- Short output — single lines, not paragraphs
- Visual over textual (emoji, ASCII art, big letters)
- Gibberish is celebrated, real words are rewarded more
- Gentle nudges toward typing real words via picture challenges
- No scores, no failures, no ads, no tracking

## License

MIT
