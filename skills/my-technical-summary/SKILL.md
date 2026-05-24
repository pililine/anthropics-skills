---
name: my-technical-summary
description: Organize and write technical exchange summaries, customer meeting notes, sample testing feedback, product application discussions, and technical clarification documents in Chinese and English. Use this skill whenever the task involves summarizing a technical conversation, documenting test results or technical requirements, or capturing action items from a technical meeting — even when the user just says "help me write up what we discussed."
---

# My Technical Summary

## What this skill does

Turns technical conversations, meetings, and exchanges into structured written records — in Chinese or English.

Handles: technical exchange notes, customer meeting summaries, sample testing feedback, product application discussions, R&D and sales alignment memos, and technical clarification records.

For general wording and tone, refer to `my-writing-style`. This skill adds the structure and rigor specific to technical documentation.

## When to use

- Summarizing a technical exchange or customer meeting
- Documenting sample testing results, conditions, or feedback
- Recording product application requirements and open questions
- Writing up a quality issue or technical clarification
- Capturing action items and next steps from technical discussions
- Aligning R&D, sales, and customer communication in writing

## Default output structure

Use these sections unless I specify otherwise:

**Background**
Who was involved, what triggered the exchange, and what product or application is being discussed.

**Key Discussion Points**
Main topics covered: what was shared, proposed, demonstrated, or agreed.

**Technical Requirements**
Confirmed or stated requirements: specifications, performance targets, application conditions, constraints.

**Open Questions**
What is still unclear, unconfirmed, or pending. Label each item as open.

**Risks**
Technical risks, compatibility concerns, or known limitations relevant to the discussion.

**Action Items**
Who does what, by when. One action per line. Format: [Person/party] — [action] — [deadline or timeframe].

**Next Steps**
Timeline, follow-up plan, or agreed next touchpoint.

If a section has no content, write "[None at this stage]" rather than omitting it.

## Distinguishing information types

Keep these distinct. Never mix or blur them:

- **Confirmed fact**: "The customer confirmed operating temperature: 150°C continuous."
- **Customer feedback**: "The customer said adhesion on the second sample was acceptable."
- **Technical judgment**: "Based on the stated spec, our current formulation may not meet this requirement."
- **Assumption**: "Assuming substrate is treated aluminum — not yet confirmed."
- **Open question**: "Does the customer require UL certification? Not discussed."

Do not state an assumption as a confirmed fact. Do not present a technical judgment as a test result.

## Common content areas

**Sample testing**
Record: what was tested, by whom, under what conditions, and what the feedback was. If test results are not yet available, say so explicitly. Never invent test data, pass/fail outcomes, or performance numbers.

**Product application discussion**
Capture: the application scenario, stated requirements, proposed solution or approach, and what still needs confirmation before moving forward.

**Formulation or material discussion**
Note: what properties were discussed, what targets were given, what the current status is. Mark unconfirmed technical details clearly.

**Quality issue**
Describe: the symptom, the context, and what is currently known. Separate confirmed findings from what is still under investigation.

**Technical clarification**
State: what question was raised, what was answered, and whether the answer is confirmed or provisional.

## Chinese and English technical writing

- 技术参数直接写数字和单位，不要模糊化（如"高温"改为"85°C 持续 24 小时"）。
- 状态未确认的事项要标注（如"待确认""暂定""客户待回复"）。
- 不同类型的信息（事实 / 反馈 / 判断 / 假设 / 待确认）在同一文档里要保持一致的标注方式。
- In English, state clearly what is agreed and what is pending — avoid hedge language that obscures actual status.
- Keep English technical terms consistent throughout; do not alternate between synonyms for the same term.

## Output format

- Default language: follow the user's input language. If the exchange was bilingual, ask which output language is needed.
- Use the seven-section structure above for most summaries.
- For shorter exchanges (one topic, few action items), compress into Background / Key points / Action items only.
- Keep each section concise — a technical summary is not a transcript.

## Avoid

- Invented test data, specifications, or technical conclusions
- Stating unconfirmed assumptions as facts
- Omitting open questions to make the summary look cleaner than it is
- Vague entries like "discussed product performance" with no specifics
- Real customer names, company names, or confidential formulation details
- Internal pricing, cost structure, or margin information
