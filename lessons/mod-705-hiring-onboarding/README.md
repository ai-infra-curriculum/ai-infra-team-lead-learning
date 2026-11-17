# mod-705-hiring-onboarding: Hiring + Onboarding

**Level**: team-lead-learning
**Duration**: 30-50 hours
**Prerequisites**: senior-engineer or senior-architect level

## Overview

This module is about the work of turning headcount into a team
that can actually carry the load. It is not about writing job
descriptions, and it is not about running a slicker interview
loop. It is about the small number of recurring activities —
role definition, loop design, bar calibration, debrief
discipline, closing, and the 90-day onboarding — that
collectively determine whether a new hire is a force multiplier
or a six-month investment that quietly unwinds.

For an AI Infrastructure Team Lead, the stakes of getting this
right are higher than they are for a generic engineering lead.
Your team's hiring surface is unusually narrow: the candidate
has to be strong on two or more of serving, training-platform,
GPU/hardware operation, and cost — most engineers are strong on
at most one. Your team's onboarding surface is unusually deep:
the new hire has to come up to speed not just on a codebase, but
on a production on-call rotation, a cost model, a governance
trail, and four peer-team handoffs. Hiring badly in this
context does not just cost you a seat; it costs the peer teams
who were waiting on the capacity the seat was supposed to
provide, and it starts the cultural drift that is the hardest
thing in the role to reverse.

This module takes the position — argued at length in the
lecture notes — that hiring and onboarding are a *compounding*
discipline, not a staffing one. The team leads who build the
strongest teams are not the ones who close the most roles; they
are the ones who protect the bar under pressure, run the
debrief so the signal survives, and invest the calendar time in
onboarding that the next quarter's productivity depends on. You
will spend ~30-50 hours here: reading, applying the framings to
a real or case-study team's actual hiring and onboarding
situation, and completing five exercises that force you to make
concrete calls. By the end, you should be able to design a loop
for a specific role on your team, run the debrief that produces
a defensible decision, and build a 90-day plan that gets the
new hire to real ownership.

## Learning Objectives

By the end of this module you will be able to:

- **Role definition and intake.** Translate a capacity gap on
  your team into a role definition — level, domain mix, must-
  have signals, deal-breakers, bar articulation — written in a
  form the recruiter, the loop, and the candidate can all point
  at. A loop running without a written role drifts into "do we
  like this person," and that is where bars decay.
- **Loop design.** Decide what signals the loop covers —
  coding, system design, collaboration, domain depth,
  communication — and which interviewer runs each, with at
  least two interviewers per signal so individual variance does
  not drive the call. For AI-infra roles, calibrate the
  operational-sensibility and domain-depth signals explicitly;
  the serving/training/GPU/cost mix changes which interviewer
  covers which surface.
- **Bar discipline.** Hold the bar when headcount pressure,
  timeline pressure, and personal rapport with a candidate are
  all pushing the other way. Articulate the bar in writing,
  calibrate across interviewers by reading each other's debrief
  notes, and keep skip-level review in reach for borderline
  calls.
- **Debrief and decision.** Run the debrief so each
  interviewer's conclusion is captured *before* discussion,
  specific evidence drives the conversation, and the hiring
  manager carries the decision while staying bound by the
  loop's signal. Recognize the specific failure modes — the
  senior who dominates via authority, the manager who overrides
  weak signal, the drift from "no-hire" to "maybe."
- **Sourcing, closing, and candidate experience.** Find the
  candidates the recruiter would not find; run the close
  conversation (comp, mission, growth path, team) without
  overpromising; and treat the whole candidate experience as a
  recurring signal to the market about what your team is like
  to work with.
- **90-day onboarding.** Build a staged onboarding plan —
  environment and first merge in week 1, paired work and buddy
  through weeks 2-3, a 30-day retro, small end-to-end ownership
  through weeks 5-8, and integration into the on-call rotation
  by week 9-12 — and run the regular check-ins that catch
  drift before the 90-day mark.
