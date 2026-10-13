---
name: social-carousel-writer
description: "Writes slide-by-slide carousel copy and its caption for LinkedIn document carousels and Instagram carousels (up to 20 slides): cover, context slide, one-point body slides and closing action slide, in listicle, framework, before and after, data story or case study formats. Text only, not design. Use when the user says write a carousel, carousel post, LinkedIn carousel, Instagram carousel, swipe post, slides for this post, or turn this into a carousel. Not for DataExplained (@dataexplain) posts, comments, reels, pins or newsletters (The Data Brief, The Data Drop), for Fredrick's evidence-graded LinkedIn posts and audit-finding posts (linkedin-artifact-engine), or for requests that say content engine or full pack, which have their own dedicated skills; use this for everything else, including TheSpark, client brands, Fredrick on Instagram, and formats those skills do not cover."
---

# Carousel writer

This skill writes carousel copy slide by slide, with the caption that sits above it, for LinkedIn document carousels and Instagram carousels. The output is text rather than design, ready to drop into Canva or whatever tool builds the slides. A carousel lives or dies on whether people keep swiping, which means every slide has two jobs at once: it has to say one thing clearly, and it has to make the next slide feel necessary.

## When another skill owns this

Some carousel requests belong to other skills, and you should hand those over rather than write them here, because Fredrick's brand skills carry rules this general skill does not, such as source verification, fixed sign-offs and evidence grading. Fredrick's own LinkedIn document posts built from evidence (checklists, scorecards, teardowns, audit findings) belong to linkedin-artifact-engine, which grades every item and names its source. DataExplained carousels belong to the DataExplained skills. Anything described as content engine or full pack goes to the skill built for that. This skill takes the rest: TheSpark company carousels, client carousels, Fredrick's Instagram carousels, and any LinkedIn carousel he explicitly wants outside the artifact format.

## Platform facts

Only two platforms run the swipeable format this skill writes for, so the facts you need are short.

| Platform | What to know |
|---|---|
| LinkedIn document carousel | Shown as swipeable pages from an uploaded document. The caption follows LinkedIn's post rules: up to 3,000 characters, with only the first two or three lines visible before "see more". This skill's working range is 7 to 12 slides, which gives depth without fatigue. |
| Instagram carousel | Up to 20 slides. Captions run up to 2,200 characters, and only the opening line or so shows before "more". |

Both captions are cut off almost immediately, so the caption's first line has to earn attention on its own. For any other platform, check its current multi-image options before promising a carousel.

## Workflow

1. Your first step is to read the profiles in the social-context skill and work out from the request whose voice this is (Fredrick, TheSpark, a client). When you cannot tell, ask one short question, because a carousel in the wrong voice has to be rewritten slide by slide. If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it too and let it override the built-in profiles.
2. Next, collect only what the user has not already given you: the topic or key message, the platform, the goal (teach, share a framework, list tips, tell a story, present data) and a slide count. A topic alone is enough to start drafting, since over-asking stalls the work for no gain.
3. With the inputs in hand, choose a format from the table below, because the format decides how the body slides progress.
4. The body slides get drafted first, then the context slide, and the cover comes last, since you can only write a cover that earns the swipe once you know what the carousel delivers.
5. Once the slides hold up, write the caption and run the voice check described at the end of this skill.
6. The slides and caption go in your reply, and only when working inside an EvoNexus workspace also save them under `workspace/social/`.

## The four zones of a carousel

The **cover** is the hook. It carries one bold, specific headline that promises value and one subtitle that makes the promise concrete, in two or three lines at most. If the cover would not earn attention as a standalone post, social-hook-writer can generate stronger options.

> Headline: Seven signs your content plan is quietly broken
> Subtitle: And the fix for each one, in the order you should make them.

> Headline: I went from [number] to [number] followers in [number] days
> Subtitle: What worked was less interesting than what I stopped doing.

The **context slide** bridges the hook and the value. One or two sentences address the reader's pain, gap or curiosity directly, and skipping this slide is a mistake because it is what tells the reader the next eight swipes are about their problem.

> Most people post consistently for a month, see nothing, and quit. The ones who keep going are usually doing one thing differently.

The **body** carries one point per slide, without exception, since a slide holding two points gets read as neither. Each slide gets a bold header of eight words or fewer and supporting text of no more than 30 words. The patterns that work best are listed below.

| Pattern | Shape |
|---|---|
| Tip slide | Bold header plus one or two lines of context or example |
| Step slide | "Step [N]:" plus what to do and why it works, in one sentence |
| Contrast slide | The wrong way, then the right way, as a two-line contrast |
| Stat slide | One real figure plus a one-sentence insight about it |

The stat slide is the one to treat carefully, because it only works with a figure the user supplied or a source they can name. When no real number exists, leave a placeholder such as [number] and ask, rather than inventing a statistic.

The **closing slide** carries one summary line and one specific action (follow, save, share, comment or message), optionally with the author's name or handle so a shared slide still points home. A menu of actions hands the reader a decision at the exact moment you want them to act, so pick the one that suits the goal.

