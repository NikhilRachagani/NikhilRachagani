# Amazon SDE Interview Prep

## Context: The Invite
- Role: Software Dev Engineer – 3108313
- Virtual interview stage: 4 interviews, 60 min each, scheduled over one or multiple days
- Recruiter asked for 5–6 available dates starting Sept 21, 5–6 hours/day availability
- Option to do all 4 interviews over 2 consecutive days instead of spread out
- Note: verify the recruiter's email is legitimately @amazon.com and any scheduling link goes to Amazon's real tool before sharing personal details.

## Typical Amazon SDE Virtual Loop Structure
- 4 rounds, 60 min each, each interviewer works independently and submits feedback; a hiring committee/bar raiser reviews before a decision
- Usually 2–3 rounds coding/DSA, 1 round system design or OOD (more common at SDE II+, sometimes lighter version at SDE I)
- Leadership Principles (behavioral) are woven into EVERY round, not just one dedicated round
- 5–10 min breaks between rounds typically; ask what coding tool/platform they'll use (e.g., shared doc, Amazon Chime, code executor)
- Doing 4 hours across 2 days (vs. one long day) helps avoid interview fatigue

## What Real Candidates Reported (2026 loops)

### Coding rounds
- One DSA problem per round, medium–hard
- Common topics: sliding window, two pointers, BFS/DFS, LCA, binary search on rotated/sorted arrays, LRU Cache
- Some SDE-1 candidates reported LeetCode-hard problems, especially graph/DP
- Example real questions: "Search in a Sorted and Rotated Array" (LC 33), "Lowest Common Ancestor of a Binary Tree" (LC 236), "design a system to schedule processes"
- Format: main interviewer + shadow interviewer → self-intros → problem shared via doc → explain brute force → code it → dry run with test case → discuss optimization → behavioral questions → your questions at the end

### System design / OOD
- More common SDE II+, but lighter versions can appear at SDE I
- Real example (senior loop): design an A/B experimentation platform (experiment setup service, traffic-splitting assignment service, metrics streaming service, manual overrides)

### Behavioral
- Can be a full dedicated round (one candidate got 5 Leadership Principle questions, zero technical content)
- Also woven into technical rounds via follow-ups
- Interviewers ask deep follow-ups that can knock you off a clean STAR structure — practice recovering
- Example real questions: "Have you taken initiative in a project and made it work?" / "Have you ever tried to convince someone to follow your approach?"

## Sources
- https://interviewkickstart.com/interview-questions/companies/amazon/sde
- https://www.tryexponent.com/guides/amazon-software-development-engineer-interview
- https://dev.to/net_programhelp_e160eef28/amazon-2026-sde-intern-vo-interview-experience-two-technical-rounds-breakdown-11da
- https://medium.com/@sreejaguduguntla/amazon-sde-i-intern-6-months-2026-interview-experience-off-campus-fa9098f5b737
- https://leetcode.com/discuss/post/8014509/
- https://www.coprep.ai/blog/amazon-sde-interview-questions-and-answers-in-2026-round-by-round-guide

---

## 2-Day Prep Plan

### Day 1 — Coding (6–7 hrs)

**Morning — Pattern review (not random grinding):**
- Arrays/Strings: sliding window, two pointers
- Trees/Graphs: BFS/DFS, LCA, level order
- Binary search on rotated/sorted arrays
- Do 2–3 problems per pattern, timed 25–30 min each

**Priority problems:**
- LC 33 — Search in Rotated Sorted Array
- LC 236 — Lowest Common Ancestor of a Binary Tree
- LC 200 — Number of Islands
- LC 146 — LRU Cache (very common at Amazon)
- LC 973 — K Closest Points to Origin

**Afternoon:** Practice narrating out loud while coding — brute force first, explain trade-offs, then optimize. This is what's actually graded, not just correctness.

**Evening:** 1 mock interview (friend or record yourself) on a fresh problem.

### Day 2 — Behavioral + Design (5–6 hrs)

**Morning — Leadership Principles:**
- Pick 6–8 stories that flex across multiple principles (ownership, dive deep, deliver results, disagree and commit, bias for action)
- Write each in STAR format: 4–5 sentences, clear metric/outcome

**Midday:** Rehearse 2–3 stories out loud until under 2 min without notes. Practice recovering from interruptions/follow-ups without losing structure.

**Afternoon — Light system/OOD design:**
- Even for SDE I, know how to design something simple (parking lot, elevator system, rate limiter) at a high level: requirements → components → data flow → one trade-off discussion

**Evening:** Full mock loop — 1 coding problem + 2 behavioral questions, timed like a real round.

---

## Next Steps
- Draft STAR stories: share 2–3 real work situations (a conflict, a deadline crunch, something you drove end-to-end) and map them to Leadership Principles
- Request a mock coding interview walkthrough for a specific problem
- Request a mock system design walkthrough (e.g., parking lot, rate limiter)