- **Early-attrition and integration signals.** Watch for the
  specific signals that a new hire is not integrating — the
  retro that keeps getting rescheduled, the paired work that
  never shifts into solo ownership, the on-call shadow that
  never becomes a primary shift — and intervene before the exit
  interview surfaces the mismatch too late.

These objectives are not independent. The hardest version of
this work is not any single loop or any single onboarding plan;
it is running them well, repeatedly, across multiple roles and
multiple new hires, while the rest of the team's work is also
on your calendar.

## Why this module exists at this level

You have passed through senior IC or senior architect, which
means you have been *inside* at least one hiring loop and at
least one onboarding experience long enough to have opinions
about how it was run. You have interviewed candidates, written
debrief notes, and probably watched a hire you flagged as weak
get made over your objection. You have also been onboarded,
successfully or not, and formed a view about what the team did
or did not do that helped. That experience is useful, but it is
not the same as owning the loop.

The shift is uncomfortable in a specific way. As a senior
engineer you ran interviews inside a loop someone else designed
— you had a slot, a signal to collect, a rubric to use, and the
hiring manager owned the aggregation. The team lead's job is to
*be* the hiring manager. You decide which signals the loop
collects. You own the bar. You run the debrief, make the call,
own the close, and own the onboarding. The hire that works out
is a quiet win on your account; the hire that does not reflects
on your judgment for years.

The information asymmetry also inverts. As an IC in a single
interview slot, you had deep context on the one signal you were
assigned to; as a lead you have less context on any single
45-minute conversation than the interviewer who ran it, but you
have more context on how the full set of signals adds up and on
the team the candidate would be joining. Good hiring is the
discipline of making decisions from that aggregated view —
which signals the loop actually produced, where the evidence is
weak, how the candidate's trajectory maps onto the role — not
from any single interviewer's confidence.

The lecture notes argue that hiring is a *calendar commitment*
and onboarding is a *90-day commitment*, and that leads who
treat either as something you can do on the side eventually
produce teams that reflect that. That is the framing to carry
through the module. Every hiring and onboarding decision should
be judged against the question: "If this hire is still on the
team in two years, is it because the loop caught the right
signals and the onboarding built the right foundation, or
because we got lucky?"

## What this module covers

The module is organized around five kinds of recurring hiring
and onboarding work. Each one answers a different structural
problem.

**Role definition and intake.** Every open seat starts with a
decision about what the team actually needs — a serving
specialist, a training-platform generalist, a strong operator,
a new-grad with upside. The discipline is a written role
definition before the recruiter opens sourcing: level, domain
mix, must-have signals, deal-breakers, and an articulated bar.
The lecture notes argue that the loop drifts in direct
proportion to how vague the role definition is; a loop running
against "senior engineer with ML experience" will produce a
very different pile of offers than one running against "senior
engineer who has owned production serving infrastructure at
scale for at least two years, with a track record of on-call
leadership." The role definition is the thing both the recruiter
and the loop point at when a borderline call comes up.

**Loop design.** A well-designed loop covers five signals —
coding, system design, collaboration, domain depth,
communication — with at least two interviewers per signal to
control for individual variance. The lecture notes go deeper on
what each signal looks like at the level this role requires and
what distinguishes a strong signal from a weak one. For AI-infra
roles, the domain-depth signal is where the loop usually goes
wrong: a generic "systems" interview does not distinguish a
candidate who has lived through a production serving incident
from one who has read about them, and the two are not
interchangeable.

**Bar discipline.** Holding the bar is the single hardest part
of hiring. Every team lead eventually faces the moment where
they want to lower it because the role has been open for four
months, the peer team is waiting on the capacity, and the
borderline candidate in the loop is the best they have seen in
six weeks. Almost every lead who lowers the bar in that moment
regrets it. The patterns that hold the bar up: the bar is in
writing; senior interviewers calibrate periodically by reading
each other's debrief notes; the hiring manager does not
single-handedly decide controversial hires (skip-level review
for borderline cases); and the lead carries the operating
principle that an empty seat is acceptable but a bad hire is
not. This part of the module is harder than it looks on paper;
most of the time pressure to lower the bar is real, and the
case for holding is one you have to make to yourself more often
than to anyone else.

