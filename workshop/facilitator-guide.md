# Workshop Facilitator Guide

## Running a Team Session on Resilience by Design

**Part of the [Resilience by Design](../README.md) toolkit**

---

## Purpose

This guide provides a structured format for running a team workshop 
based on the Resilience by Design toolkit. It's designed to move beyond 
awareness and into concrete action—helping teams collectively examine 
how they operate under pressure, where the hidden costs are, and what 
they want to change.

The [Psychological Safety Team Discussion Guide](../guides/psych-safety-team-discussion.md) 
offers a lighter-weight, single-topic conversation. This workshop is 
more comprehensive. It covers multiple dimensions of team resilience, 
includes hands-on exercises, and produces specific commitments that the 
team can act on afterward.

This is not a lecture. It's a facilitated working session. The value 
comes from what the team discovers together, not from someone 
presenting information at them.

---

## Who Should Facilitate

Ideally, the team's direct manager or team lead facilitates this 
session. The reason is simple: the person who facilitates signals 
that this matters, and the person with the most ability to act on 
what surfaces should be the one hearing it firsthand.

However, there are situations where an external facilitator or a 
peer from another team may be more appropriate:

- If the team's relationship with their manager is strained and 
  honesty might feel risky
- If the manager is themselves a significant part of the patterns 
  being discussed and their presence would limit candor
- If the manager wants to participate as a team member rather than 
  leading the session

If someone other than the direct manager facilitates, the manager 
should still be present as a participant unless there's a strong 
reason not to be. The goal is for leadership to hear what surfaces 
directly—not through a filtered summary afterward.

---

## Before the Workshop

### Timing and Context

**When to run this:**

- During a team offsite or dedicated development day
- After a sustained period of high-tempo operations, once the team 
  has had at least some recovery time
- As a quarterly or biannual practice for teams that want to build 
  resilience review into their operating rhythm
- When early burnout signals are appearing and you want to address 
  them proactively rather than waiting for visible impact

**When not to run this:**

- During an active incident surge or high-pressure period. The team 
  won't have the bandwidth for reflection, and forcing it signals 
  that you don't understand their current state.
- Immediately after a traumatic incident without any recovery buffer. 
  The [Post-Incident Team Check-In](../templates/post-incident-team-checkin.md) 
  is the right tool for that moment. This workshop is for when 
  there's enough distance to think structurally.
- As a response to a specific crisis (someone quitting, a visible 
  burnout event). If the team perceives this as reactive damage 
  control rather than proactive investment, trust will be undermined 
  from the start.

### Pre-Work

No required reading, but optional context helps. Consider sharing 
one or two of the following with the team a week before the session, 
framed as "some reading that will give context for a conversation 
we're going to have":

