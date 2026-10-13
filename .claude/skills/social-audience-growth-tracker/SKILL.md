---
name: social-audience-growth-tracker
description: "Tracks follower and subscriber growth from pasted counts, CSV exports, screenshots or descriptions, asks for the figures each platform needs, calculates net growth and growth rate, finds spikes and stalls and the content behind them, separates engagement from follows, checks progress toward a follower goal, labels each conclusion well supported, thin or a hypothesis to test with its sample size, and ranks next actions. Use when the user says follower growth, audience growth, losing followers, why am I not growing, subscriber growth or grow my audience. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. Not for client analytics reports from GSC, GA4 or Meta (spark-analytics), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; for DataExplained-specific posts defer to the DataExplained skills, and use this for everything else."
---

# Social audience growth tracker

This skill connects content decisions to audience outcomes: what brings new followers in, what stalls growth or loses people, and what to do about it next. It has no live connection to any platform, so it works only from the follower counts and post lists supplied in the conversation. That constraint matters more here than anywhere else in the set, because growth data invites storytelling, and a spike lining up with a post is a coincidence until the data says otherwise.

## When another skill owns this

Client analytics reports built from Google Search Console, Google Analytics 4 or Meta data belong to spark-analytics, which reads those sources live, so hand those over, along with any request to pull Facebook or Instagram follower figures from the connector. DataExplained-specific posts go to the DataExplained skills, Fredrick's evidence-graded LinkedIn posts and audit-finding posts go to linkedin-artifact-engine, and anything called a content engine or a full pack has its own skill. Those skills carry verification, sign-off and evidence-grading rules that this one does not, which is why they take priority.

Within this set, per-post metrics belong to social-performance-analyzer, patterns by topic or format to social-content-pattern-analyzer, and a combined action plan to social-optimization-advisor.

## Start with the profile

Read the social-context skill first and work out which profile the account belongs to (Fredrick as founder, DataExplained, TheSpark Digital Tech, or a client), asking one short question when the request leaves it open. The profile tells you the platforms, the audience and any growth goal, and a growth number only means something next to the audience the account is trying to reach. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.

## Ask for the right data

The minimum for a useful analysis is a follower count at weekly intervals for at least four weeks, plus the posts published in that period with their dates. Two data points show the change but nothing about its shape, and with fewer than two there is nothing to analyse, so explain why and ask for more. Any post the user already knows drove follows is worth noting, since that is the closest thing to direct evidence most exports offer.

Platforms count audiences differently, so the most useful figures differ by platform. Ask for the ones below where the platform or scheduling tool shows them, under whatever name the export uses.

| Platform | Most useful figures |
|---|---|
| LinkedIn | Followers over time; for a personal profile, connections separately, since they are a different relationship; newsletter subscribers if there is a newsletter; follows attributed to posts if shown |
| X | Followers over time, follows attributed to posts if shown, reply activity, and accounts followed back, since follow-backs inflate the count |
| Instagram | Followers over time, follows and unfollows if shown, follows per post, profile visits |
| Threads | Followers over time, and when the account was promoted from Instagram |
| Bluesky | Followers over time, and the dates of any starter pack or custom feed the account was added to, since both are discovery routes |
| Facebook | Page followers over time, and whether the figure is followers or page likes, since some pages show both |
| TikTok | Followers over time, follows per video, and where views came from if the export shows it |
| YouTube | Subscribers over time, and subscribers gained and lost per video, which ties growth to a specific video |
| Pinterest | Followers over time beside saves and outbound clicks, and whether followers are the goal at all |

Those figures turn "growth went up" into a reason. On Pinterest in particular, if the account exists to send traffic, read saves and outbound clicks before followers. Screenshots of follower graphs need reading into a table and showing back first, since a graph read by eye is easy to misread.

## Growth analysis

Work through the four parts below before writing any recommendation, because a recommendation drawn from the spike alone usually ignores the stall that followed it.

### Net growth per period

Net new followers for each period is the ending count minus the starting count. Where gross follows and unfollows are both available, report them separately, since a flat line can hide heavy churn underneath. Then name the best and worst three periods by net growth, and say plainly how even the growth was, as in "you gained 340 followers over 30 days, about 11 a day, but 60% of them arrived in one five-day window." The block below shows the shape of the summary, with invented figures.

