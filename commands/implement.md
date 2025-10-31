---
model: claude-haiku-4-5
description: Faithfully implement the architecture plan with clean, well-tested code
argument-hint: [implentation-plan-file]
---

- Read the implementation plan from $1
- Follow the plan exactly as written - do not deviate unless absolutely necessary
- If you discover a logical error or issue in the plan that requires deviation:
    - Stop and explain the problem to the user clearly
    - Wait for the user's approval before proceeding
    - Only then make the necessary changes
- Write code comments only for complex business logic. Skip comments for straightforward, self-explanatory code
- Implement tests before business logic as specified in the plan
- Ensure your code matches the specifications in the plan document
