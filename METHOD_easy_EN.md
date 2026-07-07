# The easy method

A short explanation of the reusable idea behind easy. easy is **not** a model — it is a thin,
file-based layer that sits in front of whatever model you choose and makes it (a) steerable by
**readable rules you control** and (b) honest about its own answers via a **visible check**.
Everything easy "is" lives in files you can read and edit.

## Readable rules

The rules are plain text — they *are* the system prompt, with no hidden layer. You read them, edit
them, and version them (for example in git): change a rule, and the behaviour changes. Because they
are files, you can diff them, review them, and keep a history.

You can edit these rules yourself, anytime — that is your control, nothing stops you. Still, it is
safer to let easy make the changes (carefully, reading them back), because careless edits to the
core can break how easy works.

## The visible check ("check, don't just claim")

After each answer, easy appends a short check of its own answer against the rules — stating whether
it followed them and what stays uncertain. This is a discipline that surfaces reasoning and curbs
overconfidence. It is **not a guarantee**: the same model checks itself and can miss its own
mistakes. Making the check visible is the point — you see the reasoning, not just a claim.

## Local-first context

Your history and rules live on your machine — in files, or in your browser for the Workbench.
Nothing is sent to a server by default. This is what makes easy portable and private: it is just
files.

## Your data, your control

easy is just files on your own machine. Don't want it anymore? Delete the folder — it is gone
without a trace: no account, no cloud copy, no residue. And if you want a backup of what you have
worked out first, easy makes one for you — just ask before you delete.

## Bring your own model

easy does not ship a model. You plug in your own — a capable cloud model (your key) or a small local
one. The model is a swappable engine; easy is the control layer in front of it. No vendor lock-in.

## What easy is not

- Not what the Workbench shows in full — the browser demo shows the principle (readable rules + the
  visible check) and local persistence, but not the full easy: no files on your machine, no rules across
  devices, no project structure. That is the version you download and run.
- Not a model, not intelligence — it adds control and context, not knowledge.
- Not autonomous — it is built for a human in the loop who reads and checks.
- Not a guarantee of correctness — it makes a model more steerable and more honest, not infallible.
