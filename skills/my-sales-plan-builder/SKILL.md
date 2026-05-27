---
name: my-sales-plan-builder
description: Build, structure, or polish a sales plan in Chinese or English — monthly, quarterly, or annual — including sales target breakdowns, customer development priorities, opportunity pipeline, action plans, and support requests. Use this skill when the task involves planning ahead, setting sales objectives, or organizing a customer development strategy, not just reporting on what has happened.
---

# My Sales Plan Builder

## What this skill does

Helps build, structure, and polish forward-looking sales plans: monthly, quarterly, or annual.

This skill is about planning — setting goals, organizing priorities, and defining actions. For reporting on what has already happened, use `my-sales-weekly-report` instead.

For general wording and tone, refer to `my-writing-style`. This skill adds plan-specific structure and logic.

## When to use

- Building or organizing a monthly, quarterly, or annual sales plan
- Breaking down a sales target into customer or segment priorities
- Structuring a customer development plan
- Mapping out an opportunity pipeline with action paths
- Writing an action plan with owners and timelines
- Identifying what support or resources are needed

## Default plan structure

Use these sections unless I specify otherwise:

**1. Objectives**
The overall target (revenue, volume, or other KPIs) and the key priorities for this period. State specific numbers where available.

**2. Customer Landscape**
Categorize active and target accounts. See Customer categories below.

**3. Target Breakdown**
How the overall target is distributed. Break down by customer, product category, region, or channel — whichever is most useful for planning.

**4. Opportunity Pipeline**
Active opportunities worth tracking: account name (or placeholder), opportunity size, current stage, and expected timing.

**5. Action Plan**
Specific actions tied to each priority, with owner and timeline. Format: [Action] — [Owner] — [By when].

**6. Support Needed**
Resources, approvals, samples, technical support, or headcount required. State what is needed, from whom, and why.

**7. Key Assumptions and Risks**
What this plan assumes to be true. What could derail it and how serious each risk is.
For each risk, state three things: what could happen, what it would affect (revenue, timeline, relationship), and what the contingency or mitigation is. A risk with no impact statement or response direction is not useful.

## Customer categories

Organize accounts into four types. Each type needs a different plan approach:

**Established accounts**
Stable revenue base. Goal: maintain the relationship, grow wallet share, prevent churn. Action focus: regular contact, service quality, upsell opportunities.

**Developing accounts**
Active engagement underway but not yet generating stable revenue. Goal: advance the relationship to confirmed business. Action focus: follow-through on outstanding items, demonstrations, samples, proposals.

**New targets**
Not yet engaged or in early outreach. Goal: establish contact and qualify. Action focus: prospecting, introductions, first meetings.

**At-risk accounts**
Showing signs of reduced engagement, competitive pressure, or internal changes. Goal: understand the situation and defend the position. Action focus: senior contact, issue resolution, retention offers.

## Breaking down targets

When breaking down a sales target:
- Start with your established accounts as the baseline. What is realistic to maintain or grow?
- Identify how much needs to come from developing accounts and new targets.
- Be explicit about the gap: if targets require new revenue, name where it is expected to come from.
- Do not back-fill with vague growth assumptions — state what is real and what is aspirational.
- Label each contribution as confirmed (已确认) or estimated/assumed (估算 / 假设). Developing accounts and new targets are almost always estimates — say so. Do not present an aspirational number as a committed forecast.

## Writing an action plan

Each action should be specific enough to execute:
- Name the account or segment it applies to.
- State what will be done (visit, proposal, sample, demo, call).
- Assign an owner.
- Set a deadline or frequency.

Avoid actions like "strengthen customer relationships" or "improve product awareness" — these are intentions, not actions.

## Output format

- Write in Chinese by default unless I ask for English or bilingual.
- Use the seven-section structure above for full plans.
- For a quick plan outline, cover: Objectives / Customer priorities / Top 5 actions / Support needed.
- If the user provides scattered notes or goals, organize them into the plan structure before writing prose.

## Avoid

- Invented revenue figures, customer names, or projected outcomes
- Backing into targets without stating assumptions
- Vague actions that cannot be measured or assigned
- Empty growth language ("accelerate penetration", "maximize potential")
- Confidential internal pricing, margin, or strategy details
