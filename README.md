# ArtSignal — Read the Chain

<a href="https://orynth.dev/projects/artsignal" target="_blank" rel="noopener">
  <img src="https://orynth.dev/api/badge/artsignal?theme=light&style=default" alt="Featured on Orynth" width="260" height="80" />
</a>

Static one-page site for **ArtSignal**, an on-chain signal intelligence brand for the Solana ecosystem.

## Pages

- `index.html` — main landing page (signals feed, protocol, roadmap, tokenomics, community, about, FAQ)
- `whitepaper.html` — full protocol whitepaper (v1.2)
- `privacy.html` — privacy policy
- `terms.html` — terms of use
- `cookies.html` — cookie policy with a working preferences panel
- `disclaimer.html` — risk disclosure / disclaimer

## Stack

Pure HTML + CSS + vanilla JS. No build step. No dependencies beyond Google Fonts. Deploy to any static host (Vercel, Netlify, GitHub Pages, Cloudflare Pages).

## Local preview

```sh
# any static server works
npx serve .
# or
python3 -m http.server 8000
```

## Highlights

- Editorial black-and-white aesthetic, custom cursor, magnetic buttons
- Live ticker, scroll reveals, stat counters, animated progress bars
- Sortable + filterable + searchable signal table
- Live "last updated" timestamps that auto-increment
- Countdown timer to the $SIGNAL TGE
- Cookie-consent banner with granular preferences (saved to localStorage)
- Full responsive layout, mobile menu, touch-friendly interactions
- Five legal pages, all linked from the global footer
