# Manuscript outline

- Introduction
  - Benefits of open reviews in general: clarify work with original authors, broader community opinion, post-publication peer review of individual papers, prune topics that don’t draw interest
  - Short intro to deep review, goals, timeline, author solicitation, etc.
- How we did it
  - Collaborative writing platform w/ tracking, drawbacks of traditional collaborative writing platforms in massively open setting
  - Review of each contribution + commenting
  - Separate setup for discussion of papers
  - Figure: flowchart showing version i of document, commits, pull request, reviews, commits, …, merge, version i + 1 of document (I think we'll need to illustrate the tracking and review system for readers who don't use version control systems)
- Dealing with authorship
  - ICMJE criteria
  - Benefit: authorship and contributions precisely defined.
  - Challenge: how to make a traditional author list?
  - Equivalence classes as generalization of “co-first”
- Manubot build system
  - Automating as much as possible, especially references
  - All authors can see current version
  - Timestamps?
  - Limitations of current system?
  - [Related projects](https://github.com/greenelab/manubot-rootstock/issues/32)
- Other considerations
  - Versioning/provenance of metadata (issues, pull requests, etc) (We can refer to or implement? strategies for backup up a GitHub repo https://help.github.com/articles/backing-up-a-repository/)
  - Publication system/journal of the future & how it relates
  - Living document, new authors after deep review version 1
  - Other areas of open science and innovative ideas, related GitHub-based projects (JOSS, ReScience, etc.)
  - Would a GitHub-based strategy be a barrier to entry for other groups that don’t already use git?  Technical knowledge required to clone manubot-rootstock, set up continuous integration.
  - Conflict management, diversity, point to open source software strategies
  - Using these ideas for primary research (SciHub manuscript)
