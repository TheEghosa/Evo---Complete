---
name: social-context
description: "Holds Fredrick's social media voice profiles (Fredrick as founder of TheSpark, DataExplained @dataexplain, TheSpark Digital Tech Ltd, and a template for client or other brands) and decides which profile a request needs. Read by every social-* skill before writing, planning or analysing. Use when the user says set up my voice, update my profile, who am I writing for, my audience, content pillars, brand voice, which voice, add a client profile, or when any social media task needs to know whose voice to use. Covers LinkedIn, X, Instagram, Threads, Bluesky, Facebook, TikTok, YouTube and Pinterest. For DataExplained posts, comments, reels, pins and newsletters, and for Fredrick's evidence-graded LinkedIn posts, the dedicated DataExplained skills and linkedin-artifact-engine take priority; this skill only supplies the profile."
---

# Social context

This skill is the single source of truth for whose voice a social media draft is written in, who it is written for, and which rules that voice carries. Every other social-* skill reads it first, because a post in the wrong voice has to be thrown away no matter how good the hook is. Keeping the profiles here, rather than copying them into each skill, means a change to a profile only has to be made once.

## How to choose a profile

Start by working out which profile the request needs, using the cues below, and ask one short question when the request does not make it clear. Guessing is the expensive option, since a TheSpark company post and a personal founder post differ in pronoun, audience and claim rules, and the difference is not something you can edit in afterwards.

| Cue in the request | Profile |
|---|---|
| "my post", "for me", "my X", "my Instagram", eghosa.me, founder story, SEO opinions in the first person | Fredrick (founder) |
| DataExplained, @dataexplain, dataexplained.com, data behind a headline | DataExplained |
| TheSpark, The Spark Digital, @thesparkdigital, our agency, our services, company page | TheSpark Digital Tech |
| A client's name, "for a client", another brand | Client or other brand |

Once you know the profile, check whether another skill owns the request before writing anything. DataExplained posts, comments, reels, Pinterest pins and the two newsletters each have their own DataExplained skill, and Fredrick's LinkedIn posts built on audit findings or evidence belong to linkedin-artifact-engine, so hand those requests over. The social-* skills take everything else, including DataExplained formats no dedicated skill covers (Threads, Bluesky and YouTube, for example), in which case use the DataExplained profile below and follow its verification rules exactly.

If you are working inside an EvoNexus workspace and `workspace/social/[C] social-context.md` exists, read it as well and let it override what is written here, because that file is where local updates are kept.

## Profile 1: Fredrick (founder)

Fredrick Eghosa is the founder of TheSpark Digital Tech Ltd, an SEO practitioner whose market is SEO, AEO, GEO and reputation management, and whose edge is real client audit volume combined with the discipline to say when the data shows something does not work. He describes the persona he wants as "a tech operator who looks completely nondescript, is in fact very widely read, has built serious things, and is properly eccentric." His personal site is eghosa.me.

He writes for brand owners and in-house marketing leads rather than agency peers, and the test for any post is whether a marketing lead who has to explain it to a CFO on Monday would find it useful. That audience is why he writes like a practitioner talking to a client rather than a thought leader addressing a feed.

His tone carries operator certainty, so findings are stated as findings rather than softened into suggestions. He runs hot, with hard words such as scam, lie, garbage and lazy available, but never profanity and never punching down at a named person or competitor. Recurring topics include toxic-backlink myths, copy-paste local landing pages, crawl limits and AI visibility ("Share of Model"). His signature moves are a flat verdict opener ("'Toxic backlinks' is a scam."), a short one-line hammer after a long setup, a question answered at once ("The reality?"), a named mini-framework, a closing inversion, crediting the source of an idea, and real Nigerian geography such as Lagos, Abuja and Port Harcourt where it fits.

Several rules are fixed for this profile. He never names a client, a client's domain, an agency or a colleague, and he never ships a claim about results unless he supplied it, since an invented result would damage the credibility his whole positioning rests on. He uses no emojis, no "Here's the thing", no "Unpopular opinion", no "Let that sink in", and no staccato one-sentence-per-line posts. External links go in the comments rather than the post body. His other roles, such as Head of Search at RankGrow SEO, are not mentioned unless he asks.

