# The TalinBuilds Brand System

**Scope, read this first.** This file governs TalinBuilds' OWN site, pitch decks, and outreach materials only. It is not a palette to reuse on client builds. Phase 3 and Phase 5 already require every client site to derive its own palette, type trio, and motion from that client's own world; a fixed house style applied to every client is exactly the industry-template failure mode (the same mistake a generic category-lookup tool makes: same spa gets the same pink-and-sage palette every time). TalinBuilds' identity below exists so the business itself has one consistent, premium face across its own site, proposals, and demo reels. Every client still gets bespoke treatment.

## The mark and what it says

An asymmetric T: the left arm shorter, the right arm longer, leaning forward rather than standing static. A single accent-color block sits at the base of the stem — a terminal cursor, the moment before the next character is typed. Read together: a builder in motion, always mid-sentence, never finished. The wordmark sits lowercase (`talinbuilds`) under it, with the tagline `builds with ai` in a much smaller, wide-tracked caps line beneath. This is already built (`logo.html`); this file is the system around it.

## Color tokens

```css
:root{
  --canvas: #111010;       /* near-black, warm, not pure black — a terminal that has been running for hours */
  --surface: #F7F7F4;      /* the light-mode counterpart, warm off-white, not pure white */
  --accent: #39FF9B;       /* cursor green on dark canvas — the only color that moves */
  --accent-light: #00C672; /* cursor green on light surface — same role, adjusted for contrast */
  --muted: #7A7A78;        /* secondary text, quiet */
  --border: #E0E0D8;       /* hairline dividers on the light surface */
}
```

The accent rule from `scrub-pipeline.md`'s Design Direction applies with extra force here, because the accent IS the brand idea: it appears in rare doses only — a cursor, a single underline, one active state, one CTA. If the accent is common on the page, it stops reading as "the thing that's alive" and becomes decoration. Everywhere else stays near-black, warm off-white, and muted gray.

## Type system

A concrete scale, not a habitual default. Base size 16px, ratio 1.25:

| Token | Size | Typical use |
|---|---|---|
| `--text-xs` | 12.8px | mono labels, timestamps, eyebrow text |
| `--text-sm` | 16px | body |
| `--text-md` | 20px | lead paragraph, subheads |
| `--text-lg` | 25px | section headers |
| `--text-xl` | 31px | page-level headers |
| `--text-2xl` | 39px | hero subline |
| `--text-3xl` | 49px | hero headline (desktop) |

Display face: something with real character that carries the "terminal / builder" idea without being a literal coding font cliché (avoid the obvious monospace-everywhere look). Body face: a quiet, highly legible sans built for long reading, not the display face turned down in weight. Mono: for the small eyebrow labels and the tagline, this is where an actual monospace face earns its place, because it is doing a specific job (evoking the cursor/terminal idea in short bursts), not carrying paragraphs. Never Inter or Roboto as the display face, per the base skill's rule — it applies to TalinBuilds' own site as much as to any client's.

## Spacing system

8px base unit, doubling rhythm: `4, 8, 16, 24, 32, 48, 64, 96, 128, 192`. Apple-style restraint reads through generous, consistent spacing more than through any other single choice — when in doubt, go up one step on the scale rather than down. Cramped spacing is the fastest way to make a "premium" claim look false in the first 50 milliseconds.

## Motion system

Two curves cover almost everything:

- **Entrances and settles:** `cubic-bezier(0.16, 1, 0.3, 1)` — fast start, long, gentle deceleration into rest. No overshoot, no bounce. This is the "Apple" feeling: confident and quiet, never springy.
- **Hovers and micro-interactions:** `cubic-bezier(0.4, 0, 0.2, 1)`, short duration (150–200ms). Quick, not snappy-to-the-point-of-cheap.

Ban elastic/bounce easing and anything that overshoots its resting position. Bounce reads as playful-cheap, not premium-confident, and it directly contradicts the restraint this whole system is built on.

## Voice, for TalinBuilds' own copy specifically

Calm, direct, technically credible, never agency-boilerplate. Concretely, avoid the exact words already flagged as generic-agency tells during the site audit: "seamless," "leverage," "unlock," "empower," "solutions," "100% asset ownership" as a headline claim, and round marketing numbers with no backing ("200+ builds") unless they are true and you can name them if asked. Say what is actually true and specific instead: name the actual process (research, design package, generated hero, engineered scrub, real speed receipts), not the adjective for it. The base skill's own copy gate (Phase 9) already filters for this; hold TalinBuilds' own site to the identical bar, not a looser one, since it is the first proof of the product itself.

## The proof-of-work argument

TalinBuilds' single strongest sales asset is that its own site is built with the exact pipeline it sells: the scrub hero, the measured speed receipts, the design package discipline. Every prospective client can be shown this directly — "the site you are looking at right now, on my phone, in front of you" is a stronger halo-effect trigger than any portfolio screenshot. Keep this literally true at all times: TalinBuilds' own site is not exempt from the self-testing checklist, the brand-coherence read, or the honest-costs standard. If it does not pass its own gates, it cannot be the proof.
