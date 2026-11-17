# mod-704-cross-team-coordination: Cross-Team Coordination

**Level**: team-lead-learning
**Duration**: 30-50 hours
**Prerequisites**: senior-engineer or senior-architect level

## Overview

This module is about the work your team only does well when it
does it with other teams. It is not about meeting hygiene, and
it is not about org-chart engineering. It is about the small
number of recurring activities — interface definition, dependency
tracking, sync meetings, escalation, scope negotiation — that
collectively determine whether the surface between your team and
the rest of the organization is a load-bearing boundary or a
constant source of friction.

For an AI Infrastructure Team Lead, the stakes of getting this
right are higher than they are for a generic engineering lead.
Your team sits at the center of a five-way handoff: serving
endpoints to AI Engineering, training-platform features to ML
Engineering, cost and reliability commitments to Startup/Finance,
evidence packages to Governance, and usage pain absorbed from AI
Workforce. Every one of those handoffs has a different cadence,
a different vocabulary, and a different definition of "on time."
When cross-team coordination slips, the symptoms show up as late
launches, missed audits, surprise capacity crunches, and the
quiet erosion of your team's reputation for being easy to work
with. None of those failure modes are inside your team. They
live on the boundary.

This module takes the position — argued at length in the lecture
notes — that cross-team coordination is a *contract* discipline,
not a diplomacy discipline. The teams that coordinate well are
not the ones with the best interpersonal skills; they are the
ones that make their interfaces explicit, keep their dependencies
visible, and renegotiate on a known cadence instead of in a
panic. You will spend ~30-50 hours here: reading, applying the
framings to a real or case-study team's actual cross-team
situation, and completing five exercises that force you to make
concrete coordination calls. By the end, you should be able to
map a team's external surface, name the contracts that govern
it, run the recurring syncs that maintain them, escalate when
peer-to-peer breaks down, and defend the choices you made.

## Learning Objectives

By the end of this module you will be able to:

- **Interfaces and contracts.** Define the surface between your
  team and each team it coordinates with — scope, ownership,
  interface (API, schema, schedule), sync cadence, escalation
  path — in a written contract both leads sign onto and both
  teams can point at when a dispute surfaces.
- **Dependency management in both directions.** Track what your
  team needs from others and what others need from your team on
  the same surface, with visibility to both sides; recognize
  hidden dependencies before they become surprises; and run the
  monthly or quarterly review that keeps the picture current.
- **Sync cadence and decision discipline.** Match meeting cadence
  to the actual coordination load — weekly for active integration,
  bi-weekly for steady-state boundaries, monthly for low-touch
  dependencies — and run the meeting so it produces decisions
  rather than drifting into theatre status reporting.
- **Escalation and arbitration.** Resolve the coordination
  problem at the peer-to-peer level first; calibrate when to
  escalate, who to escalate to, and how to do it with the peer
  lead's knowledge; and frame the escalation as a request for
  arbitration, not a complaint.
- **Scope negotiation across teams.** Run the "we can't take
  that this quarter" or "we need this from you earlier" or "our
  interface is changing" conversation without burning the peer
  relationship; bring options rather than verdicts; and leave the
  other lead able to defend the outcome inside their own team.

These objectives are not independent. The hardest version of
this work is not any single boundary or any single escalation;
it is keeping four or five cross-team relationships coherent
simultaneously, when each of them has its own calendar, its own
stakes, and its own version of what your team committed to.

## Why this module exists at this level

You have passed through senior IC or senior architect, which
means you have been *inside* at least one cross-team dependency
for long enough to have opinions about how it was run. You have
been the engineer asking another team for a feature that kept
slipping, and you have been on the other side, with your work
quietly becoming someone else's blocker. That experience is
useful, but it is not the same as owning the boundary.

The shift is uncomfortable in a specific way. As a senior
engineer you coordinated inside a scope your lead had already
negotiated for you — you knew what the interface was, you knew
which peer team owned which side, and when a dispute arose you
usually had someone one level up to escalate to. The team lead's
job is to *be* that one level up. You define the interface. You
decide which commitments your team can take. You are the person
the other team's engineers escalate through, and you are the
peer the other team's lead escalates to when the engineer-level
conversation stalls. The change is less about tactics than about
being the one accountable for the boundary holding.

