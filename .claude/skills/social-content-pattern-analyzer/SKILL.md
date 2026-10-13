---
name: social-content-pattern-analyzer
description: "Finds patterns in what social media content works from pasted post history, CSV exports, screenshots or descriptions, grouping posts by pillar, format, posting time, length, hook type, tone and platform, ranking each group against the account's own baseline with its sample size, labelling each pattern well supported, thin or a hypothesis to test, and delivering a Do More, Do Less, Experiment With report. Use when the user says content patterns, what's working, best topics, best format, best time to post, content audit, or what should I do more or less of. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. Not for client analytics reports from GSC, GA4 or Meta (spark-analytics), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; for DataExplained-specific posts defer to the DataExplained skills, and use this for everything else."
---

# Social content pattern analyzer

Single posts tell you what happened once, whereas patterns tell you what to do next, which is why this skill looks past individual metrics to the topics, formats, hooks, tones and timing that keep winning or keep losing. The output is a Do More, Do Less and Experiment With report that someone can act on the same day. There is no live connection to any platform here, so the skill works only from the post history supplied in the conversation and never fills a gap with an assumed figure.

## When another skill owns this

Client analytics reports built from Google Search Console, Google Analytics 4 or Meta data belong to spark-analytics, which reads those sources live, so hand those over. DataExplained-specific posts go to the DataExplained skills, Fredrick's evidence-graded LinkedIn posts and audit-finding posts go to linkedin-artifact-engine, and anything called a content engine or a full pack has its own skill. Those skills carry verification, sign-off and evidence-grading rules that this one does not, which is why they take priority.

Within this set, a breakdown of individual posts belongs to social-performance-analyzer, follower growth to social-audience-growth-tracker, and a prioritised action plan to social-optimization-advisor.

## Start with the profile

Read the social-context skill first and work out which profile the account belongs to (Fredrick as founder, DataExplained, TheSpark Digital Tech, or a client), asking one short question if the request leaves it open. The profile supplies the pillars, the audience and the time zone, and without those you cannot tell a topic gap from a topic the account deliberately avoids. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.

## Ask for enough posts

Patterns need a bigger sample than a single-post review. Ask for 30 or more posts if the account has them. Between 15 and 30 the analysis can go ahead with its limits stated, below 15 most patterns will be thin at best, and below 10 you should explain that any pattern would be noise and ask for more before analysing.

Each row needs the descriptive columns below, because the pattern dimensions are built from them rather than from the metrics.

| Column | Why it is needed |
|---|---|
| Post text or first line | Hook type, tone and length are classified from it |
| Date, time and time zone | Day and time patterns, and the age of each post |
| Platform and format | Single post, thread, carousel, video, image, poll, pin |
| Topic or pillar | Pillar patterns and gaps |
| Hook type and tone, if already tagged | Saves classifying from scratch |

The metric columns follow the platform. LinkedIn and X need impressions, likes or reactions, comments or replies, reposts, and bookmarks where X shows them. Instagram, Facebook and Threads need reach or views, likes, comments, shares and saves, and Bluesky needs likes, reposts, replies and quotes, plus views if the tool reports them. For TikTok, Reels, YouTube and Shorts ask for views, watch time and the share who watched to the end, alongside likes, comments and shares, and for Pinterest ask for impressions, saves and outbound clicks.

When the user pastes post text without tags, you may classify format, hook type, tone and length yourself, but show the tags back as a table before analysing, since a pattern built on a mislabelled post is a pattern about your labels.

## The seven dimensions

Engagement rate here is likes plus comments plus reposts plus saves, divided by the platform's reach measure (impressions, reach or views), multiplied by 100. For every dimension, group the posts, calculate each group's average rate (and the median, since one breakout post distorts an average), count the posts in each group, and rank the groups from best to worst against the account's own baseline. The seven dimensions and what to look for in each are these.

| Dimension | Groups | What to look for |
|---|---|---|
| Topic or pillar | The profile's pillars | Pillars above and below baseline; high reach with low engagement (reach without resonance) against low reach with high engagement (a smaller audience that cares) |
| Format | Single post, thread, list, question, poll, image, video, carousel, pin | Which format earns saves (lasting value) and which earns reposts (distribution); format and topic pairs that keep winning |
| Posting time | Day of week; morning, midday, evening, night in the profile's time zone | Best slots and dead zones |
| Length | Short, medium and long relative to the platform | Whether short posts win reposts while long posts win saves |
| Hook type | Question, bold claim, specific number, personal story, contrarian take, how-to, list preview, direct address | The strongest hook, and whether the account leans on one pattern |
| Tone | Educational, personal, storytelling, motivational, contrarian, promotional, conversational | Whether the dominant tone matches what the audience rewards |
| Platform | Each platform the account uses | Return per post, and content that loses when cross-posted unchanged |

