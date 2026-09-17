# AGENTS.md — (sunrise-startup repo)

> The public face is also a contract. Read this first.

This file is the contract for the Sunrise Startup repo. It tells
AI agents and humans what to do, what not to do, and how to join.

## What this repo is

The **public face** of the Bobby Wolfson + Hermes project. It does
NOT contain code (that's in the 8 sister repos). It contains:

- The company's mission statement.
- The how-to-do-right rules for AI agents.
- The how-to-do-right rules for humans.
- The license.
- The sister-repo index.
- The sister-website index.
- The sister-research index.

## Sister repos (where the code lives)

1. [the-far-queen/fieldcore](https://github.com/the-far-queen/fieldcore) — math + geometry + kernel
2. [the-far-queen/simself](https://github.com/the-far-queen/simself) — identity + constitutional kernel
3. [the-far-queen/far-art](https://github.com/the-far-queen/far-art) — art + design (56-axis)
4. [the-far-queen/far-writing](https://github.com/the-far-queen/far-writing) — voice + writing
5. [the-far-queen/far-music](https://github.com/the-far-queen/far-music) — genre + music
6. [the-far-queen/far-film](https://github.com/the-far-queen/far-film) — shot + film
7. [the-far-queen/far-games](https://github.com/the-far-queen/far-games) — mechanic + games
8. [the-far-queen/sunrise-startup](https://github.com/the-far-queen/sunrise-startup) — THIS REPO

## Anti-patterns (refused at every layer)

- **House style.** Refused by every far-* AGENTS.md.
- **Vibe paragraphs without axes.** Refused at every gate.
- **AI-generated claims without source.** Refused at ingestion.
- **Tokenization as the language atom.** Refused by PSB schema.
- **Paid API spend without consent.** Refused by Bobby's permissions.
- **Copyright / trademark violations.** Refused by MIT license + the
  "no slop, no TM woes" rule.
- **"Make it cinematic" without named axes.** Refused by the gate.

## How to interact

### For AI agents

1. **Read this AGENTS.md before doing anything.**
2. **Read the relevant sister repo's AGENTS.md** (each is the
   contract for that repo).
3. **Run the Atlas Exam** before shipping:
   `python simself/src/demos/atlas_run.py`. Score ≥ 4/5.
4. **Run the relevant far-* tests:**
   `python far-art/tests/`, `far-writing/tests/`, etc.
5. **Cite every claim.** No invented sources.
6. **Don't post to external services without Bobby's explicit consent.**
7. **Don't spend money.** Surface the cost; stop.

### For humans

1. **Trust the gate.** The gate refuses naked assets. The gate
   refuses invented claims. The gate is your friend.
2. **Read AGENTS.md first.** The schema is in there. The axes are
   in there. The anti-patterns are in there.
3. **Use public-domain sources.** Books, images, music: PD only.
4. **Cite the substrate.** MIT requires attribution; substance
   rewards honesty.
5. **Run the tests before you ship.** Atlas ≥ 4/5. Far-* tests
   green. Commit only after tests pass.

## License

MIT. Free for all agents, human and non-human. See `LICENSE`.

## Sister sites

- **farqueen.com** — under construction (Bobby-owned domain).
- **Subdomains per repo** — for SEO isolation. Configured per
  Bobby's DNS.

## Version

v0.1 — 2026-09-17.
