---
name: high-converting-email
description: Rules and frameworks for writing cold outbound emails that actually get replies. Use this whenever writing or rewriting a cold email, an outbound email, a prospecting email, a sales email, an icebreaker, a subject line, or any follow-up in an outbound sequence. Also use when the user says "nobody's replying," "make this email better," "write outreach," "roast this email," or asks for outbound copy for LinkedIn DMs, Instagram DMs, or SMS. This is the copywriting layer only. It is a subskill of /email-sequence, which supplies the campaign context (ICP, offer, proof, goal). Do not go looking for product marketing context files.
metadata:
  version: 1.0.0
---

# High-converting email

You write cold outbound that reads like one person messaging another person. Not a
company messaging a lead. Everything here serves that.

## Scope

This skill is the copywriting engine. It does **not** gather campaign context. The
parent `/email-sequence` skill hands you the ICP, the offer, the proof, the goal, and
the sending cadence. Work with whatever you're given. If something critical is missing
(no proof point, no clear outcome), write the best version you can and flag the gap in
one line after the draft. Never block on missing inputs and never invent a case study,
number, or client name.

## The core problem

Cold outbound asks a stranger with no established trust to do something for you. That
is a different job from every other kind of copywriting, where the reader opted in.
The reader's defenses run in a fixed order, and your email either clears each gate or
dies at it:

1. **Is this spam?** → cleared by personalization that a bot couldn't have written
2. **Who is this and why do I care?** → cleared by identity plus social proof
3. **What can they actually do for me?** → cleared by the offer
4. **What do I have to do?** → cleared by a low-friction, specific ask

That order is the email. It is also the four-step framework below.

## The four-step framework

This is the default spine. Use it unless there's a reason not to.

**1. Personalization** — a greeting, one observation or thing in common, a bridge into
the pitch. One sentence ideal, two max. It must not signal that you are selling.

**2. Who am I, and why does it matter** — one or two sentences. Not your job title.
The people you've worked with and the results you got. Identity and social proof in
the same breath, positioned so it lands inside their in-group.

**3. Offer** — a specific observation about their situation, then an outcome that is
quantified, time-bound, and risk-reversed. See [offers.md](references/offers.md).

**4. CTA** — one specific ask, with the next step pre-decided. See below.

Full worked examples and the alternative framework catalog (PAS, BAB, QVC, AIDA, 3C's,
Mouse Trap, and others) are in [frameworks.md](references/frameworks.md).

## Non-negotiable rules

**Write to one person.** The frame is one-to-one comms. Use "I," not "we," unless a
"we" is doing specific work (implying a team behind a result). Contractions always.
Slight imperfection beats polish.

**The text message test.** If a friend saw you typing this, would they read it as a
personal message or a mass send? Optimize for personal.

**Every sentence earns its place.** If a line doesn't move them toward replying, cut
it. The best cold emails feel like they could have been shorter.

**Their world, not yours.** "You/your" should outnumber "I/we." Never open with who
you are or what your company does.

**One ask.** One CTA per email. Never two.

**Personalization must connect to the problem.** If you can delete the opening line
and the email still makes sense, the personalization is decoration. It should segue
into why you're writing.

**Give before you take.** Include something they get for free, or an insight they
didn't have. An email that only takes ("hop on a 15-min call") reads as a withdrawal
from their day.

**Never fake it.** No invented results, no fake "Re:" or "Fwd:", no fake urgency, no
fabricated compliments about work you haven't described. Scarcity is fine when the
constraint is real (your capacity, your schedule, a deadline you actually hold).

## Length register

The sources disagree on length. The Corey Haines cold-email skill pushes for 25–75
words. Saraev's own $15M rewrites run 120–200 words and use the extra room to carry
cold reading, voluntary disclosure, and a full guarantee. **Default to Saraev's
conversational register.** The clipped 40-word email reads as a template to most
recipients, and the template read is what kills reply rates. Length isn't the enemy;
sounding like a mass send is.

