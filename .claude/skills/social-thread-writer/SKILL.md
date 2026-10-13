---
name: social-thread-writer
description: "Writes multi-part threads and post series that open with a hook, carry one idea per post and close with a call to action. Use when the user says write a thread, X thread, Twitter thread, tweetstorm, Threads thread, Bluesky thread, LinkedIn series, multi-part post, series of posts, thread this, or turn this article or these notes into a thread. Covers X, Threads, Bluesky and LinkedIn; Instagram, TikTok, YouTube, Facebook and Pinterest have no thread format, so it points those requests to social-carousel-writer or social-post-writer. Not for DataExplained (@dataexplain) posts, comments, reels, pins or newsletters (The Data Brief, The Data Drop), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; use this for everything else, including TheSpark, client brands, Fredrick on platforms other than LinkedIn, and formats those skills do not cover."
---

# Thread writer

A thread is a sequence of connected posts that teaches, tells a story or walks through a framework, and it works only when the first post earns the click, every post after it keeps momentum, and the last one tells the reader what to do next. This skill writes threads for the four platforms where a multi-post format exists: X, Threads and Bluesky, which chain posts as replies, and LinkedIn, where a series is a run of separate posts tied together by their copy.

The other five platforms Fredrick uses have no thread format, and pretending otherwise produces something no one can post. Instagram content that needs several parts belongs in a carousel, written by social-carousel-writer, and LinkedIn carousels go there too when slides would serve the idea better than a series. A long Facebook post, a TikTok caption, a YouTube description or a Pinterest pin all come from social-post-writer, while the spoken hook for a TikTok, Reel or Short comes from social-hook-writer. A long single article on X belongs to social-x-longform.

## When another skill owns this

Some thread requests belong to another skill, and you should hand them over because Fredrick's brand skills carry rules (source verification, fixed sign-offs, evidence grading) that this general skill does not. DataExplained (@dataexplain) posts, comments, reels, pins and the two newsletters, The Data Brief and The Data Drop, go to the DataExplained skills. Fredrick's evidence-graded LinkedIn posts and series built on audit findings go to linkedin-artifact-engine, and a request that says content engine or full pack goes to the skill built for it. Everything else is yours, including TheSpark, client brands, Fredrick on platforms other than LinkedIn, and formats those skills do not cover.

## Start with the voice

Begin by reading the social-context skill, which holds the voice profiles (Fredrick as founder, DataExplained, TheSpark Digital Tech and the client template). From the request's cues you can usually tell which profile applies, and when you cannot, ask one short question, since a ten-post thread in the wrong voice wastes far more work than a single post would. If you are inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles, because that is where local updates are kept.

## What to ask for

Only ask for what the user has not already given. You need the topic, key points or source material (an idea, a draft, an article or notes), the target platform, the goal (to educate, tell a story, share a framework or document a journey), and the length: short at three to five posts, medium at seven to ten, or long at ten or more. Once you have a topic and a platform, start drafting and choose the length from the material, because a thread should be as long as its ideas and no longer.

## Thread architecture

Every thread has three zones, and each one has a different job.

The hook post has to work as a standalone post and also make the reader want the whole thread, since most readers decide right there. Use the patterns from social-hook-writer, and make a promise about what the reader will know or be able to do by the end. On X, add a plain thread signal such as "A thread:" on the same line or just after the hook. The thread emoji is an option only for profiles that allow emojis, which Fredrick's does not.

The body posts each carry one idea, one example or one step, so if a post needs an "and also", split it. A reader who lands in the middle should still follow any single post. Inside each post, never stack more than two or three lines without an empty line, because dense blocks lose readers in a feed, and end posts on a small payoff or an open question so the next one feels earned. For Fredrick's voice, keep the lines grouped rather than one sentence per line, since his profile bans the staccato style.

The closer lands the thread in one sentence that distils what the reader learned, then gives a clear call to action: follow for more, repost the first post, reply with their own situation, or ask for a resource. A product, newsletter or service can appear here as long as it is not the main event. On X the closer is also the natural place to quote the opening post, which gives the thread a second chance to be seen.

## Thread formats

Choose the format before you write, because it sets the pacing, the shape of the body and the way the thread closes. The examples are illustrative, and square brackets mark figures the user has to supply.

