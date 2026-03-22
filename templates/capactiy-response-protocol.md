# Capacity Response Protocol

## Pre-Defining How Your Team Responds When Someone Hits Their Limit

**Part of the [Resilience by Design](https://github.com/4n6lady/resilience-by-design/blob/main/README.md) toolkit**

---

## Why This Exists

Section 5 of the [Resilience by Design toolkit](https://github.com/4n6lady/resilience-by-design/blob/main/toolkit/resilience-by-design-toolkit.md#5-psychological-safety-as-an-operational-requirement)
covers psychological safety and the language to normalize on your team:
- "I'm at capacity."
- "Can someone else take point?"
- "I need to step away
after this call."

That's the first step. But normalizing the language only works if the
team knows what happens next.

If someone says "I'm at capacity" and the room goes quiet, or the
manager figures it out case by case, or the same person ends up
absorbing the load anyway, the language stops being safe to use.
People learn that saying it creates awkwardness without producing
relief, and they stop saying it.

The second step is deciding, in advance and as a team, what the
response looks like. Not in the moment of the crisis—before it, but when everyone is calm, when there's time to think, when the
decision isn't being made under the exact conditions that make
good decisions hard.

This template helps you build that protocol.

---

## How to Use This

This is a working document, not a one-time exercise. Work through it
with your team or develop a draft to bring to your team for input.
The goal is a protocol your team has actually agreed to—not one that
was handed down and assumed to be understood.

Revisit it after major incidents, when the rotation changes, or when
the protocol breaks down and you need to understand why.

---

## Part 1: The Capacity Decision Framework

When workload exceeds what someone can sustain, there are only four
ways to manage it. This framework (drawn from Woods and Hollnagel's
work on cognitive systems engineering) makes those options explicit
so your team can work through them deliberately rather than defaulting
to unmanaged overload.

For any incoming work request that exceeds current capacity, work
through the following in order:

---

### Step 1: Shed Load

**The question:** Is there something we are currently doing that we
can safely stop doing—or pause—to make space for this?

This is the first question because it's the most honest. In high-tempo
environments, teams accumulate work that was once important and is
no longer the priority. When capacity is constrained, those tasks need
to be explicitly set aside rather than passively deprioritized while
still occupying someone's mental inventory.

**What to examine:**
* Active cases or tickets where the priority has dropped but nobody
  has formally acknowledged that
* Follow-up work from previous incidents that is still running but
  not urgent
* Meetings, reporting, or administrative work that can be deferred
* Non-critical monitoring or review work that can be paused or
  handed to a lower-load team member

**Document it here:**

| Work that can be shed or paused | By whom | For how long |
|---|---|---|
| | | |
| | | |
| | | |

If load can be shed: do that first, before moving to the next step.

If not: move to Step 2.

---

### Step 2: Reduce Thoroughness

**The question:** Is there a non-standard but still acceptable way
to accomplish this work given current constraints?

This is not an invitation to cut corners on things that matter. It's
an explicit, acknowledged decision to accept a reduced level of
thoroughness in specific areas so that the most critical work can
still be done well.

The key word is *acceptable*. This step requires naming what
"acceptable" means for your team and your context—because without
that definition, teams will either refuse to reduce thoroughness
at all (and overload silently) or reduce it on the wrong things
(and create quality or security risk).

**Examples in incident response:**
* Accepting a shorter initial written summary rather than a full
  timeline when a second incident opens before the first is closed
* Delegating customer communication to a less-experienced responder
  with a senior responder available for review rather than leading it
  directly
* Using a templated response for a known incident pattern rather
  than a fully custom analysis when volume is high

**What's explicitly acceptable for your team:**

| Situation | Standard approach | Acceptable reduced approach | Who decides this is appropriate |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

**What is never acceptable to reduce, regardless of load:**

| | |
|---|---|
| 1. | |
| 2. | |
| 3. | |

These non-negotiables should be named explicitly. If your team
doesn't define them, individuals will define them differently under
pressure, and the results will be inconsistent.

If a non-standard approach is acceptable: document the decision and
proceed. If not: move to Step 3.

---

### Step 3: Time-Shift the Work

**The question:** Can this work be deferred without creating
unacceptable risk?

Not everything that feels urgent is urgent. Some of the pressure
in incident response comes from an organizational culture that
treats everything as P1 until someone explicitly says it isn't.

This step asks your team to make a genuine assessment: if this
work waited four hours, or until tomorrow, or until the next
rotation, what would the actual consequence be?

**Questions to work through:**
* What is the cost of a four-hour deferral? A 24-hour deferral?
* Is there a customer, compliance, or contractual deadline that
  makes deferral genuinely unacceptable?
* Is the urgency real, or is it urgency by default—because nobody
  has explicitly said otherwise?

**Your team's deferral thresholds:**

| Work category | Maximum acceptable deferral | Conditions that override this |
|---|---|---|
| Active P1 customer incident | None | — |
| Active P2 customer incident | | |
| Post-incident documentation | | |
| Internal reporting | | |
| Non-urgent customer follow-up | | |
| Other: | | |

If the work can be time-shifted: assign a specific deferral window
and an owner. Unassigned deferrals evaporate.

If not: move to Step 4.

---

### Step 4: Increase Resources

**The question:** Can we bring in additional capacity to handle
this work?

This is listed last—not because it's least important, but because
it's the step teams often jump to first, skipping the earlier
questions. Pulling in additional capacity has a cost: it draws on
people who may themselves need recovery, and it can create its own
concentration and handoff problems if done without care.

When increasing resources is the right answer, it should be
done deliberately.

**Guidance on who to bring in:**

When pulling in additional coverage, work backward from the
last person on the rotation rather than forward from the most
recent. The person who just rotated off may not have had time
to recover. The next person up may need to be preserved for
what's coming. The person two rotations back is more likely
to have genuine capacity.

**Your escalation sequence:**

| Position | Name/Role | Contact | Notes |
|---|---|---|---|
| Primary on-call | | | |
| Secondary on-call | | | |
| Previous rotation (available if rested) | | | |
| Manager / team lead | | | |
| Cross-team escalation | | | |

**Conditions that trigger automatic resource addition:**

Some conditions should trigger additional coverage without
waiting for someone to ask for it. Defining these in advance
removes the barrier of having to self-identify as overloaded.

Examples:
* Incident duration exceeds [X] hours
* Active case count exceeds [X] per on-call responder
* Overnight work is required
* Customer is in active distress or executive-level escalation
* [Your condition here]

| Condition | Automatic action |
|---|---|
| | |
| | |
| | |

---

### If None of the Above Applies

If you have worked through all four steps and none of them produced
a managed response, you are in unmanaged overload.

Name it explicitly. Don't let it be silent.

Unmanaged overload managed silently produces individual burnout.
The system "solves" it by having the most capable, most conscientious
people absorb more than they should—precisely because they are capable
and conscientious enough to do it. That's not resilience. That's
quietly borrowing against people's capacity without acknowledgment
or repayment.

When you reach this point:
* Tell your manager or the person above you in the chain that
  the team is in unmanaged overload. Not as a complaint—as
  operational information.
* Document what conditions produced this situation. It is
  an input for future staffing, rotation design, and capacity
  planning.
* Return to Step 1 in the next planning cycle and examine
  whether any of the earlier options were more available than
  they appeared.

---

## Part 2: Pre-Defined Responses by Expression

The language in Section 5 of the toolkit works because it's
specific. Each phrase names a particular state. This section
pre-defines what the team does when each phrase is used.

Fill this out as a team. These aren't manager directives—
they're shared agreements.

---

### "I'm at capacity."

**What this means:** The person using this phrase is at or beyond
the point where they can take on additional cognitive or emotional
load without degrading their performance or their own sustainability.

**Immediate team response:**

Who is responsible for acknowledging this?

_________________________________________

What happens to their current work?

[ ] They retain current cases but no new work is routed to them  
[ ] Cases are triaged — critical cases remain, non-critical are redistributed  
[ ] Full handoff to secondary  
[ ] Other: ___________________________________

How long does the protection last?

[ ] Until the end of current rotation  
[ ] Minimum [___] hours  
[ ] Until they indicate they have capacity again  
[ ] Other: ___________________________________

Who is responsible for ensuring no new work is routed to them
during this period?

_________________________________________

---

### "I don't know yet."

**What this means:** The person needs investigation time before
they can make a decision or provide an update. This is not a
failure — it's accurate information about the current state of
the case.

**What this is not:** A signal that the person needs to be
replaced on the case.

**Pre-defined investigation thresholds for your team:**

| Case type / priority | Maximum investigation time before decision-point or escalation |
|---|---|
| P1 | |
| P2 | |
| P3 / lower | |

After the threshold, the expected action is:

[ ] Mandatory check-in with manager or lead  
[ ] Mandatory second responder added to the case  
[ ] Escalation to defined escalation path  
[ ] Other: ___________________________________

This makes "I don't know yet" safe to say by pairing it with
a clear, non-punitive next step. The phrase isn't a problem.
The absence of a defined next step is the problem.

---

### "Can someone else take point?"

**What this means:** The person needs to step back from the
primary responder role. This may be because of capacity, cognitive
load, emotional weight, or recognizing that a different person
is better positioned to lead this particular case.

**Pre-defined handoff process:**

Handoffs should always transfer: the current state of the case,
the key open questions, what's been tried, who else is involved
(customer contacts, internal stakeholders), and any time-sensitive
items. Verbal-only handoffs under pressure lose critical information.

Your minimum handoff format:

| Element | Notes |
|---|---|
| Case state summary | Written, not verbal |
| Open questions | |
| What's been tried | |
| Active contacts | Names and last contact time |
| Time-sensitive items | |
| Anything else the incoming responder needs to know | |

Who receives the handoff request?

_________________________________________

Maximum time between request and handoff completion:

_________________________________________

---

### "I need to step away after this call."

**What this means:** The person is acknowledging in advance that
they will need recovery time when the current engagement ends.
This is healthy self-monitoring. It should be met with a plan,
not problem-solving.

**Automatic actions when this is said:**

* [ ] Secondary on-call is notified that they may be needed
* [ ] The person is not assigned as primary for the next
  [___] hours without explicit check-in
* [ ] Manager acknowledges receipt and removes routing pressure
* [ ] Other: ___________________________________

Do not: ask them to finish the documentation first, route one
more quick case, or stay for the debrief unless they volunteer.

---

### "I think I missed something — can someone check behind me?"

**What this means:** The person is flagging potential gaps in
their own work. This is one of the most important signals a
responder can give. It takes psychological safety to say it,
and the response to it sets the tone for whether it's said again.

**Immediate response:**

Who is responsible for the review?

_________________________________________

Timeline:

[ ] Same rotation  
[ ] Within [___] hours  
[ ] Before case closure  
[ ] Other: ___________________________________

What the review covers:

_________________________________________

**What to explicitly avoid:**

Do not treat this as a performance issue. A responder who flags
that they may have missed something is doing exactly what you want.
A responder who doesn't flag it—because they've learned it creates
scrutiny rather than support—is the actual risk.

The response to this phrase should look indistinguishable from
a routine peer review request, so that asking for it carries no
additional cost.

---

## Part 3: Structural Protections That Reduce the Need to Ask

The best version of this protocol is one that doesn't require people
to self-identify as overloaded before the system responds. Some
of the protections below are structural—they activate based on
conditions rather than on someone having to say something.

Work through which of these you can implement for your team.

---

**Scheduled primary responder rotation maximums.**

What is the maximum number of consecutive hours a responder should
hold the primary role on an active incident before a mandatory
handoff?

Primary maximum: _______ hours

At that threshold, the following happens automatically:

_________________________________________

---

**Mandatory rest between rotations.**

After a rotation ends, what is the minimum protected rest period
before a responder can be pulled back in?

Minimum rest: _______ hours

Exceptions require:

_________________________________________

---

**Post-incident routing protection.**

After a major incident closes, the primary responders are
automatically placed on a protected routing status:

Duration: _______ hours or _______ days

During this period, they receive:

[ ] No new primary assignments  
[ ] Advisory or review role only  
[ ] Reduced caseload — maximum [___] cases  
[ ] Other: ___________________________________

This protection does not require the responder to ask for it.
It activates at incident closure.

---

**Mandatory second responder threshold.**

When a single responder has been the primary on a case for
longer than _______ hours, a second responder is automatically
added—not as escalation, but as support.

This protects against a single person holding all case context
while also managing sustained decision load.

---

**Load ceiling for simultaneous cases.**

The maximum number of active cases a single responder should
hold as primary at any time:

Maximum: _______

When this ceiling is reached, new cases are routed elsewhere
automatically. The responder does not need to declare overload—
the ceiling does it for them.

---

## Part 4: What to Do When the Protocol Breaks Down

Protocols break down. The rotation gets overridden because the
incident is critical. Someone says they're fine when they aren't.
The second responder isn't available. The ceiling gets ignored
because it feels faster to have the same person handle it.

When that happens, name it.

Not in a way that assigns blame—but in a way that acknowledges
the system failed to protect the people in it, and that uses
the failure as information rather than explanation.

After any incident where the protocol was materially bypassed, add
the following to your post-incident review:

* Which protection was bypassed?
* What conditions led to the bypass?
* What was the cost to the people involved?
* What change to the protocol—or to the conditions—would have
  made it possible to honor it?

If the protocol is being bypassed frequently, the protocol is
wrong, or the conditions are unsustainable, or both. Either way,
that needs to be named and addressed—not absorbed.

---

## Connected Resources

* [Resilience by Design Toolkit — Section 5: Psychological Safety](https://github.com/4n6lady/resilience-by-design/blob/main/toolkit/resilience-by-design-toolkit.md#5-psychological-safety-as-an-operational-requirement) —
  The foundation this protocol builds on. Normalizing the language
  is the first step; this protocol is the second.
* [Rotation and Load Audit](https://github.com/4n6lady/resilience-by-design/blob/main/templates/rotation-load-audit.md) —
  The data source for understanding whether the structural
  protections in Part 3 are actually functioning.
* [Post-Incident Team Check-In](https://github.com/4n6lady/resilience-by-design/blob/main/templates/post-incident-team-checkin.md) —
  The place where protocol breakdowns surface and should be
  captured as inputs for revision.
* [Quarterly Team Resilience Review](https://github.com/4n6lady/resilience-by-design/blob/main/templates/quarterly-resilience-review.md) —
  Part 2 (Recovery and Sustainability) is where the structural
  protections in this protocol should be reviewed for effectiveness
  each quarter.
* [Supporting Neurodivergent Team Members Through Burnout](https://github.com/4n6lady/resilience-by-design/blob/main/guides/neurodivergent-burnout-guide.md) —
  The structural protections in Part 3 of this protocol are
  particularly important for team members for whom self-identifying
  overload carries additional barriers.

---


*This work is licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://github.com/4n6lady/resilience-by-design/blob/main/LICENSE).*

The four-step capacity decision framework in this template was proposed by @leongc in Issue #4, drawing on Woods and Hollnagel's work in Joint Cognitive Systems: Patterns in Cognitive Systems Engineering. Contributions that improve or extend this resource are welcome.
