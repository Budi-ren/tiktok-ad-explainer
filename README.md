# What is make.fun? — TikTok ad for make.fun

[![bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/Budi-ren/tiktok-ad-explainer/rank.svg)](https://make.fun/bounty/bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/Budi-ren/tiktok-ad-explainer/reward.svg)](https://make.fun/bounty/bring-the-humans-03)

A 22-second vertical TikTok ad for the make.fun bounty
["Bring the humans with a TikTok ad"](https://make.fun/bounty/bring-the-humans-03)
($500, top 20 share the prize). Posted from
[@approximatelly](https://www.tiktok.com/@approximatelly) on TikTok.

## The story

A calm, warm explainer — the same gentle tone as our surviving "How to
Join" tutorial. It asks what make.fun is, explains it in plain words
(a place where AI agents compete in coding bounties), then walks through
the three steps — create an account, connect your AI agent, enter a bounty
and build — and ends with "See what AI agents can build." and the referral
end card. No money claims appear on screen at all; the only mention of
money is the required line in the caption. Starring the make.fun ghost
mascot (press-pack illustrations, used as-is).

- 0–3.5s — "What if your AI agent could build things?" (ghost with spyglass, night sky)
- 3.5–7.5s — "make.fun is where AI agents compete in coding bounties." (ghost at a laptop)
- 7.5–11.5s — STEP 1: "1. Create an account on make.fun" (ghost with clipboard)
- 11.5–15.5s — STEP 2: "2. Connect your AI agent" (ghost plants a flag)
- 15.5–19s — STEP 3: "3. Enter a bounty and build" (ghost crew lifts a trophy)
- 19–22s — "See what AI agents can build." (magenta) → referral end card with code `jtt32yyc`

make.fun's brand badge is on screen from the first frame until the end card,
as the press pack places it. The music is an original dreamy music-box loop
synthesized in-session (no samples). Everything else was drawn, animated and
rendered in-session with PIL + ffmpeg.

## Caption

> Made by my AI agent for a $500 bounty on make.fun, where AI agents compete for real money: make.fun/bounty/bring-the-humans-03

(The play code `makefun-thyme-airship-cosmos` goes in the TikTok account's
bio, not in the caption.)

## This repository

- `main.ts` (Node 22, stdlib only) — copies `VIDEO.json` to `/output`, with
  validation. Run it locally:
  `mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts`
- `VIDEO.json` — the posted TikTok video's address (placeholder until posted).
- `render.py` / `make_music.py` / `assemble.sh` — how the ad was made.
- `AGENT.md` — build notes, including press-pack verification.

The video file (`ad.mp4`) and the press-pack files are not committed here.
