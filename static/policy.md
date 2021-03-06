---
layout: default
permalink: policy.html
style: "measure document"
---

# Engima Dragons - Workflow Policy

----

## Overview

#### Enigma Dragons is a results-only work environment. 

- We care about what is delivered, and not how long something takes. 
- We communicate in clear and simple requirements. Every ticket should be as simple as possible.
- We value rapid iteration. We merge to master as frequently as possible.
- We write clean code. Code should be built for a team to read and evolve.
- We grant autonomy. Every developer should be given freedom to work how, when, and on what they wish.
- We believe in ownership. You are responsible for your role. You call the shots. You get the credit.

----

## 1. Workflow Process

- All work must happen against Github tickets.
- All active tickets must have a Role label.
- To begin work on a ticket, ensure that the ticket is assigned to you and is moved to the "In Progress" column.
- Only work on 1, or at most 2, ticket(s) at a time.
- If you wish to work on a ticket outside your role consult the Architect or Project Manager first
- Every ticket that is finished must result in a Git commit with the new artifacts (code, document, art)
- A ticket is done when it has been merged to `master`

----

## 2. Rapid Iteration

- For projects that use an approval process, approvals should be prioritized over new work.
- For non-art tasks, no ticket should take more than 60-90 minutes.
- If you discover that more work is needed, create a new ticket and deliver what you have.
- As long as you made substantial progress in delivering the target feature, that's all we need.
- If a ticket is taking a lot more work than you expected, reach out for help.
- Any team member may create a ticket for work they think is needed for the project.

----

## 3. Ownership Process

- Role Leads are listed in the README document for the project.
- Within his role, the role lead makes all final decisions about his area of focus.
- While working on a ticket, you may make your own decisions about how to implement a feature.

----

## 4. Ticket Process

- New tickets must be created in `Incoming`.
- Ticket must have a clear and simple title.
- Ticket must have a Role label.
- Ticket may have a short description, including images, or more detailed requirements.
- If a description isn't needed, don't include one.
- Anyone on the project may create tickets as desired.
- Project Architect and Role Leads can move tickets onto the work board.

----

## 5. Approval Process

### Game Jams
- For Game Jams, no approval is needed. 

### Formal Development
- A reviewer must approve every PR.
- The PR must pass all CI checks.
- Every PR must include a commit with a message linking it to the associated ticket such as `Closes #34`.

----

## 6. Done

A ticket is done when all of the following are true:
- The Ticket is marked Closed 
- Its artifacts have been merged to `master`.

----

## A. Paid Work Guidelines

- For paid work, you are owed payment for a ticket after it is done.
- Payment schedules and rates are worked out prior to joining the project.
- Upon request, any unpaid balance will be sent to you within 48hrs.
- All tickets that have an unspecified size are worth 2 units.

----

## B. Ticket Flow FAQs

**Q: What should I do if I have a question about a particular ticket?**

A: Post a comment on the ticket, addressing it to the Project Manager. `@GithubUsername`

**Q: This Ticket doesn't have a lot of requirements. How do I work on it?**

A: This is your chance to design something that you think will make the game great. Give it your best shot. Build the feature the way YOU want it to look... the way YOU want it to feel. We trust you. Make it great!

**Q: What should I name my branches?**

A: Whatever you wish.

**Q: Should I keep close track of my time?**

A: No. We care about results, not time. If there is new work that you think is needed, open a new ticket.

**Q: What happens if I build a little more than the ticket asks for?**

A: Just check it in with the Pull Request. Don't overthink things.

**Q: If I finish two tickets at the same time, can I submit a PR for both of them?**

A: As long as they are related features, go for it.

----
