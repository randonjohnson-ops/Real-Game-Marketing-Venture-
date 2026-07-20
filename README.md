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
assets/                        Gameplay screenshots used as promo art
```

## Roadmap

- **Phase 1 (now):** site + KEYS flagship adventure
- **Phase 2:** realtor suite (Bidding War, Closing Rush, Blockwise) + agent onboarding/branding flow
- **Phase 3:** CRM backend (play-signal pipeline, referral tracking, perk redemption)
- **Phase 4:** the other launch suites (lawyers, dentists, insurance agents)
