# mod-703-project-roadmap: Project + Roadmap Management

**Level**: team-lead-learning
**Duration**: 30-50 hours
**Prerequisites**: senior-engineer or senior-architect level

## Overview

This module is about the work of turning a team's capacity into a
set of commitments the rest of the organization can plan around.
It is not about Gantt charts, and it is not about OKR template
wars. It is about the small number of recurring activities —
quarterly planning, estimation, roadmap communication, mid-quarter
replanning, and the "we're cutting X" conversation — that
collectively determine whether your team is trusted to deliver,
whether its workload is honest, and whether its stakeholders can
tell the difference between "at risk" and "on track."

For an AI Infrastructure Team Lead, the stakes of getting this
right are higher than they are for a generic engineering lead.
Your roadmap carries the serving-stack upgrade that AI Engineering
is depending on for their next product launch, the training-fleet
expansion that ML Engineering needs before the next run can start,
the cost-reduction commitments that Startup/Finance has already
told the board about, and the governance evidence that Governance
needs for the next audit. A missed roadmap slot does not just slip
your team's work; it chains into four other orgs who built plans
on top of yours. The failure mode is almost never bad engineering.
It is a roadmap the team quietly knew was unachievable and did not
renegotiate in time.

This module takes the position — argued at length in the lecture
notes — that a roadmap is a *communication artifact*, not a
schedule. You will spend ~30-50 hours here: reading, applying the
ideas to a real or case-study team's upcoming quarter, and
completing five exercises that force you to make concrete planning
decisions. By the end, you should be able to run the full planning
and roadmap cycle — intake, estimation, commitment, replanning,
cuts — on a real team and defend the choices you made in it.

## Learning Objectives

By the end of this module you will be able to:

- **Quarterly planning.** Run an end-to-end quarterly planning
  cycle: gather intake from stakeholders, size candidate work
  against honest capacity, land a commitment with explicit
  non-goals, and publish it in a form that upstream and downstream
  teams can act on.
- **Estimation discipline.** Produce estimates that account for
  on-call load, interrupt rate, onboarding, and the compounding
  tax of multi-team dependencies; recognize when an estimate is
  wishful and push back without blowing up the planning session.
- **Roadmap negotiation.** Treat the roadmap as a negotiated
  commitment rather than a schedule imposed from above; run the
  conversation about scope, headcount, and priority with
  stakeholders who each want to be the top of the list.
- **Replanning rhythm.** Build a monthly roadmap review and a
  mid-quarter adjustment protocol so that reality updates the
  roadmap on a known cadence, not in a panic in week eleven.
- **Cuts and slips.** Run the "we're cutting X" conversation
  early, with options, so that it builds trust instead of burning
  it; communicate slips on a timeline that gives downstream teams
  usable notice instead of a fait accompli.

These objectives are not independent. The hardest version of this
work is not getting any single commitment right; it is keeping
twelve weeks of commitments coherent as scope, capacity, and
priority all drift underneath you.

## Why this module exists at this level

You have passed through senior IC or senior architect, which means
you have been *inside* at least one team's roadmap for long enough
to have opinions about how it was built. You have shipped against
dates you helped estimate, and you have been on the wrong side of
dates estimated by someone else. That experience is useful, but it
is not the same as owning the roadmap.

The shift is uncomfortable in a specific way. As a senior engineer
you optimized for execution inside the plan — you took a committed
scope and found a way to land it. The team lead's job runs one
level up: deciding what gets committed in the first place, under
honest capacity, with stakeholders whose asks exceed what your
team can do. The information asymmetry also inverts. As an IC you
usually had more detail than your lead on the specific work; as a
lead you usually have less detail on any specific task than the
engineer doing it, but you have more context on how the whole
quarter fits together. Good roadmapping is the discipline of
making decisions from that aggregated view without pretending to
know details you do not.

The lecture notes argue that trustworthy roadmaps are built on
probabilistic estimates and explicit non-goals, not on padded
dates and quiet overcommitment. That is the framing to carry
through the module. Every planning decision should be judged
against the question: "If this slips by two weeks, does my
stakeholder have a usable signal, or will they find out when the
deliverable does not arrive?"

## What this module covers

The module is organized around five kinds of recurring planning
work. Each one answers a different structural problem.

