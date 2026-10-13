---
name: social-performance-analyzer
description: "Analyses how social media posts performed from pasted tables, CSV exports, screenshots or descriptions, asks for the exact columns each platform needs, measures engagement rate against the account's own baseline, diagnoses top and bottom posts, reads trends, labels each conclusion well supported, thin or a hypothesis to test with its sample size, and ends with ranked actions. Use when the user says analyse my posts, how did my posts do, post performance, post metrics, engagement, impressions, my best posts or why did this post flop. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. Not for client analytics reports from GSC, GA4 or Meta (spark-analytics), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; for DataExplained-specific posts defer to the DataExplained skills, and use this for everything else."
---

# Social performance analyzer

This skill turns post metrics into a plain account of what worked, what did not and why, ending with actions specific enough to try this week. It has no live connection to any platform, so everything it says comes from data supplied in the conversation, whether a pasted table, a CSV export, screenshots or a description. That is the discipline rather than a limitation, because an analysis resting on a number nobody supplied is worse than none.

## When another skill owns this

Client analytics reports built from Google Search Console, Google Analytics 4 or Meta data belong to spark-analytics, which reads those sources live, so hand those over, along with any request to pull Facebook or Instagram figures from the connector. DataExplained-specific posts go to the DataExplained skills, Fredrick's evidence-graded LinkedIn posts and audit-finding posts go to linkedin-artifact-engine, and anything called a content engine or a full pack has its own skill. Those skills carry verification, sign-off and evidence-grading rules that this one does not, which is why they take priority.

Within this set, follower growth belongs to social-audience-growth-tracker, patterns across many posts to social-content-pattern-analyzer, and a prioritised plan to social-optimization-advisor. This skill covers individual posts and the trend across one window.

## Start with the profile

Before you look at a number, read the social-context skill and work out which profile the account belongs to: Fredrick as founder, DataExplained, TheSpark Digital Tech, or a client. When the request does not make it clear, ask one short question, since a diagnosis such as "the topic missed your audience" means nothing until you know who that audience is. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it as well and let it override the built-in profiles.

## Ask for the right data

The default window is the last 14 to 30 days, or the last 20 posts if the account posts rarely. Every row needs the first line of the post, the date and time it went up (with the time zone), the format, and the date the figures were exported, because a two-day-old post has not finished collecting engagement and will look weaker than it is.

Beyond those shared columns, the most useful figures differ by platform, so ask for the ones below wherever the platform or scheduling tool reports them, under whatever name the export uses.

| Platform | Most useful columns |
|---|---|
| LinkedIn | Impressions, reactions, comments, reposts, clicks, follows from the post if shown |
| X | Impressions, likes, replies, reposts, bookmarks, link clicks, profile visits |
| Instagram | Reach, views, likes, comments, shares, saves, profile visits, follows; average watch time for Reels |
| Threads | Views, likes, replies, reposts, quotes |
| Bluesky | Likes, reposts, replies, quotes, and views if the tool in use reports them |
| Facebook | Reach, views, reactions, comments, shares, link clicks |
| TikTok | Views, average watch time, the share of viewers who watched to the end, likes, comments, shares, saves, follows |
| YouTube | Impressions, impressions click-through rate, views, average view duration, average percentage viewed, likes, comments, subscribers gained; for Shorts, how many viewers kept watching rather than swiping away |
| Pinterest | Impressions, saves, pin clicks, outbound clicks |

The minimum is one reach measure (impressions, reach or views) plus likes and comments for at least five posts; with fewer, explain why the result would mislead and ask for more. When a platform reports no reach measure, no rate can be calculated, so say so and compare raw counts only between posts of similar age. Screenshots need one extra step: read the figures into a table and show it back before analysing, since a misread digit survives into every conclusion.

## How to read the metrics

Grouping the metrics before you analyse keeps a high like count from being mistaken for success. The three groups are these.

| Group | Metrics | What they tell you |
|---|---|---|
| Reach | Impressions, reach, views, profile visits | How many people saw it; impressions include repeat views, reach counts unique accounts |
| Engagement | Likes, comments, reposts and shares, saves and bookmarks | Likes are passive, comments are active, reposts carry the post to new people, saves show intent to return |
| Conversion | Link clicks, follows from the post, DMs | Whether anyone acted; DMs rarely appear in an export, so ask |

Engagement rate is likes plus comments plus reposts plus saves, divided by impressions, multiplied by 100. Where a platform reports reach or views instead, use that as the denominator and name it, since a rate means nothing until you know what it is a rate of. Compare rates rather than raw counts: 50 likes from 500 impressions (10%) beats 200 likes from 10,000 impressions (2%). Rates on different denominators cannot be compared across platforms, so keep comparisons within one platform unless they match.

