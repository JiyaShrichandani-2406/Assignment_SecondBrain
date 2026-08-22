#  Ingestion Mechanism

# Purpose

The ingestion mechanism is responsible for collecting information
from the sources I actually use and storing it in the `raw/` folder
before it is processed by my Personalization Engine.

I am currently using a manual ingestion workflow because my main goal
is to first validate the Second Brain system before automating it.

# Sources

My current information sources are:

- YouTube
- LinkedIn
- GitHub
- 100xEngineers LMS
- LeetCode / GeeksforGeeks
- LLM / ChatGPT
- Personal Notes

Instagram has been consciously removed because it has a lower
signal-to-noise ratio for my current career goal.

# Manual Ingestion Workflow

## Step 1 — Collect

During my normal learning and job-search activities, I identify
useful information from my sources.

Examples:

- A useful YouTube tutorial
- A relevant LinkedIn job posting
- A useful GitHub repository
- An LLM concept I learned
- A DSA problem
- A 100xEngineers lesson
- A useful personal learning note

## Step 2 — Record

I create a Markdown file containing:

- Source
- URL (when available)
- Topic
- Basic notes

The file is stored in the `raw/` folder.

## Step 3 — Filter

The raw information is passed through my Personalization Engine.

The engine evaluates the information against my North Star and
assigns a relevance score from 1–10.

## Step 4 — Synthesize

High-value information is converted into useful notes and stored
inside the `synthesized/` folder.

## Step 5 — Review

I review the synthesized information and decide what action to take.

Possible actions include:

- Learn
- Practice
- Build
- Apply
- Research
- Save for later
- Ignore

---

# Weekly Workflow

I will perform a manual ingestion pass at least once per week.

Example:

Weekly Pass — Saturday

1. Review my sources.
2. Collect useful new items.
3. Create Markdown files in `raw/`.
4. Run the Personalization Engine.
5. Move useful information into `synthesized/`.
6. Review the recommended actions.

# Current Ingestion Evidence

# First Manual Pass

Date: 22 August 2026

### Items Collected

- 2 YouTube resources
- 2 LinkedIn opportunities
- 1 LLM learning resources
- 1 LeetCode problems
- 1 100xEngineers lesson
- 2 GitHub resources
- 1 personal notes resource

Total: 10 real items

All 10 items were stored as Markdown files in the `raw/` folder.

# Future Improvement

Once the manual workflow is validated, I can automate deterministic
parts of the process such as collecting and storing information.

The LLM should remain responsible for personalization, filtering and
synthesis rather than basic fetching and storage.
