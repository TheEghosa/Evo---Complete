---
name: social-post-writer
description: "Writes single social media posts and captions in the right voice and format for each platform. Use when the user says write a post, draft a post, LinkedIn post, tweet, X post, Threads post, Bluesky post, Instagram caption, Facebook post, TikTok caption, TikTok description, YouTube description, Pinterest pin title, pin description, social media post, caption this, or shares a draft and asks for it to be tightened for a named platform. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. Not for DataExplained (@dataexplain) posts, comments, reels, pins or newsletters (The Data Brief, The Data Drop), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; use this for everything else, including TheSpark, client brands, Fredrick on platforms other than LinkedIn, and formats those skills do not cover."
---

# Post writer

This skill writes one post or caption at a time, in the poster's voice. It covers feed posts on LinkedIn, X, Threads, Bluesky and Facebook, Instagram captions, TikTok captions, YouTube descriptions, and Pinterest pin titles and descriptions. Anything with connected parts is a different job, so threads go to social-thread-writer, carousels to social-carousel-writer and long X articles to social-x-longform.

## When another skill owns this

Before you draft, check that the request is yours, because Fredrick's brand skills carry rules (source verification, fixed sign-offs, evidence grading) that this general skill does not. DataExplained (@dataexplain) posts, comments, reels, Pinterest pins and the two newsletters, The Data Brief and The Data Drop, go to the DataExplained skills. Fredrick's evidence-graded LinkedIn posts and posts built on audit findings go to linkedin-artifact-engine, and any request that says content engine or full pack goes to the skill built for it. Hand those over; everything else is yours, including TheSpark, client brands, Fredrick on platforms other than LinkedIn, and formats those skills do not cover.

## Start with the voice

Your first step is to read the social-context skill, which holds the voice profiles (Fredrick as founder, DataExplained, TheSpark Digital Tech and the client template). Work out which profile the request needs from its cues, and ask one short question when you cannot tell, since a post in the wrong voice has to be thrown away no matter how well it is built. If you are inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it as well and let it override the built-in profiles.

When the profile includes example posts, match their pronoun, sentence length, emotional register and structural habits, such as always ending on a question. Punctuation habits carry over too, except that no profile gets em dashes or en dashes, even if an old example used them, because the house style bans them everywhere.

## What to ask for

You need the topic or a rough draft, the platform, the content type (educational, storytelling, promotional, engagement or personal) and the angle or call to action. Ask only for what the user has not given, because over-asking stalls a job that could already be underway, and once you have a topic and a platform, start writing and fill the rest from the profile.

## Platform specs

The table below holds the limits you may rely on. Where it says to check, the number has not been confirmed, so look up the platform's current limit rather than guessing one.

| Platform | Length | What shows before the fold | Hashtags |
|---|---|---|---|
| LinkedIn | Up to 3,000 characters; aim for 1,200 to 1,500 | The first two or three lines before "see more" | Three to five, at the very end after the call to action |
| X | 280 characters on a standard account; longer needs X Premium | Short post; lead with the point anyway | None to two |
| Threads | 500 characters | Short post; lead with the point anyway | None or one |
| Bluesky | 300 characters | Short post; lead with the point anyway | None |
| Instagram | Captions up to 2,200 characters | Only the opening line or so before "more" | Follow the profile, or ask |
| Facebook | Long posts are allowed | The first few lines before "See more" | Follow the profile, or ask |
| TikTok | Check the current caption limit before writing a long one | Check in the app | Follow the profile, or ask |
| YouTube | Descriptions up to 5,000 characters; titles up to 100 | Check in YouTube's preview | Follow the profile, or ask |
| Pinterest | Titles up to 100 characters; descriptions under 800 | About 40 characters of the title in the feed grid | Follow the profile, or ask |

Because the fold is the real limit on most of these platforms, the line above it has to work on its own even when the total length allows far more.

### LinkedIn and Facebook

A LinkedIn post has three parts: a hook of one or two lines that earns the "see more" tap with no throat-clearing, a body with a line break every one or two sentences, and a call to action that invites a reply. Links go in the first comment rather than the body, which is also Fredrick's own rule, and the register is first-person and specific without sounding corporate. Facebook shares the same shape because it shares the same kind of fold, though the register can be looser.

This example is illustrative and written for a fictional agency client, so none of its details are real results.

```
For two years we sent every client a long monthly report, and almost nobody read past page two.

We found that out the honest way, by asking. Most people wanted to know what had moved and what we were doing about it.

So the report is now one page. The detail still exists, but it lives in an appendix for the few who want it.

The calls got shorter and the questions got better, because clients finally knew what they were looking at.

What does your team send every month that nobody asked for?

#marketing #reporting #clientservice
```

