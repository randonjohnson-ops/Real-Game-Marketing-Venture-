# EMBERFALL — The Last Ember Ronin

An original **16-bit SNES-era side-scrolling action platformer**, built in the spirit of Contra III, Shinobi III, Mystical Ninja, Hagane and Mega Man X — with entirely original characters, world, art, enemies and music. Pure Canvas 2D, **zero dependencies**, one self-contained file.

Play **Ash Vayle**, the last Ember Ronin, cutting through **THE HOLLOW** — a rogue machine legion that seized the burning sky-city of Aurelia.

## Run it
Open `index.html` in any modern browser (desktop or mobile).

## Controls
- **Move:** ← → / A D · **Look up:** ↑ / W · **Crouch/drop:** ↓ / S
- **Jump:** Z / Space (variable height + wall-jump)
- **Slash:** X / J (3-hit plasma-katana combo)
- **Shoot:** C / K (wrist blaster, uses EN energy)
- **Dash:** Shift / L (i-frame burst)
- **Start / confirm:** Enter
- **Mobile:** on-screen D-pad + JUMP / SLASH / SHOOT / DASH buttons

## What's in the build (Stage 1 vertical slice)
- **Authentic pixel rendering** — 384×216 internal buffer, nearest-neighbor upscale, limited saturated palette, banded skies, 3-layer parallax city, tile-based world, hand-authored 5×7 pixel font HUD.
- **Tight arcade controls** — instant acceleration, variable-height jump, full air control, coyote time + jump buffering, wall-slide/wall-jump, dash with i-frames, quick recovery.
- **Combat** — melee combo + ranged blaster, enemy hit-stun, knockback, invincibility frames, screen shake, hit sparks.
- **Handcrafted stage** — platforming over lethal pits, floor & ceiling spikes, a chain crusher, fire jets, destructible crates, health/energy pickups, checkpoints, hidden ledges.
- **Enemies with readable patterns** — spider-drone walkers (ledge-aware), hover-wing flyers (aimed shots), wall turrets.
- **Miniboss** — the **Hollow Brute** (armored charger with telegraphed lunges and its own HP bar).
- **Multi-phase boss** — the **Hollow Warden**: aimed volleys, ground-slam shockwaves and minion summons in phase 1; faster, denser patterns in phase 2.
- **Chiptune soundtrack** — driving pulse-lead / triangle-bass / noise-drum sequencer, plus synth SFX.

## Notes
This is Stage 1 of a planned multi-stage game. Characters, enemies and props are drawn procedurally from a disciplined pixel palette on the low-res buffer (no external sprite sheets), which keeps the whole game in one tiny shareable file. The natural next step for even higher fidelity is a hand-authored sprite-sheet pipeline feeding the same engine.
