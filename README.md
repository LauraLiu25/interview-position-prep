#interview-position-prep
🎯 Make interview preparation more targeted, less generic.

interview-position-prep is a reusable AI Skill for job-specific interview preparation.
You can invoke it as:

Use $interview-position-prep to analyze this JD and my resume, then prepare interview materials.
💡 Why I Built This
When you revise your self-introduction for the same JD for the third time, you may start wondering:

Am I preparing for an interview, or just wrestling with my own experience again?

Many candidates do not lack experience. They lack a clear way to connect their experience with the role they are applying for.

JD says "user operation", "data analysis", "cross-functional collaboration", and "product thinking".
Resume says project names, competition awards, internship tasks, and several nice-looking but not quite role-specific bullets.

I wanted to turn this repetitive, vague, and sometimes stressful preparation process into a clearer Agent Skill:

from the role, back to the candidate's real experience, then toward interview-ready expression.

🧩 What It Does
interview-position-prep helps users prepare for a specific role based on a target JD, resume, personal profile, project, internship, competition, or campus experience.

🔍 JD-resume matching: break down job requirements and identify strong evidence, weak evidence, transferable experience, and gaps
📝 Resume revision suggestions: suggest role-specific resume improvements based on screening signals in the JD
🎙️ Role-specific self-introduction: draft 30-second and 60-90-second interview introductions
🧠 Experience expression corpus: turn one experience into reusable interview language, including a pitch, STAR story, phrase bank, and follow-up answers
💬 Interview question prep: generate likely questions and answer angles based on the role's evaluation criteria
✨ Features
🎯 JD-first: starts from the target role instead of generic career advice
🧾 Evidence-based: connects every major claim to real candidate material
🗣️ Interview-ready: produces language that can be practiced, not just abstract suggestions
🛡️ Truthful by design: avoids fabricated metrics, fake ownership, and exaggerated achievements
🔁 Iterative: suggests which experience can be expanded next into a deeper interview expression corpus
🚀 Example Prompts
Use $interview-position-prep to analyze this JD and my resume, then give me interview preparation suggestions.
Use $interview-position-prep to write a 60-second self-introduction for this product operations role.
Use $interview-position-prep to turn my CareerMod project into an interview expression corpus.
Use $interview-position-prep to identify which experience best matches this JD and help me prepare answers.
🌱 Core Philosophy
Good interview preparation is not about making experience sound bigger than it is.

It is about making the connection between real experience and role requirements clearer, more specific, and more convincing.

interview-position-prep helps users answer three questions:

What is this role really evaluating?
Which parts of my experience best prove that I fit?
How can I explain these experiences in a concrete, truthful, and role-relevant way?
📦 Files
interview-position-prep/
├── SKILL.md
├── README.md
└── agents/
    └── openai.yaml
🛠️ Notes
This repository is designed as a Codex Skill.
SKILL.md is the agent-facing instruction file, while this README.md is the human-facing project introduction.