| Format | Best for | Structure | Example opener |
|---|---|---|---|
| Listicle | Tactical advice, tools, habits, mistakes, recommendations | State the list promise, give one post per item, and close with the lesson the list reveals | "Seven writing habits that changed how I work, one per post. A thread:" |
| Story arc | A personal journey, a case study, lessons from failure or success | Setup (who, where, when), conflict, resolution, then the transferable lesson | "Three years ago I nearly closed the business. This is the thread I wish someone had written for me then." |
| Framework | A step-by-step process, system or playbook | Name the framework, give one numbered post per step, and finish with the result of applying it | "The five-step process I use to plan a month of content in one afternoon. Save this one." |
| Breakdown | Analysing a real example such as a post, a company strategy or an event | Say why the example deserves dissecting, walk through each component, and pull out a principle | "This post reached [number] people. I took it apart line by line to see why." |
| Contrarian | Challenging a popular belief and starting a debate | State the claim, acknowledge the common belief, give your evidence, and restate the claim with nuance | "Most advice about posting every day skips the cost. This thread is about the cost." |

Naming a framework makes it easier to remember and share, and a contrarian thread needs its nuance in the closer, because an absolute position reads as a performance rather than an insight.

Here are the first three posts of an illustrative listicle on X.

```
1/ Seven writing habits that changed how I work, one per post.

A thread:

2/ Habit 1: write the hook last.

The opening line matters most, so write it once you know what the post says.
Draft the whole thing first, then come back and earn the read.

3/ Habit 2: one idea per post.

Posts lose readers when they try to say too much.
Pick one point and build everything around it, even when "and also" is tempting.
```

And here is an illustrative closer for a breakdown thread.

```
7/ What this post did differently:

It opened with a specific number the writer could prove, and it showed the work behind the result instead of just the result.

That is the pattern worth stealing. Save this thread for your next draft.

Follow @[handle] for one breakdown every week.
```

## Platform rules

Each platform builds and limits a thread differently, and the table holds only confirmed limits and settled practice, so check the platform's current rules for anything it does not cover.

| Platform | How the thread is built | Length per post | Numbering and signals |
|---|---|---|---|
| X | A chain of replies to your own first post | 280 characters on a standard account; longer needs X Premium | Number every post ("1/", "2/" and so on) so readers know how far they are, and signal the thread in post 1 |
| Threads | The native reply-chain thread | 500 characters per post | Numbering is optional, and the casual register matters more than structure |
| Bluesky | A chain of replies to your own first post | 300 characters per post | Number the posts, since the tight limit makes threads longer and readers need to know where they are |
| LinkedIn | Separate standalone posts published as a series, because LinkedIn has no native threading | Aim for 200 to 600 characters per post, within the 3,000-character cap | Put the same label at the top of each post, such as "Part 2 of 5", and tell readers to follow for the next part |

On LinkedIn, the link back to an earlier part goes in the first comment rather than the post body, which matches both the post writer's rule and Fredrick's own, so each part has to make sense without the reader having seen the others.

Here is an illustrative X thread for a contrarian take, with placeholders where the user's own data would go.

```
1/ Posting every day may be what is holding your account back.

A thread:

2/ I compared [number] months of daily posting with [number] months of posting [frequency].

Daily averaged [rate]% engagement. The slower schedule averaged [rate]%.

3/ The reason is simple enough.

Posting daily forces you to fill slots, whereas a slower schedule lets you publish only your best ideas.
```

## Pacing

Vary post length on purpose. A long explanatory post lands harder after two short ones, and one-liners work as palate cleansers between heavier posts. Hold back the payoff, because a thread that gives away its central idea in post three of ten makes the remaining seven feel like filler. A post can end on a question the next one answers, which keeps people reading without resorting to cliffhanger phrases readers have learned to ignore.

## Before you deliver

This checklist catches the failures that matter most, and the last item is not optional.

1. The hook post would perform on its own, without the rest of the thread.
2. Every post does one job.
3. Each post flows into the next.
4. On X and Bluesky, every post carries its number.
5. The closer has a clear call to action.
6. Each post fits its platform's limit.
7. The voice is the profile's throughout, not a generic expert's.
8. No post contains a number, result or claim the user did not supply.
9. The `house-prose-style` skill has been loaded, its pre-delivery voice check run across the whole thread, and every failure fixed, because Fredrick's standing rule is that no copy goes out unless it follows the house style.

Deliver the thread as numbered plain text ready to paste, with a note on how to post it, such as "post as a reply chain on X" or "publish as separate posts on LinkedIn". Only when you are working inside an EvoNexus workspace should you also save it under `workspace/social/`.

## Boundaries

This skill writes threads and series and nothing else, so a single post goes to social-post-writer, slides to social-carousel-writer and openers on their own to social-hook-writer. Strategy questions go to social-content-strategy, and performance questions to social-performance-analyzer. When a request names a platform without a thread format, say so plainly and send it to the skill that fits, since a thread that cannot be posted helps nobody.
