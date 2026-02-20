# Rotation and Load Audit

## Mapping Incident Involvement and Identifying Concentration Patterns

**Part of the [Resilience by Design](../README.md) toolkit**

---

## Purpose

One of the most common patterns in security team burnout is invisible 
concentration—the same people consistently carrying the heaviest load without 
anyone having a clear picture of how unevenly the weight is distributed.

This happens gradually. A senior responder gets pulled into a difficult case 
because they have the most context. Then the next one. Rotations technically 
exist, but they get overridden during escalations. Someone stays engaged after 
handing off because it's hard to fully let go. Over time, a small number of 
people absorb a disproportionate share of the highest-pressure work, and the 
system starts to depend on that without ever explicitly deciding to.

The problem is that this pattern is rarely visible in standard metrics. Ticket 
counts don't distinguish between routine cases and multi-day, high-ambiguity 
incidents that drain decision-making capacity. On-call schedules show who was 
technically on rotation, not who actually carried the weight.

This audit makes the invisible visible. It's a simple exercise designed to help 
leaders map who has been involved in high-impact incidents over a defined period, 
identify where load is concentrating, and determine whether rotations and 
boundaries are functioning as intended.

---

## When to Use This

- **Quarterly**, as part of the 
  [Quarterly Team Resilience Review](quarterly-resilience-review.md)
- After a period of sustained high-tempo operations (multiple major incidents 
  in a short window)
- When you notice early burnout signals on the team and want to understand 
  the structural picture
- During team planning or staffing discussions where you need data to support 
  what you're observing

---

## How to Use This

This audit has three parts:

1. **Map recent incident involvement** across your team
2. **Review rotation and boundary adherence**
3. **Identify patterns and decide on actions**

Set aside 30–60 minutes. You can do this alone as a manager, or collaboratively 
with a co-lead or trusted peer. Having a second perspective often surfaces 
patterns you've normalized.

---

## Part 1: Incident Involvement Mapping

### Step 1: Identify High-Impact Incidents

Look back over the past **90 days** (or adjust the window to match your 
operational tempo). Identify the incidents that had the highest impact on 
the team. You're not looking for every case—you're looking for the ones that 
required the most from the people involved.

Use whatever criteria make sense for your team. Common indicators:

- Extended duration (multi-day, overnight, weekend)
- High customer impact or customer distress
- Significant ambiguity or incomplete information
- Heavy decision load
- Escalation to senior leadership
- Emotional weight (difficult customer outcomes, high-stakes consequences)

List 5–10 incidents. If you've had fewer than 5 high-impact incidents in 90 
days, expand the window or include medium-impact cases.

### Step 2: Map Involvement

For each incident, record who was involved and what role they played. Use 
the following table or adapt it for your context.

| Incident | Date(s) | Duration | Primary Responder(s) | Key Decision Maker(s) | Supporting / Consulted | After-Hours Work | Notes |
|----------|---------|----------|---------------------|-----------------------|----------------------|-----------------|-------|
|          |         |          |                     |                       |                      |                 |       |
|          |         |          |                     |                       |                      |                 |       |
|          |         |          |                     |                       |                      |                 |       |
|          |         |          |                     |                       |                      |                 |       |
|          |         |          |                     |                       |                      |                 |       |

A few notes on filling this out:

- **Primary Responder(s):** Who was hands-on driving the response?
- **Key Decision Maker(s):** Who made the critical calls? This may or may not 
  be the same person as the primary responder.
- **Supporting / Consulted:** Who was pulled in for expertise, review, or 
  assistance? Include people who weren't officially assigned but contributed 
  anyway—this is often where invisible load lives.
- **After-Hours Work:** Did anyone work outside their normal schedule for this 
  incident? Note who and roughly how much.
- **Notes:** Capture anything relevant—was someone on PTO and pulled back in? 
  Did someone stay engaged after handing off? Was a rotation boundary overridden?

### Step 3: Count and Visualize

Create a simple summary of how often each team member appears across the 
incidents you mapped.

| Team Member | Appeared as Primary | Appeared as Decision Maker | Appeared as Supporting | After-Hours Involvement | Total Appearances |
|-------------|-------------------|--------------------------|---------------------|----------------------|------------------|
|             |                   |                          |                     |                      |                  |
|             |                   |                          |                     |                      |                  |
|             |                   |                          |                     |                      |                  |
|             |                   |                          |                     |                      |                  |
|             |                   |                          |                     |                      |                  |

Look at the distribution. You're looking for:

- **Names that appear in almost every row.** These are your concentration risks.
- **Names that rarely appear.** Are they being underutilized, or are they not 
  yet trusted with high-impact work? Both are worth examining.
- **People who appear frequently in the "Supporting / Consulted" column but 
  not as Primary.** This often indicates someone carrying invisible load—they're 
  not officially assigned but they're consistently being pulled in.
