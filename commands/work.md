---
description: Implement a GitHub issue using the software-engineer skill
---

Use the skill `software-engineer` to implement the following ticket: $1

Ticket details:
!`gh issue view $1 --json title,body,labels --jq 'title + "\n---\n" + body + "\n\nLabels: " + (if .labels then ([.labels[].name] | join(", ")) else "none" end)'`

Follow the software-engineer skill process — read the story, plan, write code, create a PR. Create your branch from `API-v1-Migration` and push a PR targeting the same branch.