For video on TikTok, Reels and Shorts, judge the opening by retention, because the first one to three seconds decide whether people keep watching. Strong retention with modest likes suggests the hook worked and the payoff did not, which needs a different fix from a video nobody watched past the start.

## The baseline is the account's own history

Calculate the account's average engagement rate, reach and comments per post across the window, with the median beside each, since one breakout post can drag an average far from what a typical post does. Every "top" and "bottom" label is relative to that baseline, because a rate that is excellent for one account is ordinary for another.

Never cite an industry average, a platform-wide benchmark or a "good engagement rate" figure. If the user asks for one, say that no verified figure is available here and offer the account's own history instead. When Fredrick supplies a baseline of his own, such as last quarter's averages or a client target, use it and name its source in the report.

## Label every conclusion

Each finding carries one of three labels and the sample size behind it, so the reader knows how much weight it can bear.

| Label | When it applies |
|---|---|
| Well supported | The difference holds across at least five posts on each side of the comparison and is not carried by a single outlier |
| Thin | The direction is visible, but a group has fewer than five posts or one post accounts for most of the difference |
| Hypothesis to test | One or two posts, or an explanation the numbers cannot confirm on their own |

Write the sample sizes into the sentence, as in "Tuesday posts (n = 6) averaged 4.1% against 2.9% for other days (n = 14), which is thin because one Tuesday post carries most of the gap." Explanations of why something worked start as hypotheses, because metrics record what happened rather than why, and they rise only when the same feature recurs across several top posts.

## The four parts of the analysis

The report always has four parts, since a list of winners without the trend and the actions leaves the reader nothing to do.

### Top performers

Take the three to five posts with the highest engagement rate, give the rate and the raw numbers behind it, and diagnose each across topic (timely, contrarian, educational, personal), format, hook, timing and call to action. "This post performed well" is not a diagnosis. The block below shows the expected depth, with figures invented only to show the format.

```
Post: "7 writing habits that doubled my output" (12 March, 9:14am)
Engagement rate: 8.4% against a 2.8% baseline, three times the average
Impressions 4,200, likes 189, comments 47, reposts 31, saves 86

Why it seems to have worked:
Hook: a list preview ("7 habits"), the opener on all three top posts (thin, n = 3)
Topic: productivity and writing, two of the strongest pillars
Timing: Tuesday morning, the best slot in this window (hypothesis to test)
Call to action: "Which one surprised you?", which drew 47 comments
```

### Bottom performers

For the three to five lowest posts, say what went wrong: a generic hook, a topic that missed the audience, an off-peak slot, a format unsuited to the platform, or copy that read as promotional. These are lessons rather than verdicts, because the point is the next post.

### Trends

Say whether engagement rate and reach are rising, falling or flat, whether posting frequency lines up with any shift, and whether one format keeps winning, then give the likely meaning: "engagement rate fell from 3.6% to 2.8% while impressions held steady, so the posts are reaching people without landing."

### Actions

You close with three to five ranked actions, each tied to a named finding, labelled with its evidence and concrete enough to act on this week. Most lead to new copy, so name the skill that writes it: social-hook-writer for openers, social-post-writer for single posts, social-thread-writer for threads, social-carousel-writer for carousels, social-x-longform for long X posts, social-content-repurposer for turning a top post into versions for other platforms, and social-content-calendar for scheduling the result.

## Report format

The structure below keeps the report readable, and its tables should stay under six columns because wider ones break in most chat windows.

```
## Performance analysis for [date range]

Profile: [which social-context profile]
Posts analysed: [n], on [platforms]
Baseline engagement rate: [average], median [median], per [impressions, reach or views]
Reach trend: [up, down or flat] by [x%]

### Top performers
[3 to 5 posts, each with its diagnosis and evidence label]

### Bottom performers
[3 to 5 posts, each with its diagnosis and evidence label]

### Trends
[3 to 5 sentences, with sample sizes]

### What to do next
[3 to 5 ranked actions, each with its label and the skill that writes the copy]
```

## Before you deliver

Every number in the report must appear in the data you were given or be calculated from it, so remove anything that does not, since an invented figure is the one error this skill exists to prevent. Deliver the report in your reply, and only when working inside an EvoNexus workspace also save it under `workspace/social/`.

The last step is the voice check: load the `house-prose-style` skill, run its pre-delivery voice check on the report and on any hook or line you have suggested, and fix what fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, and an analysis whose suggested hook breaks that rule hands him a rewrite instead of an answer.