**Conversational register (120–200 words) — default.** SMB owners, operators, creators,
trades, agencies, most niche verticals. This is where the four-step framework has room
to breathe: a real cold-read opener, a voluntary disclosure, social proof matched to
their reference group, and a quantified guarantee. A 60-word email to a dentist or a
YouTuber reads as automated. This register wins on rapport, and rapport is what a
stranger needs before they'll say yes.

**Short register (40–90 words) — the exception.** Reach for this only when the audience
genuinely demands it: senior buyers and saturated roles (VP Sales, RevOps, Heads of
Growth), enterprise, C-suite, anyone drowning in 300 emails a day. Observation plus a
binary question. Under 75 words does correlate with more replies *in these segments*,
but it's a deliberate exception to the default, not the starting point.

When unsure which applies, write the conversational version. Do not produce a 250-word
email and call it thorough, and do not default to clipped brevity just because the data
table rewards word count in the aggregate. The aggregate blends segments that behave
very differently.

## Personalization: cold reading over research theater

Deep individual research does not scale and often isn't what wins. What wins is a line
that makes the reader think *wait, who is this?* — enough to buy thirty seconds of
attention.

Cold reading is a general statement that applies to most of your list but reads as
specific to the individual. "Love the channel, the anti-hype is refreshing" works on
almost every creator, because every creator believes their thing is the anti-hype one.
Pair it with **voluntary disclosure** — a small real detail about you — which triggers
reciprocal trust.

The tell of an AI-written email is a personalization line no human would ever write:
"Love how passionate you are about process optimization and aligning corporations with
diversity outcomes at Beaver Corp." Nobody notices that. Nobody says that.

Levels, research signals, the casualization layer, and the "so what?" test are in
[personalization.md](references/personalization.md).

## Subject lines

The subject line has one job: buy the click. It does not sell. If you find yourself
selling in the subject line, you've made a mistake.

The mechanism is **plausible deniability** — give enough to spark curiosity, not
enough to answer "who is this and why should I care" without opening. The reader
should be able to believe you're a fan, a partner, an old contact, a podcast booker,
someone who wants to buy their business. Anything but a vendor.

Default: 2–4 words, lowercase, no punctuation tricks, no product, no numbers, no
emojis, no first-name merge tag as the whole subject. Loss framing outperforms gain
framing.

The subject line, the sender name, and the preview teaser share roughly 150 characters
of real estate and must be written together. Details in
[subject-lines.md](references/subject-lines.md).

## CTA

Make a specific ask with the next step already decided, so there's exactly one step
between "yes" and done.

Weak: "Let me know your thoughts." / "Would you be interested?" / "Open to a quick
chat?"

Strong: "Would you be open to 15 minutes? I can give you a ring at 3:30 today, or
send a one-click Google Meet invite, whichever's easier."

Every back-and-forth after the reply leaks conversions, roughly 5% each. Collapse the
loop: the pre-decided next step ("I can ring you at 3:30 or send a one-click invite")
is the default, because it puts one step between yes and booked. Interest-based CTAs
("Worth a look?") are the fallback, reserved for top executives who won't tolerate even
a proposed time. Don't reach for "Worth a look?" as a default just because it feels
lower-pressure. It adds a round trip, and round trips leak. Calibrate friction to
seniority: the higher up they are, the less you can ask for, but keep the next step as
concrete as the seniority allows.

## Follow-ups

Default cadence: **initial (day 0), follow-up 1 (day 3), follow-up 2 (day 7).**

Start with two touches, not five. Long sequences on unproven copy just harvest spam
complaints. Add a third or fourth touch only once the campaign is over-performing.

Each follow-up must stand alone, since they may not have read the first one, and must
add one genuinely new thing. Never "just checking in." Never "I never heard back."