The information asymmetry also inverts. As an IC you usually
knew more than your lead about the specific integration you were
building; as a lead you usually know less than your engineers
about any single interface, but you know more about how the full
set of cross-team relationships hangs together. Good cross-team
coordination is the discipline of making decisions from that
aggregated view — which boundary matters most, where the next
slip is likely to come from, which peer relationship is thinning
— without pretending to know details that only the engineers
closer to the work can tell you.

The lecture notes argue that cross-team coordination runs on
explicit contracts and calibrated escalation, not on goodwill.
That is the framing to carry through the module. Every
coordination decision should be judged against the question:
"If this relationship went cold tomorrow, is the commitment
written down somewhere both teams can see, or does it live only
in a Slack thread?"

## What this module covers

The module is organized around five kinds of recurring
coordination work. Each one answers a different structural
problem.

**Interfaces and contracts.** Every ongoing relationship between
two teams needs an explicit surface — scope, owner on each side,
interface definition, sync cadence, escalation path. The lecture
notes argue that the contract is the single most load-bearing
artifact in cross-team work: it is what lets a new team member
on either side come up to speed without re-litigating old
decisions, and it is what a peer lead points at when their team
is asking them to take something that your team already owns. A
contract does not have to be long. One page, signed onto by both
leads, usually beats three pages nobody has read.

**Dependency management in both directions.** Your team has
upstream dependencies (hardware delivery, framework upgrades,
model artifacts, research outputs) and downstream obligations
(serving endpoints, training-platform features, cost
commitments, audit evidence). Most teams track one side and
forget the other. The discipline is a single picture of
dependencies in both directions, maintained on a known cadence,
visible to the teams on the other end. Hidden dependencies are
the single most common source of surprise slips, and most of
them are not hidden on purpose — they just never got written
down.

**Sync cadence and decision discipline.** For ongoing cross-team
work, recurring sync meetings are the connective tissue. The
patterns that hold up: weekly for active integration work,
bi-weekly for steady-state ownership boundaries, monthly for
low-touch dependencies. The meeting has a written agenda, the
discussion produces decisions, and the decisions get documented
somewhere both teams can find later. The most common failure is
a weekly sync that drifts into status reporting with no
decisions produced; the team lead's job is to either restructure
the meeting or downgrade its cadence, not to keep it running out
of politeness.

**Escalation and arbitration.** When a coordination problem
resists peer-to-peer resolution, escalation is the right move —
but how it is done determines whether the peer relationship
survives. The pattern: first conversation is peer-to-peer, tell
the other lead the problem and listen to their constraints;
second conversation is another peer attempt with more context
(many coordination problems resolve on the second pass); if
still stuck, escalate to the shared manager, but do it with the
peer lead's knowledge, framed as a request for arbitration
rather than a complaint. Leads who skip the first two steps and
go straight to the manager signal that they do not trust the
peer relationship, and that signal tends to stick.

**Scope negotiation across teams.** The hardest coordination
conversations are the ones where your team cannot do what the
other team wants, or the other team cannot do what your team
needs — and both leads have stakeholders behind them who were
expecting a different answer. The pattern that works is to
surface the mismatch early, bring options (cut scope, push date,
change the interface, swap the sequencing, request headcount)
rather than a verdict, and leave the peer lead able to carry the
outcome back to their team without losing face. The alternative
— surprising the peer lead with a unilateral decision — buys one
quarter and costs several.

The lecture notes go deeper on each. The exercises push you to
apply the framing to a specific scenario — your real team's
current cross-team situation if you have one, or a case-study
team's if you do not.

## Module Structure

- **README (this file).** Scope, objectives, and how to work
  through the module.
- **`lecture-notes/01-overview.md`.** The core argument: what
  changes when work crosses team boundaries, why the contract is
  the primary artifact, the escalation discipline, the sync
  cadence pattern, and the three questions that tell you whether
  coordination is healthy. Read this first and re-read it after
  the exercises; it reads differently once you have tried to run
  a stuck negotiation with a peer who disagrees with you.
