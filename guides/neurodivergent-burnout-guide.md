# Supporting Neurodivergent Team Members Through Burnout

## A Guide for Security and Incident Response Leaders

**Part of the** **[Resilience by Design](https://github.com/4n6lady/resilience-by-design/blob/main/README.md)** **toolkit**

---

## Why This Guide Exists

The [Resilience by Design toolkit](https://github.com/4n6lady/resilience-by-design/blob/main/toolkit/resilience-by-design-toolkit.md)
covers early burnout signals and how to recognize them. But it assumes
a fairly uniform model of what burnout looks like, and that assumption
will cause leaders to miss it in a meaningful portion of their teams.

ADHD and autism are both overrepresented in technical fields, including
security and incident response. The work attracts people who think
systematically, pattern-match quickly, and go deep under pressure. Many
of those same people are neurodivergent. And the way burnout accumulates
and presents in someone with ADHD or autism is different enough from the
standard model that leaders who aren't looking for it will regularly
mistake it for something else—or miss it entirely until the situation
is already serious.

Note: I want to be direct about what this guide is and isn't. 
**It's not a clinical resource**. It won't help you identify or diagnose anything, and please do not use this guide to try; please respect your colleagues and employees. 
What it will do is help you recognize patterns you might otherwise
misread, ask better questions in your 1:1s, and design environments
that don't quietly erode people who are carrying costs that never
show up in your operational dashboards.

A note on language: this guide uses person-first
language ("person with ADHD"). Some individuals prefer identity-first
language. Follow the lead of your team members when you know their
preference.

---

## The Problem with Standard Burnout Models

Most burnout frameworks describe a gradual, visible decline, however that model does not reliably apply to neurodivergent burnout.

For many people with ADHD or autism, the pattern looks more like
sustained stability followed by sudden collapse. It's what I call "The masking"; this is the
continuous work of suppressing natural behaviors and appearing
neurotypical in a neurotypical environment. It continues long after the
internal reserves are depleted. And then, often without obvious warning from the outside,
the mask falls. 

By the time the collapse is visible to you as their manager, they have
usually been running on empty for a long time. The absence of early
visible signals wasn't the absence of a problem. It was the cost of
hiding it, and tt's a cost they were paying every day while the dashboards
showed nothing.

This is why the standard early warning checklist isn't sufficient on
its own for teams where neurodivergent people are present, whether
you know who they are or not. It will catch some things, however for
neurodivergent team members in masking mode, it will miss more than
you'd expect.

---

## ADHD and Burnout in Incident Response

### What ADHD Actually Looks Like in This Work

ADHD is not simply difficulty focusing. It's more accurately described
as variable attention regulation, where a nervous system that struggles to
modulate when and how focus happens, heavily governed by urgency,
novelty, interest, and challenge. When those conditions are present,
focus can be extraordinary. But when they're absent, even simple tasks
become disproportionately hard.

Incident response is almost perfectly designed to activate the ADHD
nervous system. Incident response has real urgency, and the
stakes create genuine pressure. Many responders with ADHD find this
work energizing precisely because the environment provides what their
nervous system needs to function at its best, and they are often
excellent at it. 

The problem is that the same environment enabling peak performance
during an active incident creates particular strain everywhere else: documentation, follow-through, administrative work between
incidents, and especially recovery. Real disengagement and rest require
something the ADHD nervous system often struggles to do deliberately,
which is stop engaging with something stimulating.

### What ADHD Burnout Looks Like

The most common misread is task initiation failure on lower-urgency
work. The responder can still take a P1 call at 2am, but they struggle to start
the post-incident report. They know it needs to happen and they intend to
do it. This isn't what we would describe procrastination in the way most people understand it; it's executive
function depletion. The gear that initiates tasks is worn out, and
lower-urgency work doesn't generate enough activation energy (novelty, urgency, or curiousity) to
compensate. Leaders often read this as disengagement or poor
follow-through, but what it really is is a signal that the person's executive
resources have been depleted by sustained high-load work and haven't
had space to recover.

Hyperfocus is another pattern that reads as a strength until you look
at it more carefully. A responder stays on a case well past their
handoff. This isn't because they're being irresponsible, but because they're
locked in. The ADHD nervous system can trap a person in a high-interest
problem in a way that overrides awareness of time, fatigue, and the
fact that their rotation ended an hour ago. In moments of hyperfocus, I will forget to eat. 

This looks like dedication, but repeated hyperfocus sessions carry a recovery
cost that doesn't appear in the output. It will show up later as flattened
capacity, poor follow-through on everything that came after, or
difficulty sleeping (the mind hasn't disengaged). 

Time blindness worsening is a related signal that's easy to dismiss. This looks like missing handoffs, misjudging how long they've been on, and arriving late
to check-ins that matter but don't feel urgent. Time perception
difficulties are a core feature of ADHD and are significantly worsened
by fatigue, stress, and sustained cognitive load. If someone who
previously managed their schedule reasonably well is suddenly missing
things, it's worth asking what else is going on before treating it as
a professionalism issue. 

Rejection sensitivity is less visible but can be one of the most
significant drivers of behavior change. Rejection sensitive
dysphoria: an intense emotional response to perceived criticism,
failure, or rejection—is common in people with ADHD, and in a
high-performance culture where post-incident reviews and peer feedback
are routine, it can be a major and invisible source of stress. A
responder who seems suddenly avoidant after a difficult review, or who
stops volunteering in team discussions after receiving critical
feedback, may be managing RSD rather than demonstrating defensiveness.
The behaviour looks the same from the outside. The cause matters
enormously for how you respond.

And underneath all of it, masking is running constantly. People with
ADHD spend significant cognitive energy appearing organized, on top of
things, and calm under pressure. In incident response, where composed
competence is the implicit expectation, that effort never stops. It
doesn't show in the output, it shows in the crash. This is when the person's
capacity to sustain the performance suddenly runs out and the fall
seems to come from nowhere, even though it didn't.

### What Leaders Often Misread

| What you observe                                     | What you might conclude                 | What might actually be happening                                |
| ---------------------------------------------------- | --------------------------------------- | --------------------------------------------------------------- |
| Documentation not completed despite reminders        | Poor follow-through, low accountability | Executive function depletion after sustained high-load work     |
| Staying on cases past handoff                        | Dedication, difficulty delegating       | Hyperfocus; unable to disengage without structural support      |
| Missing handoffs or check-in times                   | Disorganization, unreliability          | Time blindness worsening under fatigue and load                 |
| Going quiet after feedback or review                 | Defensiveness, fragility                | Rejection sensitivity response                                  |
| Sudden drop in performance after sustained stability | Burnout arriving suddenly               | Masking collapse—the problem existed long before it was visible |

### Leadership Reflection

* Who on your team consistently delivers during incidents but
  struggles with the follow-through work afterward? Have you
  asked what's getting in the way, or have you been attributing
  it to motivation?
* When someone stays past their rotation on a complex case, do
  you read that as dedication? How often does the same person
  do it?
* If someone went quiet after a difficult review, did you follow
  up with them—and how soon?
* Are you interpreting the absence of complaint as evidence that
  things are fine?

### Actions

When someone consistently delivers during incidents but struggles with
the aftermath, the first question to ask is about recovery, not
accountability. Is the person getting enough space between the end of
incident work and when post-incident expectations land on them?
Treating documentation lag as a capacity signal rather than a character
issue often reveals a scheduling problem, not a commitment problem.

* In your next round of 1:1s, ask directly:
  * "What does recovery actually look like for you after a high-intensity period?"
  * "What's getting in the way of the follow-through work right now?"

Take the answers seriously, even if they don't match your own experience.

* Build explicit handoff structure into your rotation process. A
  specific format, a defined time, a named person to hand to.
  For responders who struggle to disengage, structure does the
  work that willpower can't sustain—and it benefits the whole
  team.
  
* If someone's participation drops after a difficult review or
  critical feedback, follow up privately and soon. Ask how they're
  doing, not about the feedback itself. Give them a path back
  before the withdrawal becomes habitual.
* When you notice someone repeatedly staying past their rotation,
  name it in a 1:1 as a sustainability conversation, not a
  discipline one:
  * "I've noticed this pattern. I want to make sure
  the cost isn't accumulating in ways neither of us can see."

---

## Autism and Burnout in Incident Response

### What Autism Looks Like in This Work

Autism is characterized by differences in social communication, sensory
processing, and the need for predictability and routine. It also often
comes with a deep capacity for focused, systematic thinking—pattern
recognition, attention to detail, tolerance for complexity. That maps
well onto security and IR work. Many responders with autism are
exceptionally good at this work precisely because of how they process
it.

But the environment of incident response sits in direct tension with
several features of how people with autism experience the world. The work
is inherently unpredictable, meaning it requires sustained social performance
under pressure, involves ambiguous, incomplete information and rapid
communication across multiple people, with high implicit social
expectations. And it continues well past any reasonable boundary
because incidents don't follow schedules.

Each of those features carries a cost that doesn't show in your metrics.

### What Autistic Burnout Looks Like

Burnout in autism is distinct from general occupational burnout and is
recognized in the clinical and research literature as a specific state:
loss of previously manageable skills, increased sensory sensitivity,
profound withdrawal, and difficulty with tasks that were once routine.
It is typically the result of sustained masking, chronic stress, and a
mismatch between the demands of the environment and the person's
natural way of functioning. It can take months to recover from, and it
often follows a period that looked, from the outside, perfectly fine.

The social and communication load of a major incident call is something
most leaders underestimate. Multiple people talking over each other,
rapid topic shifts, unclear conversational structure, managing a
distressed customer while tracking technical state, knowing when to
speak and when not to.
They're central to how incident response gets done. For a
team member with autism, navigating that social environment while also doing the
technical work carries a load that is real and largely invisible. After
an extended call, or a series of them, the cognitive cost of social
processing can leave someone unable to function in ways that will look
like withdrawal or shutdown. It's neither. It's a depleted resource
that needs recovery time, not a behavioural signal that something is
wrong with the relationship.

Sensory overload compounds this, especially for remote workers. Fatigue
intensifies sensory sensitivity for many autistic people, and an
incident that stretches across multiple days means the home workspace
that is supposed to provide recovery becomes the incident workspace
instead. What's manageable on a normal day, like the texture of a headset
after hours on a call, screen clutter, background noise, can become
genuinely intolerable by the third day of a sustained response. 

The unpredictability of on-call is a structural stressor that tends to
be dismissed as just part of the job. For team members with autism, the
absence of predictable routine is a genuine and accumulating cost
across an entire rotation, not a minor inconvenience to be adapted to.
A person who is managing that unpredictability while also managing the
technical and social demands of the work is carrying something that
won't show up in how they perform when an incident starts. However, it shows up
later, in ways that can look disconnected from the source.

Communication differences are another invisible source of friction that
builds over time. This inscludes direct, and literal communication, a preference for
explicit expectations over implicit social norms, or a need for written
confirmation before acting. These are common communication
patterns, and in a high-pressure team environment, they generate
low-level friction that accumulates without anyone naming what it
actually is. A team member with autism asking "what exactly do you mean
by that?" may be asking because they genuinely need clarity—not because
they're being difficult. 

Autistic masking (sometimes called camouflaging) involves continuously
suppressing natural behaviors to appear neurotypical in a neurotypical
environment. It is exhausting, often partially unconscious, and running
constantly in any workplace where being openly autistic doesn't feel
fully safe. In security and IR culture, where emotional regulation and
composed performance under pressure are implicitly expected and
sometimes explicitly rewarded, masking pressure is high. A team member
who appears seamlessly well-adjusted may be working very hard to look
that way. The effort is invisible, and the cost is real.

### What Leaders Often Misread

| What you observe                                    | What you might conclude                            | What might actually be happening                                             |
| --------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------------------------------- |
| Quiet, limited participation after a major incident | Withdrawal, disengagement from the team            | Post-incident shutdown—a necessary recovery state, not a relationship signal |
| Blunt or literal communication in a tense moment    | Interpersonal difficulty, poor emotional awareness | Direct communication style; not intentional abrasiveness                     |
| Asking for written confirmation or explicit clarity | Slowing things down, lacking trust                 | Avoiding the cost of misunderstanding; explicit over implicit is functional  |
| Strong written analysis, hesitation on calls        | Inconsistent performance                           | Social processing overload; async is genuine strength, real-time is costly   |
| Seeming fine right up until they aren't             | Sudden onset burnout                               | Autistic burnout following sustained masking—the collapse wasn't sudden      |
| Declining team social events consistently           | Disengagement from team culture                    | Deliberate management of social energy; not a signal about team belonging    |

### Leadership Reflection

* After your last major incident, did the most involved responders
  get real recovery time, or were they immediately back in
  rotation? Did you ask what they needed, or assume?
* Are you running retrospectives in a format that makes it hard
  for some people to contribute honestly? Who tends to be quiet
  in those settings?
* When someone asks for written confirmation or explicit clarity,
  what is your first instinct about them? Is that instinct fair?
* Do your processes assume a single normal way of communicating
  under pressure? What would it cost you to build in more
  flexibility by default?

### Actions

Making async the default rather than the accommodation changes the
dynamic for the whole team. If written pre-submission questions are
available before every retrospective, if key decisions are documented
in writing rather than announced verbally, if the default is text over
call—nobody has to request special treatment to participate in the way
that works best for them. The quality of input from the whole team
often improves.

* Offer written pre-submission questions before retrospectives and
  post-incident reviews as standard practice, not as an option
  people have to request.
* After a major incident, ask what recovery looks like for the
  people who carried the most load—and take the answer seriously
  even if it doesn't match what you'd need. "I need two days with
  no calls" is a legitimate answer.
* Learn what each team member's baseline recovery pattern looks
  like when things are fine. That's what makes it possible to
  notice when something looks different.
* When someone delivers outstanding written analysis but seems
  uncertain on real-time calls, examine the assumption that the
  call performance is the real measure. Value the output. Ask
  whether the format is serving the work or just reflecting how
  the work has always been done.
* Clarify communication expectations explicitly, especially in
  high-stakes conversations. If you want direct feedback, say so
  and protect it when you get it. Don't leave people to interpret
  what's safe to say from implicit signals they may not be reading
  the same way you intend them.

---

## What Both ADHD and Autism Have in Common

The specifics differ, but there are shared patterns worth naming.

The standard burnout model describes gradual visible decline. For burnout in both
ADHD and autism, the trajectory is more likely to be
stable-appearing until collapse. Masking sustains the surface
performance while internal reserves are depleted, and by the time
something is visible to you, the person has often already been
struggling for significantly longer than either of you realizes.

The highest-functioning presentation frequently carries the highest
masking cost. The team member who is technically excellent, composed
under pressure, reliable across rotations, and socially fluent may be
working hardest to maintain that presentation. It is worth holding that
tension: the person who looks like they're handling everything is
sometimes the person who can least afford the cost of that performance.

Asking once isn't enough to get real information. "How are you doing?"
answered with "fine" in a 1:1 is a trained response, not data. Building
the kind of relationship where a different answer is possible takes
consistent demonstration—over time and across multiple interactions—that
the honest answer won't be used against someone. It doesn't happen
because you held a psychological safety discussion or told people your
door is open.

And disclosure is not the threshold for support. You likely have team
members who are not diagnosed, who are diagnosed and haven't told you,
or who have been navigating unrecognized ADHD or autism throughout
their careers through endurance and workarounds that never made it into
any formal record. You don't need to know someone's neurological
profile to ask better questions, create more flexible recovery options,
or build an environment where people can tell you what they actually
need. Most of the practices in this guide benefit nearly everyone.
You don't have to wait for disclosure to start using them.

---

## Creating Conditions Where Disclosure Is Possible

Whether someone chooses to disclose a neurodevelopmental condition to
their manager is a deeply personal calculation, and most of it happens
long before any direct conversation. They're weighing how it will be
received, whether it will become a filter for future assignments,
whether you'll treat them differently in ways they don't want, and
whether anything will actually change if they say something. Most of
the time, the calculation is quiet and private, and you won't know
it happened.

The question to ask yourself isn't "how do I make it easy to disclose
to me?" It's "what have I already made visible about how I respond to
vulnerability and difference?"

If you've responded to people expressing limits by stepping in to
absorb the work yourself, disclosure teaches people that their limits
create burden rather than relief. If you've responded to communication
differences with impatience or frustration, you've made clear that
different means difficult. If you've consistently rewarded endurance and
seamless performance, you've taught your team that the cost of
maintaining that performance is theirs to carry alone.

Disclosure follows trust, and trust is built through patterns over time.
Talking about the range of ways people work and recover without waiting
for someone to raise a specific need normalizes variation as a baseline
and makes it easier for individuals to name their specific version of
it. Responding to what someone shares with curiosity and practical
follow-through—rather than reassuring them that you "don't see them any
differently"—communicates that their experience is being taken seriously,
not smoothed over. And following through on what you're told. If someone
tells you they need async options after a high-demand incident and you
route them into three calls the next day, you've communicated that what
they shared didn't matter. That's a lesson they won't forget.

---

## A Note on This Work

Technical teams in security and incident response contain a higher
proportion of neurodivergent people than most fields. Some are
diagnosed and know it. Some are diagnosed and haven't shared it. Some
have been navigating unrecognized ADHD or autism throughout their
entire careers, functioning through endurance and compensating in ways
that never made it into any formal record.

The patterns in this guide aren't edge cases. They're present on most
teams of meaningful size, whether or not anyone has named them. The
burnout that results from missing these signals is not a failure of
individuals to communicate their needs clearly. It's a failure of the
environment to make honest communication safe, and a failure of the
people responsible for noticing signals to know what they're looking at.

This work doesn't require you to become a clinical resource for your
team. It requires you to expand your model of what "doing fine" can
look like, what "burning out" can look like, and what "support" can
look like, so that the team you're building is actually sustainable for
the people on it.

---

## Connected Resources

* [Resilience by Design Toolkit](https://github.com/4n6lady/resilience-by-design/blob/main/toolkit/resilience-by-design-toolkit.md) —
  Section 6 provides the overview this guide expands. See also
  Section 1 (Recognizing Early Burnout Signals) and Section 5
  (Psychological Safety as an Operational Requirement).
* [1:1 Reflection Guide](https://github.com/4n6lady/resilience-by-design/blob/main/templates/one-on-one-reflection-guide.md) —
  The questions in this guide are designed for private 1:1 use.
  The 1:1 Reflection Guide provides broader structure for the
  regular check-ins where these conversations can be embedded.
* [Post-Incident Team Check-In](https://github.com/4n6lady/resilience-by-design/blob/main/templates/post-incident-team-checkin.md) —
  The format recommendations here—async options, smaller groups,
  written pre-submission questions—apply directly to how you run
  post-incident check-ins.
* [Manager Self-Assessment](https://github.com/4n6lady/resilience-by-design/blob/main/templates/manager-self-assessment.md) —
  The practices described in this guide require honest
  self-examination of what you've been modeling and what you've
  been missing. The Manager Self-Assessment is where that
  reflection belongs.
* [Quarterly Team Resilience Review](https://github.com/4n6lady/resilience-by-design/blob/main/templates/quarterly-resilience-review.md) —
  Part 3 (Early Signals) is where neurodivergent-specific
  observations should be captured and tracked across time.


