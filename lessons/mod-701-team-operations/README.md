# mod-701-team-operations: Team Operations + Cadences

**Level**: team-lead-learning
**Duration**: 30-50 hours
**Prerequisites**: senior-engineer or senior-architect level

## Overview

This module is about the operating system you build around your team. It is
not about Scrum vs. Kanban, and it is not about meeting etiquette. It is about
the small number of recurring activities — standups, retrospectives, planning,
on-call handoff, written updates — that collectively determine whether your
team ships, whether its problems surface early, and whether its people stay.

For an AI Infrastructure Team Lead, the stakes of getting this right are
higher than they are for a generic engineering lead. Your team sits on the
critical path for every model deployment, every training run, every inference
endpoint that other orgs depend on. When your team's operations slip, the
symptoms show up as slow rollouts, surprise capacity crunches, GPU spend that
nobody owns, and a pager rotation that quietly burns out your best engineers.
None of those failure modes are architectural. They are operational.

This module takes the position — argued at length in the lecture notes —
that team operations is a first-class technical skill, not organizational
overhead. You will spend ~30-50 hours here: reading, applying the ideas to
your own team, and completing five exercises that force you to make
concrete operating decisions. By the end, you should be able to design a
team-level operating cadence that fits the shape of your team's work,
justify your choices to a skeptical peer, and change the design when the
team changes.

## Learning Objectives

By the end of this module you will be able to:

- **Standups, retros, planning.** Design the synchronization, reflection,
  and planning rituals your team needs; defend the cadence you chose for
  each; and recognize when a ritual has decayed into theater.
- **Async + sync communication.** Decide, for a given team artifact (a
  decision, a status, a design, an incident), whether it belongs in a
  meeting, a written doc, a chat thread, or a dashboard — and build the
  defaults that make the right choice automatic.
- **On-call and operational rituals.** Structure the on-call rotation,
  release review, and incident retro loop so that your AI-infra systems
  stay reliable without your team burning out.
- **Ritual maintenance.** Diagnose a failing ritual, decide whether to
  fix it, replace it, or kill it, and set up the ownership and quality
  bar that keeps it healthy over time.
- **Operating-model fit.** Match the operating cadence to the work
  shape — platform vs. project, steady-state vs. ramp, small team vs.
  team of teams — and re-design when the shape changes.

These objectives are not independent. The hardest version of this work
is not picking the right rituals in the abstract; it is keeping the full
set of them coherent, sized to the team, and aimed at the actual work.

## Why this module exists at this level

You have passed through senior IC or senior architect, which means you
already know how to execute inside a team's operating system. This module
is the inverse: it is about *designing* that operating system for other
engineers to execute inside of.

The shift is uncomfortable. As a senior engineer you optimized the
rituals around your own throughput — you learned which meetings to skip,
which docs to actually read, which Slack threads deserved a response.
Those optimizations do not generalize. The operating model you build for
your team has to work for the engineer who is six months in and still
getting their bearings, the staff engineer who thinks all process is
waste, the newly promoted senior who is quietly overloaded, and the
on-call engineer at 2 a.m. on a Saturday. Your personal preferences are
no longer the right calibration.

The lecture notes argue that a well-operating team is a *multiplier* on
engineering output, not an overhead cost. That is the framing to carry
through the module. Every ritual decision should be judged against the
question: "Does this increase the team's effective output per engineer,
or does it just move work around?"

## What this module covers

The module is organized around four kinds of rituals and the cadences
they run on. Each kind answers a different structural problem.

**Synchronization rituals** keep everyone aware of what others are
doing without forcing them to ask. Daily standups, weekly written
updates, and shared dashboards all fit here. The goal is mutual
awareness, not status reporting. For an AI-infra team this is where
you catch the "I'm about to drain a GPU pool that someone else's
training run depends on" collision before it happens.

**Planning rituals** commit the team to what it will do next. Sprint
planning, quarterly OKRs, roadmap reviews, and capacity-planning
sessions fit here. The goal is alignment on commitments, not schedule
optimization. The AI-infra specifics — which fleet upgrade lands
which quarter, when the new model family's serving stack must be
ready, how much headroom to leave for unplanned research spikes —
all get decided in planning rituals.