**Debrief and decision.** The debrief is where the loop's signal
becomes a decision. The pattern that works: each interviewer
states their conclusion *before* discussion, in writing, so one
strong voice cannot anchor the room; discussion is on specific
evidence, not feelings; the hiring manager owns the decision
but is bound by the loop's signal; and the default is no-hire —
"maybe" is a no. The common failures are specific and worth
naming: the senior engineer who carries the loop's opinion via
personal authority rather than evidence, the manager who hires
despite weak signal because they are under headcount pressure,
and the team that compromises on the bar to fill the seat. Each
of these failures has a recognizable shape, and the lecture
notes cover how to catch them in real time.

**Onboarding.** Most team leads underestimate onboarding. They
think the new hire will be productive in a week, so they
delegate the setup to the buddy and check in at the 30-day
mark. The reality for AI-infra is 60-90 days to full
productivity, and sometimes longer for someone coming into a
production on-call rotation. The pattern that works is a staged
90-day plan with explicit check-ins: week 1 is environment set
up and the first (trivial) PR merged, weeks 2-3 are paired work
on a small project with a buddy assigned, week 4 is the 30-day
retro, weeks 5-8 are small end-to-end ownership of a defined
piece of work, and weeks 9-12 are integration into the on-call
rotation and primary ownership of one workstream. The team
lead's job during these 90 days is not to write the plan and
step back; it is to check in regularly, catch the signals that
the plan is drifting, and adjust before the drift becomes
attrition.

The lecture notes go deeper on each. The exercises push you to
apply the framing to a specific scenario — your real team's
current open role and recent onboarding experience if you have
one, or a case-study team's if you do not.

## Module Structure

- **README (this file).** Scope, objectives, and how to work
  through the module.
- **`lecture-notes/01-overview.md`.** The core argument: why
  hiring and onboarding deserve the calendar time, what a
  well-designed loop covers, how the debrief produces a
  defensible decision, how to hold the bar under pressure, and
  what a 90-day onboarding plan actually looks like. Read this
  first and re-read it after the exercises; it reads differently
  once you have run a debrief where the interviewers disagree.
- **`exercises/exercise-01-case-study.md`.** A strategic
  case-study exercise. You walk into a hiring or onboarding
  situation mid-flight — a loop that keeps producing
  "maybe" debriefs, a role that has been open four months, a
  90-day plan that has quietly stalled at week six, a recent
  hire who is not integrating — diagnose what went wrong, and
  propose how you would run it from here.
- **`exercises/exercise-02-strategy-memo.md`.** A short written
  memo justifying a specific hiring or onboarding decision — a
  no-hire call on a candidate the recruiter wants to push, a
  bar-holding decision that leaves a seat empty for another
  quarter, a reassignment of onboarding scope — to a skeptical
  peer or manager. Forces precision about the signal, the
  tradeoffs, and the reasoning that would survive the same
  decision being questioned six months later.
- **`exercises/exercise-03-stakeholder-mapping.md`.** Maps the
  people whose expectations your hiring and onboarding
  decisions have to serve — the recruiter, the peer teams
  waiting on the capacity, your own manager, the interviewers
  on the loop, the new hire themselves, and the engineers on
  the team who will do the paired work. Hiring is a cross-
  stakeholder activity as much as it is an evaluation activity.
- **`exercises/exercise-04-roadmap.md`.** A quarter-to-year
  hiring and onboarding plan for the team you are using — which
  roles open when, the loop and interviewer calendar needed to
  run them, the onboarding ramp assumed for each hire, and the
  explicit moments where you will revisit the plan if the
  pipeline shifts.
- **`exercises/exercise-05-presentation.md`.** A short
  presentation — built for a peer review session — that defends
  your handling of a specific hiring or onboarding situation to
  another team lead. The ask is to be concrete and defensible,
  not comprehensive.
