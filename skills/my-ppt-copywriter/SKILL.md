---
name: my-ppt-copywriter
description: Write, structure, or polish PPT copy and slide content in Chinese and English — including slide titles, key messages, slide body bullets, deck structure, and optional speaker notes. Use this skill for sales presentations, customer visit decks, product introductions, technical exchange decks, business reviews, and any task where content needs to be shaped into slide format, even when the user doesn't explicitly say "PPT."
---

# My PPT Copywriter

## What this skill does

Shapes content into slide format: slide titles, body bullets, deck structure, and optional speaker notes, in Chinese and English.

This skill does not generate PPT files or handle visual design. It focuses on copy, structure, and the logic of a deck.

For general wording and tone, refer to `my-writing-style`. This skill focuses on slide-level structure and PPT-specific conventions.

## When to use

- Writing or polishing slide titles and body copy
- Structuring a full deck from scattered ideas or a brief
- Translating or adapting PPT content between Chinese and English
- Sales presentations, customer visit decks, product introductions
- Technical exchange decks and project summaries
- Monthly, quarterly, or annual business reviews

## Default output structure

For each slide, use this format unless I ask otherwise:

**Slide [N]: [Slide title]**
Key message: [one sentence — the main takeaway]
Body:
- [bullet 1]
- [bullet 2]
- [bullet 3]
Speaker notes: [optional, only if requested]

For a full deck, propose the slide outline first before writing all slides.

## Core PPT writing principles

**One slide, one core message.**
Every slide should have a single point. If a slide is trying to say two things, split it.

**Conclusion titles, not topic titles.**
Titles should state the conclusion, not just the subject.
- Topic title: "Product Features"
- Conclusion title: "Our Material Cuts Assembly Time by 30%"
If no concrete conclusion is available, use a clear question or sharp topic framing. Avoid vague labels like "Overview" or "Summary."

**Parallel bullet structure.**
Bullets on one slide should be grammatically parallel and similar in weight. Mixing full sentences with fragments in the same list weakens readability.

**Cut ruthlessly.**
Remove anything that doesn't support the slide's key message. Three sharp bullets beat six vague ones.

## Chinese PPT

- 标题结论化：不要只写主题词（如"产品优势"改为"我们的方案节省了 3 道工序"）。
- 要点并列清晰，句式保持一致。
- 避免口号式语言（"全方位""系统化""领先行业"等）。
- 每条要点不超过一行，中文 20 字以内为宜。
- 官腔和废话影响说服力；直接删掉。

## English PPT

- Titles should be action-oriented or conclusion-oriented.
- Keep bullets to one line each where possible.
- Use active voice; avoid "is/are" openings when an action verb works.
- For international audiences, avoid idioms and culture-specific expressions.
- Business English, not marketing copy.

## Common scenarios

**Sales presentation / customer visit**
Lead with the customer's problem or context. Arc: problem → solution → evidence → call to action.

**Product introduction**
Cover: what it is, what problem it solves, key specs or differentiators, application scenarios, why choose us.

**Technical exchange**
Cover: topic and background, key technical points shared, open questions, agreed next steps.

**Project or business review**
Cover: what was planned, what happened, key numbers, gaps or risks, next steps.

## Output format

- Write each slide as a labeled block (see Default output structure above).
- For a full deck, confirm the outline before writing all slides.
- Default language: follow the user's input language. If mixed, ask.
- If tone or audience is unclear, write one version and state the assumption.

## Avoid

- Piling all content into one slide
- Vague or topic-only titles ("Overview", "Highlights", "Introduction")
- Invented numbers, facts, or customer outcomes
- Exaggerated marketing language
- Assuming customer names, project names, or results the user hasn't provided
- Generating actual .pptx files (this skill is for copy and structure only)