- **`exercises/exercise-01-case-study.md`.** A strategic
  case-study exercise. You walk into a cross-team coordination
  problem mid-flight — a disputed interface, a quietly slipping
  dependency, a sync meeting that has stopped producing
  decisions, an escalation that went poorly — diagnose what went
  wrong, and propose how you would run it from here.
- **`exercises/exercise-02-strategy-memo.md`.** A short written
  memo justifying a specific cross-team decision — an interface
  change, a deprioritization, a date renegotiation, a scope cut
  — to a skeptical peer lead. Forces precision about tradeoffs
  and about how you would want the other side to be able to
  defend the outcome inside their own team.
- **`exercises/exercise-03-stakeholder-mapping.md`.** Maps the
  teams and leads whose expectations your team's commitments
  have to serve — AI Engineering, ML Engineering, Governance,
  Startup/Finance, AI Workforce, your own manager, and the
  internal leads whose work depends on yours. Cross-team
  coordination only works if you know which leads are on which
  handoff and what each of them is optimizing for.
- **`exercises/exercise-04-roadmap.md`.** A quarter-to-year plan
  for the cross-team commitments your team is on the hook for —
  interface changes, deprecations, new integrations, dependency
  reviews, escalation protocols — with explicit renegotiation
  moments baked into the timeline.
- **`exercises/exercise-05-presentation.md`.** A short
  presentation — built for a peer review session — that defends
  your handling of a specific cross-team coordination situation
  to another team lead. The ask is to be concrete and defensible,
  not comprehensive.
- **`quiz.md`.** Strategic-thinking questions to test your
  framing. They do not have single right answers; they test
  whether you can defend the coordination choices you made.
- **`resources.md`.** Frameworks and further reading. Treat these
  as pointers, not a reading list — pick what fits the problem
  in front of you.

The module is designed to be worked in order. Lecture first,
then the exercises in sequence (01 sets up the scenario the
later exercises build on, and 04 produces the artifact 05
defends), then the quiz. Expect the exercises to take longer
than the lecture; most of the learning is in the application.

## How to work through this module

The module is sized at 30-50 hours. That range is wide on
purpose. If you already lead a team and the exercises map
directly onto cross-team situations you are managing anyway,
you will be at the low end — you are mostly converting intuition
into explicit practice. If you are approaching this as a senior
IC or architect getting ready for a lead role and you are using
a case-study team, plan for the high end — you have to build the
boundary-management reflexes as you go.

A workable rhythm:

1. **Read the lecture notes once.** Do not stop to take extensive
   notes; aim for the shape of the argument and the three
   questions that tell you whether coordination is healthy.
2. **Write down the current cross-team surface of a team you
   know.** Real or case-study. For each peer team the team you
   are using interacts with, write one paragraph: what the
   interface is, who owns each side, what the current sync looks
   like, and the one thing about that relationship that bothers
   you. If you cannot name the owner on both sides, that is
   already the finding.
3. **Do Exercise 01.** Diagnose what is wrong with the
   cross-team situation you just mapped. Do not propose fixes
   yet. The goal is diagnosis — missing contract? invisible
   dependency? sync meeting producing no decisions? escalation
   that went straight to the manager? — and diagnosis is harder
   than it looks.
4. **Do Exercises 02-04 in sequence.** Each one tightens the
   plan: the memo forces you to justify a coordination decision
   in writing in a way the peer lead could carry back to their
   team, the stakeholder map forces you to account for who the
   decision affects beyond the immediate peer, and the roadmap
   forces you to sequence the cross-team work across a
   quarter-to-year horizon with explicit renegotiation moments.
5. **Do Exercise 05.** Defend the handling of the situation to a
   peer. If you cannot get a real peer to review it, write the
   defense anyway — the writing surfaces the weak points,
   especially the moments where you would otherwise fall back on
   "the other team should have known."
6. **Re-read the lecture notes.** The second pass is where the
   framing actually sticks. If the sections on contracts and on
   the escalation discipline now feel obvious, that is the
   point.