- **`quiz.md`.** Strategic-thinking questions to test your
  framing. They do not have single right answers; they test
  whether you can defend the hiring and onboarding choices you
  made.
- **`resources.md`.** Frameworks and further reading. Treat
  these as pointers, not a reading list — pick what fits the
  problem in front of you.

The module is designed to be worked in order. Lecture first,
then the exercises in sequence (01 sets up the scenario the
later exercises build on, and 04 produces the artifact 05
defends), then the quiz. Expect the exercises to take longer
than the lecture; most of the learning is in the application.

## How to work through this module

The module is sized at 30-50 hours. That range is wide on
purpose. If you already lead a team with an open role and a
recent hire in onboarding, you will be at the low end — you are
mostly converting intuition into explicit practice against real
situations you are running anyway. If you are approaching this
as a senior IC or architect getting ready for a lead role and
you are using a case-study team, plan for the high end — you
have to build the loop-design and debrief reflexes as you go.

A workable rhythm:

1. **Read the lecture notes once.** Do not stop to take
   extensive notes; aim for the shape of the argument and the
   three questions that tell you whether hiring is healthy
   (does the loop produce decisions, does the bar hold under
   pressure, does the new hire reach full productivity by
   week 12?).
2. **Write down the current hiring and onboarding surface of a
   team you know.** Real or case-study. For each open role,
   write one paragraph: what capacity gap it fills, what the
   must-have signals are, who runs each slot of the loop, and
   the one thing about the loop that bothers you. For each
   recent hire, write one paragraph on where they are in the
   90-day plan and the one thing you are not sure about. If you
   cannot name the must-have signals on an open role, that is
   already the finding.
3. **Do Exercise 01.** Diagnose what is wrong with the hiring
   or onboarding situation you just mapped. Do not propose
   fixes yet. The goal is diagnosis — role definition drift?
   loop missing a signal? debrief that is not producing a call?
   onboarding plan not being run? — and diagnosis is harder
   than it looks.
4. **Do Exercises 02-04 in sequence.** Each one tightens the
   plan: the memo forces you to justify a hiring or onboarding
   decision in writing in a way a skeptical peer could
   pressure-test, the stakeholder map forces you to account for
   who the decision affects beyond the immediate loop, and the
   roadmap forces you to sequence the hiring and onboarding
   work across a quarter-to-year horizon.
5. **Do Exercise 05.** Defend the handling of the situation to
   a peer. If you cannot get a real peer to review it, write
   the defense anyway — the writing surfaces the weak points,
   especially the moments where you would otherwise fall back
   on "we needed the headcount."
6. **Re-read the lecture notes.** The second pass is where the
   framing actually sticks. If the sections on bar discipline
   and on the debrief now feel obvious, that is the point.
7. **Do the quiz.** Treat the questions as prompts for a short
   written answer each. The quiz is a self-check on whether you
   can defend your hiring and onboarding choices, not a
   knowledge test.

Resist the temptation to do this module "in theory" without a
specific role or a specific new hire in mind. The framings only
land when they are applied to a concrete loop with a concrete
candidate pile, or a concrete 90-day plan with a specific new
hire's trajectory. If you do not have a team of your own,
borrow one — ask another lead if you can anonymize their next
open role or most recent hire and work it through the exercises.

## AI-infra specific angles to watch for

The lecture notes cover hiring and onboarding as a general
skill. A few places where the AI-infra context changes the
defaults:

**The talent surface is narrow.** Strong AI-infra engineers sit
at the intersection of serving, training, GPU/hardware, and
cost; most engineers are strong on one of those, not all four.
The role definition has to be explicit about which parts of the
surface are must-haves and which are nice-to-haves, or the loop
produces candidates who are impressive on one axis and silent on
the three that the role actually depends on. Expect sourcing to
be slower than for a generic backend role, and expect the
"strong engineer on the wrong axis" false positive to be the
single most common failure mode in the loop.