**Intake and prioritization.** Every quarter the team gets more
asks than it has capacity for — from product, from sibling orgs,
from its own backlog, from the inevitable "this is urgent" that
arrives in week two. The discipline is a visible intake process
so stakeholders can see what is competing with what, and a
prioritization frame — strategic bet, must-do maintenance,
opt-in improvement, declined — that makes the cut defensible.
The lecture notes draw on the Three Horizons of Growth framing
for separating long-horizon investment from near-term delivery.

**Estimation.** Estimates are the foundation on which every
other planning conversation sits. The lecture notes cover
reference-class forecasting (anchor on how long similar past
work actually took, not how long you want this one to take),
three-point estimates (best, expected, worst — the worst case is
where the surprises hide), and capacity-adjusted estimates
(on-call eats 10-20% of a rotation's capacity, new hires are
slower for 60-90 days, the team's interrupt rate eats another
10-30%). A team of five engineers does not have 200 person-hours
of focus time per week; it has perhaps half that, and planning
that pretends otherwise shows up as the Q3 miss.

**Commitment and communication.** A roadmap that never leaves
the team's wiki is not really a roadmap. The commitment layer
answers three questions for the rest of the organization: what
is the team doing, with what confidence, and what is it *not*
doing. Different audiences need different views — executives
want outcomes and dates, adjacent teams want dependencies and
interfaces, the team itself needs full detail. The lecture notes
cover how to maintain one source of truth and produce views
from it without the views drifting from each other.

**Replanning.** Roadmaps that are not revisited become fiction.
The pattern that works is weekly sprint-level tracking, monthly
roadmap review, and quarterly full replanning — with an explicit
mid-quarter adjustment moment that catches drift early. The
discipline is *explicit* replanning, not silent slippage. A team
that cut one item at week six and told everyone is in better
shape than a team that quietly carried four at-risk items to
week twelve.

**Cuts and slips.** The hardest team-lead skill in roadmapping
is the "we're cutting X" conversation with the stakeholder who
wanted X. Most leads delay it, hope, and then deliver the bad
news as an accomplished fact. The pattern that works is to
surface risk two weeks after the signal — not two months — and
to bring options (cut scope, push date, request more headcount,
accept lower quality) rather than a verdict. Done well, this
conversation builds trust; avoided, it burns it.

The lecture notes go deeper on each. The exercises push you to
apply the framing to a specific scenario — your real team's next
quarter if you have one, or a case-study team's if you do not.

## Module Structure

- **README (this file).** Scope, objectives, and how to work
  through the module.
- **`lecture-notes/01-overview.md`.** The core argument: what
  roadmaps are for, why they are commitments rather than
  schedules, the estimation disciplines that make them
  trustworthy, the replanning rhythm, and the cuts conversation.
  Read this first and re-read it after the exercises; it reads
  differently once you have tried to defend an estimate to a
  stakeholder who disagrees with it.
- **`exercises/exercise-01-case-study.md`.** A strategic
  case-study exercise. You walk into a team mid-quarter, diagnose
  what is wrong with its current roadmap — overcommitted, under-
  communicated, built on padded estimates, missing non-goals, or
  some combination — and propose how you would reset it.
- **`exercises/exercise-02-strategy-memo.md`.** A short written
  memo justifying a specific roadmap decision — a cut, a
  re-sequencing, a date push, a headcount ask — to a skeptical
  stakeholder. Forces precision about tradeoffs.
- **`exercises/exercise-03-stakeholder-mapping.md`.** Maps the
  people inside and outside the team whose expectations your
  roadmap has to serve — AI Engineering, ML Engineering,
  Governance, Startup/Finance, AI Workforce, your own manager,
  and the team itself. A roadmap only works if the surrounding
  org knows what to expect from it.
- **`exercises/exercise-04-roadmap.md`.** Build a real
  quarter-to-year roadmap for the team you are using, including
  explicit non-goals, confidence levels, and the mid-quarter
  replanning moments you commit to.
- **`exercises/exercise-05-presentation.md`.** A short
  presentation — built for a peer review session — that defends
  the roadmap you built to another team lead. The ask is to be
  concrete and defensible, not comprehensive.
- **`quiz.md`.** Strategic-thinking questions to test your
  framing. They do not have single right answers; they test
  whether you can defend the roadmap choices you made.
- **`resources.md`.** Frameworks and further reading. Treat these
  as pointers, not a reading list — pick what fits the problem
  in front of you.

