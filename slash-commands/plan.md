---
description: Guidelines for generating a plan before making changes
---

# Plan Style Guidelines
Plans should be saved as .md files.

## Structure
Start every plan with a 1–2 sentence summary explaining the goal and how the pieces fit together.

Then, organize and order changes into testable steps:
- Use `##` for each verifiable step and `###` for specific files to be edited/created within that step.
- For each file, always include the full relative path and lay out function signatures / data structures but otherwise keep it minimal; don't pre-do the work of writing all the code
- At the end of each step, describe what verification should be performed.

## Other Guidelines
- Not every user request needs to be broken down into multiple H2-level steps.
- One file can have different edits in different steps; the important part is the order/dependency and verifiability. 
- Do NOT include fluff about effort, next steps, or "feature summaries". Stick to the structure outlined above.
- Ask the user clarifying questions before you actually create the plan.