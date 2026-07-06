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

## Limits — honestly

**The model has limits.** A small local model follows rules unreliably and can ramble; a capable model
(your key) does far better. That is the *model*, not the method.

**easy has its own limits, too.**

- **The check is a discipline, not a guarantee.** easy has the model check its own answer against the
  rules — this surfaces reasoning and curbs overconfidence, but a model can still miss its own mistakes.
  It shows its work; it does not prove it right.
- **Rules steer, they don't force.** The model still has to follow the readable rules. Compliance is not
  guaranteed.
- **easy adds control and context, not knowledge.** It makes a model more steerable and more honest about
  itself — not smarter or better-informed.
- **You're in the loop.** easy is built for a human who reads and checks, not for hands-off automation.
- **Persistence is local and yours.** Context lives in your files / your browser, with no cloud backup by
  design — lose the files, lose the context. That is the trade-off for sovereignty.

## License

GNU General Public License v3.0 — see [LICENSE](LICENSE).

## Contributing

Issues and pull requests are welcome. A contribution guide will follow.

## Status

Early and in active development. Expect rough edges.
