# Motivation

The systems and tools I've developed and share here are guided by two big ideas for me: 1) standard productivity advice and tools are an uneasy fit with open-ended research work

## Standard productivity advice and tools are an uneasy fit with open-ended research work

The central productivity problem to solve for PhD work is not "How can I maximize my production of well-defined outputs", but "[[In light of my unique environmental context, how can I maximize the depth and breadth of conceptual focus required for genuine new insights for my field of study]]?" 

Some unique features of this problem include that:
- Progress towards insight appears to be reliably nonlinear with respect to time and effort, and thus is hard to neatly break down into concrete and stable schedules or outputs. I deeply resonate with how Andy Matuschak describes that [here](https://andymatuschak.org/stillness/) and [here](https://blog.andymatuschak.org/post/159979927467/satisfaction-and-progress-in-open-ended-work). I also resonate with this picture of how research typically goes:
	- ![[Pasted image 20251016105039.png]]
- Progress towards insight seems to benefit greatly from long blocks of focus, and/or minimal context switching. This has sometimes been described in terms of the [Maker vs. Manager schedule](https://www.paulgraham.com/makersschedule.html). You can also see lots of neat examples of this. 

I often experience tension between this central problem and the attendant demands that surround PhD work, both professionally (e.g., teaching, coursework, concrete milestones, grant and paper deadlines) and personally (we still have lives! and sometimes other jobs alongside our PhD work!). The latter set of issues are often quite amenable to standard productivity advice and tools, like [[Getting Things Done (GTD)]], and [[Gantt Charts]], but often don't *quite* fit with the problem of focus for insight described above.

So that's the first big ideaI I've had to solve. How to adapt some good ideas from standard productivity advice (e.g., estimation, scheduling) to the open-ended nature of research work.

## People (and environments) vary a lot, and this matters for what works productivity-wise!

The other big idea is individual and environmental variation. People are very different from each other, and they are part of situations that are also very different from each other. So there isn't really a one-size-fits-all: you kinda have to experiment and/or adapt.

This is one reason I advocate for experimenting with tools like Obsidian. They're very powerful and can implement a wide-range of systems and practices. And Obsidian is free! :) You're also probably going to need lots of other physical tools, etc., so why not *not* pay for Notion :)
# Some things that have worked for me

The following are some patterns of tools, systems, and/or workflows that I've found useful for navigating this tension.

## Extending and maximizing conceptual focus over time with tools/notes

Drawing on ideas from [distributed cognition]([url](https://en.wikipedia.org/wiki/Distributed_cognition)) and the "extended mind", I've had very good success extending and maximizing conceptual focus over time (despite distractions and interruptions inherent to being a TTK faculty + father to 2 young children + other responsibilities) with tools and notes.

Here's a preview of a discussion of this in INST803 (which I think I'll teach again!): https://joelchan.github.io/INST802-SP26/2_Lecture-Notes/Week-2---Process-Foundations,-Interdisciplinarity

I implement a hypertext notetaking system in a mixture of [Roam]([url](https://roamresearch.com/)) and Obsidian, using a [Discourse Graph](https://discoursegraphs.com/) structure. 
I wrote about the roots of this approach in [this piece]([url](https://oasislab.pubpub.org/pub/54t0y9mk/release/3)) a few years back, and and recently also described these practices in more detail in [this paper]([url](https://dl.acm.org/doi/abs/10.1145/3654777.3676338)) I co-authored on hypertext note-taking practices for scholars.

Basic ideas:
- Try to orient projects towards scientific goals
- Make the goals/questions things that I can add to or draw from over time (using hypertext)
- Take notes to enable me to preserve context over time (or at least to make recontextualization way faster!)

This structure allows me to maintain and deepen threads of thinking over time, and not start from scratch when I have the time to focus or pick up research threads.

You can [implement]([url](https://discoursegraphs.com/docs/obsidian/getting-started)) a lot of this in [Obsidian]([url](https://obsidian.md/)) (hence this vault!) which is free and has a very large and thriving community of academic users (including many in the INFO College at UMD!). 

## [[A regular practice of reflection at multiple scales]]

I took inspiration from Robert Talbert's series on GTD for academics (see [this post](https://intentionalacademia.substack.com/p/the-weekly-review), for example), which introduced me to the idea of Annual, Trimesterly, and Weekly Reviews (and mostly let the GTD stuff fall by the wayside, and as you can see in the example in [[Week of 2025-09-01]], my practices differ QUITE a bit). But the core idea of taking the time to step back and reorient and reflect is still there. Turns out this reflection approach is a pretty common best practice, showing up in best practices in Jessica Calarco's book, which is drawn from wisdom from the [NCFDD](https://www.ncfdd.org/.)

I've found that this helps me:
- Stay oriented towards what I actually care about, and enable me to make more aligned decisions on a day to day basis
- Figure out what is working or not working and tweak accordingly
	- E.g., split exercise into morning and evening, write on paper at breakfast to ground myself, be outside more, etc. etc.

I've included here examples of review at the following levels:
- Daily (daily notes in `00 Commonplace`)
- Weekly (example: [[Week of 2025-09-01]])
- Trimesterly and Annually (just templates for now in [[Trimesterly Review]] and [[Annual Review]]), which are guided by documents like [[My Mission and Values]] and [[My Goals]])

## [[Coordinating my goals and tasks with my actual schedule]]

From here we start to get into more experimental territory, where I have things that work kinda well, but I wouldn't say they are amazing.

I found with GTD that I had a lot of trouble estimating what was a reasonable ask for myself for a given week. I experimented with [UseMotion]([url](https://www.usemotion.com/)) for about a year as my general task management system because it has a default process for putting my commitments and tasks on my calendar, like a digital calendar version of the "sands and stones" activity.

I never really followed the actual scheduling, though: because Motion doesn't know about my energy levels and priorities at a more granular level. But I did like the ability to visually see my commitments, which helped me say no (see next section).
Time boxing and Toggl also kind of help me not "scope creep" the time I spend on things that are not on my critical path.

I've now integrated these practices into an AI-assisted hybrid time-tracking + calendar blocking + interstitial journaling based system that runs through Obsidian (loosely inspired by the above ideas + [this system]([url](https://www.chatprd.ai/how-i-ai/teresa-torres-claude-code-obsdian-task-management))). It's pretty complicated and is probably the most functional system I've created so far (most weeks now I know how much capacity I have, and can estimate the time load required to say yes/no to common tasks, which is a big win), but it's probably too complicated for most people and too messy to share atm.

As a foil to this, I give you this dead-simple approach that runs on similar principles around calendar-todo-journaling integration (which I don't use, but seems to work well for many successful people): https://jeffhuang.com/productivity_text_file/

## Clear rules and procedures for saying no to things that I actually follow

I've tried, with varying success:
- A "no committee"
- A "cooldown" rule: don't say yes until at least N time has passed, and I've taken the time
- The hell yeah or nah rule

Big upgrades came from:
- Therapy
- Explicitly articulating and orienting to my priorities (which falls out of [[A regular practice of reflection at multiple scales]])
- Time estimation work to at least order of magnitude estimate what I'm saying yes to - but more generally just [[Coordinating my goals and tasks with my actual schedule]]

These seemed to be the higher order blockers and preconditions for other strategies to work (e.g., what counts as "hell yeah"?)

## Mechanical boundaries to reduce reliance on willpower

Inspired in part by Matt Might's ["path of least resistance" methodology](https://matt.might.net/articles/productivity-tips-hints-hacks-tricks-for-grad-students-academics/#philosophy), I've had some degree of success recently with a set of supplemental mechanical boundaries that add friction or blockers to undesired behavior. 

I use [Cold Turkey](https://getcoldturkey.com/) to set some friction during the day, and Frozen Turkey to reduce the incidence of late nights of work (takes away the option, no need to decide to go to bed)
And a [customized delay timer](https://github.com/joelchan/social-delay-extension).

Works best when I pair with these with the above strategies, especially positive ones (e.g., use the friction as a trigger to go for a walk instead).
