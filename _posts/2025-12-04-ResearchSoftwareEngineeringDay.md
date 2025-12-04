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



### The Marvelous Misadventures of a Scientist-in-progress: from PhD Disasters to Corporate Farces

Presenter: Giada Lalli