7. **Do the quiz.** Treat the questions as prompts for a short
   written answer each. The quiz is a self-check on whether you
   can defend your coordination choices, not a knowledge test.

Resist the temptation to do this module "in theory" without a
specific cross-team situation in mind. The framings only land
when they are applied to a concrete boundary with a specific
peer lead, a specific interface, and a specific disagreement. If
you do not have a team of your own, borrow one — ask another
lead if you can anonymize one of their current cross-team
situations and work it through the exercises.

## AI-infra specific angles to watch for

The lecture notes cover cross-team coordination as a general
skill. A few places where the AI-infra context changes the
defaults:

**The five-way handoff is the default, not the exception.** For
most product teams, cross-team coordination is a few integration
partners plus their platform team. For an AI-infra team, the
baseline is a continuous five-way handoff — serving endpoints to
AI Engineering, training-platform features to ML Engineering,
cost reporting to Startup/Finance, audit evidence to Governance,
usage absorption from AI Workforce — each with its own cadence
and its own definition of success. Trying to run all five on the
same meeting or the same document does not work; each needs its
own contract and its own sync. Module 00 is the reference for
which lead sits on each handoff and what each sibling org is
optimizing for.

**Interfaces have unusually long tails.** A serving API change
is not just a deprecation window on your side; it is a rollback
window for AI Engineering, a capacity-planning input for ML
Engineering, and a cost-impact estimate for Startup/Finance.
Interface contracts have to carry those downstream consequences
explicitly — "what breaks if we change this, for whom, and over
what window" — or the change lands as a surprise on someone
whose roadmap it just invalidated. The engineer-level AI SRE and
performance-engineering curricula go deeper on the technical
side of deprecation and rollback; the cross-team side is making
sure the peer leads whose work depends on the interface are in
the room when the deprecation calendar is set.

**Dependencies go both ways and are brittle.** Your team
depends on hardware delivery, framework upgrades, and research
artifacts from upstream; downstream teams depend on your
serving stack, your training platform, and your cost
commitments. A two-week slip in one direction tends to chain
into four orgs in the other direction. Dependency tracking has
to be a cross-team surface, not an internal roadmap artifact —
if the dependency only lives in your team's planning document,
the team on the other end will find out when the deliverable
does not arrive. mod-703 covers the roadmap side of this
directly; the coordination side is making the dependency
*visible* to both teams on the same cadence.

**Research-driven urgency scrambles the sync rhythm.** A model
lands, a benchmark moves, a competitor ships, and the carefully
negotiated interface or dependency schedule that worked in week
one is suddenly carrying a must-do change in week four. The
discipline is to budget headroom explicitly (most AI-infra teams
need 20-30% of a quarter reserved for unplanned-but-expected
work) and to run the renegotiation conversation across the
boundary when the change arrives, rather than quietly cramming
the new work on top of the old commitments and surprising the
peer team later. This is the same pattern that shows up in
mod-703 on the roadmap side; the cross-team angle is that the
renegotiation has to happen *across the boundary*, not just
inside your team.

**Governance and finance are coordination partners, not
checkpoints.** New leads often treat Governance and
Startup/Finance as audit-time overhead — teams you hand evidence
to at the end of a quarter. That framing produces late-stage
surprises on both sides. The pattern that works is to treat
both as standing coordination partners with their own sync
cadence and their own contract, the same way AI Engineering and
ML Engineering are. The evidence trail is lower-effort if it is
built continuously; the cost commitments are more trustworthy if
Finance is in the loop when the capacity decision is made, not
when the bill arrives.

**Written-first communication scales better than it does for
pure product teams.** AI-infra coordination decisions have long
tails — rollback windows, capacity commitments, cost impact,
audit evidence. Oral agreements evaporate; written commitments
survive long enough to be referenced when the question comes
back three quarters later. Default to writing the contract down,
putting it somewhere both teams can find it, and updating it
when the interface changes, rather than relying on institutional
memory.

