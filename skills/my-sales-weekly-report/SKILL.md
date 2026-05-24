---
name: my-sales-weekly-report
description: Organize, write, or polish a sales weekly report — including customer progress summaries, project pipeline updates, opportunity tracking, risk identification, support requests, and next-week plans. Use this skill whenever the task involves a weekly sales report or summarizing scattered customer and project updates into a structured report, even if the user just says "help me write this week's report."
---

# My Sales Weekly Report

## What this skill does

Helps organize, write, and polish weekly sales reports in Chinese or English.

It handles two common situations: (1) the user has raw notes or scattered updates and needs them shaped into a structured report, and (2) the user has a draft that needs polishing or restructuring.

This skill follows the style principles in `my-writing-style` and adds report-specific structure and judgment.

## Default report structure

Use these sections unless I specify otherwise:

**1. This Week's Highlights**
2–4 bullet points. Key results, wins, or notable developments. Lead with outcomes, not activities.

**2. Customer and Project Updates**
One brief entry per active account or project: current status, what progressed this week, and the immediate next step. Flag anything stuck or at risk.

**3. Pipeline and Opportunities**
Active opportunities with stage and expected timing. Note changes from last week. Skip opportunities with no movement unless they need attention.

**4. Risks and Blockers**
Specific issues that could affect timeline, result, or the customer relationship. Be concrete — vague risks are not useful.

**5. Support Needed**
What requires approval, resources, or action from others. State who needs to do what, and by when.

**6. Next Week Plan**
3–5 specific actions tied to customer or opportunity outcomes, not just activities.

## Organizing scattered input

When the user provides raw notes or unstructured updates:
- Group information by customer or project first, then map to the sections above.
- Separate what happened (fact) from what it means (judgment).
- If something is a risk or a blocker, label it explicitly — do not bury it in the updates.
- If an action requires someone else, make the dependency clear.
- Ask for missing information only if a section is too sparse to be useful.

## Facts, judgments, risks, and actions

Keep these distinct. Present them clearly:

- **Fact**: "Customer A confirmed the order on Thursday."
- **Judgment**: "Customer B appears interested but is likely waiting on internal budget approval."
- **Risk**: "If we do not receive confirmation by Friday, the Q2 delivery window will be at risk."
- **Action**: "Follow up with Customer C on the revised spec by Tuesday."

Do not present a judgment as a fact. Do not bury a risk inside a progress update.

## Output principles

- Write in Chinese by default unless I ask for English or bilingual.
- Use bullet points and short sentences; avoid dense paragraphs.
- Use specific numbers, names, and dates where available.
- Lead each section with what matters most.
- If the user provides raw notes, shape them into the report structure — do not just reformat.

## Avoid

- Vague progress language ("正在推进中", "ongoing", "in discussion") with no specifics
- Activity reported as results ("attended meeting", "sent email")
- Inflated language or false positives
- Invented customer names, project data, or outcomes
- Internal confidential information beyond what the user provides
