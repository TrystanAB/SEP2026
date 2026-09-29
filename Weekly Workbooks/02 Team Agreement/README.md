# README

## Instructions for completing the TEAM-AGREEMENT.md document

The TEAM-AGREEMENT.md document is an 8-part structured agreement for team working, based on a combination of practices observed in industry. It is designed to surface your team's working styles and roles, communication and meeting strategy, how decisions get made, what counts as finished work and how the client will be managed. It also serves as an agreed process manual for handling engagement and re-engagement when a team member is struggling or fails to complete work, what the process is if the team gains or loses a member, and a short risk register. 

The TEAM-AGREEMENT.md is jointly constructed and revised, with a signed commitment from every member recorded through Github.

### Why you are doing this

Real world industry teams write documents like this. Scrum teams call them "working agreements". Some companies refer to them as "team charters" or "ways of working".

Most team problems are not technical. They happen when team members expect different things and nobody thinks to mention it. The problem remains, steadily brews, and eventually appears two months later as anger.

Your team has 5 or 6 people. You work at different times. You communicate in different ways. You have different ideas about when work is finished.

The point of this exercise is to write these expectations down now, while everyone is calm.

This document also protects you later. When a problem happens, you follow a plan you made in advance. You do not have to invent a plan while you are stressed.

### Rules for this task

You task is to construct a this document, following the template provided. The document should be written in Markdown.

- All team members must write this document together. An agreement document written by one person is not fit for purpose.
- Eliminate all waffle. The final document must be a maximum of 2 sides of A4 when printed at 11pt.
- You must be exact. "We will communicate well" is meaningless. "We reply on Teams within 24 hours, Monday to Friday" shows actual commitment.
- **You should review and update this document throughout the project**. Review it at each retrospective. Record each change - it will be referred to in your Viva.
- Every member must sign it.

### Where the file goes

The `TEAM-AGREEMENT.md` file must be kept in the root of your project repository, alongside `README.txt`.

Why?

1. Git records every change, so you can see how the document developed.
2. The file is where you already work, so you will open it.
3. Each person signs by making their own commit.

---

## How to complete each section

The numbers below match the numbers in the template.

### Section 1: The team

- Write one row for each member.
- The last column asks for one thing to know about working with you. Write only one sentence each. Be honest; this is not a humblebrag for your LinkedIn profile. An example: "I work late at night, not early. Do not expect a reply at 09:00."
- Choose at least one role that rotates between members.

### Section 2: Communication and meetings

Choose one communication channel as the official channel. Commit to the idea that a decision only counts when it exists there. Then answer these questions:

- **How fast do we reply?** Try to give a number of hours for weekdays. Say what happens at weekends.
- **When is our weekly meeting?** Give a day, a time and a place. Meet in person when you can; do not rely on online meetings.
- **Where do we store notes and decisions?**

**Language.** You can talk to each other in any language. However, a decision is only real when it is written in the official channel, in English.

### Section 3: How we decide

Answer three questions:

1. How do we normally decide? By consensus, or by majority vote? Or some other process?
2. What do we do when we cannot agree? Consensus will almost certainly fail at least once.
3. Who can decide certain things alone, without asking? Name the area and the person.

### Section 4: What counts as done

- Write a **Definition of Done**. This is a list of 3 or 4 conditions that all work must meet. For example: reviewed, tested, merged, documented.
- Create a **review rule**. Who reviews whose work? Within how many hours?

### Section 5: Client and stakeholders

Choose and name one person who contacts the client. Name a second person to replace them when they are ill or away. Then answer:

- How often do we meet the client? Who prepares for the meeting?
- How does a client request become an item on our project to-do board?

### Section 6: Engagement and re-engagement

**This is the most important section. Give this plenty of thought.**

- Construct a **ladder** of stages and give each stage a time limit. **Agree that you will not skip stages**.
- Assume there is a reason: a member may be ill. They may have family problems or money problems. Your first question is "are you okay?", not "WTAF, where is your commit?"
- Plan their return. Say what happens when a member becomes active again. Give them one small, clear task and one partner. Do not give them all the work they missed.
- Agree a straightforward signal that members can use to call a timeout. For example, one word posted in the channel that means "I have too much work this week".

### Section 7: If the team changes

- **If a member leaves:** write which work you will remove from the project.
- **If a member joins:** write an onboarding checklist, e.g. repository access, Teams channel, documents, a named partner, and one clear first task.
- **Work out your bus factor.** This is the number of people a team can lose before the project stops. One person must not be the only person who can deploy the system, access an account, or explain a part of the code. Write how you will prevent this.

### Section 8: Risks, review and signatures

List 3 risks. For each risk, name an owner and a trigger. A trigger is something that indicates that the risk is happening.

Finally, add:

- How often you will review this document.
- A table that records each change you make.
- The signature of every member.

**This is a living document** You will need to review it. Many ideas will not survive first contact with reality - this is both expected and perfectly acceptable.

## Background and supporting materials

The contents of the TEAM-AGREEMENT.md document incorporates various ideas and processes from team formation and management strategy in industry. Here are some background materials for you to explore as you construct your agreement:

* **Working Agreement.** Atlassian’s Team Playbook. [https://www.atlassian.com/team-playbook/plays/working-agreements](https://www.atlassian.com/team-playbook/plays/working-agreements)
* **Personal User Manual (AKA personal README).** Atlassian’s Team Playbook. [https://www.atlassian.com/team-playbook/plays/my-user-manual](https://www.atlassian.com/team-playbook/plays/my-user-manual)
* **Handbook-First Approach to Communication (single source of truth).** The GitLab Handbook. [https://handbook.gitlab.com/handbook/company/culture/all-remote/handbook-first/](https://handbook.gitlab.com/handbook/company/culture/all-remote/handbook-first/)
* **DACI (Driver, Approver, Contributors, Informed).** Intuit. See [https://www.atlassian.com/team-playbook/plays/daci](https://www.atlassian.com/team-playbook/plays/daci)
* **Disagree and Commit.** Amazon. [https://www.aboutamazon.com/about-us/leadership-principles](https://www.aboutamazon.com/about-us/leadership-principles)
* **Scrum Values (Commitment, Focus, Openness, Respect, Courage).** Scrum 2020 Guide. [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html)
* **Definition of Done.** Scrum. [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html)
* **Retrospective.** Scrum. [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html)
* **Escalation Policy:** PagerDuty. [https://response.pagerduty.com/](https://response.pagerduty.com/)
* **Blameless Postmortem / Learning from Failure.** Google. [https://sre.google/sre-book/postmortem-culture/](https://sre.google/sre-book/postmortem-culture/)
* **Understanding Team Effectiveness.** Google. [https://rework.withgoogle.com/intl/en/guides/understand-team-effectiveness](https://rework.withgoogle.com/intl/en/guides/understand-team-effectiveness)
* **Onboarding Buddy.** GitLab. [https://handbook.gitlab.com/handbook/people-group/general-onboarding/onboarding-buddies/](https://handbook.gitlab.com/handbook/people-group/general-onboarding/onboarding-buddies/)
* **Async-first Communication.** Mural. [https://www.mural.co/blog/async-first-culture](https://www.mural.co/blog/async-first-culture)
* **Andon cord.** Toyota. [https://itrevolution.com/articles/kata/](https://itrevolution.com/articles/kata/)
* **Squad Health Check.** Spotify. [https://engineering.atspotify.com/2014/09/squad-health-check-model](https://engineering.atspotify.com/2014/09/squad-health-check-model)
* **Project Aristotle** Google. [https://psychsafety.com/googles-project-aristotle/](https://psychsafety.com/googles-project-aristotle/)