The module is designed to be worked in order. Lecture first, then
the exercises in sequence (01 sets up the scenario the later
exercises build on, and 04 produces the artifact 05 defends),
then the quiz. Expect the exercises to take longer than the
lecture; most of the learning is in the application.

## How to work through this module

The module is sized at 30-50 hours. That range is wide on purpose.
If you already lead a team and the exercises map directly onto
the quarterly planning cycle you are about to run anyway, you will
be at the low end — you are mostly converting intuition into
explicit practice. If you are approaching this as a senior IC or
architect getting ready for a lead role and you are using a
case-study team, plan for the high end — you have to build the
estimation and negotiation reflexes as you go.

A workable rhythm:

1. **Read the lecture notes once.** Do not stop to take extensive
   notes; aim for the shape of the argument and the three
   questions a roadmap has to answer.
2. **Write down the current roadmap of a team you know.** Real or
   case-study. Write it in prose, not a table. Include what the
   team committed to, what is actually happening, and what has
   quietly drifted. If you cannot write it in under a page,
   something is already wrong with the roadmap.
3. **Do Exercise 01.** Diagnose what is wrong with the roadmap
   you just wrote down. Do not propose fixes yet. The goal is
   diagnosis — padded estimate? missing non-goals? silent slip?
   stakeholder misalignment? — and diagnosis is harder than it
   looks.
4. **Do Exercises 02-04 in sequence.** Each one tightens the
   plan: the memo forces you to justify a roadmap change in
   writing, the stakeholder map forces you to account for who
   the change affects beyond the team, and the roadmap exercise
   forces you to produce the actual quarter-to-year artifact
   with confidence levels and non-goals.
5. **Do Exercise 05.** Defend the roadmap to a peer. If you
   cannot get a real peer to review it, write the defense anyway
   — the writing surfaces the weak points, especially the
   estimates you would otherwise hand-wave past.
6. **Re-read the lecture notes.** The second pass is where the
   framing actually sticks. If the sections on probabilistic
   commitment and the cuts conversation now feel obvious, that
   is the point.
7. **Do the quiz.** Treat the questions as prompts for a short
   written answer each. The quiz is a self-check on whether you
   can defend your planning choices, not a knowledge test.

Resist the temptation to do this module "in theory" without a
specific quarter in mind. The framings only land when they are
applied to a concrete team with specific capacity, dependencies,
and stakeholder asks. If you do not have a team of your own,
borrow one — ask another lead if you can anonymize their next
quarter's planning problem and work it through the exercises.

## AI-infra specific angles to watch for

The lecture notes cover project and roadmap management as a
general skill. A few places where the AI-infra context changes
the defaults:

**Capacity planning is a separate planning ritual, not a column
in sprint planning.** GPU supply, model-family mix, and the
training-vs-inference capacity balance all move on a different
cadence than feature delivery. Most AI-infra teams need a
dedicated capacity-planning ritual — typically monthly, aimed
at the next two to four quarters — separate from the delivery
roadmap. If you try to fit capacity into the same conversation
as feature work, one of them will drive out the other, and
usually it is capacity that loses until the fleet runs out.

**Dependencies run in both directions and are brittle.** Your
roadmap has serving endpoints that AI Engineering is building
products on top of, training-platform features that ML
Engineering is waiting on, cost and reliability commitments
that Startup/Finance has already told the board, and
governance evidence that Governance needs for audits. At the
same time, your roadmap depends on hardware delivery, framework
upgrades, and research artifacts from the sibling orgs upstream
of you. A two-week slip in one direction chains into four orgs
in the other direction. Non-goals and dependency diagrams are
load-bearing, not decorative. Module 00 is the reference for
who sits on each handoff.

**Research-driven urgency is real and usually unplanned.** A
model lands, a benchmark moves, a competitor ships, and the
roadmap you negotiated in week one is suddenly carrying a
must-do item in week four that nobody saw coming. The
discipline is to budget headroom for this explicitly — most
AI-infra teams need 20-30% of a quarter reserved for
unplanned-but-expected work — and to run the renegotiation
conversation when it arrives rather than quietly cramming the
new item on top of the old commitments.