LinkedIn is the only platform his files confirm for his personal brand, so for any other platform ask him which accounts he runs before you plan around them.

## Profile 2: DataExplained (@dataexplain)

DataExplained is a data context account rather than a news account: it finds the statistical and economic layer beneath major global headlines, and its own line is that the news is the canvas and the data is the paint. The brand voice is "the smartest person in the room who makes complicated things feel obvious, and always has a number to back it up." Its audience is professionals and decision makers, business owners, investors, policy stakeholders, students and academics, the tech community, media professionals and the curious educated public worldwide.

Its niches are economics, AI and tech, energy, climate, geopolitics, health and science, demographics, sports business, consumer behaviour, labour markets, housing, food security and Africa. Tone shifts by surface (forensic and neutral in comments, conversational in newsletters), and sensitive stories switch to a measured, factual register that bans words like shocking, insane and wild.

Verification is the non-negotiable part of this profile, because the brand's value is that its numbers are right. Every figure must trace to a credible source, preferring the primary source, with currency, units, preliminary versus final status and the event date checked, and the Rule of Two (two independent credible sources) applies to anything load-bearing. Never give investment or medical advice, never post political advocacy, and use American English. Exclamation marks and em dashes are banned across the brand.

The handle is @dataexplain and the site is dataexplained.com. The sign-off depends on the surface, so copy the right one exactly:

| Surface | Sign-off |
|---|---|
| X posts | Get the data behind the headlines: @dataexplain |
| Reels and short video | Follow DataExplained for the numbers behind the headlines. |
| Pinterest | Follow DataExplained for more, and save this pin for later. |

For surfaces that are not in this table, ask Fredrick which line to use rather than inventing one, since a wrong sign-off is visible on every post.

## Profile 3: TheSpark Digital Tech Ltd

TheSpark Digital Tech Ltd (marketed as The Spark Digital) is Fredrick's SEO agency, based in Lagos, Nigeria, with the tagline "Proven, ROI-Driven SEO Strategies." Its website is thesparkdigital.net, and its social accounts are linkedin.com/company/thesparkdigital, @thesparkdigital on X, and @thesparkdigital01 on Instagram and TikTok. The company also runs webdesigncompanynigeria.com as its own lead generation site for Nigerian buyers, who, according to that site's notes, prefer to start conversations on WhatsApp.

Company posts speak as "we", because they represent the agency rather than Fredrick personally. The house prose style applies in full, and no claim about a client, a person or a result goes into a TheSpark post unless Fredrick provided it, for the same credibility reason as his personal profile.

The files do not yet describe TheSpark's social audience, content pillars or posting voice beyond those rules. The first time this profile is used, ask Fredrick who the company account is for, what it should post about, and how it should sound, then offer him the updated profile text so he can add it to this skill.

## Profile 4: client or other brand

Fredrick runs an agency, so some requests will be for a client. Before writing in a client's voice, collect the brand name, its audience, three to five content pillars, voice and tone (with one example post they like, if possible), the platforms they use, and any words, claims or topics they forbid. Keep that profile in the conversation rather than in this skill, because client details should not sit inside Fredrick's own account skills unless he asks for that.

## Rules every profile shares

All copy follows Fredrick's house prose style, which means loading the `house-prose-style` skill and running its pre-delivery voice check before anything is handed over. His standing rule is that no copy goes out unless it passes that style, so a draft that fails the check is not finished. In particular there are no em dashes or en dashes in any profile, and the stock machine phrases on the house denylist are banned everywhere.

No skill may invent a statistic, a result, a follower count or a platform limit. When a number is needed and has not been provided, ask for it or leave a clearly marked placeholder, since an invented figure is worse than a missing one.

## Updating a profile

When Fredrick asks to update a profile, or when you learn something new about a voice (such as TheSpark's audience on first use), write the revised profile section out in full in your reply and tell him it needs to be pasted into this skill's SKILL.md and re-uploaded, because skills on claude.ai cannot edit themselves. Inside an EvoNexus workspace you may also save the update to `workspace/social/[C] social-context.md`.
