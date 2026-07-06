# easy-framework

> easy — a file-based control layer for AI: readable rules, a visible checking step, bring your own model.

## What it is

**easy** is a small, file-based way to steer an AI model with **readable rules you control** — with a
**visible checking step** ("check, don't just claim") and **context that persists across sessions**.

The model is a swappable engine: **bring your own**. Nothing is locked to a vendor, nothing is a black box.

## Why it exists

easy grew out of a real, long-running project — building a tube amplifier with a planned microprocessor,
so electrical engineering *and* programming — which needed an AI that could hold context across *many*
sessions, not just a single chat. That need — context that stays — became the heart of easy.

## How it works

- **Rules live in plain, human-readable files.** You read them, edit them, version them. They are the
  system prompt — no hidden layer.
- **A visible check.** After each answer, easy appends a short check of its own answer against the rules.
  If the model fails to provide it, easy says so openly instead of hiding it.
- **Local-first context.** Your history and rules stay on your machine (files / your browser), not on
  someone else's server.
- **Your model.** Strong cloud model or a small local one — your choice, and you can see where your data
  goes on each path.

## Try it

- **Interactive (browser):** the Workbench runs easy with **your own API key** — a capable model, so you
  see easy's real behaviour (rules take effect, the check appears). A small in-browser model is offered
  as a fully-private option, but it is weak and only shows the *principle*, not easy's performance.
- **Run it yourself:** download and run easy locally. Open to everyone.

## Honest limits

- A small local model follows rules unreliably and can ramble — that is the *model*, not the method. For
  real quality, use a capable model (your key).
- easy is a **method plus tooling, not a model.** It makes whatever model you plug in more steerable and
  more honest about itself.

## License

GNU General Public License v3.0 — see [LICENSE](LICENSE).

## Contributing

Issues and pull requests are welcome. [Contribution guide + any CLA note — to be added.]

## Status

Early and in active development. Expect rough edges.
