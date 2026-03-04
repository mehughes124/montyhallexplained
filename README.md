# montyhallexplained.cc

An interactive visualization of the Monty Hall problem using a deck of 52 playing cards instead of the classic 3-door framing.

## Why cards instead of doors?

The Monty Hall problem is famous for being unintuitive — even PhD mathematicians have gotten it wrong. The 3-door version makes it hard to *feel* why switching is correct because 33% vs 67% is close enough to 50/50 that your brain rebels.

With 52 cards, the same logic produces a 1.9% vs 98.1% split. Nobody looks at those numbers and thinks "could go either way." The math is identical. Only the feeling changes.

## The core insight

You pick a card. A dealer who knows where the Ace of Spades is flips over 50 cards — carefully avoiding the Ace every time. Two face-down cards remain.

The question is: **why did each card survive?**

- Your card survived because you froze it with a blind guess.
- The other card survived because the dealer was *forced to protect it*.

One was preserved by ignorance. The other was preserved by knowledge. They look the same, but they have completely different origins — and completely different odds.

## Tech

Single static HTML file. No build step, no dependencies, no JavaScript frameworks. Two Google Fonts loaded via CDN. Runs anywhere.

## Deploy

Drop `index.html` on any static host — GitHub Pages, Cloudflare Pages, Netlify, or just open the file in a browser.

## License

MIT — see [LICENSE](LICENSE).
