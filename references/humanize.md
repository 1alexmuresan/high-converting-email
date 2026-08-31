# Humanize

Adapted from the humanizer skill, which is built on Wikipedia's "Signs of AI writing."
Scoped here to cold outbound, where the stakes are higher: the reader is *already*
asking whether a machine wrote this, and one tell ends the email.

Run every draft through this before shipping. Do not change what the email claims. Do
not invent facts, names, numbers, or results to make it sound more human.

These rules govern **email output**, not the reference docs in this skill. The
documentation uses dashes and formatting freely; the emails you write must not.

---

## Absolute rules

**No em dashes or en dashes.** Search for `—` and `–` and remove every one. Replace
with a period, comma, colon, parentheses, or rewrite the sentence. Also check for
spaced hyphens ( - ) and double hyphens ( -- ) used as dashes. This is the single most
recognizable AI tell in 2025-era writing and it is unambiguous.

**No curly quotes.** Use straight quotes. Mail clients and copy-paste chains mangle
curly quotes anyway.

**No emojis.**

**No bold text in the body.** No bolded mini-headings, no bulleted lists with bold
labels. A cold email is a message from a person, and people don't format their messages
like documentation.

**No title case.** Not in subject lines, not anywhere.

---

## Words and phrases to strip

**Cold email specific openers:**
I hope this email finds you well · I hope you're doing well · I came across your
profile · I wanted to reach out · I stumbled upon · My name is X and I work at Y ·
I'll keep this brief · I'll be brief · Quick question (as an opener) · Hope you don't
mind me reaching out

**Corporate jargon:**
leverage · synergy · synergistic · streamline · robust · best-in-class · cutting-edge ·
seamless · scalable solution · end-to-end · turnkey · value-add · circle back · touch
base · align · bandwidth · low-hanging fruit · move the needle · game-changer ·
solution provider · leading provider · industry-leading

**High-frequency AI words:**
delve · landscape (abstract) · tapestry · testament · underscore · pivotal · crucial ·
intricate · showcase · foster · garner · elevate · unlock · empower · navigate
(abstract) · realm · myriad · plethora · vibrant · profound · comprehensive ·
meticulous · commitment to · enhance · facilitate · utilize (use "use") · additionally ·
furthermore · moreover

**Sales language:**
boasts · exemplifies · renowned · groundbreaking · revolutionary · transformative ·
must-have · unparalleled · state-of-the-art

---

## Structural patterns to remove

**"Not X, but Y" and "not only... but also."** AI overuses both.

> It's not just about booking meetings, it's about building pipeline.

Rewrite as the direct claim.

**Clipped negative endings.** "The system handles it, no guessing." Write a clause
instead.

**Forced groups of three.** "Faster, cheaper, and more reliable." Real people list two
things, or four, or one.

**Shallow -ing phrases.** "...helping teams scale efficiently while reducing overhead."
The -ing clause almost always adds nothing. Cut it or make it its own sentence.

**Repeated sentence openings.** Three sentences starting with "I" in a row. Merge, vary
the subject, or lead with the action.

**Synonym cycling.** Calling the same thing "your platform," then "your solution," then
"your product." Pick one name and reuse it. That's how people actually write.

**False "from X to Y" ranges.** "From lead gen to close." Only use it when X and Y are
genuinely the endpoints of a range.

**Passive voice hiding the actor.** "Results are delivered within 60 days." Say who
does it: "I'll deliver it within 60 days."

**Announcing the next point.** "Here's what I mean." / "Let me explain." / "Here's the
thing." Just say the thing.

**Fake-candid openers.** "Honestly?" / "Look," / "Real talk," / "Let's be honest," as
standalone theatrical pauses. Mid-sentence "honestly" is fine and normal.

**Answering objections nobody raised.** "I'm not trying to sell you anything" is a
partial exception in cold email, where explicitly disclaiming the pitch can build
trust. But "To be clear, this isn't about X" when X hasn't come up is the failure mode.

**Rejecting fake alternatives.** "You could hire an agency, but..." when nobody
suggested hiring an agency.

**Formulaic sayings.** "X is the Y of Z." "Trust is the currency of B2B." Replace with
the specific claim.

**Pretending to reveal a deeper truth.** "The real question is..." / "At its core..." /
"What really matters is..." Just make the point.

**Generic positive endings.** "Looking forward to the possibility of working together!"
/ "Excited about what we could build!" End on the ask or the last concrete fact.

**Chatbot residue.** "I hope this helps" · "Let me know if you'd like" · "Feel free to"
· "Would you like me to" · "Certainly!" · "Of course!"

**Excessive hedging.** "It could potentially possibly help with..." Hedging destroys
the authority principle. State it.

**Perfectly even rhythm.** AI writes mid-length sentences at a consistent cadence. Real
writing alternates: a long one, then three words. Read it aloud and listen for the
metronome.

---

## What to add: deliberate imperfection

The inverse problem is over-polishing. A flawless email reads as generated. Small
imperfections signal that a person typed it on a phone between meetings.

Use sparingly, and only in the conversational register:

- lowercase subject lines and occasional lowercase sentence starts
- contractions everywhere, including the awkward ones ("I'd've" is too far; "that's,"
  "you're," "idk," "imo," "tbh" are fine)
- "lol," "haha," "man," "dude" where the audience supports it
- a sentence fragment
- a parenthetical aside or a self-correction
- "sent from my iPhone" in the signature
- a missing Oxford comma, a slightly informal dash-free run-on

Do not fake typos in the prospect's name or company. That reads as careless, not human.

Match the register to the audience. Lowercase and "lol" to a startup founder or a
creator. Not to a hospital procurement director.

---

## What not to over-correct

Don't flag these as AI just because a pattern-matcher would:

- Correct grammar. Polish isn't proof of a machine.
- A single "however" or "additionally." The tell is stacking, not the word.
- One short sentence for emphasis. A *row* of dramatic fragments is the tell.
- Deliberate repeated openings used for rhythm.
- Formal vocabulary that's genuinely correct for the audience.
- Industry jargon that insiders actually use. "CTR," "ACV," "NPE," "TAM" build
  in-group identity. The banned list above is corporate *filler*, not technical
  vocabulary.

---

## The pass

1. Read the draft and mark every pattern above.
2. Rewrite. Don't patch individual flagged words; restate the point naturally.
3. Ask two questions:
   - What still sounds generated?
   - Did the rewrite add or remove any claim, number, name, or fact? If it added one,
     that's an error.
4. Search for `—` and `–`. Remove all of them.
5. Read it aloud. If it sounds like marketing copy, rewrite it. If it sounds like a
   text message from a competent person, ship it.

---

## The final test

Would a friend, watching you type this, think it was a personal message or a mass send?

Optimize for personal.