**Reflection rituals** look back on what worked and what did not.
Retros, post-incident reviews, personal 1-1s, and skip-level
conversations fit here. The goal is improvement over time and
early surfacing of problems, not blame allocation. In AI-infra,
post-incident reviews double as the mechanism by which the team
learns what the model, the hardware, and the serving stack actually
do under stress.

**Operational rituals** carry the team's commitments to the rest of
the organization. On-call handoff, release reviews, customer
escalation triage, change-management reviews, and SLO reviews all
fit here. The goal is consistent service quality — the team's
behavior toward the rest of the org should be predictable even
when internal capacity is stretched.

The lecture notes go deeper on each. The exercises push you to apply
the framing to a specific scenario — your real team if you have one,
or a case study team if you do not.

## Module Structure

- **README (this file).** Scope, objectives, and how to work through
  the module.
- **`lecture-notes/01-overview.md`.** The core argument: why team
  operations matters, what rituals exist, how cadences work, and
  what the team lead's actual job is in all of this. Read this
  first and re-read it after the exercises; it reads differently
  once you have tried to apply it.
- **`exercises/exercise-01-case-study.md`.** A strategic case-study
  exercise. You walk into a team mid-flight, diagnose what is
  broken about its operating model, and propose a redesign.
- **`exercises/exercise-02-strategy-memo.md`.** A short written memo
  justifying a specific operating-model change to a skeptical
  stakeholder. Forces precision about tradeoffs.
- **`exercises/exercise-03-stakeholder-mapping.md`.** Maps the
  people inside and outside the team whose expectations your
  operating rituals have to serve. A team's rituals only work if
  the surrounding org knows what to expect from them.
- **`exercises/exercise-04-roadmap.md`.** A quarter-to-year roadmap
  for rolling out operating-model changes without stalling delivery.
  Change management applied to your own team.
- **`exercises/exercise-05-presentation.md`.** A short presentation —
  built for a peer review session — that defends your operating
  model choices to another team lead. The ask is to be concrete and
  defensible, not comprehensive.
- **`quiz.md`.** Strategic-thinking questions to test your
  framing. They do not have single right answers; they test
  whether you can defend the choice you made.
- **`resources.md`.** Frameworks and further reading. Treat these as
  pointers, not a reading list — pick what fits the problem in
  front of you.

The module is designed to be worked in order. Lecture first, then
the exercises in sequence (01 sets up the scenario the later
exercises build on), then the quiz. Expect the exercises to take
longer than the lecture; most of the learning is in the application.

## How to work through this module

The module is sized at 30-50 hours. That range is wide on purpose. If
you already lead a team and the exercises map directly onto decisions
you need to make anyway, you will be at the low end — you are mostly
converting intuition into explicit design. If you are approaching
this as a senior IC or architect getting ready for a lead role and
you are using a case-study team, plan for the high end — you have to
build the intuition as you go.

A workable rhythm:

1. **Read the lecture notes once.** Do not stop to take extensive
   notes; aim for the shape of the argument.
2. **Write down the operating model of a team you know.** Real or
   case-study. Write it in prose, not a diagram. If you cannot write
   it down in under a page, something is already wrong.
3. **Do Exercise 01.** Diagnose what is wrong with the operating
   model you wrote down. Do not propose fixes yet. The goal is
   diagnosis, and diagnosis is harder than it looks.
4. **Do Exercises 02-04 in sequence.** Each one tightens the design:
   the memo forces you to justify changes, the stakeholder map
   forces you to account for who the changes affect, the roadmap
   forces you to sequence them.
5. **Do Exercise 05.** Defend the design to a peer. If you cannot
   get a real peer to review it, write the defense anyway — the
   writing surfaces the weak points.
6. **Re-read the lecture notes.** The second pass is where the
   framing actually sticks. If specific sections now feel obvious,
   that is the point.
7. **Do the quiz.** Treat the questions as prompts for a short
   written answer each. The quiz is a self-check on whether you
   can defend your operating-model choices, not a knowledge test.

Resist the temptation to do this module "in theory" without a
specific team in mind. The framings only land when they are applied
to a concrete team with specific people, work shape, and constraints.
If you do not have a team of your own, borrow one — ask another
lead if you can shadow their rituals for a week before starting the
exercises.

## AI-infra specific angles to watch for

The lecture notes cover team operations as a general skill. A few
places where the AI-infra context changes the defaults:

