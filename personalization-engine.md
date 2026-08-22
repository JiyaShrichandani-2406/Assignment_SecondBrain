# Step 5 — Personalization Engine

# Purpose

The Personalization Engine evaluates incoming information against my
North Star and determines whether the information is useful for my
career goal.

My North Star is:

> By November 2026, as a prefinal-year Computer Science student who
> has completed Full Stack Development with Python and is currently
> learning Generative AI, I will secure a Full Stack/AI Developer job
> by building and deploying at least 2 AI-powered full-stack projects,
> completing 150+ DSA problems, and receiving at least one job offer.

# Scoring Criteria

Each incoming item is scored from 1 to 10.

# 1. Career Relevance — 0 to 3 points

Does this information directly help me get a Full Stack/AI Developer
job?

- 3 = Directly related to my target role
- 2 = Related to software development or technology careers
- 1 = Indirectly useful
- 0 = Not related

# 2. Skill Development — 0 to 2 points

Does this help me improve an important technical skill?

- 2 = Strongly improves a required skill
- 1 = Somewhat useful
- 0 = Does not improve my skills

# 3. Generative AI / Full Stack Relevance — 0 to 2 points

Does the information support my Full Stack or Generative AI learning?

- 2 = Directly related
- 1 = Partially related
- 0 = Not related

# 4. Interview / DSA Value — 0 to 1 point

Does it help with DSA, technical interviews or placement preparation?

- 1 = Yes
- 0 = No

# 5. Project / Portfolio Value — 0 to 1 point

Can I use this information to build or improve a project or portfolio?

- 1 = Yes
- 0 = No

# 6. Actionability — 0 to 1 point

Can I take a clear action from this information?

- 1 = Yes
- 0 = No

# Total Score

Maximum Score = 10

# Priority Levels

# 8–10 → HIGH PRIORITY

The information directly supports my North Star.

Action:
Learn, practice, build, apply or investigate immediately.

# 5–7 → MEDIUM PRIORITY

The information is useful but not immediately important.

Action:
Save it for later or review when relevant.

# 1–4 → LOW PRIORITY

The information has little connection to my current goal.

Action:
Ignore or do not include it in the synthesized knowledge base.

# Personalization Prompt

For every incoming item, I will use the following prompt:

You are my personal career-information filter.

My North Star is:

"By November 2026, as a prefinal-year Computer Science student who
has completed Full Stack Development with Python and is currently
learning Generative AI, I will secure a Full Stack/AI Developer job
by building and deploying at least 2 AI-powered full-stack projects,
completing 150+ DSA problems, and receiving at least one job offer."

Evaluate the following incoming information against my North Star.

For the given item:

1. Identify its category:
   - Job
   - Learning
   - DSA / Interview
   - Generative AI
   - Project / Portfolio
   - Other

2. Give it a relevance score from 1–10.

3. Explain briefly why it is relevant or not relevant to my goal.

4. Identify the specific skill, opportunity or outcome it supports.

5. Recommend one action:
   - Apply
   - Learn
   - Practice
   - Build
   - Research
   - Save for later
   - Ignore

6. If the score is below 5, explain why it should be filtered out.

Return the result in this format:

Title:
Category:
Score:
Why Relevant:
Skill / Goal Supported:
Recommended Action:
Priority:
