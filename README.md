# interview-position-prep

> 🎯 Make interview preparation more targeted, less generic.

`interview-position-prep` is a reusable AI Skill for job-specific interview preparation.  
You can invoke it as:

```text
Use $interview-position-prep to analyze this JD and my resume, then prepare interview materials.
```

## 💡 Why I Built This

Many candidates are not short of experience. They are short of a method to connect their existing experience with a specific role.

`interview-position-prep` starts from a target JD, mines the candidate's profile for transferable evidence, and turns that evidence into interview-ready language.

The goal is not to package a candidate into someone they are not. It is to help them explain their real experience in a way that is concrete, truthful, and role-relevant.


## 🧩 What It Does

`interview-position-prep` helps users prepare for a specific role based on a target JD, resume, personal profile, project, internship, competition, or campus experience.

- 🔍 **JD-resume matching**: break down job requirements and identify strong evidence, weak evidence, transferable experience, and gaps
- 📝 **Resume revision suggestions**: suggest role-specific resume improvements based on screening signals in the JD
- 🧠 **Experience mining**: find role-relevant evidence from non-vertical or indirect experiences
- 🎙️ **Role-specific self-introduction**: draft 30-second and 60-90-second interview introductions based on the strongest evidence
- 🧠 **Experience expression corpus**: turn one experience into reusable interview language, including a pitch, STAR story, phrase bank, and follow-up answers
- 💬 **Interview question prep**: generate likely questions and answer angles based on the role's evaluation criteria

## ✨ Features

- 🎯 **JD-first**: starts from the target role instead of generic career advice
- 🧾 **Evidence-based**: connects every major claim to real candidate material
- 🧭 **Transferable-experience friendly**: helps users without perfectly matched internships find credible role-relevant stories
- 🗣️ **Interview-ready**: produces language that can be practiced, not just abstract suggestions
- 🛡️ **Truthful by design**: avoids fabricated metrics, fake ownership, and exaggerated achievements
- 🔁 **Iterative**: suggests which experience can be expanded next into a deeper interview expression corpus

## 🚀 Part I: Interview Prep Prompt Collection

💡 Usage: The following prompts can be copied directly into a chat with an AI assistant. For best results, paste the complete prompt and replace the input placeholders with your JD, resume, profile, or experience notes.

### 1. JD-Resume Fit Diagnosis

```text
# Role
You are a senior career strategist and interview coach. You are especially good at reading job descriptions, identifying hidden evaluation criteria, and finding transferable evidence from a candidate's existing experience.

# Task
Use $interview-position-prep to analyze the target JD and my resume/profile. Diagnose how well I fit this role and identify which experiences are most useful for interview preparation.

# Constraints
1. Start from the JD, not from generic career advice.
2. Do not fabricate metrics, responsibilities, titles, tools, awards, or outcomes.
3. If an experience is only indirectly related, explain how it can be positioned truthfully.
4. Mark any strengthened claim that needs my confirmation.
5. Prioritize interview usefulness over resume decoration.

# Output Format
Part 1 [JD Requirement Map]: list the role's key requirements, responsibilities, keywords, and implied evaluation criteria.
Part 2 [Candidate Evidence Map]: identify strong evidence, transferable evidence, weak evidence, and missing proof from my materials.
Part 3 [Match Matrix]: use Strong / Medium / Weak / Missing for each major JD requirement.
Part 4 [Interview Positioning]: summarize my best positioning for this role in 3-5 sentences.
Part 5 [Next Step Suggestion]: name 1-2 experiences worth expanding into an interview expression corpus.

# Input
Target JD:
[Paste the job description here]

Resume/Profile:
[Paste your resume or personal profile here]
```

### 2. Resume Revision for a Specific JD

```text
# Role
You are a resume strategist for early-career candidates. You specialize in helping candidates adapt existing experiences to a specific job description without exaggeration.

# Task
Use $interview-position-prep to give preliminary resume revision suggestions for this target role.

# Constraints
1. Only suggest changes that improve JD-role fit.
2. Do not rewrite the resume into a fake profile.
3. Separate confirmed facts from facts that need my confirmation.
4. Preserve my actual seniority and contribution level.
5. Prefer concrete bullet rewrites over abstract advice.

# Output Format
Part 1 [Screening Signals]: list the keywords, capabilities, and evidence the recruiter is likely looking for.
Part 2 [High-Priority Revisions]: changes that directly improve role fit.
Part 3 [Medium-Priority Revisions]: wording, ordering, or evidence improvements.
Part 4 [Sample Bullet Rewrites]: provide role-specific bullet directions or draft bullets.
Part 5 [Facts to Confirm]: list missing metrics, tools, scope, users, stakeholders, or outcomes that would strengthen the resume.

# Input
Target JD:
[Paste the job description here]

Current Resume/Profile:
[Paste your resume or profile here]
```

