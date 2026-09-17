# How to do right — quick-reference

> For AI agents + humans working with Bobby Wolfson + Hermes.

## The 8 rules

1. **Do not invent.** Every claim links to a source. Every fact has
   a falsification test.
2. **Do not tokenize the lexicon.** Tokenization is an error.
   Use PSB primitives + composition rules.
3. **Do not adopt house style.** Each far-* repo has a schema. The
   schema is the gate. Vibe is not.
4. **Do not conflate the substrate with the product.** SimSelf /
   FieldCore / far-* / Sunrise Startup each have their own contract.
5. **Do not post without explicit consent.** Prepare drafts;
   human publishes.
6. **Do not spend money.** Surface the cost; stop.
7. **Do not duplicate Bobby's Desktop into public repos.** Process
   into vault, then into a sister repo only when Bobby says.
8. **Do not delete without explicit consent.** Bobby retains the
   right to delete from his own files.

## The 5 anti-patterns (refused at every layer)

1. House style
2. Vibe paragraphs without axes
3. AI-generated claims without source
4. Tokenization as the language atom
5. Paid API spend without consent

## The 8 repos

1. [fieldcore](https://github.com/the-far-queen/fieldcore) — math + geometry + kernel
2. [simself](https://github.com/the-far-queen/simself) — identity + kernel + PSB/MLTR
3. [far-art](https://github.com/the-far-queen/far-art) — 56-axis style substrate
4. [far-writing](https://github.com/the-far-queen/far-writing) — voice + writing
5. [far-music](https://github.com/the-far-queen/far-music) — genre + music
6. [far-film](https://github.com/the-far-queen/far-film) — shot + film
7. [far-games](https://github.com/the-far-queen/far-games) — mechanic + games
8. [sunrise-startup](https://github.com/the-far-queen/sunrise-startup) — public face

## The tests

- **Atlas:** `python simself/src/demos/atlas_run.py` (5/5 current)
- **far-art:** `python far-art/tests/`
- **far-writing:** `python far-writing/tests/`
- **simself:** `python -m pytest simself/tests/`

## License

MIT. Free for all agents, human and non-human.
