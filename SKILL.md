---
name: interview-position-prep
description: "Job-specific interview preparation for users with a target role, job description, resume, personal profile, or project experience. Use when Codex needs to compare a JD with candidate evidence, diagnose resume-role fit, suggest resume revisions, draft a role-specific self-introduction, convert one experience into interview-ready talking points or an expression corpus, prepare behavioral/technical answer material, or position a candidate for a concrete application. Do not use for generic career advice without a target role or for writing unrelated resumes from scratch."
---

# Interview Position Prep

## Overview

Prepare interview materials from the target role outward. Anchor every recommendation in the JD, then map the candidate's resume and experiences into evidence, gaps, and interview language.

## Scope

Use this skill when the user asks for one or more of these outputs:

| User intent | Required inputs | Output |
| --- | --- | --- |
| JD-resume matching | JD + resume/profile | Requirement map, evidence map, match matrix |
| Resume revision | JD + resume/profile | Prioritized edits and rewrite directions |
| Self-introduction | JD + resume/profile | 30-second and 60-90-second versions |
| Experience expression corpus | JD + one experience | story, answer bank, phrase bank, depth ladder |
| Interview answer prep | JD + resume/profile | likely questions and answer angles |

Do not use this skill for generic resume writing without a target role, broad career planning, salary negotiation, or job search tracking unless the user also asks for JD-specific interview positioning.

## Input Handling

Request or infer the minimum useful inputs:

- Target JD or role description. If only a role title is provided, ask for the JD before doing detailed matching.
- Candidate resume, personal profile, LinkedIn-style summary, project notes, or raw experience bullets.
- Interview context if known: company, seniority, location, language, interview round, and target output length.

If inputs are incomplete, proceed with a clearly labeled draft and list the missing information that would improve precision. Do not invent facts, metrics, employers, technologies, awards, or outcomes.

## Quick Decision

First decide whether the materials are sufficient:

| Available materials | Action |
| --- | --- |
| JD + resume/profile | Proceed with full matching and requested artifact |
| JD + one experience | Produce experience-level positioning; ask for resume only if full fit analysis is needed |
| Resume/profile only | Ask for the target JD before detailed positioning; provide only general readiness notes if useful |
| Role title only | Ask for the JD or company posting; do not infer detailed requirements from the title alone |
| Missing metrics or facts | Draft cautiously and mark stronger claims as "needs user confirmation" |

Then route by the user's main goal:

| Main goal | Primary analysis | Required output modules | Optional add-ons |
| --- | --- | --- |
| Judge role fit | Requirement map + evidence strength | Match matrix, top advantages, top gaps, interview positioning |
| Improve resume for this JD | Screening keywords + missing proof | High/medium/optional edits, sample bullet rewrites, facts to confirm |
| Draft self-introduction | 2-3 strongest evidence clusters | 30-second version, 60-90-second version, role-specific closing |
| Reframe one experience | Experience-to-JD relevance | one-sentence pitch, 30-second answer, STAR answer, follow-up bank, phrase bank |
| Prepare interview questions | Implied evaluation criteria | question bank, answer angles, weak-gap handling language |
| Full interview package | All of the above, in priority order | fit summary, resume advice, self-intro, experience corpus, likely questions |

When multiple goals are requested, order outputs by interview usefulness: fit diagnosis first, then resume edits, then self-introduction, then experience corpus, then question bank.

## Core Workflow

1. Parse the JD into a compact requirement map:
   - Must-have skills and qualifications
   - Preferred skills and signals
   - Responsibilities and business goals
   - Keywords, tools, methods, and domain language
   - Implied evaluation criteria, such as ownership, stakeholder work, analysis depth, execution speed, or leadership

2. Parse the candidate profile into evidence:
   - Direct evidence: experience that clearly matches a JD requirement
   - Transferable evidence: adjacent skills that can be credibly reframed
   - Differentiators: unusually strong, rare, or memorable material
   - Risk areas: gaps, weak proof, unclear scope, or unsupported claims

3. Build a JD-to-candidate match matrix. Prefer this structure:
   - JD requirement
   - Candidate evidence
   - Match strength: Strong / Medium / Weak / Missing
   - Recommended positioning
   - Resume or interview action

4. Produce the requested artifacts. Keep all language truthful, specific, and interview-usable.

## Match Matrix Rules

Use these match labels consistently:

| Label | Meaning | Handling |
| --- | --- | --- |
| Strong | Direct evidence clearly supports the JD requirement | Use as main interview story |
| Medium | Evidence is relevant but needs reframing or more detail | Provide rewrite and proof to add |
| Weak | Evidence is adjacent, generic, or thin | Position cautiously and ask for confirmation |
| Missing | No credible evidence in provided materials | Mark as gap; do not fabricate |

For each requirement, state whether the evidence is confirmed from the materials or needs user confirmation.

## Resume Revision Suggestions

When asked for resume suggestions, organize recommendations by priority:

