# mod-702-people-management: People Management Basics

**Level**: team-lead-learning
**Duration**: 30-50 hours
**Prerequisites**: senior-engineer or senior-architect level

## Overview

This module is about the first-line people-management work: 1-1s,
feedback, performance management, career conversations, and the
difficult conversations that sit on top of all of them. It is not
about HR process, and it is not about leadership style. It is about
the small number of recurring conversations you have with your
reports that collectively determine whether they grow, whether they
stay, and whether they tell you the truth about what is going on in
the team.

For an AI Infrastructure Team Lead, this work has a specific shape.
Your reports are typically deep specialists — inference engineers,
performance engineers, AI SREs, platform engineers — whose careers
move on a narrower ladder than a generic backend engineer's, whose
on-call load is heavier than most, and whose market value is
volatile enough that retention is itself a management problem. The
generic management skills still apply; the distributions are
different.

This module takes the position — argued at length in the lecture
notes — that first-line people management is a set of learnable
skills, not an aptitude. Most engineers who fail in their first
management role fail in predictable ways: they avoid hard
conversations until they become harder, they treat 1-1s as optional
when busy, they default to fixing the problem themselves instead of
growing the report. You will spend ~30-50 hours here: reading,
practicing the conversations on your own team or a case-study team,
and completing five exercises that force you to make concrete
calls. By the end, you should be able to run the full cycle — 1-1,
feedback, performance, career, difficult conversation — on a real
team and defend the way you did it.

## Learning Objectives

By the end of this module you will be able to:

- **1-1s as the foundational ritual.** Run weekly or bi-weekly 1-1s
  that are the report's time, not yours; set an agenda convention
  that surfaces what is actually going on; and recognize when a 1-1
  pattern is drifting into status-reporting theater.
- **Giving feedback timely.** Give specific, behavioral feedback at
  the next 1-1 rather than stockpiling it for performance review;
  calibrate the escalation from an offhand remark to a sit-down
  conversation; and receive feedback from your reports without
  getting defensive.
- **Performance management.** Notice the gap early, name it clearly
  with specific examples, set concrete expectations for improvement,
  check in on a known cadence, and escalate to HR or a formal PIP
  when the gap does not close.
- **Career growth conversations.** Separate the "are you meeting the
  current bar" conversation from the "where do you want to go"
  conversation; explore paths honestly, including paths that lead
  the report off your team; and translate stated aspirations into
  the next concrete growth assignment.
- **Difficult conversations.** Handle the conversations most
  managers avoid — withheld feedback, interpersonal conflict,
  compensation disappointment, scope disputes with peers, personal
  difficulties, departures — with structure rather than improvisation.

These objectives are not independent. The hardest version of this
work is not any single conversation; it is the cumulative discipline
of running them all, every week, on every report, when you are
tired and the quarter is slipping and the pager just went off.

## Why this module exists at this level

You have passed through senior IC or senior architect, which means
you have been *inside* a manager-report relationship for long
enough to have opinions about how yours was run. That experience
is useful, but it is not the same as doing the work. As a report
you saw one side of maybe three or four conversations a year. As a
manager you will run those same conversations dozens of times, and
you will run them with people whose situations do not match yours.

The shift is uncomfortable in a specific way. Most engineers are
trained to optimize systems: define the inputs, define the outputs,
build the thing that maps between them. People management does
not reward that reflex. The inputs — a report's career
aspirations, an unspoken grievance, an emerging conflict with a
peer team, a quiet burnout — arrive in unstructured form and
require active attention to notice. The outputs — a report who
grew into the next level, a team member who left well instead of
badly, a performance conversation that saved a career instead of
ending one — are slow and noisy signals that resist the kind of
feedback loop engineers prefer. You will often not know, in the
moment, whether you did the right thing.

The lecture notes argue that first-line management is a set of
learnable skills, not a personality. That is the framing to carry
through the module. Every conversation choice should be judged
against the question: "Did I treat this as a skill I am
practicing, or as something I got away with?"

## What this module covers

The module is organized around five kinds of recurring work with
your reports. Each one answers a different structural problem.