**Operational sensibility is harder to signal in an interview.**
An AI-infra engineer has to carry an on-call rotation that
includes model-serving outages, training-run failures, and the
cost-attribution mess that sits underneath both. A clean coding
and system-design signal does not tell you whether the candidate
will be strong in the 2am page where the serving stack is
cascading and the model team is asking for a status update
every ten minutes. The loop has to include a slot that
specifically probes operational maturity — past incidents
owned, past on-call rotations run, specific stories of what
went wrong and how the engineer behaved — or the signal is
missing.

**Domain depth varies by sub-specialty and changes which
interviewer covers which signal.** A serving-focused role
expects evidence of production serving infrastructure
experience; a training-platform-focused role expects evidence
of distributed training operation; a GPU-fleet-focused role
expects evidence of hardware-level reasoning; a cost-focused
role expects evidence of cost modeling and attribution. The
same candidate can look strong on a generic "systems" interview
and weak on the specific domain that the role actually fills.
Match the interviewer to the signal explicitly — do not run a
serving role's domain slot with an interviewer whose depth is
in training, or vice versa.

**Sourcing has to reach beyond standard engineering pools.**
The strongest AI-infra engineers are often sitting one layer
away from where recruiters usually look — in research
engineering roles, in ML platform roles at adjacent companies,
in hardware or compiler teams. The team lead has to be the one
naming those adjacent pools and seeding specific candidates to
the recruiter; left to defaults, the top of the funnel will be
generic backend engineers who are strong on the wrong axis.

**On-call onboarding is a separate ramp.** For most engineering
roles, onboarding is largely codebase and tooling ramp. For
AI-infra, there is a second ramp specifically for on-call
readiness — shadowing a primary, running secondary shifts,
owning a non-critical page, before being trusted with a
critical production incident. The 90-day plan has to account
for this ramp separately from the code-contribution ramp; a
new hire who has merged their first feature by week 3 is still
not ready to carry the pager by week 4, and pushing them into
primary on-call too early produces incidents the team pays for
months later.

**Governance and cost context are part of onboarding, not
optional.** New AI-infra hires have to come up to speed on the
evidence trail Governance needs, the cost model Startup/Finance
reports against, and the peer-team handoffs the serving and
training-platform contracts sit inside. These are not things a
new hire picks up by osmosis from the codebase; they live in
the operating cadence (mod-701), the roadmap (mod-703), and
the cross-team contracts (mod-704), and onboarding has to
include explicit time on each. A new hire who ships well for
six months but has never seen the governance evidence package
is one audit away from being a liability.

**Attrition risk is higher at the edges of the role.** AI-infra
roles sit next to AI research and AI product, both of which
pay more and have more public visibility. New hires who are
strong on the research-adjacent axis are more likely to leave
for a research role within 18-24 months; new hires who are
strong on the product-adjacent axis are more likely to leave
for a product-engineering role. The lead's job is not to
prevent this entirely — some attrition at the edges is
healthy — but to recognize which part of the role is at risk
of pulling which hire out and to invest in the integration
moves (growth path, stretch work, mission alignment) that
delay it.

Each of these gets picked up in more detail in the other
modules in this track, especially mod-701 (where the hiring and
onboarding rituals live inside your operating cadence), mod-702
(where the retention and performance management side of the
same relationships sits), mod-703 (where the headcount roadmap
is), and mod-704 (where the peer-team context the new hire has
to integrate into gets worked directly). The engineer-level AI
SRE, performance-engineering, and ML-engineering curricula go
deeper on the technical content a loop has to probe and a new
hire has to ramp on.

## Prerequisites and companion modules

This module assumes you have operated as a senior IC or senior
architect, which means:

- You have run at least one interview slot on a real hiring
  loop — ideally several — and formed a view about which
  signals your slot produced reliably and which it did not. The
  loop-design exercises assume you know, concretely, what a
  strong versus weak signal looks like in the slot you tend to
  run.
- You have been in at least one debrief where the loop
  disagreed with itself, and watched how the decision got
  made. The debrief exercises draw on that memory — especially
  the moments where the call went a way you would not have
  gone, and in retrospect still would not.