- High impact: changes that directly improve JD fit or screening probability.
- Medium impact: wording, ordering, or evidence upgrades.
- Optional polish: clarity, formatting, or concision.

For each suggestion, include:

- Current issue or missed opportunity
- Why it matters for this JD
- Suggested rewrite or bullet direction
- Missing proof to add, such as metric, tool, scope, stakeholder, dataset size, revenue, users, latency, accuracy, or outcome

Keep edits preliminary unless the user asks for a full resume rewrite. Flag claims that need user confirmation before strengthening.

## Role-Specific Self-Introduction

Draft self-introductions from the role's needs, not from chronological autobiography. Use this structure:

1. Positioning sentence: candidate identity matched to the target role.
2. Evidence cluster: two or three experiences that map to the JD.
3. Differentiator: domain, method, execution style, or cross-functional strength.
4. Motivation bridge: why this company or role is a coherent next step.
5. Close: concise confidence signal.

Offer variants when useful:

- 30-second version for screening calls
- 60- to 90-second version for formal interviews
- Chinese, English, or bilingual version according to the user's language
- More confident, more modest, more technical, or more business-facing tone

## Experience Expression Corpus

When the user provides one experience and asks how to express it for a role, convert it into a reusable corpus:

1. Core story:
   - Context
   - Task or goal
   - Actions
   - Tools, methods, or frameworks
   - Results or learning
   - Relevance to the JD

2. Interview answer bank:
   - "Tell me about this project"
   - "What was your contribution?"
   - "What was difficult?"
   - "How did you measure success?"
   - "What would you improve?"
   - "Why is this relevant to this role?"

3. Phrase bank:
   - Role-aligned verbs
   - Domain keywords
   - Technical or analytical phrases
   - Collaboration and impact phrases
   - Concise resume bullet alternatives

4. Depth ladder:
   - One-sentence pitch
   - 30-second answer
   - 2-minute STAR answer
   - Follow-up details for technical or behavioral probing

Use the JD's language where it fits naturally. Avoid buzzword stuffing and avoid turning a small experience into an exaggerated accomplishment.

## Interview Question Prep

When asked to prepare likely questions, cover:

- Motivation: why this company, role, business line, and product direction.
- Role fit: why the candidate can do the JD's responsibilities.
- Experience depth: contribution, difficulty, trade-offs, metrics, and iteration.
- Product/operation thinking: user segmentation, conversion funnel, retention, content/channel strategy, data monitoring, risk control, and cross-functional execution.
- Weakness or gap handling: concise, honest bridging language.

For each question, provide an answer angle instead of a fully scripted answer unless the user asks for scripts.

## Follow-up Prompting

At the end of a response, suggest one concrete next step when useful. Prefer recommending the strongest experience to convert into an interview expression corpus.

Use this pattern:

- Identify 1-2 experiences that best match the target JD.
- Say why each experience is worth expanding in one short phrase.
- Ask whether the user wants that experience converted into interview language.

Example prompts:

- "Your <experience> matches this role's <requirement> especially well. Do you want me to turn it into a reusable interview expression corpus?"
- "If you want to continue, I suggest expanding <experience> next because it can support questions about <skill/competency>."
- "I can also help convert <experience> into a one-sentence pitch, 30-second answer, STAR story, and follow-up answer bank."

Do not add a follow-up prompt when the user explicitly asks for final-only output, a strict format, or no extra suggestions.

## Output Standards

Write in the user's preferred language. If the source materials mix Chinese and English, preserve role-specific English terms where they are standard in hiring contexts.

Be direct and practical:

- Separate "confirmed from materials" from "needs user confirmation."
- Prefer concrete rewrites over abstract advice.
- Explain the reasoning only enough for the user to revise confidently.
- Preserve the candidate's actual seniority and voice.
- Avoid overclaiming, fabricated metrics, and generic career-coach filler.

For sensitive or high-stakes claims, use cautious phrasing such as "can be positioned as" or "if accurate, strengthen this by adding..."

## Safety Boundaries

- Never invent metrics, titles, responsibilities, company names, awards, publications, tools, or outcomes.
- Never recommend dishonest keyword stuffing or fake project ownership.
- Mark any strengthened claim that depends on missing facts as "needs user confirmation."
- If a resume contains private contact details, do not repeat them unless necessary for the user's requested artifact.
- If the user asks to exaggerate, fabricate, or hide material facts, refuse that part and offer a truthful alternative.

## Quality Checklist

Before finalizing, verify:

- The output starts from the target JD, not a generic candidate narrative.
- Every major claim links to provided candidate evidence or is marked for confirmation.
- The advice includes concrete rewrites or phrasing, not only abstract suggestions.
- The self-introduction has role fit, evidence, differentiator, motivation, and close.
- The expression corpus provides multiple depths: one sentence, short answer, full STAR, and follow-up material.
- The closing follow-up, if included, names a specific experience and the JD requirement it supports.