### X, Threads and Bluesky

On X the hook, the message and the call to action have to fit into one tight unit, so cut every word that does not earn its place. Contrarian, bold and question hooks draw the most replies there, and a conversational line reads better than an authoritative one. An idea that needs more room becomes a thread through social-thread-writer.

> Illustrative X post: "Most brand guidelines spend [number] pages on the logo and one paragraph on the voice. That ratio explains a lot of bad copy."

Threads is conversational, closer to texting a smart friend, and a little rawness reads as more honest there than polish does. Empathy and story openers land best, and first-person experience beats advice.

> Illustrative Threads post: "honestly the hardest part of posting is hitting publish when you're not sure anyone cares. the writing is easy by comparison, so if you're stuck, it's probably nerve rather than ideas."

Bluesky rewards wit and a genuine take, and its users have little patience for marketing language, so dry observation and confession hooks fit best. A direct, short line suits it better than a polished one.

> Illustrative Bluesky post: "Every brand voice guide I have read says 'friendly but professional', which is also how you would describe a dentist's waiting room."

### Instagram captions

Since only the opening line or so shows before "more", that line has to add something the image cannot say on its own, whether a question, a moment or a claim. The rest can run long, up to 2,200 characters, as long as it keeps the same white-space rules as LinkedIn and ends on a clear call to action. Put any hashtags at the end so they do not crowd the opening.

### TikTok captions and YouTube descriptions

On TikTok the video carries the hook, which social-hook-writer writes, so the caption adds context the video does not say, with a first line that stands alone; check the current caption limit before writing anything long. A YouTube description can run to 5,000 characters. Open it with two or three plain sentences on what the viewer will get, then add links and any chapter timestamps the user supplies, and never invent a timestamp, because a wrong one sends the viewer to the wrong moment. Titles come from social-hook-writer.

### Pinterest pins

A pin title can run to 100 characters, but only about 40 show in the feed grid, so the payoff goes first. Keep descriptions under 800 characters, the same ceiling Fredrick's existing Pinterest skill uses, and write them as a short, plain explanation of what the reader gets from the pin. DataExplained pins never come here, since they have their own skill and sign-off.

## Writing process

The steps below run in order for every post, because each one depends on the one before it.

1. Pick or write the hook first, using the nine patterns in social-hook-writer and matching the pattern to the platform and content type.
2. With the hook settled, draft the body in the profile's voice, mirroring its vocabulary and rhythm rather than a generic expert tone.
3. The call to action comes next, chosen to fit the content type from the table below.
4. Format the post for reading, using the spacing patterns described after the table.
5. Platform rules come last: hashtags, length and where any link goes.
6. If the user wants options, offer two or three versions with different hooks or angles.
7. Load the `house-prose-style` skill, run its pre-delivery voice check on the finished copy, and fix what fails, because Fredrick's standing rule is that no copy goes out unless it follows the house style.

These calls to action are starting points for each content type rather than fixed lines.

| Content type | Call to action |
|---|---|
| Educational | "What would you add?" |
| Storytelling | "Has this happened to you?" |
| Promotional | "Link in the first comment", or "DM me [word]" |
| Engagement | An open question that invites a real reply |
| Personal | "Anyone else?" |

A call to action that does not fit the post reads as bolted on, so rewrite these in the profile's voice rather than pasting them.

For spacing, never stack more than two or three lines without an empty line, because dense blocks get scrolled past on every platform. The grouped rhythm (one line, a gap, two lines, a gap, one line) suits most posts, while the single-line rhythm suits some voices but never Fredrick's, since his profile bans staccato one-sentence-per-line posts.

## Before you deliver

Run through this checklist, since each item catches a failure that is easy to miss on a quick read.

1. The hook would stop you scrolling if someone else had written it.
2. The voice is the profile's, not a generic expert's.
3. The reader knows what to think or do next.
4. The length is within the platform's spec, and the line above the fold works alone.
5. A LinkedIn post has no links in the body, and the link note for the first comment is included.
6. The hashtag count matches the table or the profile.
7. No number, result or claim appears that the user did not supply, and any gap is a marked placeholder.
8. The house-style voice check has been run and passed.

Deliver the post as plain text ready to paste, with a note for any action outside the post itself, such as the link that belongs in the first comment. Only when you are working inside an EvoNexus workspace should you also save it under `workspace/social/`.

## Boundaries

This skill writes single posts and captions as text, not images or video. Adapting a finished post to other platforms belongs to social-content-repurposer, deciding what to post to social-content-strategy, and performance questions to social-performance-analyzer, since a writer that also tries to plan and analyse ends up doing each job with half the context it needs.
