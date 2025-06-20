+++
title = "new grad swe recruiting"
date = "2025-05-31"
+++

this is my guide to navigating the new grad software engineering recruiting process, from applying to landing an offer. it’s based on my real experiences with various companies from startups to faang, and inspired by my friend bradley tian (berkeley'25, incoming at openai) and his detailed [early-career swe guide](https://docs.google.com/document/d/10js6ag75jgrwsng7eklexppmks3dpmwzsnibwe3sawq/edit?tab=t.0#heading=h.iadjqcmoxurc).

---

## ⚠️ disclaimer & background

i’m **not** a cracked, top-tier bay area cs student. i just grew up building pcs and playing games, and one day my aunt said:

> “you’re always on the computer. why not make it your job?”

that stuck. i picked up cs in hs with limited resources, and in college i realized how little i knew about how computers _really_ worked. the deeper i went, the more fascinated i became with creating software and understanding systems under the hood.

i’ve been extremely lucky to have interned at **google** multiple times, worked part-time at **amd**, and a part of a **student tech consulting club** that gave me hands-on experience and a great support system. i also want to acknowledge how hard recruiting is, especially for **international students** navigating visa barriers. everyone’s journey is different.

this guide is for people who feel like they’re _not the best_. you don’t need to be a usaco platinum or a leetcode god.

i still haven’t finished leetcode 75. i noticed i **learn best under pressure**, so i started using interviews as way of preparation, which i will get into later.

just keep learning and showing up. use each experience as a building block.

> you only lose when you stop trying.

i hope this helps anyone feeling overwhelmed or unprepared. you’re more capable than you think.

---

## tl;dr

- **apply early.**
  - for spring grads, start applying as early as june before senior year, many roles are rolling. don't give up if you're still applying late into your senior year. i was still applying for roles in april and i got a handful of interviews in may. it does depend on how the market is faring as well. finalize your resume in may and begin leetcoding right after finals if you can.
- **apply broadly.**
  - if you're a generalist or non-researcher, don’t limit yourself to specific sectors. entry-level roles don’t expect deep niche knowledge. apply broadly and prep as you go. you can learn a lot with just 1–2 weeks of focused prep before interviews. don’t wait to “know everything” before applying. good companies have recruiters and interviewers that want you to succeed, and if they don’t, that says something about the company.
- ensure your resume has **extensive coverage** to avoid getting filtered out.
  - make sure your resume has broad and relevant coverage to avoid getting filtered out. in my opinion, don’t waste time tailoring it for every role. instead, build a strong general resume that highlights **key and relevant tools**, skills, and experiences. if you're getting 0 interviews, it's time to revise your resume. use all available resources: your school’s career center, honor societies, fraternities, friends, or online experts.
- **keep taking interviews** and **learn from each one.**
  - take every interview opportunity, even if you don’t feel fully prepared. you’re not expected to know everything. what matters is showing effort, clear communication, and creative problem-solving.
  - after each interview, write down what happened, questions asked, what went well, and what didn’t. if you couldn’t solve a question, review it later and try again. this reflection is way more effective than just moving on and forgetting it happened.
  - if you get rejected, politely ask for feedback. you might not always get it, but when you do, it’s valuable. and remember: it’s not personal. treat every interview as a learning opportunity, stay respectful, and keep improving.
  - if you’re stuck mid-question, talk through your thought process. say things like “i’m thinking of trying x, but i’m not sure if it’s optimal…”. this invites your interviewer to engage and often leads to helpful nudges. most interviewers genuinely want you to succeed.

---

## about me

- **degree**: b.s. in electrical engineering & computer sciences
- **school**: uc berkeley
- **graduation**: may 2025
- **focus**: computer science

### high school

- ap computer science a / principles
- los angeles computing circle
- google computer science summer institute
  - built a terraria-style survival game (javascript)
- created a google sheets extension for budgeting called budget sheets
- built small projects in react.js and next.js

### year 1 (freshman)

- **cs61a**: structure & interpretation of computer programs
- **cs61b**: data structures & algorithms
- student tech services: student tech consultant (hardware/software troubleshooting)
- internship: google wear (mountain view, ca, usa) - internal test engineering dashboard (angular)

### year 2 (sophomore)

- **cs61c**: computer architecture
- **data8**: intro to data science
- hackathon: cal hacks – blockchain wallet project
- plextech: mobile app for car maintenance (react native, spring boot, postgresql)
- plextech: music tag visualization dashboard (react + typescript + jotai)
- internship: google recaptcha (durham, nc, usa) - bot signals, threat report (java, golang, javascript)

### year 3 (junior)

- **cs70**: discrete math & probability
- **cs161**: computer security
- **cs162**: operating systems & system design _(favorite course!)_
- **cs164**: compilers & programming languages
- **cs186**: database systems
- **eps109**: scientific simulations with python/jupyter
- cloud at cal: legal doc summarization app with tone rewriting
- internship: google recaptcha (montreal, qc, canada) - multilingual signal collection framework, feature engineering, validation stage for data pipeline (java, golang, python, javascript, bazel)

### year 4 (senior)

- **data100**: principles & techniques of data science
- part-time swe at amd
  - built full-stack tools using angular, django, postgresql
- ported [plextech website](https://plextech.berkeley.edu/) from html+css+js to next.js

### now

- full-time swe at google on ads engineering (irvine, ca, usa)

---

## introduction

recruiting is tough.

as my friend dylan huynh (berkeley ‘24, databricks) once told me (paraphrased):

> “recruiting is just a numbers game and all you can do is just increase your odds. there are too many variables that come with it, and there’s no clear-cut path to getting an offer.”

**this guide will be broken up into the following stages of the interview process**:

- applying (internal/external applications, resume prep, networking, how to get experience)
- interviews
  - recruiter screening
  - technical
  - behavioral
  - system design
- offer
  - review
  - negotiate
  - accept

we will focus on the first two topics extensively and the latter topics will be some small words of advice.

---

> **Note:**
THIS SECTION IS A WORK IN PROGRESS; PLEASE COME BACK AGAIN LATER.

## applying

### internal vs. external applications

- when to prioritize referrals
- how to reach out to recruiters, engineers, and alumni
- how to track applications (spreadsheet, notion, airtable)
- sourcing jobs via career fairs, LinkedIn, team pages, Discord/Slack, and career mailing lists

### resume prep

- how to structure an effective 1-page resume
- the "golden triangle": top third of your resume matters most
- action verbs + measurable impact
- keyword scanning and ATS systems
- how to position class projects or club work like internships

### networking

- cold outreach templates (LinkedIn/email)
- how to ask for referrals without being annoying
- building genuine connections at events or online
- why to follow up after interviews or coffee chats
- examples of successful outreach → referral → interview

### how to get experience

- clubs, research, side projects, freelancing, teaching
- don’t overlook: course projects, open-source, hackathons
- how to present non-internship experience on your resume
- using GitHub as a portfolio (README, clean commits, docs)

---

## interviews

### recruiter screening

- how to prepare for common questions:
  - "tell me about yourself"
  - "why our company?"
  - "what are you looking for?"
- how to stand out without sounding scripted
- being honest about timelines, interests, and gaps

### technical

- dsa prep strategies (leetcode grind vs. topic-based)
- how to study under a time constraint (e.g. 2 weeks before interview)
- frameworks for solving problems out loud (clarify, plan, code, test)
- common patterns: sliding window, two pointers, BFS/DFS, heap, etc.
- how to handle system-level questions (e.g. OS, memory, concurrency)
- whiteboard vs. virtual interviews (tips and differences)

my friend matthew nguyen (meta intern, berkeley ‘26) gave me this great mindset:

> “gaslight yourself into loving the topic you’re studying.”

### behavioral

- STAR method (situation, task, action, result)
- common prompts: conflict, leadership, failure, teamwork
- how to tie in technical depth during behavioral rounds
- mistakes to avoid (rambling, vague responses, no reflection)

### system design

- beginner-friendly intro to SD for new grads
- high-level topics to understand:
  - REST vs. RPC
  - load balancers, CDNs, caching
  - basic scaling strategies (vertical, horizontal)
  - data modeling and storage (SQL vs. NoSQL)
- how to walk through an API design or architecture sketch
- resources: Grokking System Design, ByteByteGo

---

## offer

### review

- what to check in an offer: role, location, comp, team, manager
- how to evaluate company fit (growth, stability, mentorship)
- comparing startup vs. big tech offers

### negotiate

- how to ask for more money/tc: scripts and best practices
- what leverage you actually have as a new grad
- working with third-party negotiation services (e.g. Rora, Levels.fyi)
- equity: RSUs, cliffs, vesting schedules explained

### accept

- how to politely decline other interviews or offers
- when to accept early vs. wait for other responses
- post-acceptance prep (onboarding, housing, relocation, tax docs)

---

## final thoughts



---

## favorite resource

i highly recommend **[grokking algorithms](https://www.amazon.com/Grokking-Algorithms-illustrated-programmers-curious/dp/1617292230)**.  
it helped me break down complex topics into **visuals and stories** i could understand and explain clearly in interviews.