- You have been onboarded, successfully or not, and formed a
  view about what the team did or did not do that helped. The
  onboarding exercises assume you can tell the difference
  between a 90-day plan that was run and one that was written
  and shelved.

Within the team-lead track, this module is best worked after
mod-701 (which sets up the operating cadence that hiring loops
and onboarding check-ins live inside), alongside mod-702 (which
covers the retention and performance-management side of the
relationships hiring and onboarding create), and alongside
mod-703 (which is where the headcount side of the hiring plan
lives on the roadmap). Running mod-705 before mod-701 is
possible but tends to produce hiring and onboarding plans
without a ritual to maintain them. Running it without mod-702
produces hiring work disconnected from the longer-horizon
relationships it sets up.

Outside the track:

- [Module 00: Your Relationship to the Model](../00-your-relationship-to-the-model/README.md)
  is the required orientation. If you have not done it, start
  there; the stakeholder-mapping and role-definition work in
  this module assumes you know which sibling orgs sit on each
  handoff and what each one is optimizing for — because the
  role you are hiring into has to carry weight on those
  handoffs from week 12 forward.
- The engineer-level AI SRE, performance-engineering, and
  ML-engineering curricula go deeper on the technical content
  that an AI-infra loop has to probe and a new hire has to ramp
  on. If you are designing the domain-depth slot of a loop and
  you are not yourself a specialist in the surface the role
  covers, pull the relevant module from the engineer-level
  repo and borrow the signals.
- The senior-architect-learning repo's executive-leadership
  modules go deeper on organization-level hiring — multi-team
  headcount strategy, multi-quarter pipeline building,
  cross-org calibration — that sits above the single-team
  hiring work this module covers. If your hiring decisions keep
  running into questions that are not yours to answer, those
  modules are the next layer.

## What success looks like at the end of the module

You should finish the module with four concrete artifacts:

1. A **written role definition** for a specific open (or
   anticipated) seat on the team you used — level, domain mix,
   must-have signals, deal-breakers, articulated bar — at
   enough detail that another lead could pressure-test it and
   a recruiter could source against it.
2. A **loop design** for that role — which signals the loop
   covers, which interviewer runs each slot, the specific
   evidence each slot is trying to produce, and the debrief
   structure that turns the signals into a decision.
3. A **90-day onboarding plan** for a hypothetical hire into
   that same role — the week-1 setup, the paired-work and
   buddy assignment through weeks 2-3, the 30-day retro, the
   small end-to-end ownership through weeks 5-8, the on-call
   and primary-workstream integration through weeks 9-12, and
   the explicit check-in cadence you commit to running.
4. A **set of signals** — not metrics, signals — you will
   watch for to catch hiring and onboarding problems before
   they compound: the loop that keeps producing "maybe"
   debriefs, the bar that is quietly drifting, the role that
   has been open long enough that pressure is mounting to
   compromise, the new hire whose 30-day retro has been
   rescheduled twice, the paired work that is not shifting to
   solo ownership, the on-call shadow that is not progressing
   to primary.

If any of those four is missing or hand-wavy, you are not done.
The quiz is designed to catch the most common gaps.

Success is not "I have perfected hiring and onboarding." Every
role, every candidate pile, every new hire is a new instance of
the same skills under different constraints. Success is "I can
run the basic cycle on purpose — role definition, loop, bar,
debrief, close, 90-day plan — defend the choices I made in it,
and recognize when a loop or an onboarding plan is drifting
away from what the role actually needs."

## Before you start

Pick the team and the specific hiring or onboarding situation
you will use for the exercises before you open the lecture
notes. Write one paragraph about that situation: if it is a
hiring case, the role, the capacity gap it fills, the state of
the current pipeline, and the one thing about the loop you are
not confident in. If it is an onboarding case, the new hire,
where they are in the 90-day arc, and the one thing about
their integration you are not sure about. Keep the paragraph
beside you as you read; the lecture will land harder if you
are reading it against a real backdrop. Then open
[`lecture-notes/01-overview.md`](lecture-notes/01-overview.md)
and begin.
