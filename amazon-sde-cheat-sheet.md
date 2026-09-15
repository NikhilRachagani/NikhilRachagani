# Amazon SDE Interview Cheat Sheet

## Format
- 4 rounds × 60 min each (virtual), possibly spread across 1–2 days
- Each interviewer scores independently → reviewed by a hiring committee/bar raiser
- Typical mix: 2–3 coding/DSA rounds + 1 system design/OOD round (lighter at SDE I)
- Leadership Principles questions are woven into **every** round, not just a dedicated one

## Coding round structure (every technical round follows this shape)
1. Self-intros
2. Problem shared via shared doc/code editor
3. You restate the problem, ask clarifying questions
4. Explain brute-force approach out loud *before* coding
5. Code it
6. Dry-run with a test case
7. Discuss/implement optimization (they almost always push for better than brute force)
8. 1–2 behavioral questions
9. Your questions for them

## Core topics to know cold
| Topic | Why it matters |
|---|---|
| Big-O | Every solution gets judged on this |
| Arrays/Strings — two pointers, sliding window | Most common problem family |
| Hash maps | The #1 trick for turning O(n²) → O(n) |
| Recursion | Foundation for trees, backtracking, DP |
| Trees — BFS/DFS, LCA | Very common; LC 236 (LCA) reported repeatedly |
| Binary search (incl. rotated arrays) | LC 33 reported repeatedly |
| Linked Lists + LRU Cache | LC 146, frequently asked at Amazon specifically |
| Graphs — BFS/DFS | LC 200 (Number of Islands) is a classic |

## Leadership Principles (behavioral) — know these, have a story for each
Customer Obsession, Ownership, Invent and Simplify, Are Right A Lot, Learn and Be Curious, Hire and Develop the Best, Insist on the Highest Standards, Think Big, Bias for Action, Frugality, Earn Trust, Dive Deep, Have Backbone; Disagree and Commit, Deliver Results.

- Use **STAR**: Situation, Task, Action, Result — keep each story under 2 minutes
- Have 6–8 stories that each map to 2–3 principles (interviewers ask follow-ups that pull you off-script — be ready to go deeper on any part)
- Have a metric/outcome in every story, even a rough one

## System design / OOD (lighter at SDE I)
- Structure: requirements → components → data flow → trade-off discussion
- Practice one simple design end to end: parking lot, rate limiter, elevator system, LRU cache system

## Logistics to confirm with recruiter
- What coding platform/tool will be used (shared doc vs. code executor vs. whiteboard tool)
- Whether interviews run back-to-back or with breaks
- Confirm interviewer identities/emails are legitimately @amazon.com

## What to bring to every single round
1. Clarify the problem before coding — never start typing immediately
2. Think out loud — silence is scored against you
3. State time/space complexity of your solution unprompted
4. Test your code with an example after writing it
5. Have questions ready to ask them at the end
