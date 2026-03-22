# Changelog

All meaningful changes to this repository are documented here.

This includes new resources, significant revisions to existing content,
structural changes, and contributions from the community. It is not a
commit log — it's a record of what changed and why, written for people
who use these materials rather than people who maintain the repository.

---

## [Unreleased]

### Added

* `templates/capacity-response-protocol.md` — A team exercise for
  pre-defining how the team responds when someone hits their limit.
  Includes a four-step decision framework (shed load, reduce
  thoroughness, time-shift, increase resources) drawn from Woods and
  Hollnagel's work on cognitive systems engineering, and pre-defined
  response scripts for each of the psychological safety phrases
  introduced in Section 5 of the toolkit. Proposed by
  [@leongc](https://github.com/leongc) in
  [Issue #4](https://github.com/4n6lady/resilience-by-design/issues/4).

* `guides/neurodivergent-burnout-guide.md` — A leader reference guide
  for recognizing ADHD-specific and autism-specific burnout patterns
  in security and incident response work. Expands on Section 6 of the
  toolkit with detailed pattern descriptions, misread signal tables,
  leadership reflection questions, and concrete actions for each.
  Includes guidance on creating conditions where disclosure is possible.

* `CONTRIBUTING.md` — Contribution guidelines for the repository,
  including how to propose new content, submit pull requests, and
  what the bar is for additions in terms of voice and scope.

### Changed

* `toolkit/resilience-by-design-toolkit.md` — Section 5 (Psychological
  Safety) updated to reference the new Capacity Response Protocol.
  Section 6 (Neurodivergent Team Members) updated to summarize and
  link to the new full guide rather than carrying all content inline.
  Both new resources added to the Companion Resources list.

* `guides/psych-safety-team-discussion.md` — Discussion 2 section
  updated to reference the Capacity Response Protocol as a next step
  for teams ready to move beyond naming the language. Connected
  Resources updated accordingly.

* `README.md` — Templates and Guides tables updated to include both
  new resources.

### Fixed

* `toolkit/resilience-by-design-toolkit.md` — Incomplete sentence on
  line 45 of the Companion Resources section ("Note: If you cannot
  find these, then it means") removed.
  Reported by [@leongc](https://github.com/leongc) in
  [Issue #1](https://github.com/4n6lady/resilience-by-design/issues/1).

---

## [1.0.0] — [REPLACE WITH INITIAL LAUNCH DATE]

Initial release of the Resilience by Design toolkit.

### Added

* `toolkit/resilience-by-design-toolkit.md` — The full leadership
  guide covering early burnout signals, post-incident recovery, hero
  culture, invisible work, psychological safety, neurodivergent
  support, and leaders as part of the system.

* `templates/one-on-one-reflection-guide.md` — Structured reflection
  questions for managers to use in regular check-ins.

* `templates/post-incident-team-checkin.md` — A guide for
  decompression conversations within 48 hours of a major incident
  closing.

* `templates/rotation-load-audit.md` — An exercise for mapping
  incident involvement across the team and identifying concentration
  patterns.

* `templates/cognitive-failure-mapping.md` — An exercise for
  identifying where critical knowledge and context are concentrated.

* `templates/quarterly-resilience-review.md` — A structured
  self-assessment for leaders to review team patterns once a quarter.

* `templates/manager-self-assessment.md` — A private reflection tool
  for leaders examining their own role in the system.

* `workshop/facilitator-guide.md` — A guide for running a team
  workshop based on the toolkit content.

* `guides/bringing-this-to-your-leadership.md` — For individual
  contributors and senior responders who want to advocate for
  sustainable practices upward.

* `guides/psych-safety-team-discussion.md` — Discussion prompts for
  opening a team conversation about capacity, limits, and
  communication norms.

---

## A Note on Versioning

This repository uses a simple versioning approach. Version 1.0.0 marks
the initial public release. Subsequent versions will be numbered based
on the significance of changes: new resources and structural changes
increment the minor version; corrections and small improvements
increment the patch version.

The [Unreleased] section above accumulates changes as they are made
and is moved to a versioned entry when a release is tagged.

---

*This repository is maintained by
[Shannon Brazil](https://www.linkedin.com/in/shannonbrazil/).*
