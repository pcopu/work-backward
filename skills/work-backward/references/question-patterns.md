# Question patterns

Choose one question that resolves the current bottleneck. Skip anything the user or available evidence already answers. Tailor a brief recommendation to the actual context.

## From aspiration to observable outcome

| Current answer | Useful next question | Recommended framing |
| --- | --- | --- |
| "I want this to be great." | What would someone be able to do with the finished result that they cannot do now? | Center the primary person and a concrete change. |
| "Make it fast." | Which interaction needs to feel immediate? | Identify the workflow before discussing architecture or a timing target. |
| "Make it look like this." | Which quality of this reference matters most to you? | Name observable candidates such as hierarchy, spacing, imagery, or tone without choosing the user's taste. |
| "I want more revenue." | What revenue result would make this effort worthwhile? | Establish the user's target and relevant period before working backward through the business assumptions. |
| "I don't know; I will know when I see it." | Which of these two small examples is closer to what you want? | Supply concrete examples when feasible; vary a meaningful dimension and use the reaction to sharpen the brief. |

Do not ask all three destination, measurement, and deadline questions at once. Keep unsettled targets visibly provisional.

## From result to proof

- "What could we inspect that would settle whether this worked?"
- "Could this check pass while the main problem still exists?"
- "Which requirement would make you reject an otherwise good result?"
- "Which part requires your judgment rather than a measurement?"

Prefer an actual demonstration over confidence or a self-assigned score. If a user requests an impossible guarantee, explain the limit and define a measurable deliverable plus an honest later outcome check.

## From proof to prerequisites

- "Immediately before we can demonstrate that, what must already be working?"
- "Which of these conditions is necessary, and which is just our current approach?"
- "What evidence do we have that this dependency is already satisfied?"
- "Which unresolved assumption could make the whole route fail?"
- "What is the smallest experiment that would settle that assumption?"

For each proposed dependency, connect it to the result it enables. Avoid inventing elaborate supporting systems without showing why they are needed.

## Worked patterns

### Software performance

Starting goal: "Opening an item should be instant even with a large history."

First resolve the user-visible endpoint: an immediate shell, readable details, or fully interactive details are different outcomes. Inspect the implementation and available measurements yourself. Agree on representative data and operating conditions before proposing a timing target.

Work backward from a measured usable detail screen to correct detail data, an appropriate data access path, and a reproducible baseline. Treat caching or precomputation as candidate approaches whose need depends on the observed bottleneck. Validate output correctness as well as speed. If the target device is unavailable, report that limitation and keep the device criterion unverified.

### Visual deliverable

Starting goal: "Build a page that matches this reference."

Resolve the reference qualities the user cares about. Define comparison conditions and the core user flow. Work backward from a rendered, usable page to the required layout and assets, then to the information or small exploratory draft needed now. A style comparison does not replace checking the interaction; an interaction check does not establish aesthetic acceptance.

### Research for a decision

Starting goal: "Help me choose between these options."

Resolve what decision the evidence must support and the constraint most likely to change the choice. Work backward from a defensible recommendation to comparison criteria, the evidence needed for each, and the specific sources or unknowns to investigate. Preserve unresolved uncertainty when evidence is missing or conflicts.

### Business outcome

Starting goal: "Get retailers to reorder our product."

Separate the later outcome of repeat orders from controllable work. Establish which retailers, what counts as a reorder, and the relevant period only as needed, one decision at a time. Work backward from repeat ordering to viable retailer economics and customer demand, then to the evidence and activities needed to test those assumptions. Label conversion or sales assumptions; do not manufacture a numerical funnel or equate a presentation with purchase intent.
