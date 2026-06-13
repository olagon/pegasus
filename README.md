# Pegasus

**Learn the Major System Fast.**

Pegasus is a single file web app for mastering the Major System, the mnemonic
peg technique that turns the numbers 0 to 100 into memorable words. It uses the
same proven learning ideas behind apps like Duolingo and Anki: spaced
repetition, active recall, interleaving, and a daily streak.

## Run it

Open `index.html` in any modern browser. That's it. No install, no server, no
build step, and no internet connection required. All progress is saved locally
in your browser.

## What's inside

- **Spaced repetition** with levels 0 to 5 and growing review intervals.
- **Flashcards both directions**, number to word and word to number.
- **Adaptive difficulty**, multiple choice for new cards, typing once a card is
  learned, then speed.
- **Instant feedback** with the sound breakdown for every answer.
- **Daily practice loop** of about 20 cards, with an end of session summary.
- **Streak tracker** with a daily goal and a calendar heatmap.
- **Sound Code lesson** to drill the ten digit sounds.
- **Decode drill** that teaches you to break any number into sounds then a word.
- **Speed drill** with best and average response time.
- **Personal images** you save for each peg.
- **Number chaining** for random numbers, phone numbers, dates, and years.
- **Memory test** with a growing digit span that tracks your best.
- **Optional audio** using the browser voice.

## Editing the pegs

The peg words live in a `PEG_DATA` array at the top of the script in
`index.html`. Edit a word there any time. Your progress is keyed by number, so
changing a word keeps the level and personal image you already built.

## Tech

One file. Plain HTML, CSS, and JavaScript with no frameworks or libraries.
State is stored in `localStorage`. Audio uses the browser `speechSynthesis` API.
