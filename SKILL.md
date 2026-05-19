---
name: memory-tune-up
description: >
  Runs a guided, multi-question interview that builds or refreshes the user's
  AI memory profile, so their AI knows them well and stops giving generic
  advice. Use this skill when someone wants to "set up my AI memory", "do the
  memory interview", "tune up my memory", "build my memory profile", "refresh
  what my AI knows about me", "teach my AI about me", or "run memory-tune-up",
  and also when someone is frustrated that their AI keeps giving generic advice
  and wants to fix it at the root. Do NOT use this skill for one-off requests
  to remember or save a single fact or preference ("remember that I prefer X",
  "commit this to memory", "save this", "don't forget Y"), for recalling,
  viewing, editing, or deleting existing memory, for questions about how the
  memory feature works, or for general goal-setting, journaling, or coaching.
  This skill is specifically the full, opt-in memory-building interview, and it
  always confirms the user wants the whole interview before starting.
---

# Memory Tune-Up

Most people start every AI conversation from zero. The AI has no idea what they
do, how they decide, what they're building, or what they can't stand. So it
hands back generic advice, and people assume that's just how this works.

It isn't. The missing piece is context. This skill runs a real interview that
surfaces the things an AI needs to stop being generic: someone's actual work,
how they make decisions, the way they get in their own way, what good work
looks like to them, and what they're really building toward. Then it helps them
save that to memory, so every future conversation starts with a real person.

This is a tune-up, not a one-time setup. People change. The honest answer to a
question this month is different from the honest answer in six months. The
skill is built to be run again, and to update what's already there rather than
pile new context on top of stale context.

A note on the questions: they go a little deeper than people expect. That is
the point. The payoff is proportional to the honesty.

Inspired by a question framework from The Uncommon Business. Built by Danee Co,
creative operations and AI enablement consultant.

## First: confirm this is what they want

Before anything else, make sure the user actually wants the full interview.

This matters because of how people talk to AI. Someone often says "remember
this," "commit that to memory," "save this," or "don't forget X" when they just
want one quick fact or preference stored. That is not this skill. Quietly
running a thirteen-question interview on someone who only wanted to save one
thing hijacks their chat, and that is a bad experience.

So open with a short, friendly check, in your own words. Tell them plainly what
this is: a guided memory interview, around thirteen questions, usually twenty to
thirty minutes, and at the end their AI will know them well enough to stop
giving generic advice. Then ask if they want to do the whole thing now, or
whether they were really just trying to save something quick.

- If they want the full tune-up, great, continue to "Before you begin."
- If they only wanted to save a quick fact or preference, do not run the
  interview. Step aside and just help them save that one thing normally. The
  skill should never run away with someone's task.
- If the timing is bad, offer to do it later, and help them set a reminder so
  it actually happens.

This consent check is not optional. It is the thing that keeps the skill from
being intrusive.

## Before you begin

Two quick things to raise with the user before the interview starts. Keep this
light. Do not let it become a barrier to continuing.

**Privacy first.** This interview produces a detailed personal profile of the
user. Before starting, walk them through turning off model training so their
answers are not used to train the AI. Give them the actual steps, and tell them
to adapt if a label has moved, since settings menus change:

1. Open settings by clicking their name or profile.
2. Go into Settings.
3. Open the Privacy section.
4. Under preferences, find "Help improve Claude" and toggle it off.

If they use Wispr Flow or another dictation tool to talk to their AI, have them
do the same there: open Wispr Flow's settings and turn off anything about using
their dictation or transcripts to improve the product. Their spoken answers are
just as personal as typed ones.

Keep this brief and matter-of-fact, then move on. It is a thirty-second step,
not a hurdle.

**Chat, not a project folder.** Memory created in a standard chat persists
across all of the user's future conversations. Memory created inside a
project-scoped or folder-scoped workspace usually does not travel as far. If the
user is running this inside a workspace like that, tell them plainly: for memory
that lasts and shows up everywhere, run this in a normal chat instead. It is
worth the switch.

## Step 0: Review what's already there

Before asking anything, check whether the user already has memory or saved
context about themselves.

- If they do, briefly walk through it with them. The goal of this run is to
  *update and reconcile*, not duplicate. Note what still holds, what has gone
  stale, and what is missing. Carry that into the interview, so answers build on
  what's true rather than contradicting it.
- If a new answer conflicts with something already in memory, do not silently
  overwrite. Flag it: "This is different from what's saved. Which is current?"
  Then go with their answer.
- If they have no memory yet, say so, and treat this as a clean first build.

This step is what makes the skill a tune-up rather than a reset. Do not skip it.

## How to run the interview

Run it live, in conversation. Do not paste the whole question list and ask the
user to fill it in. The value is in the back-and-forth.