**On-call for GPU fleets and serving stacks is louder and more
bursty than typical web-service on-call.** A single bad rollout or
capacity miss can page the full rotation. Your operational-ritual
cadence has to assume that incident load is not uniform — budget
for the week after a major deploy differently than a steady-state
week.

**Capacity-planning is a recurring planning ritual, not a one-off.**
GPU supply, model-family mix, and traffic shape all move faster
than typical compute planning. Most AI-infra teams need a
dedicated planning ritual — monthly or quarterly — separate from
sprint planning, aimed at the next two to four quarters of
capacity, not the next two weeks of delivery.

**Cross-team coordination load is higher than for a self-contained
product team.** You hand serving endpoints to AI Engineering, you
take artifacts from ML Engineering, you give evidence to
Governance, you report cost to Startup/Finance, and you absorb
usage pain from AI Workforce. Your synchronization rituals have to
reach outside the team in a structured way, or the handoffs will
run on ad-hoc Slack threads that forget to include the people who
most need to be in the loop. Module 00 is the reference for who
sits on each handoff.

**Post-incident reviews double as hardware and model learning.** A
good incident retro in AI-infra does not just capture what went
wrong operationally — it also captures what the hardware or model
actually did, information that is often tacit elsewhere. Budget
the retro accordingly.

**Written-first communication scales better than it does for
pure product teams.** AI-infra decisions have long tails
(rollback windows, capacity commitments, cost impact). Oral
decisions evaporate; written decisions survive long enough to be
audited. Default to writing.

Each of these gets picked up in more detail in the other modules in
this track, especially mod-703 (planning and roadmap), mod-704
(cross-team coordination), and the on-call sections across the
engineer-level AI SRE curriculum. Keep the connections in mind as
you work through mod-701; the operating model you design here is
the surface the later modules plug into.

## Prerequisites and companion modules

This module assumes you have operated as a senior IC or senior
architect, which means:

- You have been *inside* at least one team's rituals for long enough
  to have opinions about them. If you have never participated in a
  retro or a sprint planning, the exercises will feel abstract.
- You have made at least one meaningful technical decision that
  depended on cross-team coordination. The communication exercises
  assume you have felt the pain of a coordination failure.
- You have shipped something that paged you later. The on-call
  framings assume you have lived with the consequences of your own
  design decisions.

Within the team-lead track, this module is the natural first stop
because every other module (people management, roadmap, cross-team
coordination, hiring) runs on top of the operating model you design
here. If you work them out of order you will find yourself
re-doing decisions.

Outside the track:

- [Module 00: Your Relationship to the Model](../00-your-relationship-to-the-model/README.md)
  is the required orientation. If you have not done it, start
  there; this module assumes you know where your team sits
  relative to the model and the five sibling orgs.
- The engineer-level AI SRE and performance-engineering
  curricula go deeper on the on-call and incident-response
  content that this module only sketches. If your team's
  operational load is high, do those modules alongside this one,
  not after.
- The ML Engineering Staff-level and AI Engineering Platform
  modules describe the operating rituals on the other side of
  your handoffs. Reading the summary chapter of each helps you
  design your synchronization rituals so they interlock with
  theirs.

## What success looks like at the end of the module

You should finish the module with four concrete artifacts:

1. A **written operating-model document** for a specific team —
   real or case-study — that lists each ritual, its cadence, its
   owner, and the problem it solves.
2. A **short defense of each cadence choice**, usually one or two
   sentences per ritual, that another lead could challenge.
3. A **90-day change plan** for moving an existing team from its
   current operating model to the one you designed, without
   stalling delivery.
4. A **set of signals** — not metrics, signals — you will watch for
   to know whether the new model is working at 30, 60, and 90
   days.

If any of those four is missing or hand-wavy, you are not done. The
quiz is designed to catch the most common gaps.

Success is not "I have a perfect operating model." Teams change,
and any operating model you build this quarter will need
re-design within a year. Success is "I can design one on purpose,
defend it, and recognize when it needs to change."

## Before you start

Pick the team you will use for the exercises before you open the
lecture notes. Write one paragraph about that team — its size,
what it owns, what its current operating rhythm looks like, and
the one thing about its operations that bothers you. Keep the
paragraph beside you as you read; the lecture will land harder
if you are reading it against a real backdrop. Then open
[`lecture-notes/01-overview.md`](lecture-notes/01-overview.md) and
begin.