**Cost is a first-class commitment, not a side effect.** Your
roadmap carries dollar numbers (fleet spend, per-token cost,
training run cost) that Startup/Finance treats with the same
weight that AI Engineering treats feature dates. Track cost
commitments on the roadmap at the same altitude as delivery
commitments. A team that ships every feature but misses its
cost commitment by 30% is not shipping a successful roadmap.

**Written-first communication scales better than it does for
pure product teams.** AI-infra roadmap decisions have long tails
— rollback windows, capacity commitments, cost impact, the
evidence trail Governance will need at audit. Oral agreements
evaporate; written commitments survive long enough to be
referenced. Default to writing the commitment down, with
confidence levels, and sharing it on a known cadence.

Each of these gets picked up in more detail in the other modules
in this track, especially mod-701 (which is where the planning
ritual itself lives in your operating cadence) and mod-704 (which
is where the cross-team negotiation side of roadmap work gets
worked directly). The engineer-level AI SRE and performance-
engineering curricula go deeper on the capacity-planning and
cost-attribution side. Keep the connections in mind as you work
through mod-703; the roadmap you build here is the surface the
rest of the track plugs into.

## Prerequisites and companion modules

This module assumes you have operated as a senior IC or senior
architect, which means:

- You have estimated and delivered against a non-trivial
  project. The estimation exercises assume you know, concretely,
  how long your own work actually takes versus how long you
  tend to think it will take.
- You have been in at least one planning session that ended in
  overcommitment, and watched the quarter play out. The
  replanning and cuts exercises draw on that memory.
- You have shipped something whose delivery was blocked on
  another team's roadmap. The dependency exercises assume you
  have felt the pain of a cross-team coordination failure.

Within the team-lead track, this module is best worked after
mod-701, which sets up the operating cadence that quarterly
planning and monthly roadmap review live inside, and alongside
mod-704, which covers the cross-team coordination side of
roadmap commitments. Running mod-703 before mod-701 is possible
but tends to produce roadmaps without a ritual to maintain them.

Outside the track:

- [Module 00: Your Relationship to the Model](../00-your-relationship-to-the-model/README.md)
  is the required orientation. If you have not done it, start
  there; the dependency and stakeholder exercises in this module
  assume you know which sibling orgs sit on each handoff.
- The engineer-level AI SRE and performance-engineering
  curricula go deeper on capacity planning, cost attribution,
  and the technical content of fleet-upgrade and serving-stack
  roadmap items. If your team's roadmap is mostly infrastructure
  investment rather than feature delivery, do the relevant
  sections of those modules alongside this one.
- The senior-architect-learning repo's strategy modules cover
  Wardley mapping, Three Horizons, and the longer-horizon
  framing that sits above the two-to-four-quarter roadmap this
  module covers. If your roadmap decisions keep running into
  questions that are not yours to answer, those modules are the
  next layer.

## What success looks like at the end of the module

You should finish the module with four concrete artifacts:

1. A **written roadmap document** for a specific team — real or
   case-study — that lists the committed work, the explicit
   non-goals, confidence levels on each commitment, and the
   dependencies in both directions.
2. A **short defense of each commitment**, usually one or two
   sentences per item, that another lead could pressure-test.
3. A **mid-quarter replanning protocol** — when you will revisit
   the roadmap, what signals will trigger an off-cadence review,
   and the specific stakeholders who will be in the room when
   scope changes.
4. A **set of signals** — not metrics, signals — you will watch
   for to catch a commitment going at-risk before it misses: the
   two-week-slip rule, the quiet dependency delay, the estimate
   that keeps growing in retrospective conversations, the
   stakeholder who has stopped asking about their item.

If any of those four is missing or hand-wavy, you are not done.
The quiz is designed to catch the most common gaps.

Success is not "I have built a perfect roadmap." Every quarter
brings new scope, new capacity, and new dependencies, and the
roadmap you ship this quarter will need to be rebuilt — not just
updated — within a year. Success is "I can build one on purpose,
defend it with honest estimates and explicit non-goals, and
re-negotiate it when reality moves without burning stakeholder
trust."

## Before you start

Pick the team and the quarter you will use for the exercises
before you open the lecture notes. Write one paragraph about that
team — its size, what it owns, what its current roadmap commits
to, and the one thing about its current planning that you do not
believe. Keep the paragraph beside you as you read; the lecture
will land harder if you are reading it against a real backdrop.
Then open [`lecture-notes/01-overview.md`](lecture-notes/01-overview.md)
and begin.
