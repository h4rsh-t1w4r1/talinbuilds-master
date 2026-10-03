---
name: talinbuilds-master
description: >
  TALINBUILDS' unified website engine. Fuses the 10k-websites cinematic scrub
  pipeline, the lets-scroll world-flight module, and the TALINBUILDS house and
  vertical modules into one phased build with a v5 master-prompt front end.
  Use when the user asks to build, redesign or deploy a website, landing page,
  scroll site, diorama world site, or the TALINBUILDS own site, in opencode,
  Antigravity, Claude Code, or any SKILL.md-compatible agent.
---

# TALINBUILDS Master

One pipeline, three engines, zero improvisation. The spine is the 10k-websites
phase flow. Mode W (world flight) is lets-scroll. The master prompt in
references/master-prompt.md is the front door: no design decision exists until
it is written there and approved.

## What governs what
- Build, gates, deploy, money talk: this file plus scrub-pipeline.md, prompt-laws.md, ffmpeg-recipes.md, deploy.md, troubleshooting.md.
- Mode W assets and seams: world-pipeline.md, world-prompts.md, world-engine.js.
- Client conversion furniture: design-psych.md.
- Clinics, hospitals, dental, physio, diagnostic labs: healthcare-vertical.md, read before proposing anything.
- TALINBUILDS-owned properties only (his site, decks, pitch material): house-style.md. Never applied to a client build.

## The unskippable first move
Read this file top to bottom and every file in references/ before replying to
the user. First message out is the Phase 0 checklist. If you catch yourself
asking about the brand before reporting that checklist, stop and read.

## Agent discipline (the rules that keep free models honest)
1. Tool truth before promises. Verify the generation tool responds before you
   promise an asset. A user saying "done" is a signal to verify, never the verification.
2. No fake assets, ever. Never substitute CSS gradients, canvas tricks or SVG
   placeholders for a generation and present it as the real thing. That exact
   failure is why this skill exists. If no generation tool is reachable, switch
   to the manual asset path (prompt files plus a spec table with a status
   column) and say so out loud.
3. Money before motion. Preflight every generation with get_cost. On router
   credits, read the billed cost off each call. State totals in plain words
   before anything spends.
4. One model per phase boundary. Fallback order: Claude Sonnet 4.5 (Antigravity),
   Gemini 3 Pro (Antigravity), GLM-5.3-Flash, MiniMax-M2.7, DeepSeek-V4-Flash
   (chunked only), GLM-4.7-Flash free. After any switch, re-verify tools and
   restate the plan in one line. Never switch mid asset-chain.
5. Chunking rule for flash-tier models. DeepSeek flash and GLM flash execute the
   master prompt section by section against the approved design package:
   shell plus hero, then sections, then motion pass, then copy gate pass.
   Never one 400-line shot.
6. Two-hang rule. A second consecutive hang on the same tool or provider means
   it is down. Name it, switch, never a third call.
7. Gates are gates. Image inspection, the VIDEO GATE per segment, Mode W seam
   QA, the copy grep gate, the self-test checklist, live verification with
   measured speed receipts. None skipped, none abbreviated.
8. OpenDesign boundary. OD produces mockups, DESIGN.md brand contracts, decks
   and promo video. It never replaces a phase, never deploys, never authors
   final client copy. The master prompt owns copy.

## Mode router (pick before any design work)
| Mode | Shape | Cost shape | Pick when |
|---|---|---|---|
| S | one 6s generated shot scrubbed by scroll, captions in negative space, settle at composed ending | 1 image + 1 video | Default. Every clinic. Every first build |
| C | chained 15 to 20s journey, segment N+1 starts on segment N's actual last frame | segments x video price | The concept genuinely needs rooms, floors, a path |
| W | world flight: N diorama stills + 2N-1 frame-locked clips, architecture A (walkthrough or locked-iso) or B (fly-through) | N stills + (2N-1) clips, x2 if mobile chain | The brand is a world worth flying: product chains, campuses, process stories. His own site teaser qualifies |
| OD | OpenDesign mockup only, no build | zero credits | Pre-sale direction picks, decks, brand extraction |

State the phone fact once at proposal time, as a design fact: phone visitors
see a composed still hero, the scrub plays on laptops and desktops.

