# Contributing to easy

Thanks for looking. easy is small on purpose, and contributions are welcome — from a typo fix to a
new starter ruleset.

## The spirit of easy

Before contributing, it helps to know what easy tries to be:

- **Readable rules the user controls.** Behaviour lives in plain, human-readable files — no hidden
  layer. Keep it that way.
- **Check, don't just claim.** easy makes a model check its own answer against the rules and shows
  that check. Honesty about limits beats overpromising.
- **Local-first and yours.** Context lives in the user's files. No account, no cloud by default.
- **Bring your own model.** The model is a swappable engine; easy is the control layer in front.

If a change makes easy less readable, less honest, or less under the user's control, it's probably
not the right change — even if it's clever.

## Ways to help

- **Report a problem** — open an issue. Describe what you did, what you expected, what happened.
- **Suggest an improvement** — open an issue first for anything larger than a small fix, so we can
  agree on the direction before you spend time.
- **Share a ruleset** — a well-commented starter ruleset for a specific use (a role, a language, a
  workflow) is genuinely useful. Keep it generic; strip anything personal.
- **Improve the docs** — clarity fixes are always welcome.

## Pull requests

1. Keep them focused — one change per PR is easier to review.
2. Explain the *why*, not just the *what*.
3. For rules and docs: plain language, short, honest about limits.
4. Be kind in review. We're all here to make the thing better.

## Please don't

- Don't add hidden state, telemetry, or anything that phones home by default. Local-first is not
  negotiable.
- Don't commit secrets (API keys, tokens, passwords). This repo is public and permanent, and bots
  scan for keys. If you spot one, report it privately rather than in a public issue.
- Don't add a required cloud dependency for core behaviour. Bring-your-own-model stays optional and
  swappable.

## License

By contributing, you agree that your contributions are licensed under the project's
**GNU General Public License v3.0** (see [LICENSE](LICENSE)).

> Note: a formal Contributor License Agreement (CLA) may be added later if the project gains a
> separately licensed commercial edition. This is not required today; it's noted here for
> transparency.

## Code of conduct

Be respectful and constructive. Assume good faith. Harassment or discrimination isn't welcome here.
