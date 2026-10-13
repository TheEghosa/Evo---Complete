---
name: social-x-longform
description: "Writes long-form X (Twitter) posts and X Articles in a direct, contrarian, evidence-backed founder voice, split into numbered posts when the account lacks Premium, with optional ASCII diagrams and code-block visuals. Default profile is Fredrick as founder; also TheSpark (@thesparkdigital) and client brands. Use when the user says X article, long tweet, long-form X post, long post for X, thought leadership on X, or contrarian take for X. Not for DataExplained (@dataexplain) posts, comments, reels, pins or newsletters (The Data Brief, The Data Drop), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; use this for everything else, including TheSpark, client brands, Fredrick on X, and formats those skills do not cover."
---

# X long-form writer

This skill writes long posts and Articles for X that read as though someone who has done the work wrote them, rather than a content team or a model. Its default voice is Fredrick's founder profile, which suits the format, since a flat claim and a specific story carry a long post further than polish does. It also writes for TheSpark's company account and for client brands.

## When another skill owns this

DataExplained posts on X belong to the DataExplained skills, so hand those over rather than write them here, because that brand runs X as its own editorial pipeline with its own verification rules and sign-off, and this skill carries none of them. If the request is really an evidence-graded LinkedIn post, it belongs to linkedin-artifact-engine, and anything described as content engine or full pack goes to the skill built for that. Everything else on X comes here.

## Whose voice

Begin by reading the profiles in the social-context skill and working out which one the request needs; when the request does not make it clear, ask one short question, because a founder post and a company post differ in pronoun, audience and claim rules, and that difference cannot be edited in afterwards. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.

For Fredrick, use the founder profile in social-context as the voice reference: his operator certainty, his signature moves (the flat verdict opener, the one-line hammer after a long setup, the question answered at once, the closing inversion), his bans, and his rules about never naming clients and never shipping a result he did not supply. That profile is the only voice reference for him, so do not invent traits a generic founder template would supply. Social-context also notes that LinkedIn is the only platform confirmed for his personal brand, which means you should confirm he runs an X account before planning a series around it. For TheSpark, write as "we" from @thesparkdigital, and follow social-context's instruction to ask about the company's audience and voice on first use. For a client, collect the client profile that social-context describes before you write.

## Length and format on X

A standard X account can post 280 characters at a time, and longer posts need X Premium, so ask whether the posting account has Premium before writing a single long post. Without it, deliver the piece as numbered posts that each fit inside 280 characters and each carry something worth reading alone. The same applies when a long draft would read better as a thread, which this skill's rule of thumb puts at anything past roughly 1,500 characters. Social-thread-writer holds the fuller craft for threads, so lean on it when the piece is a thread from the start.

Keep paragraphs to between one and three sentences, with a line break between thoughts, because dense blocks are hard to read on a phone screen. Articles and long posts allow more formatting than a standard post, though the exact options change, so check bold, headings and code blocks in the composer preview before relying on them.

## Voice rules

Common X advice says to write simple declarative sentences and short paragraphs, which conflicts with Fredrick's house style, so the rule here is different. Readability on X comes from short paragraphs and generous line breaks; it does not come from chopping every sentence into a fragment. Inside each paragraph, let a longer sentence carry the reasoning with because, so or which means, and then let a short sentence land the point, since a hammer only works when it follows something longer. Fredrick's profile bans staccato one-sentence-per-line posts outright, and a feed full of them is exactly what makes long-form X read as generated.

Open with a hook that stops the scroll, and choose from three kinds: a contrarian claim, a surprising number the user supplied, or an uncomfortable truth. Angles should be contrarian where the evidence supports it and backed by specific numbers and real examples, since a contrarian claim with nothing behind it is just noise. Corporate phrasing has no place here, so "I'm excited to share" and its relatives are out, and emojis stay out of the body.

The house denylist covers most machine tells, though a few more are worth catching because they cluster in long-form posts. Significance inflation ("a pivotal moment", "stands as a testament") should become a plain statement of the fact. Vague attribution such as "experts believe" or "industry reports suggest" needs a named source or deletion. Copula dodges like "serves as" become "is", stacked hedges like "could potentially" become one honest qualifier, and generic upbeat endings ("exciting times ahead") give way to the actual implication.

