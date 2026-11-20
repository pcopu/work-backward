---
name: work-backward
description: Interview the user one question at a time to turn an intended outcome into observable success criteria, then work backward through the prerequisites to an actionable plan. Use when the user asks to work backward from a goal, make a goal verifiable, define what done looks like, or use Grill Me-style questioning focused on a desired result. Apply to coding, product, design, research, business, and personal projects. Do not start an interview for a simple factual question or a fully specified routine task.
---

# Work Backward

Start with the result the user wants to see. Make success observable, then reason backward until the next useful action is clear. Be curious, direct, and willing to challenge a weak answer while keeping the user in charge of the destination.

## Run the conversation

- Ask **one substantive question per turn**. Choose the most consequential unresolved question whose prerequisites are settled. Wait for the answer; do not bury several decisions inside one question or present the entire question bank.
- Offer a short recommended answer or framing and explain why it fits the available context. Label it as a proposal. Never present a recommendation as the user's decision. When the destination is unknown, recommend a way to define it instead of inventing a goal.
- Read supplied material, prior answers, project files, and relevant evidence before asking for facts you can establish yourself. Ask the user for preferences, tradeoffs, or information only they can supply.
- After each answer, incorporate it, resolve contradictions, and choose the next question from the updated understanding. Preserve earlier decisions unless the user changes them. Summarize briefly at meaningful transitions, not after every answer.
- Challenge words such as "best," "fast," "polished," "successful," and "finished" by asking what the user would observe. Keep questions concrete and tied to the outcome; explain consequential tradeoffs without turning the session into a lecture.
- If the user delegates a choice or asks you to proceed, use stated assumptions and keep moving. Do not ask them to reconfirm decisions already made. Scale the interview to the actual uncertainty.

## 1. Establish the destination

Extract the outcome, intended beneficiary, and relevant context already supplied. Distinguish the desired change from a suggested implementation. Treat explicit implementation constraints as constraints.

Express the destination in a short sentence: **[Who] can [do or experience what] in [relevant conditions], evidenced by [observable result].** Leave unknown parts open instead of fabricating precision.

If the outcome is missing, start with the future scene: what could the user show or demonstrate when this is finished? If several goals compete, resolve the priority before choosing a solution. Add a deadline only when it matters or the user supplied one.

## 2. Decide what would prove success

For each essential condition, establish:

| Condition | Basis | Evidence and check |
| --- | --- | --- |
| Observable behavior or result | User requirement, supplied reference, established constraint, or labeled proposal | What will be inspected or measured, under which conditions, and what would pass or fail |

Use the smallest set that captures the real outcome. Separate required conditions from preferences. Include a meaningful failure case when it helps distinguish genuine success from a superficial pass.

Use numerical targets only when supplied, grounded in an applicable standard, or explicitly proposed with a rationale. A proposed target remains provisional until accepted or covered by the user's delegation. Do not invent visual-match percentages, satisfaction scores, latency limits, or requirements and attribute them to the user.

Match the evidence to the work:

- **Software:** Demonstrate the actual workflow with representative data; verify relevant error cases and preserved behavior. A build alone does not establish usability or speed.
- **Visual or creative work:** Identify the particular qualities of a reference that matter. Compare the actual rendered output under comparable conditions. Keep human preference visible as a review step.
- **Research or decisions:** Define the question the result must answer, evidence quality, coverage, and material uncertainties. Support consequential factual claims with sources.
- **Business or personal outcomes:** Separate controllable deliverables from results dependent on customers, markets, other people, or time. Define how and when those later outcomes will be measured; do not promise them because a plan is complete.

Check that the evidence could expose a bad result. Replace weak proxies when they can pass while the user's real need remains unmet. Freeze settled criteria as the working baseline; show any subsequent change and its reason rather than lowering the bar silently.

## 3. Work backward through prerequisites

Starting at the final proof, ask: **What must already be true immediately before this result is possible?** For each answer:

1. Identify the prerequisite and why it enables the downstream result.
2. Specify the evidence that would show this prerequisite is satisfied.
3. Identify what must precede it, distinguishing a necessary condition from one possible implementation.
4. Continue until the branch reaches something already established or an action that can begin now.

Follow dependencies in this reverse direction. Resolve a consequential upstream decision before asking questions that assume its answer. Prioritize the branch with the largest uncertainty or risk to the goal. Ground the end of each branch in the actual current state by inspecting available evidence.

Do not substitute a generic forward task list for this reasoning. Do not turn optional improvements into prerequisites. Defer implementation details that cannot change the outcome, feasibility, verification, or next useful step.

## 4. Turn unknowns into evidence

If the user does not yet know what they want, offer a small concrete example, a focused pair of alternatives, or a reversible draft they can react to. Ask which specific quality should change. Record both positive preferences and rejected qualities without assuming that every attribute of a reference should be copied.

If a question needs observation rather than another opinion, do or identify the smallest useful inspection, comparison, prototype, or experiment. Research discoverable facts yourself. Keep work inside the requested scope and available permissions.

When feedback invalidates the direction, revise the outcome or criteria explicitly and revisit the affected dependencies. Restart only the affected work when that is clearer than accumulating patches. Do not repeatedly rephrase an unanswerable question.

## 5. Produce a usable brief and stop the interview

Finish when the desired result, essential evidence, constraints, and dependency path are clear enough for the next action. Do not keep asking merely to cover every conceivable detail. If the user stops early, summarize the useful decisions and label remaining assumptions.

Provide a compact brief containing:

1. **Goal:** The intended result in plain language.
2. **Success evidence:** The essential conditions, their basis, and how each will be checked. Future checks are planned, not already passed.
3. **Backward map:** The result and its prerequisites in reverse order; show branches only where dependencies matter.
4. **Forward plan:** The smallest practical sequence to reach the result, with an observable completion check for each step.
5. **Open issues:** Material assumptions, external dependencies, and any decision or experiment still required.
6. **First action:** A concrete step that can start now.

Keep the brief in the conversation unless the user requested a saved artifact or an existing project record is the natural place for it. Use the environment's normal saving rules for any files you create.

If the request is only to think through the goal, deliver the brief. If execution is already requested, carry the plan forward within that authorization without adding a confirmation gate. While executing, compare observed results with the criteria, repair material gaps, and stop when the required checks pass or a concrete blocker prevents progress. Report what was actually verified, what failed, and what remains unverified or subject to human judgment. Never claim execution or measurement that did not happen.

## Question selection reference

Read [references/question-patterns.md](references/question-patterns.md) only when choosing a difficult next question or adapting the flow to a domain. Use its examples as patterns, never as a questionnaire to dump on the user.