- [What Burnout in Security Teams Really Costs Us](https://www.linkedin.com/pulse/what-burnout-security-teams-really-costs-us-shannon-brazil-i2gwc) (Article 1)
- [Burnout Is Feedback: What Effective Leaders Do Differently](https://www.linkedin.com/pulse/burnout-feedback-what-effective-leaders-do-shannon-brazil-4rgnc) 
  (Article 3)
- The core idea section from the 
  [Resilience by Design Toolkit](../toolkit/resilience-by-design-toolkit.md)

Don't require it. People who read it will come in with context. 
People who don't will still be able to participate fully—the 
exercises are designed to work without background reading.

### Materials

- Whiteboard, shared document, or virtual equivalent for capturing 
  group output
- Sticky notes or a digital equivalent (Miro, FigJam, etc.) for 
  individual reflection exercises
- Timer (for keeping exercises on track)
- Printed or shared copies of any exercise templates used during 
  the session (provided in this guide)

### Room Setup

If in person, avoid a classroom or presentation layout. A circle 
or around-the-table arrangement signals that this is a conversation, 
not a briefing. If remote, use video (cameras encouraged but not 
required) and have a shared digital workspace ready.

---

## Workshop Formats

This guide is designed for a **half-day session (3 hours)** but 
includes guidance for adapting to shorter formats. The full session 
covers four modules. Shorter formats use a subset.

| Format | Duration | Modules |
|--------|----------|---------|
| Full workshop | 3 hours | All four modules + opening and closing |
| Focused session | 90 minutes | Opening + any two modules + closing |
| Team meeting | 60 minutes | Opening + one module + closing |

If you only have time for one module, choose based on what's most 
relevant to your team right now:

- **Module 1 (Load and Patterns)** if you suspect uneven 
  distribution but haven't made it visible
- **Module 2 (Recovery and Sustainability)** if the team has been 
  through a demanding period and recovery hasn't been addressed
- **Module 3 (Communication and Safety)** if the team struggles 
  with honesty about limits and capacity
- **Module 4 (Commitments)** only works after at least one other 
  module—it needs the preceding conversation to produce meaningful 
  output

---

## Full Workshop Structure

### Opening (15 minutes)

#### Setting the Frame (5 minutes)

Open by explaining what the session is and why you're running it. 
Be direct and genuine. If you're doing this because you've noticed 
patterns that concern you, say so. If you're doing it as a 
proactive investment, say that.

Suggested framing:

> "I want to spend the next few hours on something I think matters 
> a lot for how we work as a team. Not our technical processes or 
> our tooling—but whether the way we operate is actually sustainable.
>
> We're good at what we do. We handle hard incidents, we support 
> each other, and we deliver. But I want to make sure that the way 
> we're delivering doesn't depend on people quietly carrying more 
> than they should, or pushing through without real recovery, or 
> absorbing things that the system should be handling differently.
>
> This session is a chance to look at that honestly—together. 
> There's no documentation going outside this room. Nothing said 
> here affects performance evaluations. I'm asking for honesty 
> because I genuinely want to understand what's working and what 
> isn't, so we can make this team sustainable, not just effective."

Key points to hit:

1. This is about sustainability, not performance problems
2. Nothing leaves the room without the team's agreement
3. Honesty is what makes this valuable
4. You're participating, not just observing

#### Ground Rules (5 minutes)

Establish norms for the session. You can propose these and ask the 
team to add or modify:

- **What's said here stays here** unless the team explicitly agrees 
  to share something
- **No devices** unless needed for the exercises (this is 
  important—if people are monitoring cases during the session, 
  they're not present, and the session reinforces the very 
  pattern you're trying to examine)
- **No right answers.** Observations and honest experiences are 
  what we need, not polished takes
- **It's okay to pass.** Nobody has to speak on any given question 
  if they don't want to
- **Listen more than you debate.** When someone shares an 
  experience, the first response should be curiosity, not 
  correction

A note on the devices rule: if your team is currently on-call or 
there's a genuine operational need for someone to be reachable, 
designate one person to monitor and excuse them from the session 
if something comes in. Don't ask everyone to monitor "just in 
case." That defeats the purpose.

#### Individual Check-In (5 minutes)

Before diving into content, give everyone a moment to arrive 
mentally. Use a simple, low-stakes prompt:

> "On a scale of 1 to 5, where 1 is 'running on empty' and 5 is 
> 'fully charged,' where are you right now? You can share your 
> number, or just hold it in your mind."

If the team is comfortable sharing, go around briefly. Don't 
comment or problem-solve—just acknowledge. This serves two purposes: 
it gives you a read on the room, and it starts the practice of 
being honest about how people are actually doing.

---

### Module 1: Load and Patterns (40 minutes)

**Purpose:** Make visible how work, pressure, and cognitive load 
are distributed across the team.

This module is the most data-oriented part of the workshop. It 
draws on concepts from the 
[Rotation and Load Audit](../templates/rotation-load-audit.md) 
and the 
[Single Points of Cognitive Failure Mapping](../templates/cognitive-failure-mapping.md), 
but adapted for a group exercise rather than a solo leadership 
assessment.

#### Exercise 1: Incident Mapping (15 minutes)

**Setup:** On a whiteboard or shared document, list the 5–8 most 
demanding incidents from the past 90 days. These should be 
incidents the team collectively recognizes as high-impact. You can 
prepare this list in advance or build it together—building it 
together often surfaces incidents that leadership didn't realize 
were demanding.

**Activity:** For each incident, ask the team to identify:

- Who was most involved?
- Who carried the heaviest decision load?
- Who worked after hours or outside their rotation?
- Who stayed engaged after handing off?

Capture names on the board. You don't need precision—general 
agreement is sufficient.

**Facilitator note:** This exercise makes concentration patterns 
visible in a way that's hard to ignore. If the same 2-3 names 
appear across most incidents, the team will see it. You don't 
need to point it out—let the visual speak for itself. But be 
prepared for the people whose names appear most often to 
minimize it: "That's just how it works" or "I don't mind." 
Acknowledge their contribution without dismissing the pattern.

#### Exercise 2: What Would Break (10 minutes)

**Setup:** This exercise makes concentration risk concrete.

**Activity:** Ask the team:

> "Pick one person on this team—someone whose name came up a lot 
> in the last exercise, or someone who you know holds critical 
> context. Imagine they're completely unavailable for 30 days. 
> What would break, slow down, or degrade?"

You can do this as an open discussion or, if the team is larger, 
have people write answers individually first and then share. The 
individual-first approach often produces more honest answers 
because people don't anchor on the first person to speak.

**Facilitator note:** This exercise can feel uncomfortable for the 
person being discussed. Frame it clearly: "This isn't about any 
individual's importance or replaceability. It's about whether we've 
built redundancy into our team the way we'd build it into any 
critical system. If the answer is 'a lot would break,' that's 
feedback about the system, not about the person."

If the team is hesitant to name specific people, you can 
depersonalize it: "Think about the key areas of knowledge or 
capability on this team. Where does it live in one person's head?"

#### Group Discussion (15 minutes)

Bring the team together to discuss what the exercises revealed.

**Discussion questions:**

- "What patterns do you see in how load is distributed?"
- "Is this distribution deliberate, or has it evolved by default?"
- "What would need to change to make this more sustainable?"
- "Are there skills or context areas where we have no backup? 
  What's the risk there?"
- "For those whose names came up most often—how does that land? 
  Is this something you've been aware of? What's it been like?"

That last question is important. It gives the people carrying the 
most load an explicit invitation to say what it's costing them, 
in a setting where the team can hear it directly.

---

### Module 2: Recovery and Sustainability (40 minutes)

**Purpose:** Examine whether the team is actually recovering 
between high-pressure periods, and what gets in the way.

#### Exercise 3: Recovery Mapping (15 minutes)

**Setup:** Draw a simple timeline on the board covering the past 
90 days. Mark the high-impact incidents from Module 1 on it.

**Activity:** As a team, fill in the spaces between incidents:

- Was there recovery time between them?
- Were the same people involved in consecutive incidents without 
  a buffer?
- Were there periods where the team had genuine breathing room, 
  or has it been continuous?
- Did anyone have PTO during this period? Was it actually 
  respected, or was it interrupted?

The visual timeline often reveals something that individual memory 
obscures: the cumulative density of high-pressure work and the 
absence of real recovery between surges.

**Facilitator note:** If the timeline shows a relentless pace with 
no genuine recovery windows, don't rush past that observation. Let 
the team sit with it. This is often the moment where people realize 
that the "temporary" pace they've been enduring has become permanent.

#### Exercise 4: Individual Reflection — Recovery Honest Check (10 minutes)

**Setup:** Give everyone a few minutes for private reflection. 
Provide sticky notes or a digital equivalent.

**Prompt:** Ask each person to privately answer three questions. 
They'll choose what to share afterward.

1. "When was the last time you felt genuinely recovered—not just 
   'not actively in crisis,' but actually rested and ready?"

2. "What does good recovery actually look like for you? Not what 
   you think it should look like—what actually works?"

3. "What's the biggest barrier to recovery for you right now?"

Give 3-4 minutes of quiet writing time.

**Sharing:** Invite people to share whatever they're comfortable 
sharing. Start with question 3 (barriers to recovery) as it's 
the most actionable and least personally vulnerable. If people 
want to share answers to questions 1 and 2, let them.

**Facilitator note:** Question 1 often produces a long pause 
before people can identify an answer. That pause is data. If most 
of the team struggles to remember the last time they felt genuinely 
recovered, the session has already surfaced something important.

Question 2 is included because recovery isn't one-size-fits-all, 
and this connects to the toolkit's section on 
[supporting neurodivergent team members](../toolkit/resilience-by-design-toolkit.md#6-supporting-neurodivergent-team-members). 
What restores one person may not restore another. Leaders hearing 
directly what different team members need is valuable.

#### Group Discussion (15 minutes)

**Discussion questions:**

- "Looking at the timeline and what we've shared—is the way 
  we're operating sustainable for another six months?"
- "What would need to change for recovery to actually happen 
  between high-pressure periods?"
- "Are there structural barriers to recovery that we could 
  address—things about how we're organized, how handoffs work, 
  how cases are assigned?"
- "Is there work that continues after an incident is 'closed' 
  that we're not accounting for? Follow-through, documentation, 
  remediation, emotional processing?"
- "Do we treat recovery as real work, or as something that 
  happens if there's time left over?"

---

### Break (15 minutes)

If running the full three-hour workshop, take a break here. The 
first two modules are the most data-heavy and can be emotionally 
demanding. Give people space before moving into the more 
forward-looking modules.

A genuine break means not talking about the session content. Let 
people get coffee, check messages if they need to, and decompress. 
The irony of running a resilience workshop without building in 
recovery would not be lost on your team.

---

### Module 3: Communication and Safety (35 minutes)

**Purpose:** Examine what's easy and hard to say on the team, 
especially under pressure, and establish norms the team wants 
to commit to.

This module covers similar territory to the 
[Psychological Safety Team Discussion Guide](../guides/psych-safety-team-discussion.md) 
but in a condensed format within the broader workshop context. If 
you've already run that discussion as a standalone session, you can 
abbreviate this module or replace it with a check-in on how those 
commitments are going.

#### Exercise 5: What's Safe to Say (15 minutes)

**Setup:** Present the following phrases, either on the board or 
as a handout:

- "I'm at capacity."
- "I don't know yet."
- "Can someone else take point?"
- "I need to step away after this call."
- "I think I missed something—can someone check behind me?"
- "I need a break before taking on another case."
- "I'm not okay."

**Activity:** For each phrase, ask the team to rate (individually 
and silently first, then discussed):

- **How safe does it feel to say this on our team right now?** 
  (1 = very risky, 5 = completely safe)
- **How often is it actually said?** (Rarely / Sometimes / 
  Regularly)

You can do this with anonymous polling (digital tools make this 
easy), with sticky dots on a chart, or with a show of hands if 
the team is comfortable. Anonymous methods tend to produce more 
honest data.

**Facilitator note:** The gap between "how safe does it feel" and 
"how often is it actually said" is where the real insight lives. 
A phrase might feel moderately safe in theory but never actually 
get used—which tells you that the barrier isn't explicit risk but 
something more subtle: culture, habit, identity, or the fear of 
being the first one to say it.

Pay particular attention to "I'm not okay." If that one scores 
low on safety, it tells you something important about how far 
psychological safety has to go.

**Discussion:** After reviewing the ratings:

- "Where are the biggest gaps between 'safe to say' and 
  'actually said'?"
- "What do you think explains those gaps?"
- "For the phrases that scored lowest on safety—what would 
  need to change?"
- "Are there other things you wish were safe to say that 
  aren't on this list?"

#### Exercise 6: Designing Our Norms (20 minutes)

**Setup:** Shift from describing the current state to defining 
what the team wants to commit to.

**Activity:** As a team, develop three to five specific 
communication norms you want to adopt. These should be concrete 
and behavioral—not aspirational values.

The difference:

- Aspirational: "We value open communication."
- Concrete: "When someone says 'I'm at capacity' during an 
  incident, the first response is 'thank you'—followed by 
  identifying who can take over. We don't ask them to push 
  through."

Work through this together. For each norm, discuss:

1. **What's the specific behavior or phrase?**
2. **When does it apply?** (During incidents? In team meetings? 
   In 1:1s? Always?)
3. **What's the expected response from the team?**
4. **What would undermine this norm?** (Naming the anti-pattern 
   helps people recognize it when it happens.)

Capture the norms on the board. These become team commitments 
in Module 4.

**Facilitator note:** Resist the urge to generate too many norms. 
Three to five that the team genuinely commits to are far more 
valuable than ten that get written down and forgotten. Push for 
specificity—every time a proposed norm feels vague, ask "what 
would that actually look like in practice?"

The "what would undermine this norm" question is particularly 
valuable. It surfaces the behaviors that currently exist and 
need to stop, framed constructively as something the team is 
choosing to move away from rather than something someone is 
doing wrong.

---

### Module 4: Commitments and Action (30 minutes)

**Purpose:** Convert what the team has discussed into specific 
commitments—from the team, from leadership, and from individuals.

This module only works if the preceding modules have generated 
genuine conversation. If the workshop has been surface-level, 
the commitments will be surface-level too. If the conversation 
has been honest, this is where it becomes actionable.

#### Team Commitments (10 minutes)

Based on everything discussed, identify **three to five team-level 
commitments**. These should be specific, observable, and something 
the whole team owns.

**Prompt:**

> "Based on what we've discussed today—the load patterns, the 
> recovery gaps, the communication norms—what are the most 
> important things we want to commit to as a team?"

Examples of strong team commitments:

- "We will hold a decompression check-in within 48 hours of 
  every high-impact incident, using the 
  [Post-Incident Team Check-In Guide](../templates/post-incident-team-checkin.md)."

- "When someone flags their capacity during an incident, we 
  will respond with support first and reassignment second. We 
  will not ask them to push through."

- "We will respect rotation boundaries. Off-rotation means off. 
  If someone is needed outside their rotation, the manager makes 
  the call and it's logged—it doesn't happen by default."

- "We will actively distribute high-impact case assignments rather 
  than defaulting to the same people. The manager will track this 
  monthly."

- "We will recognize prevention, mentorship, and follow-through 
  work with the same visibility as crisis response."

Capture these somewhere the team can reference them. They should 
be visible and revisitable, not buried in meeting notes.

**Facilitator note:** Test each commitment with the question: 
"How will we know if we're actually doing this?" If the team 
can't describe what success looks like, the commitment is too 
vague. Push for observable behavior.

#### Leadership Commitments (10 minutes)

This is where the manager or team lead makes specific commitments 
to the team about what they will do differently.

**Prompt (for the facilitator/manager):**

> "Based on what I've heard today, here's what I'm committing 
> to. I want you to hold me to these."

This should be prepared in real-time based on what surfaced 
during the session, not scripted in advance. The authenticity 
of responding to what you actually heard matters more than 
having polished commitments.

Examples:

- "I'm going to run a 
  [Rotation and Load Audit](../templates/rotation-load-audit.md) 
  within the next two weeks and share the findings with the team."

- "I'm going to be more intentional about distributing 
  escalations rather than defaulting to whoever I'm most 
  confident in."

- "I'm going to model limit-setting myself. When I'm at 
  capacity, I'll say so instead of absorbing it."

- "I'm going to create a recovery buffer after major incidents. 
  The people most involved won't be assigned to the next 
  high-intensity case immediately."

- "I'm going to recognize invisible work more explicitly—in 
  1:1s, in team settings, and in performance conversations."

After sharing your commitments, ask: "Is there anything you 
heard today that you think I should be committing to that I 
haven't named?" Be prepared for honest answers.

#### Individual Reflection (10 minutes)

Close with a private, individual exercise. Not everything needs 
to be shared with the group.

**Prompt:** Give each person a few minutes to write down answers 
to the following:

1. "What's one thing from today's session that landed the most 
   for you?"

2. "What's one thing you personally want to do differently going 
   forward?"

3. "Is there anything you didn't say today that you want to 
   share with your manager privately?"

Questions 1 and 2 can optionally be shared with the group. 
Question 3 is explicitly private—it gives people an outlet for 
things that didn't feel safe to say in the group but that they 
want their manager to know. Collect these anonymously if 
possible, or let people know they can follow up in their next 1:1.

---

### Closing (10 minutes)

#### Summary (5 minutes)

Briefly recap what the session covered and the commitments that 
were made. Keep it concise—the team has been working hard for 
three hours and doesn't need a lengthy recap.

Hit these points:

- What you heard as the most important themes
- The team commitments
- Your leadership commitments
- When and how you'll follow up

#### Final Check-Out (5 minutes)

Mirror the opening check-in:

> "Same scale as the beginning: 1 to 5, where 1 is 'running on 
> empty' and 5 is 'fully charged.' Where are you now?"

This isn't about expecting everyone to be at a 5. The session 
may have surfaced difficult things. But comparing the opening 
and closing numbers gives you a sense of whether the session 
energized or depleted the team.

Close with genuine thanks:

> "Thank you for being honest today. What makes this valuable 
> isn't that we had a nice conversation—it's what we do with it. 
> I'll follow up on the commitments we made, and I'll check in 
> on how it's going. If anything from today is still on your mind, 
> my door is open."

---

## After the Workshop

The workshop is the beginning, not the end. What happens afterward 
determines whether it was meaningful or performative.

### Within One Week

- **Document the commitments** (team and leadership) and share 
  them with the team in a format they can reference. A shared 
  document, a pinned message in the team channel, a page in your 
  team wiki—whatever fits your workflow.

- **Review any private reflections** from the individual exercise 
  in Module 4. If people shared things they didn't say in the 
  group, follow up individually.

- **Start on any commitments that can begin immediately.** If 
  you committed to running a rotation audit, schedule it. If you 
  committed to distributing escalations differently, make the 
  first different choice the next time one comes in. Early visible 
  action builds trust that this wasn't just talk.

### Within One Month

- **Check in on commitments in a team setting.** This doesn't 
  need to be a formal review—a five-minute check-in during a 
  regular team meeting is enough. "A few weeks ago we committed 
  to [specific things]. How's that going? What's working? What's 
  been hard?"

- **Notice and name when commitments are being honored.** If 
  someone flags their capacity and the team responds well, 
  acknowledge it. "That's exactly what we talked about in our 
  session. That's this team operating the way we said we wanted 
  to." Reinforcement of new norms is how they become actual norms.

- **Notice and address when commitments are being broken.** If a 
  rotation boundary gets overridden, if the same person gets 
  assigned to another high-impact case without a buffer, if 
  someone flags capacity and gets asked to push through anyway—name 
  it. "We committed to handling this differently. What happened, 
  and how do we get back on track?"

### Within One Quarter

- **Run the 
  [Quarterly Team Resilience Review](../templates/quarterly-resilience-review.md).** 
  Use the workshop commitments as a reference point. Were they 
  sustained? Did they produce change? What still needs work?

- **Consider whether a follow-up session is needed.** Not every 
  quarter requires a full workshop, but a shorter check-in session 
  (60–90 minutes) focused on progress and recalibration can 
  maintain momentum.

- **Share outcomes with your own leadership if appropriate.** If 
  the workshop surfaced structural issues that require support 
  beyond your team—staffing, tooling, organizational change—bring 
  that upward with specifics. The 
  [Bringing This to Your Leadership](../guides/bringing-this-to-your-leadership.md) 
  guide provides framing that works for upward advocacy.

---

## Adapting for Shorter Formats

### 90-Minute Focused Session

Choose two modules based on what's most relevant. Suggested 
pairings:

**If load distribution is the primary concern:**
- Module 1 (Load and Patterns) — 35 minutes
- Module 4 (Commitments) — 25 minutes
- Opening and closing — 20 minutes
- Buffer — 10 minutes

**If recovery and pace are the primary concern:**
- Module 2 (Recovery and Sustainability) — 35 minutes
- Module 4 (Commitments) — 25 minutes
- Opening and closing — 20 minutes
- Buffer — 10 minutes

**If communication and safety are the primary concern:**
- Module 3 (Communication and Safety) — 35 minutes
- Module 4 (Commitments) — 25 minutes
- Opening and closing — 20 minutes
- Buffer — 10 minutes

For 90-minute sessions, shorten exercises by reducing discussion 
time rather than cutting exercises entirely. The exercises are 
where the team generates its own insight—the discussions are where 
they process it. Both matter, but if time is limited, the 
exercises should stay intact.

### 60-Minute Team Meeting

Choose one module and pair it with a streamlined commitment 
exercise.

**Structure:**
- Opening and framing — 5 minutes
- Single module (abbreviated) — 35 minutes
- Quick commitments — 15 minutes
- Closing — 5 minutes

For a 60-minute format, pick the single exercise from each module 
that's most impactful:

- From Module 1: Exercise 1 (Incident Mapping) alone is powerful 
  enough to generate meaningful conversation
- From Module 2: Exercise 4 (Individual Reflection — Recovery 
  Honest Check) is the most personally resonant
- From Module 3: Exercise 5 (What's Safe to Say) produces the 
  most actionable data

Follow the exercise with open discussion and close with one or 
two commitments. Don't try to do too much in 60 minutes—one 
genuine insight that leads to one real change is worth more than 
a rushed tour of every topic.

---

## Facilitator Notes

### Managing Energy

A three-hour workshop on team sustainability and burnout is 
inherently demanding. Monitor the room's energy throughout and 
adjust accordingly.

Signs the team needs a break or a shift:
- Responses becoming shorter and less engaged
- People checking devices despite the ground rules
- Body language shifting (leaning back, looking away, fidgeting)
- The conversation becoming circular or abstract

If you sense the energy dropping, you have options:
- Take an unscheduled break
- Shift from group discussion to individual reflection (quieter, 
  less demanding)
- Acknowledge it directly: "I'm noticing the energy is dipping. 
  Let's take five minutes."

### Managing Emotion

These topics can surface genuine emotion—frustration, sadness, 
exhaustion, anger. That's not a problem. It's a sign that the 
conversation is reaching something real.

**If someone gets emotional:**
- Don't rush past it or redirect immediately
- Acknowledge it simply: "Thank you for sharing that. That 
  clearly matters to you."
- Don't ask the person to explain or elaborate unless they 
  want to
- Don't let the group immediately pivot to problem-solving. 
  Sit with it for a moment before moving on
- Check in with the person privately after the session

**If someone expresses frustration directed at leadership 
(including you):**
- Listen. Don't defend.
- "Thank you for being honest about that. I want to 
  understand it better."
- This is the moment that defines whether psychological 
  safety is real or theoretical in this session

**If the conversation becomes heated between team members:**
- Acknowledge the tension: "It sounds like there are 
  different perspectives here, and that's okay."
- Redirect to the shared goal: "We're all trying to figure 
  out how to make this more sustainable. Let's focus on what 
  we can change."
- If needed, pause and take a break

### Managing Silence

Silence after a question is not a failure. It often means people 
are thinking. Wait longer than feels comfortable before speaking 
again. If you fill every silence, the team learns that they don't 
need to—and the most thoughtful responses never surface.

If silence persists beyond 15-20 seconds:
- Rephrase the question
- Offer your own honest answer first to model that engagement 
  is safe
- Shift to individual written reflection and then share ("Take 
  a minute to write your thoughts, and then we'll discuss")
- Acknowledge it: "This is a hard question. Take your time."

### Managing Dominant Voices

In any team, some people speak more readily than others. In a 
session about sustainability and limits, it's particularly 
important that quieter voices have space.

Techniques:
- Use individual written reflection before group discussion 
  (several exercises already include this)
- Explicitly invite input: "I want to hear from some people 
  who haven't spoken yet—no pressure, but the invitation is 
  there"
- Don't let a single person's perspective define the group's 
  conclusion. "That's one perspective. Does anyone see it 
  differently?"
- If someone is dominating, redirect gently: "I appreciate 
  your input. Let's hear from some others."

### When You're the Problem

There may be moments during the workshop where it becomes clear 
that your own leadership behaviors are part of what the team is 
struggling with. You might hear feedback—direct or indirect—that 
your modeling, your expectations, or your decisions have 
contributed to the patterns being discussed.

This is the hardest moment to navigate as a facilitator, and it's 
also the most important. How you respond determines whether the 
session was genuine or performative.

**What to do:**
- Listen without defending
- Thank the person for their honesty
- Resist the urge to explain your intentions
- Acknowledge what you're hearing: "I hear you. That's something 
  I need to think about and work on."
- Follow up with specific changes, not just acknowledgment

**What not to do:**
- Explain why you did what you did
- Minimize it: "I didn't realize it came across that way"
- Redirect to external factors: "That's because of pressure 
  from above"
- Promise change you can't deliver

Your team doesn't need you to be perfect. They need you to be 
honest about your impact and willing to change. That's the 
entire thesis of this toolkit.

---

## Measuring Impact

The success of this workshop isn't measured by how it felt in 
the room. It's measured by what changes afterward.

### Short-Term Indicators (1–4 weeks)

- Are commitments being referenced and acted on?
- Has anyone used the normalized language from Module 3 in an 
  operational context?
- Have you followed through on your leadership commitments?
- Did anyone follow up privately with things they didn't share 
  in the session?

### Medium-Term Indicators (1–3 months)

- Has the distribution of high-impact case assignments changed?
- Are rotation boundaries being respected more consistently?
- Is recovery time being created after major incidents?
- Are people flagging capacity more openly?
- Has invisible work received more recognition?

### Long-Term Indicators (3–6 months)

- Does the next [Quarterly Team Resilience Review](../templates/quarterly-resilience-review.md) 
  show improvement in the areas discussed?
- Has the [Rotation and Load Audit](../templates/rotation-load-audit.md) 
  shown better distribution?
- Has retention remained stable or improved?
- Does the team describe its operating environment differently 
  than before?
- When new pressure arises, does the team respond with the 
  norms discussed, or revert to old patterns?

Reverting to old patterns under pressure is normal and expected. 
The question isn't whether it happens—it's whether the team 
recognizes it and corrects. That recognition is the lasting 
impact of the workshop.

---

## Connected Resources

This workshop draws on and connects to every resource in the 
repository:

- [Resilience by Design Toolkit](../toolkit/resilience-by-design-toolkit.md) — 
  The foundational guide underlying all workshop content
- [1:1 Reflection Guide](../templates/one-on-one-reflection-guide.md) — 
  For individual follow-up after the workshop
- [Post-Incident Team Check-In](../templates/post-incident-team-checkin.md) — 
  Referenced in team commitments and ongoing practice
- [Rotation and Load Audit](../templates/rotation-load-audit.md) — 
  The data-gathering tool behind Module 1
- [Single Points of Cognitive Failure Mapping](../templates/cognitive-failure-mapping.md) — 
  Deeper analysis of concentration patterns surfaced in Module 1
- [Quarterly Team Resilience Review](../templates/quarterly-resilience-review.md) — 
  The ongoing review that tracks progress after the workshop
- [Manager Self-Assessment](../templates/manager-self-assessment.md) — 
  For the facilitator's own reflection on their role in the system
- [Psychological Safety Team Discussion Guide](../guides/psych-safety-team-discussion.md) — 
  A lighter-weight alternative to Module 3, or a follow-up session
- [Bringing This to Your Leadership](../guides/bringing-this-to-your-leadership.md) — 
  For surfacing structural issues upward after the workshop reveals 
  them