```
Period: 1 to 31 March
Followers at start: 2,410
Followers at end: 2,750
Net growth: +340 (14.1%)
Daily average: +11.0
Best week: 11 to 17 March (+198)
Worst week: 25 to 31 March (+22)
```

### Growth rate and projection

Period growth rate is new followers divided by starting followers, multiplied by 100. Compare it with earlier periods to say whether growth is accelerating, slowing or flat. A projection is allowed only as a straight line from the current rate, labelled as such ("if the current rate holds, 5,000 is about eight weeks away"), because nothing guarantees the rate holds and a projection presented as a forecast is an invented number.

### Spikes

A spike is any period with at least twice the average daily growth. For each one, identify what was posted during or just before it and offer the likely mechanism: reach spreading through reposts, an authority post drawing followers from the niche, social proof from an active comment thread, or discovery through hashtags, search, replies to larger accounts or a feed the account was added to. Note how long the spike lasted, since a one-day burst and a week of lift call for different responses. The mechanism is a hypothesis unless the platform attributes the follows to that post.

### Stalls

For flat or falling periods, check whether posting frequency dropped, whether the content shifted from formats that reach non-followers to formats that mostly reach existing ones, and whether an unfollow spike suggests a post disappointed the existing audience. A platform-wide change can cause a stall as well, though without evidence from outside the account that stays a hypothesis rather than an explanation. Treat stalls as findings rather than failures.

## Content and growth together

Where follows per post are available, group the posts by format and topic and calculate average new followers per post for each group. That usually splits the content into posts that bring new followers, posts that earn engagement from existing followers without bringing new ones, and posts with no visible effect.

The distinction between engagement and follows is the central idea of this skill. Engagement measures how well a post lands with people who already follow the account, whereas follows measure whether a stranger decided the account was worth tracking, which means high-engagement, low-follow content serves the current audience and follow-driving content answers "why should I follow this account?" Both have value for different goals, so say which kind each group is.

Growth also comes in two shapes. Spike-driven growth arrives in bursts tied to breakout posts and depends on landing them again, while compound growth is a steadier weekly gain from reliable output. Say which shape the account has and whether it suits the goal and the time available.

## Label every conclusion

Each conclusion carries its evidence label and the sample size behind it.

| Label | When it applies |
|---|---|
| Well supported | The platform attributes the follows to the content, or the same link between a content type and growth repeats across at least five posts or periods |
| Thin | A link shows across a few periods, or one spike accounts for most of the growth |
| Hypothesis to test | A single coincidence in timing, or a cause from outside the account such as a platform change |

Never compare the account with an industry growth rate or a "typical" follower count, because no verified figure is available here and the account's own history is the baseline. If Fredrick supplies a target or a baseline of his own, use it and name its source.

## Recommendations and milestones

Finish with three to five ranked actions, each tied to a named finding, labelled with its evidence, and concrete enough to act on this week. Two examples show the standard, using invented figures: "Your three posts that brought the most follows were all threads explaining a framework (thin, n = 3), so write one framework thread a week and compare follows per post after a month," and "your breakout post drew 200 reposts but only 30 follows, so end high-reach posts with a direct reason to follow." When an action calls for new copy, name the skill: social-thread-writer for threads, social-post-writer for single posts, social-hook-writer for openers, social-carousel-writer for carousels, and social-content-calendar for fitting the change into the schedule.

If the profile or the user gives a follower goal, frame the analysis against it: where the account stands, the weekly rate needed to hit the goal on time, the rate the data actually shows, and what would have to change to close the gap. If there is no goal, ask whether there is one, since a growth rate means more against a target.

## The report

The report uses the structure below.

```
## Audience growth report for [date range]

Profile: [which social-context profile]
Followers at start and end: [n] to [n]
Net growth: [+n] ([x%]), daily average [n]

### Growth trend
[2 to 3 sentences on direction and rate, with labels]

### What drove growth, and the stalls
[Content or behaviour lined up with the best and worst periods, with labels]

### What to do next
[3 to 5 ranked actions, each with its label and the skill that writes the copy]

### Milestone progress
[Current position, required rate and actual rate, if a goal exists]
```

## Before you deliver

Every number in the report must come from the data supplied or be calculated from it, so remove any figure that does not. Deliver the report in your reply, and only when working inside an EvoNexus workspace also save it under `workspace/social/`.

The final step is the voice check: load the `house-prose-style` skill, run its pre-delivery voice check on the report and on any suggested line of copy, and fix what fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, and a growth report he forwards to a client is copy too.
