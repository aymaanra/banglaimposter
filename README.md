# 🕵️ Bangla Imposter

A pass-the-phone party word game. Everyone secretly sees the same Bangla word — except the imposter, who only gets a vague hint. Talk your way around the word and figure out who's bluffing!

## How to play

1. **Set up** — choose the number of players (3–12) and imposters (1, or 2 with 6+ players), then tap **Start Game**.
2. **Pass the phone** — each player takes the phone in turn and taps once to secretly reveal their card:
   - Regular players see the **secret word** (e.g. ইলিশ মাছ).
   - The imposter sees only a **hint** (e.g. একটা মাছ) — and must bluff.
3. **Clue rounds** — going around the circle, everyone says **one word** related to the secret word (never the word itself). The imposter has to improvise from the hint.
4. **Not sure who's faking?** Tap **Another Round** and go again.
5. **Accuse out loud**, then tap **Reveal Imposter** to see who it was, the secret word, and the hint.

## Running it

It's a single self-contained `index.html` — no build, no dependencies, works offline.

- Open `index.html` in any mobile browser, **or**
- Enable **GitHub Pages** for this repo (Settings → Pages → deploy from the `main` branch) and play at the published URL.

## Notes

- ~100 built-in Bangla word/hint pairs across categories: food, places, transport, sports, animals, everyday things, culture, nature, professions, and school.
- Words don't repeat within a session until the whole list has been used.
- UI is in English; secret words and hints are in Bangla.
