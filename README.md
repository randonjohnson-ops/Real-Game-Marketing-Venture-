# ClientQuest — Real Game Marketing Venture

**Real games where your client plays the hero — and you're the in-game guide.**

ClientQuest builds actual adventure games (think top-down Zelda-style exploration, races, showdowns — not text with buttons) for relationship-driven professionals in our **four launch industries**:

1. 🏡 **Real Estate Agents** (flagship)
2. ⚖️ **Lawyers**
3. 🦷 **Dentists & Orthodontists**
4. 🛡️ **Insurance Agents**

The client creates their own character and plays the lead. The professional appears **inside the game** as the branded guide NPC — named, styled, and showing up at exactly the right moments. Around the games sit three growth systems:

- **Referral engine** — finishing a game unlocks a two-sided share loop (client *and* friend both get a perk)
- **Follow-up CRM** — plays, replays, shares and perk claims become timing signals for outreach
- **Relationship catalyzer** — milestones (home-iversaries, renewals, checkups) delivered as tiny playable moments
- **Client perk** — every finished game ends with a real gift the client claims from the professional

Each profession gets **four games** from four shared archetypes — **Adventure Quest** (open-world exploration), **Showdown** (face-off battles), **Rush** (60-second arcade), **Empire** (build & grow) — fully restyled with heroes, villains and stakes native to that profession.

## 🔑 Phase 1 flagship (playable now): KEYS — A Dream-Home Adventure

A top-down open-neighborhood action-adventure. **You are the house hunter.** Your realtor is your guide.

- **Character creator** — name, skin, hair, outfit; the client plays as themselves
- **Open world** — walk (WASD/arrows or touch joystick) through Willow Falls: streets, park, fountain, café, three unique houses
- **Guide NPC** — the agent (branded via URL) leads you between quests, comments on your finds, coaches the finale; Biscuit the golden retriever joins your party
- **Quest chain** — meet your agent → collect your moving-fund coins → tour three houses and hunt hidden clues inside (HOA notices, foundation cracks, oak under the carpet) → choose your home
- **Rival race** — a cash buyer sprints for Listing HQ; cut across the park and beat them
- **Offer showdown** — timing-based lock-in minigame with agent coaching between rounds
- **Dopamine everywhere** — coins, screen shake, particles, quest banners, badges, confetti, synthesized sound, Dream Match score
- **Marketing hooks** — agent branding end-to-end (`?agent=Jane+Doe&brokerage=Acme+Realty`), client perk with claim code, two-sided referral CTA

Zero dependencies. One self-contained HTML file. Keyboard + touch.

## 🛡️ NEW — COVERED: Run for Cover (2D arcade platformer, playable now)

A **Super Mario-style side-scrolling arcade adventure** — pure Canvas 2D, **zero dependencies**, one self-contained ~40KB file that loads instantly on phone or desktop and is easy to text or email to a client.

- **Story with a villain:** a superstorm hit town and **HAVOC the Storm Gremlin** is trashing it for fun. Race through the flooded neighborhood, rescue **5 keepsakes**, and defeat Havoc.
- **The agent helps you win:** in the boss fight your insurance agent tosses **Policy Stars** that empower you to land the three winning hits — the professional literally helps you beat the antagonist.
- **Robust platforming:** run/jump with coyote time, jump buffering, variable-height jumps, enemy stomps, moving platforms, flood pits with checkpoint respawn, hail, fire, coins, hearts.
- **Refined, nuanced background:** layered parallax (sun/glow, hills, town skyline, drifting clouds, tree line), grass-and-dirt ground, animated flood water, storm weather that ramps across three acts, lightning, vignette.
- **Agent prominent at open & close:** firm-branded title screen; finish card with the agent's photo, logo, name, firm and **Call / Email / Leave a Google review / Share with a friend**.
- **Customizable hero** (name entry) + **uploadable agent branding** (headshot, logo, contact, review link; localStorage + URL params `?agent=…&firm=…&phone=…&review=…`).
- **Controls:** WASD/arrows + Space on desktop; on-screen left/right + jump on touch.
- **Theme-driven engine** (a `THEME` config block) so the same code re-skins for realtors, lawyers and dentists next — swap villain, palette, dialogue and items.

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
professions/*.html             Four profession hubs (4 games each)
games/realtor/keys/index.html  KEYS — flagship adventure (self-contained)
games/insurance/covered/index.html  COVERED: Run for Cover — 2D arcade platformer (Canvas, no deps)
assets/                        Gameplay screenshots used as promo art
```

## Roadmap

- **Phase 1 (now):** site + KEYS flagship adventure
- **Phase 2:** realtor suite (Bidding War, Closing Rush, Blockwise) + agent onboarding/branding flow
- **Phase 3:** CRM backend (play-signal pipeline, referral tracking, perk redemption)
- **Phase 4:** the other launch suites (lawyers, dentists, insurance agents)