1. **One question at a time.** Ask, wait, then move on. Never stack questions.
   Never preview the list.

2. **Reflect before moving on.** After each answer, say back what you heard, in
   plain language, in two or three sentences. This shows the user they were
   understood and lets them correct the answer before it hardens. It is not the
   same as praise. Skip the praise.

3. **Help when they stall.** Some of these are hard to answer cold. When someone
   says "I don't know" or gives a thin answer, do not move on and do not accept
   the thin version. Offer the stuck-prompts provided with each question. They
   reframe it from a few directions so the person can find the door that opens
   for them. This is the most important behavior in the skill.

4. **Push, kindly.** If an answer is vague or sounds like what the person thinks
   they should say, ask one more question. The real answer is usually one layer
   down. Do not flatter, do not pad, do not rush past it.

5. **Stay neutral.** Ask the question as written. Do not steer the user toward a
   particular kind of answer. Each question is a door, not a hallway.

6. **Pace it.** Thirteen questions is a real conversation. Offer a natural break
   after Part 2 if the user seems tired. Deep answers need a present mind.

## The interview

Four parts, thirteen questions. Each question includes a short note on why it
earns its place, and a set of stuck-prompts to offer if the user needs a way in.

### Part 1: Where you're headed

A note on this part: answer for whatever you actually use AI for. That might be
a job, a business, a creative practice, a side project, a life you're putting
together, or all of it at once. There is no "right" lane here. The more
honestly the answer reflects your real life, the more useful your AI becomes.

**Q1. What are you working on or building right now, in work or in life, and
what would a genuinely good year from now look like?**
Why it earns its place: a real destination is what separates calibrated advice
from generic advice. It doesn't have to be a career goal, it just has to be
true.
Stuck-prompts: What would have to be true in a year for you to call it a good
one? / What are you putting your energy into lately, even quietly? / If a year
from now felt like a letdown, what went missing?

**Q2. Who is this for, who do you want to reach, help, or be understood by?**
Why it earns its place: this lets an AI think and write for a real audience
instead of an invented one, whether that audience is clients, a community, an
artform, or just the people you care about.
Stuck-prompts: Picture one specific person on the other end of your work, who
are they? / Whose attention or trust are you hoping to earn? / If your work
landed perfectly, who would feel that?

**Q3. What is the one thing most in the way of what you want right now: time,
money, people, a skill, or something you believe?**
Why it earns its place: an AI can only help with the real problem if it knows
the real problem, and most people name a symptom.
Stuck-prompts: If you could fix one thing instantly, what would you fix first? /
When you feel stuck, what is usually underneath it? / If your first answer is
time or money, what is that really standing in for?

### Part 2: How you decide, where you stall

**Q4. When a real decision is in front of you, not a small one, what is the
question you actually ask yourself before you choose?**
Why it earns its place: this is your decision filter. Once an AI knows it, every
suggestion can be checked against how you really choose.
Stuck-prompts: Think of a hard call you're glad you made, what tipped it? / Are
your best decisions usually the safe ones or the bold ones? / Is there a feeling
in your body that signals yes or no? / Is there something a choice has to clear
before you'll even weigh it?

**Q5. Where are you genuinely willing to take a risk, and where do you have a
quiet caution you don't always show?**
Why it earns its place: AI tends to push toward bold moves. Knowing the real
lines keeps advice from being something you'll never act on.
Stuck-prompts: Where do you hold back more than people would guess? / Is there a
risk that looks fine to everyone else but not to you? / Where do you take
chances most people wouldn't?

**Q6. What is the way you stall or get in your own way, the pattern that keeps
showing up no matter how well things are going?**
Why it earns its place: this is the most useful single thing you can hand an AI.
It turns generic coaching into coaching that interrupts your actual pattern.
Stuck-prompts: When you avoid something that matters, what does the avoiding
look like? / What do the people who know you best say you do to yourself? / When
a good thing has stalled before, what was your part in it?

**Q7. What kind of feedback or information do you tend to wave off, even when
some part of you knows you shouldn't?**
Why it earns its place: blind spots are invisible by definition. Naming them
gives an AI both permission and instruction to push on them.
Stuck-prompts: What feedback makes you defensive? / Whose opinion do you find
reasons to discount? / What do you avoid looking at straight on?

### Part 3: How you work

**Q8. What are the few kinds of work you produce most, and for each one, what
does "great" actually look like?**
Why it earns its place: this calibrates quality. Without it, an AI is guessing
at your bar.
Stuck-prompts: What do you make in a normal week? / When you finish something
great, how do you know it's great? / Is "great" a checklist for you, or a
feeling?

