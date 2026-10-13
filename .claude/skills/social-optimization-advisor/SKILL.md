---
name: social-optimization-advisor
description: "Turns social media performance, growth and pattern findings into a prioritised, evidence-backed action plan of quick wins, strategic shifts, experiments and things to stop, built from earlier analyses in the conversation or from pasted data, each item with its evidence, sample size, label (well supported, thin or a hypothesis to test), expected direction, a measure, and the skill that writes the content. Use when the user says what should I do next, how do I improve, optimise my social media, recommendations, next steps, biggest opportunity, or help me grow. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. Not for client analytics reports from GSC, GA4 or Meta (spark-analytics), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; for DataExplained-specific posts defer to the DataExplained skills, and use this for everything else."
---

# Social optimization advisor

This skill does not stop at diagnosis. It takes what is known about an account's posts, growth and content patterns and turns it into a short, ranked plan, in which every item names an action someone can take this week, the evidence for it from the account's own data, and a way to tell whether it worked. Nothing is pulled from a live platform here, so the plan rests only on analyses already run in the conversation or on data the user supplies, and a recommendation without evidence behind it is left out rather than padded in.

## When another skill owns this

Client analytics reports built from Google Search Console, Google Analytics 4 or Meta data belong to spark-analytics, which reads those sources live, so hand those over. DataExplained-specific posts go to the DataExplained skills, Fredrick's evidence-graded LinkedIn posts and audit-finding posts go to linkedin-artifact-engine, and anything called a content engine or a full pack has its own skill. Those skills carry verification, sign-off and evidence-grading rules that this one does not, which is why they take priority.

The analysis itself belongs to the sibling skills: social-performance-analyzer for individual posts, social-audience-growth-tracker for followers, and social-content-pattern-analyzer for patterns across many posts. This skill sits on top of them, and broader questions about pillars or which platforms to be on belong to social-content-strategy and social-platform-strategy.

## Start with the profile

Read the social-context skill first and work out which profile the account belongs to (Fredrick as founder, DataExplained, TheSpark Digital Tech, or a client), asking one short question if the request leaves it open. Every recommendation is filtered through that profile, since advice that is right for a founder building authority on LinkedIn can be wrong for an agency account that exists to generate enquiries. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.

## Gather the evidence

There are two routes in, depending on what already exists.

When one or more of the sibling analyses has already run in this conversation, build on their findings instead of asking for the data again. Look for convergence across them, because agreement between independent analyses is the strongest signal available. If the performance analysis shows Tuesday educational threads winning and the pattern analysis independently shows the list format winning, a Tuesday educational list thread deserves a high place in the plan, and its label can rise accordingly.

When nothing has run yet, there are two options. If the user has a full export, offer to run the matching analysis first, since a plan built on a proper analysis is worth more than one built on impressions. Otherwise ask for a quick picture, using a prompt along these lines.

> To give you useful recommendations I need a quick picture of what is working. Could you share your two or three best posts and your two or three worst, with their numbers if you have them (impressions or views, likes, comments, shares, saves), how often you post on each platform, your follower count at the start and end of the last month if growth matters, and the one goal that matters most right now, whether that is growth, engagement, enquiries or something else?

Work with whatever comes back, and remember that figures quoted from memory or rounded ("about 2,000 views") can support a thin label at best.

Recommendations from a platform's own insights or a scheduling tool can come in too. Treat them as one input among several: when one agrees with your own finding, say so, since the agreement raises confidence, and when one contradicts it, show both views and explain the difference rather than quietly picking one.

## Label every recommendation

Each recommendation carries its evidence label and the sample size behind it, so the reader knows which items to act on and which to test.

| Label | When it applies |
|---|---|
| Well supported | The finding rests on at least five posts or periods on each side of the comparison, or two independent analyses agree |
| Thin | The direction is visible but the sample is small, one post carries the difference, or the figures are rough |
| Hypothesis to test | One or two posts, or reasoning the data cannot yet confirm, which makes it an experiment rather than a change |

