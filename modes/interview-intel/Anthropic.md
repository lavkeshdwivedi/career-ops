# Anthropic Interview Intelligence

## Overview

Anthropic's process is thorough, thoughtful, and deliberately paced. Interviewers are deeply technical and genuinely curious — they value people who can engage seriously with both the capabilities and the safety implications of large language models. Expect a mix of engineering depth, research breadth, and serious conversation about AI risk.

The culture is collaborative rather than combative. Interviewers want to see how you think, not just whether you get the right answer.

> ⚠️ Verify: Process details change. Confirm current format with your recruiter before the first call.

---

## Stages

| Stage | Format | Typical Duration |
|-------|--------|-----------------|
| Recruiter screen | 30 min phone | 1 week to schedule |
| Hiring manager / team intro | 45–60 min, background + team fit | Within 2 weeks |
| Technical screen × 1–2 | Coding or ML deep dive, 60 min each | 1–2 weeks |
| Virtual on-site | 4–6 rounds × 60 min | Scheduled as a full day block |
| Writing / work sample (some roles) | Async, 2–4 hours | Sent after technical screen |
| Reference checks | 3 references, substantive | After on-site |
| Offer | Written offer with detailed breakdown | 1–2 weeks post on-site |

### On-site round breakdown (typical for mid–senior engineering)

- **Coding × 2** — algorithms, data structures, sometimes ML-adjacent
- **System design × 1** — distributed systems or ML infrastructure
- **ML / research depth × 1** — model evaluation, safety, interpretability, or fine-tuning
- **Mission & values × 1** — reasoning about AI safety, tradeoffs, and ethics
- **Cross-functional fit × 1** — collaboration, communication, judgment under ambiguity

---

## Typical Questions

### Behavioral

- "Why are you interested in Anthropic's approach to AI safety compared to other labs?"
- "Tell me about a time you had to balance speed with rigor — how did you decide?"
- "Describe a project where you had to change course mid-execution based on new information."
- "What's a technical belief you've changed your mind on in the last two years?"
- "How do you handle disagreements about what to build or how to build it?"

### ML / Applied AI

- "How would you evaluate whether a fine-tuned model is actually safer than its base model?"
- "Walk me through the Constitutional AI approach — what are its strengths and blind spots?"
- "How do you measure alignment in a model that you can't enumerate all possible inputs for?"
- "What are the tradeoffs between RLHF and direct preference optimization (DPO)?"
- "Design a red-teaming framework for a new capability added to Claude."

### System Design

- "Design a feedback collection pipeline that minimizes annotation bias."
- "How would you build an inference system that can gracefully degrade under load?"
- "Design a versioning and rollback system for ML model deployments in production."

---

## Coding Tasks

Expect **LeetCode medium** difficulty, sometimes with a research or NLP framing:

- Implement a basic tokenizer or BPE merge step.
- Given a dataset of model outputs and human ratings, compute inter-rater reliability.
- Efficiently compute pairwise similarities in a large embedding space.
- Parse structured + unstructured mixed data into a canonical format.
- Classic algorithm problems (graph traversal, DP, string manipulation) — clean code matters.

**Python is standard.** Anthropic values clarity and correctness over cleverness. Write code you'd be comfortable reviewing with a colleague.

---

## Cultural & Technical Signals

| Signal | What they're looking for |
|--------|--------------------------|
| **Safety seriousness** | Do you engage with AI risk as a real engineering and research problem, not a PR concern? Surface-level answers don't pass. |
| **Epistemic humility** | Anthropic values people who hold views with appropriate uncertainty and update on evidence. Overconfidence is a red flag. |
| **Writing quality** | Many roles include an async writing sample. Clear, precise writing is a core competency — not a bonus. |
| **First-principles thinking** | They want to see you build up answers from fundamentals, not recite memorized patterns. |
| **Collaborative disagreement** | Challenge ideas respectfully. Interviewers test whether you can maintain position under pressure while staying open. |
| **Mission fit** | Generic "I love AI" answers don't land. Specific engagement with Anthropic's research directions and published work does. |

---

## Pro Tips

1. **Read the Anthropic research blog before your interview.** At minimum, understand the Constitutional AI paper and the Responsible Scaling Policy. Reference them with specific details, not just titles.
2. **Prepare a concrete view on a safety tradeoff.** "Here's a capability I think we should be careful about, and here's how I'd approach it" shows you think seriously about the mission.
3. **The writing sample is a real filter.** If there's an async component, treat it as a high-priority deliverable. Clarity, structure, and precision matter as much as content.
4. **Don't undersell interpretability knowledge.** Even rudimentary familiarity with mechanistic interpretability signals genuine interest in Anthropic's research agenda.
5. **Ask about team-specific safety challenges.** It shows depth of engagement and helps you evaluate role fit.
6. **Compensation is structured but negotiable.** Equity vesting schedules and signing bonuses have flexibility. Competing offers are the strongest lever.

---

*Sources: public Glassdoor reviews, Blind threads, Anthropic engineering blog, open candidate write-ups. Verify current process with your recruiter.*