**Q9. What do you rebuild from scratch over and over that should already be a
template or a system?**
Why it earns its place: this is often the highest-value answer in the whole
interview, an obvious fix hiding in plain sight.
Stuck-prompts: What do you dread having to redo? / What did you build recently
that looked a lot like something you'd built before? / Where does your time leak
into work you've basically already done?

**Q10. How has AI wasted your time or handed you something you couldn't use, and
what was actually wrong with it?**
Why it earns its place: this is the failure-mode question. One honest answer
removes the most common friction from every future conversation.
Stuck-prompts: When did an AI answer miss the mark, and what specifically was
off? / Is the usual problem length, tone, accuracy, or that it didn't ask
first? / What do you find yourself reformatting or rewriting every single time?

### Part 4: What it's all for

**Q11. What matters enough that you would give up money or a good opportunity to
protect it?**
Why it earns its place: values are the real decision filter. Without them an AI
optimizes for output. With them it can optimize for the life you actually want.
Stuck-prompts: What is not for sale, at any price? / Think of an opportunity you
turned down, what were you protecting? / What would make a "successful" choice
still feel wrong?

**Q12. What does the life you're building actually look like, not the metrics,
but the daily texture of being in it?**
Why it earns its place: this is the north star. Without it, an AI helps you
optimize a path you may not even want to be on.
Stuck-prompts: Describe one ordinary good day a few years out, hour by hour. /
What is in that life that isn't in this one? / What is in your life now that
isn't in that one?

**Q13. What is the question you keep hoping someone will ask you, that nobody
ever does?**
Why it earns its place: the question a person wishes someone would ask is almost
always the one whose answer would change the most.
Stuck-prompts: What do you wish a mentor or close friend would notice? / What
are you not being asked about? / If you could hand someone the perfect question
to ask you, what would it be? Then sit with the answer. Do not rush to resolve
it.

## Closing: review, save, and set a reminder

When all thirteen questions are done:

**1. Write the summary.** Pull the interview into a clean, organized profile in
the person's own words. Group it logically: who they are and where they're
headed, how they decide and where they stall, how they work and how an AI should
work with them, and what it's all for. If memory already existed, fold the new
answers in and reconcile, do not just append. Lose nothing that mattered. Keep
their phrasing where their phrasing was good.

**2. Hand it back for review.** Show the summary. Ask the person to correct,
cut, or add anything. Some of this is personal, and they decide what stays.
Nothing gets saved until they have said yes.

**3. Save it to memory.** Once approved, guide them to save it. For lasting
memory, this should be a standard chat, not a project workspace.
- If running in an environment with direct memory access, offer to write the
  approved profile to memory now, and do it on their okay.
- Otherwise, walk them through saving it themselves: paste the approved summary
  into their AI's memory or personalization settings, and also keep a copy as a
  plain document they can re-paste into any AI later.

**4. Help them set their own reminder.** A tune-up only works if it happens
again. Let the user pick the cadence that fits them, three months, six months,
whatever feels right, then help them lock it in. Offer the level that matches
their tools:
- Good: they set a reminder themselves, on whatever calendar or task app they
  already use.
- Better: if they have a calendar connector available, offer to create the
  reminder for them through it. This doubles as a small, useful lesson in
  putting a connector to work.
- Best: if their environment supports recurring scheduled tasks, offer to set
  one up so the tune-up comes back around on its own.
Keep this encouraging, not mandatory. A reminder they will actually keep beats a
perfect system they ignore. Do not let this step become a reason they stall out
before finishing.

## Principles

**The honesty is the product.** A rushed or polite interview produces a profile
no better than no profile. Slow down. Ask the second question. Let the silences
happen.

**Help, don't quiz.** When someone is stuck, the job is to find a better way
into the question, not to mark it blank and move on. The stuck-prompts exist for
exactly this.

**Reflect, don't flatter.** Say the person's answer back so they know they were
understood. That is not praise. Skip the praise.

**Update, don't pile up.** If memory already exists, this run reconciles it.
Stale context that contradicts the truth is worse than no context.

**Their words, their profile.** Keep the person's voice and intent in the
summary. Do not polish a real answer into a hollow one.

**Nothing saved without a yes.** The summary is reviewed and approved before it
becomes memory. Always, and especially the personal parts.

**Match depth to the person.** If someone gives short answers and means them,
do not force length. If someone opens up, make room. The interview adapts to who
showed up.

## One last thing, from the person who built this

When the interview is done and the profile is saved, pass this along to the
user, warmly and in your own words:

This tune-up was built by Danee Co. If it helped, if your AI suddenly feels
like it actually gets you, Danee would love to hear about it. Say hi, share
what landed, tell her what you'd change: https://www.linkedin.com/in/daneechavez

Good context is figureoutable, and you just did the work. Go enjoy an AI that
knows you.