## Carousel formats

The topic and goal decide the format, and the five below cover most requests.

| Format | Structure | Best for | Cover example |
|---|---|---|---|
| Listicle | [N] tips, mistakes, lessons or tools, one per slide | Quick wins, resource lists, common mistakes | Nine LinkedIn habits that are costing you readers |
| Framework | Numbered steps with a clear progression | Teaching a repeatable method or system | The five-step process behind every post I write |
| Before and after | Slides alternating the wrong approach and the right one | Reframing habits, teaching by contrast | You are writing your hooks backwards, and the fix is simple |
| Data story | One real figure per slide, each with a one-sentence insight | Research-backed content, credibility | I reviewed [number] posts from our own account, and three patterns kept showing up |
| Mini case study | Problem, approach, result, lesson, one or two slides each | Personal stories, client wins, experiments | How I [result] in [time period] without posting more |

A data story or case study needs real numbers and a real outcome from the user, so ask for them first, and leave placeholders such as [number] or [result the user supplied] where they are still missing. A single listicle slide looks like this:

```
Slide 4 (Mistake 3)
Header: Putting the link in the post
Body: A reader who clicks away has left your post, so put the link in the first comment and let the post itself do the persuading.
```

## Writing the slides

People skim carousels, so the header on each slide has to communicate its point even if the body is never read, and a header that fails that test gets rewritten. Keep the body under 30 words; when a slide runs over, split it into two, since crowded slides are where readers abandon the deck.

Arrows, numbers and bold help only when used sparingly, because a slide where everything is emphasised has nothing emphasised. Each slide should also leave a reason to swipe, such as a partial thought or a count ("and that is only number three"), so the best part always feels one swipe away.

Slide copy is short, but the house style still applies across the deck: if every slide uses the same sentence shape the carousel reads like a chant, so vary the rhythm and keep the logic visible with because and so. For Fredrick's profile in particular, social-context rules out emojis, "Here's the thing" and staccato one-line-per-sentence writing, and those bans hold on slides as much as in posts.

## Writing the caption

The caption is a short post that happens to carry slides, so write it in the profile's voice (first person for Fredrick, "we" for TheSpark) and make its opening line a hook in its own right, since readers meet it above the cover and judge the post by both. The body should land the single most useful or surprising point from the deck rather than summarise every slide, and it should end with the same one action as the closing slide. On LinkedIn, keep external links out of the caption and put them in the first comment, as Fredrick's profile requires. On Instagram, put any hashtags at the very end, where they do not interrupt the hook.

## Output format and example

Deliver each slide as a labelled block (cover with headline and subtitle, context, body slides with header and body, close with summary and action), followed by the caption with its platform named. This example uses a framework format for a client brand on LinkedIn, in eight slides.

```
Slide 1 (Cover)
Headline: The five-step structure behind posts people actually finish
Subtitle: Most people skip step two, which is why their posts lose readers halfway.

Slide 2 (Context)
Writing a LinkedIn post is easy. Writing one that people read to the end takes structure, and most people are improvising theirs.

Slide 3 (Step 1)
Header: Step 1: Write the hook last
Body: The opening line matters most, so write the whole post first and come back to the hook once you know what it has to promise.

Slide 4 (Step 2)
Header: Step 2: One idea per post
Body: Posts lose readers when they try to say too much. Pick one insight and build everything around it, even when "and also" is tempting.

Slide 5 (Step 3)
Header: Step 3: Break paragraphs early
Body: White space is what makes a post readable on a phone, so break any paragraph that runs past two lines on a small screen.

Slide 6 (Step 4)
Header: Step 4: Add one specific detail
Body: "I grew my audience" is forgettable. "I grew [number] followers in [number] days by posting every Tuesday" is a post, as long as the numbers are real.

Slide 7 (Step 5)
Header: Step 5: End with a direction
Body: A post that simply stops leaves the reader nothing to do, so ask a real question, suggest a save, or invite a reply.

Slide 8 (Close)
Summary: Structure is what turns a decent idea into a post people finish.
Action: Save this for your next draft, and follow for one writing tip a week.

Caption (LinkedIn)
When a post loses its readers early, the cause is usually that it tried to carry three ideas at once, not that the idea was weak. These five steps are the structure we use on every draft. Step two does most of the work, so if you only try one, start there.
```

## Final voice check

Before you hand anything over, load the `house-prose-style` skill and run its pre-delivery voice check on every slide and the caption, then fix whatever fails. Fredrick's standing rule is that no copy goes out unless it follows the house style. A carousel that has not passed the check is not finished. Pay particular attention to the dash scan, since slide templates invite dashes, and to the closing slide, where summary lines drift into restating the cover.

## Boundaries

This skill writes slide text and captions only, so it does not produce images, design files or PDFs. A single standalone post belongs to social-post-writer and a multi-part thread to social-thread-writer, while turning an existing article or post into a carousel among other formats is the job of social-content-repurposer. Posting schedules belong to social-content-calendar, and judging how a published carousel performed belongs to social-performance-analyzer.
