# Amazon Interview Intelligence

## Overview

Amazon's interview process is unlike any other major tech company in one critical way: the **Leadership Principles (LPs)** are not a soft filter — they are the primary evaluation framework. Every behavioral question maps to one or more LPs, and interviewers score candidates against them explicitly. You can have excellent coding skills and still fail because your behavioral stories don't demonstrate LP depth.

For ML/AI roles (Alexa AI, AWS AI/ML, AGI, Bedrock, etc.), there's strong additional emphasis on applied ML systems, production reliability, and customer-backward thinking.

> ⚠️ Verify: Process details change. Confirm current format with your recruiter before the first call.

---

## Stages

| Stage | Format | Typical Duration |
|-------|--------|-----------------|
| Recruiter screen | 30 min phone | Within 1 week |
| Online assessment (OA) | 2 coding problems, 90 min, timed | Within 1–2 weeks (some roles) |
| Technical phone screen × 1–2 | 60 min, coding + LP question(s) | 1–2 weeks |
| Virtual on-site ("loop") | 5–7 rounds × 60 min | Scheduled as a full day |
| Debrief / bar-raiser decision | Internal — candidate not present | 3–7 days |
| Offer | Written, tight negotiation window | Within 1 week |

### On-site loop breakdown (SDE / Applied Scientist, SDE II–Principal)

- **Coding × 2** — algorithms + implementation problems, often LP-adjacent framing
- **System design × 1** — large-scale distributed systems ("design Amazon's X")
- **ML design × 1** (ML roles) — end-to-end ML pipeline design, evaluation strategy
- **Behavioral × 2–3** — LP deep dives; each interviewer focuses on 2–4 LPs
- **Bar raiser × 1** — senior interviewer from a different team, focused on overall bar, not team fit

---

## Leadership Principles — Interview Mapping

Amazon has 16 Leadership Principles. You will be asked about most of them across your loop. Prepare specific STAR+R stories for each:

| LP | Common Question Pattern |
|----|------------------------|
| Customer Obsession | "Tell me about a time you went beyond what was asked to serve a customer." |
| Ownership | "Tell me about a time you took on something outside your job scope." |
| Invent and Simplify | "Describe a time you simplified a complex process or system." |
| Are Right, A Lot | "Tell me about a time you made a decision with incomplete data." |
| Learn and Be Curious | "Tell me about something you taught yourself recently. How did you apply it?" |
| Hire and Develop the Best | "Tell me about someone you mentored and what you did to help them grow." |
| Insist on the Highest Standards | "Tell me about a time you raised the bar on quality when others thought it was good enough." |
| Think Big | "Describe a time you proposed a bold idea. How did you get buy-in?" |
| Bias for Action | "Tell me about a time you made a decision quickly with limited information." |
| Frugality | "Tell me about a time you achieved more with fewer resources." |
| Earn Trust | "Tell me about a time you had to rebuild trust after a mistake." |
| Dive Deep | "Tell me about a time you used data to investigate an unexpected problem." |
| Have Backbone; Disagree and Commit | "Tell me about a time you disagreed with your manager. What happened?" |
| Deliver Results | "Tell me about the most impactful project you've owned end-to-end." |
| Strive to be Earth's Best Employer | "How have you contributed to an inclusive or psychologically safe environment?" |
| Success and Scale Bring Broad Responsibility | "How do you think about the broader societal impact of your work?" |

---

## Typical Technical Questions

### ML / Applied AI

- "Design a product recommendation engine for Amazon.com at scale."
- "How would you build and evaluate a question-answering system using a foundation model?"
- "Walk me through how you'd detect fraudulent seller activity using ML."
- "How do you handle class imbalance in a high-stakes classification problem?"
- "What's your approach to offline vs. online evaluation of a ranking model?"

### System Design

- "Design Amazon's order management and fulfillment pipeline."
- "Design a distributed rate limiter for the AWS API Gateway."
- "Design a real-time inventory management system for a warehouse network."
- "Design S3: object storage with high durability and eventual consistency."

---

## Coding Tasks

Expect **LeetCode medium** difficulty. Two problems per coding round in 60 minutes:

- Array and hash map manipulation
- String processing and parsing
- Linked list operations
- Tree and graph traversal
- Sliding window / two pointers
- Sorting and binary search variants

**Python, Java, or C++** are most common. Amazon interviewers pay close attention to edge cases — handle null inputs, empty arrays, and boundary conditions explicitly. Think out loud and narrate your approach before writing code.

---

## Cultural & Technical Signals

| Signal | What they're looking for |
|--------|--------------------------|
| **LP story depth** | Shallow stories ("I once helped a customer") fail. Deep stories with context, conflict, specific actions, and measurable outcomes succeed. |
| **Customer-backward thinking** | Start every design answer from the customer problem, not the tech stack. What does the user need? Then work backward to the architecture. |
| **Bar raiser awareness** | The bar raiser is not your friend or your enemy — they're enforcing the company bar. Focus on being clear, specific, and evidence-based. |
| **Data fluency** | Amazon is extremely metrics-driven. Quantify outcomes in every behavioral story. "We improved latency" is weak. "p99 dropped from 2.1s to 400ms, reducing cart abandonment by 8%" is strong. |
| **Frugality signals** | Show you think about cost and efficiency. Unlimited budget solutions score lower than constrained, practical ones. |
| **Delivery mentality** | Amazon values shipping. Show you can define scope, cut what doesn't matter, and deliver on time — not just plan perfectly. |

---

## Pro Tips

1. **Prepare 10+ STAR+R stories, mapped to specific LPs.** Each story should be flexible enough to answer 3–4 different LP questions. Before the loop, map your stories to the LP grid and identify gaps.
2. **Use the STAR format strictly — and add the R (Result).** Amazon interviewers are trained to probe for the Result if you omit it. Don't make them drag it out of you.
3. **The bar raiser can override the team.** If the bar raiser thinks you're below bar, you won't get an offer even if every team interviewer said yes. Treat this round with the same weight as the others.
4. **Ask about the team's tenets.** Many Amazon teams have explicit written tenets that guide decisions. Asking to see them shows LP alignment (Dive Deep, Insist on Highest Standards).
5. **Total comp at Amazon is front-loaded.** Year 1 and Year 2 often include signing bonuses to compensate for back-loaded RSU vesting (years 3 and 4 vest faster). Model out 4-year total comp before comparing offers.
6. **Level calibration affects your scope.** SDE II vs. SDE III (L6) is a significant jump in autonomy and impact expected. Make your stories reflect the level you're targeting.

---

*Sources: public Glassdoor reviews, Blind threads, Amazon engineering blog, open candidate write-ups. Verify current process with your recruiter.*
