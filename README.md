# ClientQuest — Real Game Marketing Venture

**Marketing your clients will actually play.**

ClientQuest turns relationship-driven professionals (realtors, lenders, insurance agents, financial advisors, dentists, attorneys) into the hero of beautiful, 5-minute story games — custom-branded to each professional and wired into three growth systems:

1. **Referral engine** — finishing a game unlocks a two-sided share loop (client *and* friend both get a perk)
2. **Follow-up CRM** — plays, replays, shares and perk claims become timing signals for outreach
3. **Relationship catalyzer** — milestones (home-iversaries, renewals, birthdays) delivered as tiny playable moments
4. **Client perk** — every finished story ends with a real gift the client claims from the professional

Each profession gets **four games** built from four shared archetypes — Story Adventure, Cozy Puzzle, 60-Second Arcade, Tycoon Builder — fully restyled with characters, stakes and humor native to that profession.

## 🔑 Phase 1 flagship (playable now): KEYS — A Realtor Story Adventure

A cinematic, choice-driven story game: guide the Rivera family (and Biscuit the golden retriever) from a nervous café meeting to keys-in-hand.

- **Hand-drawn animated SVG scenes** — golden-hour bungalow, dusk loft, night skyline, drifting clouds, twinkling windows
- **Choices that matter** — Trust 💛, Insight 🔍 and Momentum ⚡ shape branches and endings
- **Dopamine systems** — XP, levels, streak multipliers, floating rewards, particle bursts, confetti, WebAudio chimes
- **Hidden-detail hunts** — find what the listing photos hide (foundation cracks, HOA hikes, oak floors under carpet); foresight pays off later in the story
- **Timed bidding war** — a countdown decision under pressure
- **Dream Match score + badges** at the finale
- **Agent branding end-to-end** — `?agent=Jane+Doe&brokerage=Acme+Realty` personalizes the whole game, down to the SOLD sign
- **Client perk + referral CTA** built into the ending

Zero dependencies. One self-contained HTML file.

## Running the site

Static site — no build step:

```bash
npx serve .          # or: python3 -m http.server
# open http://localhost:3000            → marketing site
# open /games/realtor/keys/index.html   → the flagship game
```

## Project structure

```
index.html                     Marketing site (landing)
css/site.css                   Shared site styles
js/site.js                     Scroll-reveal behavior
professions/*.html             Six profession hubs (4 games each)
games/realtor/keys/index.html  KEYS — flagship story adventure (self-contained)
assets/                        Gameplay screenshots used as promo art
```

## Roadmap

- **Phase 1 (now):** site + KEYS flagship demo
- **Phase 2:** realtor suite (Staged!, Closing Rush, Blockwise) + agent onboarding/branding flow
- **Phase 3:** CRM backend (play-signal pipeline, referral tracking, perk redemption)
- **Phase 4:** remaining profession suites (lenders, insurance, advisors, dentists, attorneys)