> Before: SEO is changing. AI is everywhere. Most agencies are behind. We adapted early. Results followed.

> After: Most agencies are still selling rankings for searches that now get answered before anyone clicks. We started checking which of our pages AI answers actually cite, and only [number] of our top [number] ranking pages showed up. That gap is where the next year of work sits.

## Structure

Most long-form posts follow the same six-part shape, set out below in order, because each part answers the question the reader has at that point.

1. **Hook**, one or two lines: the contrarian claim, real number or uncomfortable truth that earns the next line.
2. **Setup**, two or three lines: why you are worth listening to on this, established fast, since credibility is what the reader checks second.
3. **Sections**, each running problem, then what actually happened, then the fix or lesson, which keeps the post grounded in events rather than opinions.
4. **Visual**, optional: an ASCII diagram or code-block visual where a system or comparison is easier to see than to read (see below).
5. **Uncomfortable truth**: the insight most people avoid, which is usually the reason the post exists.
6. **Payoff**: was it worth it, and why, so the reader leaves with a resolution instead of a shrug.

The payoff is where long posts most often collapse into summary, so check that it adds something the hook did not already say.

## Optional visuals: ASCII diagrams and code blocks

A diagram in a code block breaks up a wall of text and can make a system visible in a way prose cannot, so it is worth adding when the post explains a process, a before and after, a decision path, a hierarchy or a simple comparison of values. It is optional, because an opinion post or a story usually reads better without one, and a diagram added only to tick a box makes the post feel templated. Rendering also varies, so preview the post and drop the diagram if it does not hold its shape in monospace.

When you do use one, keep it under 40 characters wide so it survives a phone screen, simple enough to parse in about three seconds, and clearly labelled, with no ambiguous boxes. Box-drawing characters work well for flows:

```
┌─────────┐    ┌─────────┐
│  Input  │───►│ Process │
└─────────┘    └────┬────┘
                    ▼
               ┌─────────┐
               │ Output  │
               └─────────┘
```

Block characters suit a quick comparison, with the values filled in from the user's real data:

```
Result by category:
Category A  ████████████ [n]%
Category B  ████████░░░░ [n]%
Category C  ░░░░░░░░░░░░ [n]%
```

## Content sources

Real material is what makes this format work, so pull from the user's own metrics, specific incidents and debugging stories, and decisions they actually made and why. Never fabricate a metric. When the post needs a number that has not been provided, leave a placeholder such as [number] and ask for it, since an invented figure can be challenged in the replies, and being caught costs more credibility than the post earns. For Fredrick, the social-context rules also apply here: no client names, no client domains, and no results he did not supply.

## Inputs

Ask only for what is missing: the topic, the angle (the contrarian or unusual framing), any source material such as real examples, data or incidents, and whether the account has Premium. A topic with an angle is enough to draft from, because you can mark gaps with placeholders rather than holding the draft back.

## Example skeleton

This skeleton shows the shape in Fredrick's voice, with the specifics left for him to supply:

```
Copy-paste location pages are lazy SEO.

In [number] of the last [number] audits I ran, the site had one service page cloned for every city, with "Lagos" swapped for "Abuja" and "Port Harcourt" and nothing else changed. The owner thinks they have [number] pages. To a search engine, that looks like one page and a stack of near duplicates.

The reality? A location page earns its place only when it says something true about that location that the other pages cannot.

[optional diagram: one template feeding many identical pages]

The uncomfortable part is that the fix is slower than the shortcut, because someone has to know each market well enough to write about it.

Worth it? Yes, because [result Fredrick supplies].
```

## Output and final voice check

Deliver the complete post ready to paste into X, with no preamble before it; afterwards, add one line listing any placeholders the user still needs to fill. When working inside an EvoNexus workspace, also save the post under `workspace/social/`.

Before handing it over, load the `house-prose-style` skill and run its pre-delivery voice check on the whole post, then fix whatever fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, so a post that has not passed it is not finished. On X, add two quick checks of your own: count characters per post when the account has no Premium, and confirm that every number in the draft is one the user supplied.
