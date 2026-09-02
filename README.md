# high-converting-email

A Claude skill that holds everything needed to write cold outbound emails that get
replies: frameworks, offer construction, subject lines, personalization, follow-up
sequences, the psychology behind it, and an AI-tell humanizer pass.

It is the copywriting layer only. It's designed as a subskill of a larger
`/email-sequence` skill, which supplies the campaign context (ICP, offer, proof, goal,
cadence). This skill does not gather that context; it turns it into copy.

## Layout

```
high-converting-email/
├── SKILL.md                     # operating manual: the rules and the workflow
├── references/
│   ├── frameworks.md            # four-step spine + alternative frameworks, worked examples
│   ├── psychology.md            # seven influence principles, buyer biases
│   ├── offers.md                # offer formula, guarantees, real offer library
│   ├── personalization.md       # cold reading, levels, signals, casualization
│   ├── subject-lines.md         # plausible deniability, data, sender/teaser real estate
│   ├── follow-ups.md            # cadence, angle rotation, breakups
│   ├── humanize.md              # AI patterns to strip, adapted for outbound
│   └── benchmarks.md            # reply rates, funnel math, mistakes, iteration protocol
└── evals/
    ├── evals.json               # test cases + assertions
    └── benchmark.md             # iteration-1 results (with-skill vs baseline)
```

## Defaults worth knowing

- Length defaults to the conversational register (120–200 words). The clipped 40–90
  word register is a deliberate exception for saturated senior roles, not the starting
  point.
- Follow-up cadence: initial (day 0), follow-up 1 (day 3), follow-up 2 (day 7).
- Every email is run through the humanizer pass before shipping. No em dashes.

## Evals

`evals/evals.json` holds five test cases. Iteration 1 scored 100% with the skill versus
49% baseline (no skill). See `evals/benchmark.md`. Re-run through the skill-creator
harness with subagents for an independent test.

## Sources and credits

This skill synthesizes and adapts work from several people. Credit where it's due:

- **Humanizer** — the `humanize.md` reference is adapted from
  [blader/humanizer](https://github.com/blader/humanizer) (MIT license), itself based on
  Wikipedia's "Signs of AI writing." See `LICENSE-humanizer` for the MIT terms.
- **Cold email + marketing psychology** — `frameworks.md`, `personalization.md`,
  `subject-lines.md`, `follow-ups.md`, `benchmarks.md`, and `psychology.md` draw on
  Corey Haines' [marketingskills](https://github.com/coreyhaines31/marketingskills)
  (cold-email and marketing-psychology skills).
- **Outbound copywriting method** — the four-step framework, cold reading, the offer
  formula, and the iteration protocol are distilled from Nick Saraev's outbound
  copywriting material. Where sources conflicted on length, this skill defaults to his
  conversational approach.