### 3. Role-Specific Self-Introduction

```text
# Role
You are an interview coach who helps candidates introduce themselves for a specific role in a natural, credible, and structured way.

# Task
Use $interview-position-prep to write a role-specific self-introduction based on the JD and my existing experience.

# Constraints
1. Do not write a chronological autobiography.
2. Start from the role's needs and select only the most relevant evidence.
3. Do not overclaim or invent achievements.
4. Make the introduction sound natural when spoken aloud.
5. If my experience is not vertically matched, use transferable evidence carefully.

# Output Format
Part 1 [Positioning Sentence]: one sentence that defines my fit for this role.
Part 2 [30-Second Version]: concise version for screening calls.
Part 3 [60-90-Second Version]: fuller version for formal interviews.
Part 4 [Evidence Notes]: explain which experiences support the introduction.
Part 5 [Polishing Suggestions]: list what information I can add to make it stronger.

# Input
Target JD:
[Paste the job description here]

Resume/Profile:
[Paste your resume or profile here]
```

### 4. Experience Expression Corpus

```text
# Role
You are an interview expression coach. You are excellent at turning one real experience into reusable interview language for a target role.

# Task
Use $interview-position-prep to convert the experience below into an interview expression corpus for this specific role.

# Constraints
1. Keep the story truthful and grounded in the provided experience.
2. Do not inflate my ownership, metrics, or impact.
3. Translate the experience into the language of the target JD.
4. Prepare both concise answers and deeper follow-up material.
5. Mark missing details that I should confirm or supplement.

# Output Format
Part 1 [Role Relevance]: explain why this experience is useful for the target role.
Part 2 [One-Sentence Pitch]: one sentence I can use to introduce this experience.
Part 3 [30-Second Answer]: a short spoken answer.
Part 4 [STAR Story]: a structured 2-minute version.
Part 5 [Follow-Up Answer Bank]: answers to likely follow-up questions, such as contribution, difficulty, metrics, trade-offs, and improvement.
Part 6 [Phrase Bank]: reusable role-specific verbs, nouns, and sentence patterns.
Part 7 [Details to Add]: missing facts that would make the story stronger.

# Input
Target JD:
[Paste the job description here]

Experience:
[Paste one project, internship, competition, research, campus, or personal product experience here]
```

### 5. Interview Question Preparation

```text
# Role
You are a realistic interviewer and interview coach. You understand how interviewers evaluate candidates for a specific role.

# Task
Use $interview-position-prep to generate likely interview questions and answer angles based on the JD and my resume/profile.

# Constraints
1. Questions must come from the JD's actual responsibilities and evaluation criteria.
2. Include questions that probe weak or indirect experiences.
3. Do not provide generic question lists.
4. Provide answer angles, not overly memorized scripts, unless a script is necessary.
5. Suggest which experience I should use for each answer.

# Output Format
Part 1 [Likely Questions]: grouped by motivation, role fit, experience depth, product/operation thinking, and gap handling.
Part 2 [Answer Angles]: key points I should cover for each question.
Part 3 [Best Experience to Use]: map each question to the most suitable experience from my profile.
Part 4 [Risk Questions]: list questions that may expose weak fit and provide honest bridging language.
Part 5 [Practice Priority]: rank the top 5 questions I should practice first.

# Input
Target JD:
[Paste the job description here]

Resume/Profile:
[Paste your resume or profile here]
```

## 🌱 Core Philosophy

Good interview preparation is not about making experience sound bigger than it is.

It is about making the connection between real experience and role requirements clearer, more specific, and more convincing.

`interview-position-prep` helps users answer three questions:

1. What is this role really evaluating?
2. Which parts of my experience best prove that I fit?
3. How can I explain these experiences in a concrete, truthful, and role-relevant way?

## 📦 Files

```text
interview-position-prep/
├── SKILL.md
├── README.md
└── agents/
    └── openai.yaml
```

## 🛠️ Notes

This repository is designed as a Codex Skill.  
`SKILL.md` is the agent-facing instruction file, while this `README.md` is the human-facing project introduction.
