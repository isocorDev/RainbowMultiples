# Rainbow Multiples

An interactive hundred chart for kids learning multiplication. Every square from 1 to 100 has nine small windows laid out like a phone keypad, one for each number from 1 to 9. A window lights up in that number's color when you can skip count by it and land exactly on the square's number.

Built for a second grader, but the patterns hold up for anyone.

## What you can do

- **Turn colors on and off.** The keypad matches the window layout inside every square.
- **Switch layouts.** Choose between the 1 to 100 chart and a 10 by 10 times table.
- **Tap a square.** See which jumps land on it, place value or a dot array, and whether it's prime.
- **Tap a row or column label.** Follow one line and see how often each color shows up in it.
- **Skip count.** Watch any number from 1 to 9 hop across the grid.
- **Things to notice.** Eight guided questions: even numbers, the 9s diagonal, primes, the most colorful number, the times table mirror, and more.

## English and Spanish

Use the English / Español switch at the top. The page remembers the choice, and opens in Spanish on devices set to Spanish. To share a link that always opens in Spanish, add `?lang=es` to the end of the address.

## Running it

It's a single `index.html` with no build step and no dependencies. Open it in a browser, or serve the folder with any static host.

## Hosting on GitHub Pages

1. Push this folder to the repo's `main` branch.
2. In the repo, go to **Settings > Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. The site goes live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Notes

- Works on phones, tablets and desktops, in light and dark mode.
- Fonts load from Google Fonts. If they can't load, the page falls back to system fonts and still works offline.

## License

MIT. See `LICENSE`.