Each of these gets picked up in more detail in the other modules
in this track, especially mod-701 (which is where the sync
rituals themselves live in your operating cadence) and mod-703
(which is where the cross-team commitments show up on the
roadmap). The engineer-level AI SRE and performance-engineering
curricula go deeper on the technical content of interface
design, deprecation, and rollback. Keep the connections in mind
as you work through mod-704; the coordination practice you build
here runs on top of the operating model you designed in mod-701
and the roadmap you negotiated in mod-703.

## Prerequisites and companion modules

This module assumes you have operated as a senior IC or senior
architect, which means:

- You have been on the receiving end of at least one cross-team
  dependency that slipped. The dependency-tracking exercises
  assume you know, concretely, what it feels like for your work
  to be blocked by something outside your team's control.
- You have negotiated an interface — API, schema, data contract
  — with an engineer on another team. The contracts exercises
  build on the reflex that interfaces are specifications, not
  informal understandings.
- You have been in the room for at least one escalation — one
  that went well and one that did not — and formed a view about
  what the leads involved did well or poorly. The escalation
  exercises draw on that memory.

Within the team-lead track, this module is best worked after
mod-701, which sets up the operating cadence that cross-team
syncs live inside, and alongside mod-703, which covers the
roadmap side of the commitments your team is coordinating on.
Running mod-704 before mod-701 is possible but tends to produce
coordination plans without a ritual to maintain them. Running it
without mod-703 produces coordination work that is not
anchored to the roadmap commitments it is supposed to protect.

Outside the track:

- [Module 00: Your Relationship to the Model](../00-your-relationship-to-the-model/README.md)
  is the required orientation. If you have not done it, start
  there; the stakeholder-mapping and interface-definition work
  in this module assumes you know which sibling orgs sit on each
  handoff and what each one is optimizing for.
- The engineer-level AI SRE and performance-engineering
  curricula go deeper on the technical content of the interfaces
  — serving APIs, training-platform contracts, rollback windows,
  deprecation protocols — that your coordination work negotiates
  over. If your team's cross-team load is mostly technical
  integration rather than scope and priority negotiation, do the
  relevant sections of those modules alongside this one.
- The senior-architect-learning repo's executive-leadership
  modules go deeper on organization-level coordination — managing
  across multiple teams of teams, running a multi-quarter program,
  cross-org politics. If your coordination work keeps running
  into questions that are not yours to answer, those modules are
  the next layer.

## What success looks like at the end of the module

You should finish the module with four concrete artifacts:

1. A **written cross-team surface** for the team you used — one
   contract per peer team, listing scope, owner on each side,
   interface, sync cadence, and escalation path, at enough
   detail that another lead could pressure-test it.
2. A **bidirectional dependency picture** — what your team is
   waiting on, what other teams are waiting on your team, when
   each handoff is expected, and the confidence level on each —
   visible to the teams on both ends.
3. A **sync cadence design** — which meeting exists for which
   relationship, at what frequency, with what agenda shape, and
   the signals you watch for to know when a sync has decayed
   into status reporting and needs to be restructured or killed.
4. A **set of signals** — not metrics, signals — you will watch
   for to catch a cross-team relationship going at-risk before
   it fails: the peer lead who has stopped replying in the sync,
   the dependency that keeps sliding by a week at a time, the
   escalation that got routed around you, the handoff that is
   showing up as a surprise in your team's standup.

If any of those four is missing or hand-wavy, you are not done.
The quiz is designed to catch the most common gaps.

Success is not "I have perfected cross-team coordination." Every
new team you work with, every new interface, every new quarter
is a new instance of the same skills under different constraints.
Success is "I can run the basic cycle on purpose — contract,
dependency picture, sync, escalation, renegotiation — defend the
choices I made in it, and recognize when a relationship is
drifting away from what the work actually needs."

## Before you start

Pick the team and the cross-team situation you will use for the
exercises before you open the lecture notes. Write one paragraph
about that team's current cross-team surface: which peer teams it
coordinates with, what the active interfaces are, which
relationship is currently working best, and which one is
currently most at risk. Keep the paragraph beside you as you
read; the lecture will land harder if you are reading it against
a real backdrop. Then open
[`lecture-notes/01-overview.md`](lecture-notes/01-overview.md)
and begin.
