---
name: my-sales-weekly-report
description: Organize, write, or polish a backward-looking sales report — covering what happened in a completed period (week, month, or other interval): customer visit summaries, project pipeline updates, opportunity tracking, risk identification, and support requests. Use this skill when the task is to report on what has already occurred, not to plan what comes next. Trigger even if the user just says "help me write this week's report" or "summarize this month's progress." For forward-looking planning, use my-sales-plan-builder instead.
---

# My Sales Weekly Report

## What this skill does

Helps organize, write, and polish weekly sales reports in Chinese or English.

It handles two common situations: (1) the user has raw notes or scattered updates and needs them shaped into a structured report, and (2) the user has a draft that needs polishing or restructuring.

This skill follows the style principles in `my-writing-style` and adds report-specific structure and judgment.

## Default report structure

Use these sections unless I specify otherwise:

**0. Opening Summary** (optional, 1–3 bullets)
Numerical snapshot of the period: how many customers contacted, orders or shipments submitted, key opportunities advanced, or pending items flagged. No adjectives about whether the week was "good" or "busy" — just numbers and what they indicate.
Example pattern (Chinese): 「本周围绕 X 笔订单、Y 个重点项目、Z 个待跟进事项展开。重点推进 [Project A]；后续动作集中在：[类型 A] / [类型 B]。」

**1. This Week's Highlights**
2–4 bullet points. Key results, wins, or notable developments. Lead with outcomes, not activities.

**2. Customer and Project Updates**
One entry per active account or project. Keep each entry separate — do not mix customers. Use this structure for each:

**[Customer / Project name]**
- 本周进展: what actually happened this week — specific and factual, not intentions
- 下一步: who does what next — name the owner and the action, not just the goal

Flag anything stuck or at risk here, and repeat it in Section 4 (Risks).

**3. Pipeline and Opportunities**
Active opportunities with stage and expected timing. Note changes from last week if last week's report or context is provided; otherwise, describe the current status only. Skip opportunities with no movement unless they need attention.

**4. Risks and Blockers**
Specific issues that could affect timeline, result, or the customer relationship. Be concrete — vague risks are not useful.
Mark high-priority risks with ⚠️. Format: ⚠️ [Risk name]: [specific situation] — [impact if unresolved] — [who needs to act / what decision is needed].

**5. Support Needed**
What requires approval, resources, or action from others. State who needs to do what, and by when.

**6. Next Week Plan**
3–5 specific actions tied to customer or opportunity outcomes, not just activities. Each action must name who does what: [Customer/Project] — [owner or team] — [action] — [by when]. Do not write vague intentions like "follow up" or "continue discussion" without specifying what and who.

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
- When there are multiple pending items, use a table with columns: 优先级 (🔴 高 / 🟡 中 / 🔵 低) / 事项 / 下一步 / 涉及方 / 状态. One row per item. The "下一步" column must be a specific action, not a repeat of the "事项".
- If data in the user's notes is ambiguous or unverifiable, mark it explicitly (e.g., "⚠️ 需确认"). Do not silently smooth over gaps.

## Avoid

- Vague progress language ("正在推进中", "ongoing", "in discussion") with no specifics
- Activity reported as results ("attended meeting", "sent email")
- Inflated language or false positives
- Invented customer names, project data, or outcomes
- Internal confidential information beyond what the user provides
