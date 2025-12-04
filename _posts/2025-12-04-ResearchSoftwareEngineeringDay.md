---
title: Research Software Engineering Day 2025
background:
  img: /assets/backgrounds/rse_day2025.png
  by: BE-RSE
author: Damiano Oldoni
tags: [software, rse, Leuven, Belgium, foss, open science, open, fair]
toc: true
comments: false
published: true
---

## General

- [Website](https://www.kuleuven.be/rdm/en/training/events/rse-day-2025)
- Program: [html](https://www.kuleuven.be/rdm/en/training/events/rse-day-2025/research-software-engineering-day-2025). [Full program](https://www.kuleuven.be/rdm/en/training/events/rse-day-2025/rse_day_2025_handout_programme.pdf) (pdf). See also [Abstracts](https://www.kuleuven.be/rdm/en/training/events/rse-day-2025/programabstracts.pdf).
- Organizer: [BE-RSE](https://be-rse.org/)
- Host: [KU Leuven](https://www.kuleuven.be/kuleuven/), Machinezaal in Thermotechnical Institute (Kasteelpark Arenberg 41 , 3001 Heverlee)
- Founder: BE-RSE
- Date: 4/12/2025


{:.alert .alert-warning}
These notes are a very first **DRAFT**. A review will occurr soon.

## Keynotes - part 1

### From FAIR to Good Practice: How Do We Improve Research Software?

Presenter: Neil Chue Hong (Director, Sofware Sustainability Institute), Professort of Research Software Policy and Practice

Chue Hong, Neil (2025). From FAIR to Good Practice: How do we improve research software?. figshare. Presentation. [https://doi.org/10.6084/m9.figshare.30764660](https://doi.org/10.6084/m9.figshare.30764660)

A lot has changed since 2010.

Research Software Engineer is a kind of "family" as there are different tasks-research users.

Software Sustainability Institute has been founded in 2010 to improve practice aroud the software that enables research. Dedicated to any kind of sustainability.

Some milestones of the institute: 
- [Carpentries](https://carpentries.org/)
- FAIR principles for software ([FAIR4RS](https://www.nature.com/articles/s41597-022-01710-x))

FAIR principles for software are comprehensive but quite difficult to fully achieve. So, a new paper was written speaking about **FAIR enough** principles. What are the FAIR enough principles?
- Write code to be **readable**, **reusable**, and **testable**
- Often dependent on institutional policies and sector

UNESCO and OECD have been working in recognizing the role of software and software community in research.

Check "Software and skills for research computing in the UK" report: [full](https://zenodo.org/records/10473186), [short](https://www.software.ac.uk/news/new-report-software-and-skills-research-computing-uk).

Software citation support: GitHub code repo added support for software citation using CFF files in July 2021.
By Sept 2022, more than 11k projects had added a citation file.

Research software is **team work** and must to think **globally**. Check [Research Software Development Principles, Chue Hong N.](https://zenodo.org/records/11494174). Key aspects:
1. FAIR: reusable by as many users as possible
2. Secure: respect data privacy and assume attacks
3. Maintainable: easy to adapt and to correct faults
4. Reproducible: enable trust in research
5. Recognition: reward all roles and develop the next generation
6. Inclusive: Accessible and supportive of a broad community
7. Responsible: build to reduce impact on our environment
8. Open & global: transcend national and discipline boundaries
9. Humanist: unbiased, ethical and in support of humanity


Communities of Practice, e.g. [code check](https://codecheck.org.uk/), [Research Software Alliance](https://www.researchsoft.org/), [The Carpentries](https://carpentries.org/). It's all about:
- Enthousisasm
- Engagement
- Knowledge exchange

AI is everything, everywhere, all at once. Impact on RSE?
- Majority of survey respondents use AI as part of their work and believe it has increased their productivity.
- Y combinator reporeted that 25% of startup companies in its Winter 2025 batch had codebases that were 95% AI-generated!
- AI in RSE? Curious but cautious 
- What about the university students? They are using AI but are the most skeptical.

Two tendencies:
- less experienced developers see the advantages of speeding up producing working code
- most experiences see a slow down of the productivity (less quality of code)

Are there some simple rules for AI-assisted coding in science? [Ten simple rules for AI-Assisted coding in Science](https://arxiv.org/abs/2510.22254), aRxiv.

- Coding assistants open the possibilities for many more people to develop effective researhc software
- But not aa substitute for teaching users the basics of algorithmes, data strucutres and software engineering
- Not a substitute for understanding how to frame a problem: domain knowledge, architectural and design choices for a language, identifying requirements
- What tool to use where and when - we need more training about how to use coding assistants proberly for research software

Key question/challenge: how do we train people now that they use code assistance?

Coding assistants good at creating unit tests for edge cases
what happens if the tools you rely on increase their price/disappear?
Sustainability aspects are very important while thinking about code assistants.

### The Impact of Open Source Robotics Research - or the Lack thereof on Industry

Presenter: [Peter Soetens](https://www.imecitf.com/flanders/speakers/peter-soetens), CEO at [Intermodalics](https://www.intermodalics.ai/)

What Intermodalics does?
- Produce software for Vision Guided Robots. 
- Real-time system, [Robot Operating System](https://ros.org/) (ROS)

All modern digital infrstructure is in some way based on open software, e.g. linux, created by "poor" Linus Torvalds (poor in comparison with all tech CEOs):
https://www.lets-code.co.in/blogs/getting-started-with-open-source/

But, the Linux Foundation is not poor at all as big tech and many other companies worldwide understand the importance of it.

Was ROS the best when launched? No, just "good enough". And that's was its success; together with being open source.

Check the [Open Source Robotics Alliance](https://osralliance.org/).

What we all need from research:

1. Open up the foundational levels (R package, Python library or a model, ...)
2. If you cannot open it up because your research has been paied by companies and you have confidentiality issues, collaborate globally: the overhead is worth the win!
3. If what you are doing is so secret that even the previous step is not possible, just start your own company: do you have any breaktrough idea? Keep it and build it! *And get back to 1, or at least 2* (italic: my personal addition).


## Parallel Track 1 - Workflow

Chair: Johan Philips

### The journey of migrating a spreadsheet with 500 rows

Presenter: Neil Chue Hong (Director, Sofware Sustainability Institute), Professort of Research Software Policy and Practice
Slides: https://doi.org/10.6084/m9.figshare.30764660 (CC BY 4.0)

Database was a colleciton of non harmonised ~500 rows long spreadsheets (MS Excel).
The researcher must be sarch by all of them sometimes.
Data quality? Quite poor! Example: a numeric column was not always numeric as comments sometimes were added.

Migration from MS Xecel to PostgreSQL? No, researchers didn't want (have time) to learn SQL. Maybe building a web application on top of it? No, research software engineer didn't have time to do that.
.

Part of the solution: [eLabFTW](https://www.elabftw.net/), a free and open source electronic lab notebook. It's open source, it has an API, it is built with a Role Based Access Control (RBAC) and it has **structured metadata**, which can be created via User Interface.

So, all the worksheet / tables were mapped to resource categories/templates in eLabFTW.


Daily all data go to a data warehouse, where data analysis pipelines and dashboards are built on top of the data.

Now the research team has its own research software engineer and can move further on their own.

### Research software made EESSI: the European Environment for Scientific Software Installations

Presenters: Kenneth Hoste, Lara Peeters.

https://www.eessi.io/docs/

## Keynotes - part 2

### Hack, Fix, Repeat: FOSS and the Future of Systems Security

Presenter: Jo Van Bulck.


[Kerckhoff's Principle](https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle): No Security through Obscurity.

[Linus's Law](https://en.wikipedia.org/wiki/Linus%27s_law): Security through Open Source? *"Given enough eyeballs, all bugs are shallow"* (Eric S. Raymond). 

"Given a large enough beta-tester and co-developer base, almost every problem will be characterized quickly and the fix obvious to someone. [..] Researchers and practitioners have repeatedly shown the effectiveness of reviewing processes in finding bugs and security issues." (Pfleeger, Charles P.; Pfleeger, Shari Lawrence (2003). [Security in Computing, 4th Ed.](https://openlibrary.org/books/OL7339893M/Security_in_Computing_%284th_Edition%29) Prentice Hall PTR. pp. 154–157. ISBN 0-13-239077-9.)

Linux: hundreds of vulnerabilities

Let's speak about [**Confidential Computing**](https://en.wikipedia.org/wiki/Confidential_computing).

Truested execution: hardware-level isolation and attestation.
There is a growing ecosystem of Trusted Execution Environments (TTEs). TTEs are here to stay: "Confidential Computing Today, Just Computing Tomorrow" (Mark Russinovich, CTO Microsoft Azure)

Research Agenda: test security claims of these TTEs

- Offensive security analysis of closed-source (large) commercial systems: critical analysis of vendor claims.
- Defensive prototypes on open-source (small) research systems: next-generation innovations

DistriNet is vetting confidential computing for more a decade.

Let's speak now about [Sancus](https://downloads.distrinet-research.be/software/sancus/), a long-lived open source project, do's and don'ts.

Sancus is a lightweight Trusted computing for the Internet Of Things (IOT).

No commercialization, but FOSS licenses
Limit dependencies
Upstream eagerly : avoid dead forks. 2012-2017: public tarballs + private git. From 2017: move to public GitHub organisation: [Sancus](https://github.com/sancus-tee).

Check the inspiring book The Cathedral & The Bazaar, by Eric S. Raymond (see [online version](http://www.catb.org/~esr/writings/cathedral-bazaar/), [paper book](https://www.oreilly.com/library/view/the-cathedral/0596001088/)).


**Build usable systems**

- large engineering effort resulting in minimal publication effort.
- Simulators and test frameworks
- Continuous integration

**Impact through Education**

Having master students on Sancus allows understanding, by putting theory into practice. Highly recommended: continuous master thesis involvement.

**Science Communication**

Documentation, conferences: FOSSDEM is the most important probably.

Let's speak now about [SGX-Step](https://github.com/jovanbulck/sgx-step), a versatile open-source attack framework.

SGX-Step enlights an important aspect: **Engage with Industry**!
SGX-Step lef to changes in major OSs, Intel chipts and enclaves SDKs.

Conclusions. What are the **magic ingredients**?

1. **Open-source** ecosystem
2. **Modular** base design
3. Impact through **education**
4. Science **communication**
5. Accessible **library design**
6. Reusable **primitives**
7. Engage with **industry**


### The Marvelous Misadventures of a Scientist-in-progress: from PhD Disasters to Corporate Farces

Presenter: Giada Lalli, Bioinformatician

Coding was her next-step. It was like taking control on something she hadn't control before. Coding perceived like a game.

[What makes PhD students happy? Good supervision](https://www.nature.com/articles/d41586-025-03416-7).

Seek **mentorship**, not control
Seek **guidance**, not permission
Seek **direction**, not directives
Seek **feedback**, not instructions
Seek **support**, not dependence

Never forget: you are in charge of your PhD as it's your project. Do not forget that your promotor was in your position just few years before you.

Trust your skills.

And don't be shy, but **reach out** even just for advice.

## Parallel Track 2 - Data & AI/ML

Chair: Ingrid Barcena Roig

### AI pair programming: how lazy can you afford to be?

Presenter: [Geert Jan Bex](mailto:geertjan.bex@uhasselt.be)

Attempt to making slides with voice over.

AI generated code:
How to debug?
How to maintain?


Formulate specs


Write documentation about User Interface and let AI to create code based on it.
Better precision of my speces, more correct the output.

AI is good in "boring work":
- command line arguments
- input validation
- documentation stubs
- initial unit tests

Code completion and suggestions: yes, but pay attention that they could be "outdated", even if working. AI systems 


Code reviews: [sourcery](https://www.sourcery.ai/). Nice.

Use agents: they will improve incredibly the quality.

Online agents:
- GitHub Copilot
- [OpenAi Codex](https://openai.com/nl-NL/codex/)

On your machine:
- OpenAI Codex CLI


OpenAI Codex CLI for something where discussion/iterations are expected as the goal is more complex, not just unit-tests.

Provide context via Markdowns, e.g. `AGENTS.md`.

General guidelines
Specialization:
- in GIthub repository
- in specific directories


Boring science is easy, science not.

- Use scpeifications
- Can save lots of time
- Check answers/review code

You won't be out of a job anytime soon... if you add value and **you know your stuff**.

**AI doesn't replace** competence: it **complements** it.


### Valorise your research by developing software: challenges and opportunities in the domains of digital education and healthcare 

Presenter: Frederik Cornillie, Stefaan Haspeslagh

[Slides](https://kulak.kuleuven.be~u0037921/pub/RSE_Day_2025.pdf).


Think beyond your current collaboration. Have a mission, a long-term goal.

### dtaianomaly: A Python library for time series anomaly detection

Presenter: Louis Carpentier

[dtaianomaly](https://dtaianomaly.readthedocs.io) is a Python tool for time series anomaly detection.

There is a web application on top of it: [InTimeAD](https://intimead.cs.kuleuven.be/) ([GItHub](https://github.com/ML-KULeuven/InTimeAD)).

During poster session, the presenter showed me another Python tool, [patsemb](https://patsemb.readthedocs.io/en/stable/) which could be interesting for migration/spawning detection in eels/shads time series I work on. PaTSEmb is a Python package for creating a pattern-based embedding of the time series. This is an embedding of the time series which contains information about the typical shapes are occurring at which locations in the time series.