**1-1s** are the recurring cadence that makes every other kind of
work possible. The goal is a reliable, protected channel where
the report brings what is actually going on and the manager
listens, asks questions, and gives feedback when relevant. Run
badly, they decay into status updates and the manager loses
line-of-sight to the team; run well, they surface problems
weeks or months before those problems would otherwise become
visible. The lecture notes draw on the pattern described in Grove
(*High Output Management*) and Fournier (*The Manager's Path*) for
how a good 1-1 looks over time.

**Feedback** is the day-to-day delivery mechanism for everything
else. Withheld feedback compounds — the report does not know
they need to change, the gap widens, and the eventual
conversation is harder than it needed to be. The discipline is
feedback at the next 1-1, not feedback at performance review.
The lecture notes use Scott's (*Radical Candor*) framing of care
plus directness, and spend time on the specific failure mode of
being indirect in the name of kindness.

**Performance management** is the structured work of closing a
gap between what a report is delivering and what the role
requires. Most new managers fear this conversation and therefore
delay it, which guarantees it gets worse. The pattern is the
same every time: notice the gap, name it clearly with specific
examples, set concrete expectations with timelines, check in on
a known cadence, document privately, and escalate to HR or a
formal plan if the gap does not close. Most performance problems
caught and addressed early resolve; most avoided become eventual
departures.

**Career growth** is the conversation that asks a different
question than performance. Performance asks "are you meeting the
current bar?" Career asks "where do you want to go, and how do
we get you there?" These conversations happen at a slower cadence
than feedback but are no less important. For AI-infra engineers,
the career-path question is especially open-ended: the next step
is sometimes the next level on the IC ladder, sometimes a shift
toward research-adjacent work, sometimes management, sometimes a
move to ML Engineering or AI Engineering. Honest exploration,
including paths off your team, is the standard — and the report
notices when it is not.

**Difficult conversations** is the catch-all for the conversations
most managers avoid. The withheld piece of feedback that has been
sitting for three weeks. The two reports who stopped talking to
each other after the incident. The report whose compensation
expectation does not match what the market or the company can
offer. The scope dispute with a peer manager. The report going
through a personal difficulty that is affecting work. The
resignation, handled well. The lecture notes draw on Patterson et
al. (*Crucial Conversations*) and Hogan (*Resilient Management*)
for how to structure these; the exercises push you to run them.

The lecture notes go deeper on each. The exercises push you to
apply the framing to a specific scenario — your real team if you
have one, or a case-study team if you do not.

## Module Structure

- **README (this file).** Scope, objectives, and how to work through
  the module.
- **`lecture-notes/01-overview.md`.** The core argument: what is
  actually different about people management, the five core skills,
  the 1-1 as the foundational ritual, and the structure of the
  harder conversations. Read this first and re-read it after the
  exercises; it reads differently once you have tried to have one
  of these conversations in anger.
- **`exercises/exercise-01-case-study.md`.** A strategic case-study
  exercise. You walk into a team with a specific people-management
  problem — a drifting performance situation, a departure risk, a
  misaligned career conversation — diagnose what went wrong, and
  propose how you would run it from here.
- **`exercises/exercise-02-strategy-memo.md`.** A short written memo
  justifying a specific people-management decision — a promotion, a
  performance escalation, a scope change, a role split — to a
  skeptical stakeholder. Forces precision about tradeoffs.
- **`exercises/exercise-03-stakeholder-mapping.md`.** Maps the
  people inside and outside the team whose expectations your
  people-management decisions have to account for — your manager,
  HR, peer managers, the report themselves, and the rest of the
  team who are watching how you handle the situation.
- **`exercises/exercise-04-roadmap.md`.** A quarter-to-year plan
  for building the growth, retention, and succession capacity of
  the team you lead. Change management applied to the people side
  of the team, not the roadmap side.
- **`exercises/exercise-05-presentation.md`.** A short presentation
  — built for a peer review session — that defends your handling
  of a people-management decision to another team lead. The ask is
  to be concrete and defensible, not comprehensive.
- **`quiz.md`.** Strategic-thinking questions to test your
  framing. They do not have single right answers; they test
  whether you can defend the call you made.
- **`resources.md`.** Frameworks and further reading. Treat these as
  pointers, not a reading list — pick what fits the problem in
  front of you.

The module is designed to be worked in order. Lecture first, then
the exercises in sequence (01 sets up the scenario the later
exercises build on), then the quiz. Expect the exercises to take
longer than the lecture; most of the learning is in the application.

## How to work through this module

The module is sized at 30-50 hours. That range is wide on purpose.
If you already lead a team and have real conversations to run this
quarter — a performance situation that needs naming, a report who
wants a promotion case, a peer dispute to mediate — you will be at
the low end; you are mostly converting intuition into explicit
practice. If you are approaching this as a senior IC or architect
getting ready for a lead role and you are using a case-study team,
plan for the high end — you have to build the reflexes as you go.

A workable rhythm:

1. **Read the lecture notes once.** Do not stop to take extensive
   notes; aim for the shape of the argument and the five core
   skills.
2. **Write down the state of the people side of a team you know.**
   Real or case-study. For each report (or imagined report), write
   one paragraph covering: what they are good at, where the gap is,
   what they have said about their career, and the last piece of
   feedback you gave them. If you cannot answer any of those for a
   real report, that is itself the finding.
3. **Do Exercise 01.** Diagnose what is going wrong in the
   case-study team's people-management situation. Do not propose
   fixes yet. The goal is diagnosis, and diagnosis is harder than
   it looks.
4. **Do Exercises 02-04 in sequence.** Each one tightens the
   practice: the memo forces you to justify a people-management
   decision in writing, the stakeholder map forces you to account
   for who the decision affects beyond the report, the roadmap
   forces you to think about the team's growth and retention over
   a longer horizon than the current conversation.
5. **Do Exercise 05.** Defend the decision to a peer. If you cannot
   get a real peer to review it, write the defense anyway — the
   writing surfaces the weak points, especially the ones you would
   otherwise hand-wave past.
6. **Re-read the lecture notes.** The second pass is where the
   framing actually sticks. If the sections on performance
   management and difficult conversations now feel obvious, that
   is the point.
7. **Do the quiz.** Treat the questions as prompts for a short
   written answer each. The quiz is a self-check on whether you
   can defend your people-management choices, not a knowledge
   test.

Resist the temptation to do this module "in theory" without
specific people in mind. The framings only land when they are
applied to concrete reports with specific strengths, gaps, and
aspirations. If you do not have reports of your own, borrow a
team — ask another lead if you can anonymize one of their current
situations and work it through the exercises.

## AI-infra specific angles to watch for

The lecture notes cover first-line people management as a general
skill. A few places where the AI-infra context changes the defaults:

**Deep specialists need a wider conversation about growth than
generalists.** Your reports are often inference engineers, kernel
and GPU specialists, performance engineers, or AI SREs whose next
step is not obvious from the standard IC ladder. The career
conversation has to range further: the next level on the ladder,
a lateral move into ML Engineering or AI Engineering, a shift
toward research-adjacent work, or management. Pitching only
in-team promotions reads as self-interested, and the report
notices. Module 00 is the reference for which sibling orgs are
realistic destinations and what the handoff shape is in each
direction.

**On-call load is a people-management problem, not just an
operational one.** AI-infra on-call is louder and more bursty than
typical web-service on-call — a single bad rollout or capacity
miss can page the full rotation. The people-management
consequences — accumulating fatigue, resentment about rotation
fairness, quiet burnout in the engineers who absorb the hardest
pages — show up in 1-1s weeks before they show up in operational
metrics. Treat on-call sentiment as a standing 1-1 topic, not
something you check in on quarterly.

**Retention is itself a management problem, not a comp problem.**
AI-infra engineers often face market pressure that outstrips what
any single company can match on compensation alone. The levers
that actually move retention — interesting work, growth, respect,
a manager who notices — are people-management levers. The career
conversation and the growth-assignment conversation are where most
of this gets decided; a comp cycle rarely saves a report who had
already quietly checked out two quarters earlier.

**Blast radius per report is unusually high.** A small number of
specialists own the inference stack, the training platform, the
GPU scheduling, the serving fleet. One of your reports losing
engagement, or quietly working around a performance issue they
should have raised, or leaving without a knowledge transfer, has
larger downstream consequences than the same event on a product
team. This is not a reason to over-manage; it is a reason to run
the basics — 1-1s, feedback, succession thinking — with unusual
consistency.

**Peer-manager relationships carry an unusual amount of your
reports' growth.** Many AI-infra engineers grow more through
partnership with their counterparts in ML Engineering or AI
Engineering than through internal promotion. The quality of your
relationships with peer managers in those orgs determines the
quality of the stretch assignments you can offer your reports.
mod-704 covers the cross-team coordination work directly; the
people-management angle is that stretch assignments are among the
most valuable things you give a report, and most of them cross
org boundaries.

Each of these gets picked up in more detail in the other modules
in this track, especially mod-701 (operating cadence, which is
where on-call sentiment surfaces), mod-704 (cross-team
coordination, which is where stretch assignments get negotiated),
and mod-705 (hiring and onboarding, which is the top of the
retention funnel). Keep the connections in mind as you work
through mod-702; the people-management practice you build here
runs on top of the operating model you designed in mod-701.

## Prerequisites and companion modules

This module assumes you have operated as a senior IC or senior
architect, which means:

- You have been in at least one manager-report relationship for
  long enough to have opinions about how it was run. If you have
  never had a 1-1 or received a piece of hard feedback, the
  exercises will feel abstract.
- You have given technical feedback to another engineer in a code
  review or a design review. The feedback exercises build on the
  reflex of "specific, behavioral, actionable" that code review
  already taught you.
- You have been in the room for at least one difficult work
  conversation — a project cancellation, a reorg, a departure —
  and formed a view about what the manager running it did well or
  poorly. The difficult-conversation exercises draw on that memory.

Within the team-lead track, this module is best worked after
mod-701, which sets up the operating cadence (the 1-1 is one of
its rituals), and before mod-705, which depends on your having
decided how you develop and retain the reports you already have
before you decide how to bring new ones in.

Outside the track:

- [Module 00: Your Relationship to the Model](../00-your-relationship-to-the-model/README.md)
  is the required orientation. If you have not done it, start
  there; the career-conversation work in this module assumes you
  know which sibling orgs your reports might realistically grow
  into.
- The senior-architect-learning repo's executive-leadership
  modules go deeper on the organizational-politics side of people
  management — compensation strategy, promotion calibration across
  teams, managing managers. If your first-line work in this module
  starts bumping into decisions that are not yours to make, those
  modules are the next layer.

## What success looks like at the end of the module

You should finish the module with four concrete artifacts:

1. A **written 1-1 practice** for the team you used — your agenda
   convention, your note-taking approach, the questions you default
   to, and the signals you watch for when a 1-1 is decaying.
2. A **worked example** of a performance conversation you ran or
   would run — the gap, the specific examples, the expectations,
   the cadence, the escalation path — at enough detail that another
   lead could pressure-test it.
3. A **career-conversation template** adapted to the shape of
   AI-infra careers — the ladder paths, the lateral paths into
   sibling orgs, and the growth-assignment inventory you would
   draw from for each.
4. A **set of signals** — not metrics, signals — you will watch
   for across your reports to catch disengagement, burnout, and
   departure risk before they become unrecoverable.

If any of those four is missing or hand-wavy, you are not done.
The quiz is designed to catch the most common gaps.

Success is not "I have mastered people management." Every new
report, every new situation, every new conflict is a new instance
of the same skill applied under different constraints. Success is
"I can run the basic cycle on purpose, defend the choices I made
in it, and recognize when a conversation has drifted away from
what the report actually needed."

## Before you start

Pick the reports you will use for the exercises before you open
the lecture notes. If you lead a team, that is your current team;
if you do not, borrow one — anonymize three to five engineers from
a team you know. For each one, write one paragraph: what they are
good at, what the gap is, what they have said about their career,
and the last piece of real feedback they received. Keep the
paragraphs beside you as you read; the lecture will land harder
if you are reading it against specific people. Then open
[`lecture-notes/01-overview.md`](lecture-notes/01-overview.md) and
begin.
