---
description: Review a PR using the software-engineer skill
---

Use the skill `software-engineer` to review the following PR: $1

PR details:
!`gh pr view $1 --json title,body,additions,deletions,files,headRefName,baseRefName --jq 'title + "\n---\n" + body + "\n\nChanges: +\(.additions)/-\(.deletions) lines, \(.files | length) files\nBase: \(.baseRefName) ← Head: \(.headRefName)"'`

Review the code and post inline comments if you find any issues. Read the full diff with `gh pr diff $1` to examine the changes.