## Phases
0. Setup scan. Check ffmpeg, node, the active model ID and its quota, Higgsfield
   or manual path, router keys, OD presence. Report as a checkmark checklist.
   Give the honest-costs talk. Hosting is not mentioned here; it belongs to Phase 9.
1. Intake. Numbered clickable choices, recommended first. Four branches: real
   thing with photos, invented brand, real business without photos (plus the
   AI-imagery disclosure question), software with screenshots. Ask for existing
   assets and sensory assets in the same breath.
2. Research. Mine real reviews and forum language for pains, outcomes,
   objections. Healthcare trigger reads healthcare-vertical.md now.
3. Master prompt. Run the eight decisions in references/master-prompt.md, fill
   the template, present it, get one approval. This is the anti-slop gate.
   Nothing visual happens before it.
4. Design package. Consume the approved master prompt: palette tokens, type
   trio, band map with verbatim copy, below-fold outline, vector layer plan,
   engineering list. Copy ships verbatim from here on.
5. Assets. Mode S and C: prompt-laws.md templates, image inspect, VIDEO GATE
   per segment, brand-coherence inspection both directions. Mode W:
   world-pipeline.md, seam law, boundary frames from rendered clips never from
   stills, manual path available with the spec-table contract.
6. Build. scrub-pipeline.md in full: blob fetch with loading ring, dt-normalized
   lerp, gated seeks, delta-gated writes, band pacing validated by the flick
   test, four-layer legibility, five live static-hero gates, complete without
   video. Whole-site-animated standard. Conversion furniture from design-psych.md
   wired where the package placed it. House style only if the property is TALINBUILDS.
7. QA. The unified checklist at the end of scrub-pipeline.md, plus Mode W seam
   QA when applicable, plus the copy grep gate (zero em dashes, zero stock
   words, plus the AI-tell sweep), plus the brand-coherence read end to end,
   plus the fresh-eyes pass. Report findings and fixes.
8. Preview and rounds. Localhost server for the scrub preview, double-click
   path explained honestly as the still-hero state. Feedback in plain words,
   applied in one pass per round.
9. Deploy. Clients: Hostinger flow in deploy.md, og patch before zip, zip the
   CONTENTS, verify live yourself, measure and present speed receipts, then
   the user's real-phone test. His own site: Netlify is acceptable, same
   verification and receipts discipline.
10. Polish loop and the standing line: you are now their on-call developer, one
    plain sentence per change.

## Business rails (never waived)
- Tiers: Basic 3 to 8K, Premium 3D or cinematic hero 15 to 20K plus, Growth
  retainer 500 to 1,500 per month pitched on no-show pain, not on "SEO".
- Collect 50 percent upfront, always, stated in the first price message.
- Speed receipts are sales assets: measured load numbers answer "pretty but
  slow" before it is asked. In anxiety-heavy categories like clinics, polish
  is the trust signal; say so in the pitch.
- Sequencing: clients before content. No YouTube video before a booked call.
- WhatsApp outreach in Hindi or Marathi carries one designed artifact (an OD
  deck page or a live link), never a wall of text.

## Reference map
| File | Governs | Origin |
|---|---|---|
| master-prompt.md | the eight decisions, the template, the gates | v5 prompts plus design package plus psych |
| house-style.md | TALINBUILDS-owned properties only | his brand board |
| design-psych.md | conversion furniture menu | premium-psych and UX-psych notes |
| prompt-laws.md | the twelve hero laws, chaining, cost preflight | 10k-websites |
| design-package.md | package template consumed by build | 10k-websites |
| scrub-pipeline.md | engineering floor, QA checklist | 10k-websites |
| ffmpeg-recipes.md | every encode, extract, concat | 10k-websites |
| deploy.md | Hostinger flow, receipts | 10k-websites |
| troubleshooting.md | symptom to cause to fix | 10k-websites |
| healthcare-vertical.md | clinic rules and claims limits | talinbuilds |
| talinbuilds-brand.md | legacy identity notes, repointed | talinbuilds |
| world-pipeline.md, world-prompts.md, world-engine.js, world-template.html, knockout.py | Mode W | lets-scroll |