- **After-hours patterns.** Is the same person always the one working nights 
  and weekends?

---

## Part 2: Rotation and Boundary Review

This section examines whether your structural protections—rotations, on-call 
boundaries, time off—are functioning as designed or being routinely overridden.

Answer the following questions honestly. If you're not sure about some of them, 
that's a finding in itself.

### On-Call and Rotation Boundaries

- How many times in the past 90 days was an on-call rotation overridden or 
  extended for a specific individual?
- Were there cases where someone who was technically off-rotation was pulled 
  back in? How often? Who?
- When someone hands off a case at the end of their rotation, do they actually 
  disengage? Or do they continue monitoring, reviewing notes, or weighing in?
- Are there people on the team whose "off-rotation" behavior is 
  indistinguishable from their "on-rotation" behavior?

### Recovery and Time Off

- After the high-impact incidents you mapped in Part 1, was there a deliberate 
  recovery period for the people most involved?
- Did anyone go from one major incident directly into another without a buffer?
- Has anyone on the team had PTO interrupted or shortened due to operational 
  needs in the past 90 days?
- When people take time off, do they actually disconnect? Are there timestamps 
  (messages, logins, case activity) that suggest otherwise?

### Escalation Patterns

- When a case escalates, who gets called first? Is that by design or by habit?
- Are escalation paths documented and followed, or do they default to whoever 
  is most experienced or most available?
- When a critical case comes in, is there a genuine choice about who handles 
  it, or does it effectively always go to the same person?

---

## Part 3: Identifying Patterns and Taking Action

### Pattern Recognition

Based on Parts 1 and 2, answer the following:

- **Who are the top 2–3 people carrying the most concentrated load?** 
  Write their names down. This is important to make explicit rather than 
  leaving it as a general impression.

- **What would happen if one of those people was unavailable for 30 days?** 
  Not a hypothetical about whether someone could technically cover—an honest 
  assessment of what would break, slow down, or degrade.

- **Are your rotations protecting people, or are they being routinely 
  overridden?** If they're being overridden more often than not, they're 
  not rotations—they're suggestions.

- **Is invisible load showing up in your data?** People who aren't officially 
  on high-impact cases but keep appearing in the supporting column. People 
  whose after-hours activity tells a different story than their schedule.

- **Is recovery actually happening between high-impact events?** Or is the 
  pace such that the team moves from one surge to the next without real space 
  in between?

### Action Planning

For each pattern you identified, define at least one concrete action. 
Avoid vague commitments like "distribute work more evenly." Be specific.

| Pattern Identified | Action | Owner | Timeline |
|-------------------|--------|-------|----------|
|                   |        |       |          |
|                   |        |       |          |
|                   |        |       |          |

Examples of concrete actions:

- "Alex has been primary on 7 of the last 9 high-impact incidents. For the 
  next 30 days, Alex will not be assigned as primary on any new escalations 
  unless no other qualified responder is available. Jordan and Sam will take 
  primary on the next two escalations with Alex available for consultation 
  only."

- "Rotation handoffs are not resulting in actual disengagement. Starting next 
  sprint, we will implement a 'clean break' protocol where the outgoing 
  responder is removed from the case channel after handoff and the incoming 
  responder is explicitly designated as the point of contact."

- "Three team members worked after-hours on incidents they weren't assigned 
  to. In the next team meeting, we will discuss norms around off-rotation 
  engagement and make explicit that monitoring cases you've handed off is 
  not expected."

---

## Tracking Over Time

This audit is most valuable when repeated. Run it quarterly and compare 
results. You're looking for:

- Whether concentration is improving or persisting
- Whether actions from previous audits actually changed anything
- Whether new concentration patterns are emerging as the team composition 
  or operational tempo changes

Keep a simple log:

| Quarter | Key Findings | Actions Taken | Results |
|---------|-------------|---------------|---------|
|         |             |               |         |
|         |             |               |         |
|         |             |               |         |

This log feeds directly into the 
[Quarterly Team Resilience Review](quarterly-resilience-review.md).

---

## A Note on Using This Data

The purpose of this audit is to improve the system, not to create a 
performance evaluation of individuals. If someone appears on every incident, 
the question isn't "why is this person always involved?" The question is 
"why does the system keep routing the hardest work to the same person, and 
what needs to change structurally to distribute it?"

Be careful about how you use and share this data. The goal is to make 
invisible patterns visible so you can act on them—not to make individuals 
feel surveilled or penalized for the load they've been carrying.

If anything, the people who show up most often in this audit are usually 
the ones who deserve the most recognition and the most protection. They've 
been holding the system together. Leadership's job is to make sure the 
system doesn't require that of them indefinitely.