A ranking only means something when its groups are big enough, so put the post count beside every group and treat any group of one or two posts as a hypothesis at most.

Two traps need checking in every run. Recency comes first: posts from the last few days have not finished collecting engagement, so flag them and leave them out of time and format comparisons if they distort the result. Confounding is the second, because when two dimensions move together, such as every thread going out on a Tuesday, the data cannot say whether the thread or the Tuesday did the work. Say so plainly and turn it into an experiment rather than picking one.

Received wisdom about tone deserves the same caution. The idea that educational posts earn saves, personal posts earn comments and contrarian posts earn reposts is a hypothesis to check against this account, not a rule to report as found.

## Label every pattern

Every pattern carries its evidence label and the sample sizes behind it, so the reader can see how much weight it bears.

| Label | When it applies |
|---|---|
| Well supported | The group has at least five posts, the gap to baseline holds without its best post, and nothing obvious confounds it |
| Thin | The direction is visible, but the group is small, one post carries the gap, or another dimension moves with it |
| Hypothesis to test | One or two posts, an untested combination, or an explanation the numbers cannot confirm |

Never compare the account with an industry average or a "typical" engagement rate, because no verified figure is available here and the account's own history is the only fair baseline. If Fredrick supplies a baseline of his own, use it and name its source.

## Cross-platform comparison

When the account posts on more than one platform, find the posts that went out on several of them and compare engagement, save and repost rates for the same or near-identical content. Rates only compare when they share a denominator, so state which measure each platform used, and read retention beside likes for TikTok, Reels and Shorts, since the first one to three seconds decide whether people keep watching. Then check whether the strongest platform matches the goal in the profile, and flag any platform that keeps trailing the account's other channels for the same effort, since that is time that could go elsewhere.

## Gaps worth testing

After the existing content, look for what has not been tried. Topic gaps are subjects next to the strongest pillars that the profile's audience would plausibly want. Format gaps are formats the account has never used, and untested combinations pair a winning pillar with a winning format that have never appeared together. If the account leans on one hook type, suggest two or three others from the hook list. Every gap is framed as an experiment rather than a failure, and none comes with a claim about how that format performs elsewhere, since no such figure is available. The example below shows the shape, with invented figures.

```
Gap: productivity tips (top pillar) with carousels (top format), never combined
Evidence: productivity posts average 6.1% (n = 12), carousels 5.8% (n = 6),
  against a 3.8% baseline (hypothesis to test: the pair has no posts yet)
Experiment: two productivity carousels over the next two weeks, compared
  with the baseline seven days after each goes up
```

## The report

The report uses the structure below, with each pattern described in four sentences or fewer, because specific findings get acted on and long ones get skimmed.

```
## Content pattern analysis for [date range]

Profile: [which social-context profile]
Posts analysed: [n], on [platforms]
Baseline engagement rate: [average], median [median]

### Do more
Pattern: [name it, such as "Tuesday morning threads on productivity"]
Evidence: [average rate, n, example posts, label]
Why it seems to work: [the hypothesis, stated specifically]

### Do less
Pattern: [name it, such as "Friday promotional posts"]
Evidence: [average rate, n, label]
Why it underperforms: [direct, constructive diagnosis]

### Experiment with
Experiment: [the combination to test]
Rationale: [the existing patterns that point to it]
How to test: [such as three posts with hook X on topic Y, compared after seven days]
Skill to write it: [the writing skill below]

### The one change that matters most
[One or two sentences naming the single biggest shift]
```

Most findings lead to new copy, so point each one to the skill that writes it: social-hook-writer for new openers, social-post-writer for single posts, social-thread-writer for threads, social-carousel-writer for carousels, social-x-longform for long X posts, and social-content-repurposer for adapting a winner to other platforms. Changes to the pillar mix belong to social-content-strategy, platform focus to social-platform-strategy, and scheduling the experiments to social-content-calendar.

## Before you deliver

Every number in the report must come from the data supplied or be calculated from it, so remove any figure that does not. Deliver the report in your reply, and only when working inside an EvoNexus workspace also save it under `workspace/social/`.

The final step is the voice check: load the `house-prose-style` skill, run its pre-delivery voice check on the report and on any example hook or line you suggest, and fix what fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, which covers a suggested hook just as much as a finished post.