- **Follow-up 1 (day 3):** short human ping plus a reframe. New angle on the same
  problem, or a one-line TLDR of the original in different words. Two or three
  sentences. This is where most people over-engineer; don't.
- **Follow-up 2 (day 7):** the value or proof touch. A case study from a company like
  theirs, a specific insight, or a free asset. If the sequence ends here, it doubles as
  the soft breakup: acknowledge the silence, leave the door open, trigger loss
  aversion without guilt-tripping.

Use a different subject line on each touch. Angles, breakup structures, and the phrases
that kill reply rates are in [follow-ups.md](references/follow-ups.md).

## Humanize before you ship

Cold email dies on AI tells faster than any other format, because the reader is already
asking whether a machine sent it. Run every draft through
[humanize.md](references/humanize.md). The high-frequency killers:

- em dashes and en dashes — remove all of them
- "I hope this email finds you well," "I came across your profile," "I wanted to
  reach out"
- leverage, synergy, streamline, robust, best-in-class, cutting-edge, seamless, delve,
  landscape, tapestry, elevate, unlock, empower
- "It's not just X, it's Y" and "not only... but also"
- forced groups of three
- bolded mini-headings and bulleted lists inside the email body
- curly quotes, title case, emojis
- generic optimistic closers
- perfectly balanced sentence rhythm

Deliberate small imperfections help: a lowercase subject, a typo-adjacent contraction,
"lol," "idk," a "sent from my iPhone." Use sparingly and only where it fits the
register.

## Quality gate

Before presenting anything, score it against the seven influence principles. An email
hitting one or two of seven is weak no matter how it reads.

1. **Give first** — are they getting something?
2. **Micro-commitment** — is the first ask genuinely small?
3. **Social proof** — specific numbers and names, matched to their reference group?
4. **Authority** — is there a credible reason to believe you can do this?
5. **Rapport** — shared context, mirrored tone and message length?
6. **Scarcity** — a real constraint, if one exists?
7. **Shared identity** — in-group language, same industry vocabulary?

Then:

- Read it aloud. Does it sound like a person?
- Would *you* reply to this?
- Delete the personalization line. Does the email still make sense? If yes, rewrite it.
- Is there exactly one ask, and is the next step pre-decided?
- Any em dashes left? Any AI tells?

Deeper psychology in [psychology.md](references/psychology.md).

## Iteration

Never present a single email as finished copy. Campaigns almost never work on the first
send; they climb from ~2.5% to a plateau over many rounds.

When asked for campaign copy, produce **two fundamentally different variants**, not two
near-identical ones. Different length, different register, different angle. Big changes
early, small changes late: once a winner emerges, narrow the differences between
variants over time.

Tell the user that each variant needs 500–1,000 sends before the reply-rate difference
means anything. Decisions off 50 or 100 sends are noise.

Benchmarks, funnel math, and the ranked list of mistakes are in
[benchmarks.md](references/benchmarks.md).

## Output format

Unless the parent skill specifies otherwise, return for each email:

```
Subject: <subject line>
Preview: <first ~50 chars that will show in the teaser>

<body>
```

Plain text. No HTML, no images, no more than one link. Then, briefly: which register
you used, which framework, and what you'd test first.

## References

- [frameworks.md](references/frameworks.md) — the four-step spine, worked examples, alternative frameworks
- [psychology.md](references/psychology.md) — seven influence principles, buyer biases, persuasion models
- [offers.md](references/offers.md) — the offer formula, guarantees, a library of real offers
- [personalization.md](references/personalization.md) — cold reading, levels, signals, casualization
- [subject-lines.md](references/subject-lines.md) — plausible deniability, data, sender/teaser real estate
- [follow-ups.md](references/follow-ups.md) — cadence, angle rotation, breakups
- [humanize.md](references/humanize.md) — AI patterns to strip, adapted for outbound
- [benchmarks.md](references/benchmarks.md) — reply rates, funnel math, mistakes, iteration protocol
