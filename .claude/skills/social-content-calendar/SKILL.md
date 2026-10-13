---
name: social-content-calendar
description: "Builds a social media content calendar across Fredrick's profiles (Fredrick as founder, DataExplained, TheSpark Digital Tech and client brands): weekly or monthly calendars, batching plans, flexible slots and a review cadence. Use when the user says content calendar, posting schedule, plan my week across accounts, monthly plan, what should we post this week, when should I post, how often should I post, content cadence, batch content, or schedule these posts. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. For DataExplained-specific posts defer to the DataExplained skills; not for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; use this for everything else, including TheSpark, client brands, Fredrick on platforms other than LinkedIn, and formats those skills do not cover."
---

# Social content calendar

This skill turns a content strategy into a schedule, so every profile knows what goes out, where, in which format and on which day. A good calendar takes the daily decision away, which is what protects consistency, while leaving deliberate room for what nobody can plan.

## When another skill owns this

Two rhythms in Fredrick's week are already designed elsewhere, and this calendar slots them in by reference instead of redesigning them. DataExplained's LinkedIn and X posts follow the weekly editorial rhythm in dataexplained-social-master, where each weekday has a purpose on each platform and the two platforms run independently, and the brand's daily visual runs on its own schedule. Fredrick's personal LinkedIn cadence, along with the alternation of post shapes, is set by linkedin-artifact-engine. Reserve those slots, label them with the skill that owns them, and leave their purposes, shapes and topics blank here, because a second copy of either rhythm in this skill would drift the moment the owning skill changed. The posts for those slots come from the owning skills, which carry verification, sign-off and evidence-grading rules this skill does not.

If the request is only for DataExplained's week, or only for Fredrick's LinkedIn, hand it straight to the owning skill. Requests described as a content engine or full pack go to their own skill as well.

## 1. Read the profiles and the strategy

Read the profiles in the social-context skill and work out which profiles the calendar covers, asking one short question if the request does not say. When you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.

Social-context also records which platforms each profile is confirmed to use. Schedule only those, and ask before adding a slot for any other platform, because a slot for an account that may not exist creates work nobody can publish. For a client, the confirmed platforms are the ones in the client profile collected in the conversation.

Then look for a strategy from social-content-strategy in the conversation or, inside an EvoNexus workspace, under `workspace/social/`. Without one, collect the pillars in discovery, or suggest building the strategy first when there are no clear pillars at all, since a calendar without pillars only schedules improvisation.

## 2. Discovery

Ask only what social-context and the strategy have not already answered, and group the questions into one message rather than asking them one at a time.

| Area | What to find out |
|---|---|
| Platforms and frequency | Which confirmed accounts each profile will post to, the target posts per week on each, and which platforms get priority versus maintenance effort |
| Pillars and mix | The three to five pillars, the rough share of each, and any pillar that must appear every week |
| Capacity | Hours per week for content, whether they prefer to batch or write day by day, and any long-form assets to repurpose |
| Key dates | Launches, events, campaigns or seasonal moments in the next four to eight weeks, and any topics that are off limits or time sensitive |

When someone asks how often they should post, answer from their capacity rather than a benchmark, because no frequency figure available here is verified and a cadence they can keep is worth more than one they abandon in the third week. The owned rhythms above are not up for discussion in this step, so take them as given.

## 3. Build the calendar

Default to a weekly view for a profile that is new to planning and a monthly view for one with an established strategy. Each entry needs a day, a profile, a platform, a pillar, a specific topic or angle, a format, and an owner, meaning the skill that will write it.

The rules below keep a calendar balanced, and each one exists to stop a particular way calendars go wrong.

1. No pillar takes more than 40% of the slots unless the user asks for that, since one dominant pillar makes a profile read as a one-topic account.
2. No platform that a profile posts on several times a week goes more than three days without a post. Slower formats such as long YouTube videos and pins can follow their own steadier cadence.
3. Formats vary within each platform across the week, so the feed does not settle into one shape.
4. Between 20% and 30% of slots stay open for timely or reactive content (section 6 explains why).
5. Heavy pieces such as threads, carousels and videos do not stack on the same day for the same profile, because one person cannot do them all justice in an afternoon.
6. Two profiles do not post the same idea on the same day. When Fredrick and TheSpark share a topic, one goes first and the other adds to it later in the week.

The example below is illustrative and assumes social-context confirms each account shown.

| Day | Profile | Platform | Pillar | Topic or angle | Format | Owner |
|---|---|---|---|---|---|---|
| Per that skill | DataExplained | LinkedIn and X | Rhythm slots | Set by dataexplained-social-master | Per that skill | dataexplained-social-master |
| Per that skill | Fredrick | LinkedIn | Engine slots | Number and shapes set by linkedin-artifact-engine | Per that skill | linkedin-artifact-engine |
| Mon | TheSpark | Instagram | Educational | What a real location page contains | Carousel | social-carousel-writer |
| Tue | TheSpark | X | Engagement | Do you check your Google Business Profile every week? | Poll | social-post-writer |
| Wed | TheSpark | TikTok | Educational | One question to ask before paying for a backlink audit | Short video | social-hook-writer, then social-post-writer |
| Thu | Client | Facebook | Storytelling | [Story the client has approved] | Post | social-post-writer |
| Fri | TheSpark | LinkedIn page | Promotional | What the team shipped this month, with client approval | Carousel | social-carousel-writer |
| Fri | TheSpark | X | Open | [Flexible: timely or reactive] | To be decided | |
| Weekend | Any | Any | Open | [Flexible: two open slots] | To be decided | |