With fewer than 15 posts behind the whole plan, say so at the top, as in "this plan rests on eight posts, so treat the strategic shifts as experiments until more data is in." Never compare the account with an industry average or benchmark, because no verified figure is available here, and the account's own history is the only fair baseline. Where Fredrick supplies a baseline or target of his own, use it and name its source. A calibrated "this looks promising, test it" helps more than a false certainty.

## The four tiers

Every recommendation goes into one of four tiers, ordered by effort, with quick wins first because early results build the case for the bigger changes.

| Tier | What belongs there |
|---|---|
| Quick wins | Changes that take under an hour and apply what the data already shows, such as a hook pattern, a posting slot or a call to action |
| Strategic shifts | Changes to content mix, platform focus or cadence that take two to four weeks to implement and measure |
| Experiments | Promising but unproven ideas, each with a hypothesis, a test, and criteria for success and failure |
| Things to stop | Habits or content types the data shows are draining time or pulling results down, each with a replacement |

Each tier asks for something different. A quick win must cite a specific data point rather than a general principle, as in "start every educational post with a specific number, since your top three posts all open with one (thin, n = 3)." A strategic shift has to name its trade-off as well as its upside, because moving from daily posting to four times a week, for example, gives up volume in exchange for time spent on fewer, stronger posts. An experiment is written as "if I do this, then this metric should move, because this finding suggests it," with a test (how many posts over what period) and success and failure thresholds set against the account's own baseline. Any stop item names what to do instead, since a plan that only removes things leaves a gap in the calendar.

The example experiment card below shows the shape, using invented figures.

```
Experiment: Tuesday carousel test
Hypothesis: if I post LinkedIn carousels on Tuesdays, saves per post will rise,
  because my one Tuesday carousel drew four times my average saves (hypothesis to test, n = 1)
Test: three carousels on Tuesdays over the next three weeks
Success: average saves at least double my text-post baseline
Failure: under one and a half times after three tries, so drop it
```

## How each recommendation is written

Each item has five parts, and none may be skipped, since a recommendation without a measure cannot be judged and one without a skill cannot be acted on quickly.

1. What to do, as one specific action rather than a category.
2. Why, meaning the evidence from the account's own data, with the sample size and the label.
3. Expected impact, given as the metric that should move and in which direction. Leave out any predicted percentage, since no data in hand supports forecasting the size of a change.
4. How to measure it, naming the metric and the window, such as engagement rate on the next five educational posts against the previous five.
5. The skill that writes the content, chosen from social-hook-writer, social-post-writer, social-thread-writer, social-carousel-writer, social-x-longform and social-content-repurposer, with social-content-calendar for scheduling the change.

The plan holds ten items at most, and seven strong recommendations serve the reader better than ten diluted ones, so stop when the evidence runs out.

## The plan

The plan uses the structure below.

```
## Optimisation plan for [date]

Profile: [which social-context profile]
Based on: [which analyses or data, and the number of posts]
Primary opportunity: [one sentence naming the biggest change]

### Quick wins (this week)
1. [Action]
   Why: [evidence, n, label]
   Expected impact: [metric and direction]
   Measure: [metric and window]
   Write it with: [skill]

### Strategic shifts (this month)
[same format, plus the trade-off]

### Experiments to run
[hypothesis, test, success, failure, skill]

### Stop doing
[the behaviour, the evidence, and what to do instead]

### Your number one priority
[One direct paragraph: if nothing else on this list gets done, this should]
```

## Before you deliver

Every number in the plan must come from the analyses or data supplied, or be calculated from them, so remove any figure that does not. Deliver the plan in your reply, and only when working inside an EvoNexus workspace also save it under `workspace/social/`.

The final step is the voice check: load the `house-prose-style` skill, run its pre-delivery voice check on the plan and on any example hook or line it contains, and fix what fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, and a plan that models a hook in the wrong voice teaches the wrong habit the moment someone copies it.