The owned rows hold a place and nothing more, which is why their topics stay blank: when you reach those days, run the owning skill.

After presenting the calendar, ask whether it reflects their accounts and pillars and whether any day or slot needs to move.

## 4. Batching

A calendar only survives a busy week if the writing happens in batches, so it should come with a batching plan. The sessions below are a starting shape to adjust to the person's week.

| Session | Length | Output |
|---|---|---|
| Weekly planning (Monday morning) | 30 minutes | Confirm the week's topics and note any news worth reacting to |
| Long-post batch, one platform | 90 minutes | Three to five longer posts drafted and ready to schedule |
| Short-post batch (X, Threads, Bluesky) | 60 minutes | Five to eight short posts drafted |
| Review and schedule (Friday) | 30 minutes | Approved posts queued for the following week |

Short video is harder to time in advance, so plan one filming session for several clips and let the editing set its own length. There are two ways to group the writing. Batching by platform means switching into each platform's register once per session, which suits work across very different platforms such as LinkedIn and Threads. Batching by pillar means writing everything on one topic together and reformatting afterwards, which suits topics that need research. Default to batching by platform, but across several profiles batch by profile first, because switching between "I", "we" and DataExplained's voice mid-session is the mistake that costs most, and a draft in the wrong voice is thrown away whole.

When the profile has a newsletter, podcast or long article, map one long piece to three to five short posts across the week, mark the source in the calendar, and use social-content-repurposer to do the adapting.

## 5. Posting times and scheduling

This skill gives no benchmark posting times, because none could be verified and the right time depends on where a profile's audience lives and works. Start instead with two windows per platform that make sense for the audience's time zone and working day (a Lagos audience and a London audience will not share them), keep them for a few weeks, and compare the results with social-performance-analyzer once the numbers are pasted in. Add a planned time column to the calendar so manual scheduling is straightforward.

If a scheduling tool is connected in the session, show each draft with its account, platform and time and get an explicit yes before scheduling anything, since a scheduled post goes out under someone's name without a second look. If no tool is connected, the calendar table is the hand-off for scheduling by hand.

## 6. The flexibility buffer

Protect 20% to 30% of the week's slots as open, and mark them `[Flexible: timely or reactive]` instead of filling them during planning. Open slots let a profile respond to news while it still matters, absorb a planned post that is not ready without breaking the week, and give a new format or pillar a trial run without committing it to the plan. A profile can only look in the moment if its week has room for it, so if the user resists leaving gaps, explain that the gaps are where the timely posts come from.

## 7. Review cadence

A calendar without a review loop drifts, so pair it with a light routine. The weekly review takes 15 to 20 minutes each Monday: note which posts beat expectations (pillar, format and angle), consider dropping the format or angle of an underperformer rather than its pillar, check whether any open slots are needed, and confirm the week still reflects current priorities. The monthly recalibration takes 30 to 45 minutes on the first Monday, when you check whether one pillar is dominating or another is neglected, adjust frequency per platform if engagement has shifted, and update the template for the next month.

Both reviews work only from numbers the user pastes, so ask for them, and pass any real analysis to social-performance-analyzer. A review note should look like this, with placeholders until real figures arrive:

```
Weekly review, week of [date]
Above expectations: [post], [metric and value from the pasted data]
Below expectations: [post], [metric and value]; try [format or day change]
Open slots needed this week: [number and reason]
Next week confirmed: [yes or no]
```

## 8. The calendar document

Present the final calendar in this shape, so it can be followed as written or handed to whoever schedules.

```
# Content calendar

Period: [week of or month of] [date]
Profiles and platforms: [confirmed accounts per profile]
Planned posts: [N]   Flexible slots: [N]
Owned slots: [DataExplained and Fredrick LinkedIn slots, by skill]

## Calendar
[Calendar table with planned times]

## Batching plan
[Session table]

## Open slots
[Each flexible slot and its purpose]
```

## 9. Before you hand it over

Load the `house-prose-style` skill and run its pre-delivery voice check on the calendar, including every topic line and any posts drafted for the slots, then fix whatever fails. Fredrick's standing rule is that no copy goes out unless it follows the house style, and a topic line in a calendar usually becomes the hook of the post. Deliver the calendar in your reply, and only when working inside an EvoNexus workspace also save it under `workspace/social/`. From there, social-post-writer, social-thread-writer and social-carousel-writer write the general slots, while the owned slots go back to their own skills.
