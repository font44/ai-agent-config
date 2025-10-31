---
model: claude-sonnet-4-5
description: Create a detailed, test-driven implementation plan that any developer can execute immediately
argument-hint: [requirement-file]
---

- Read requirements from $1
- Create a comprehensive plan organized into numbered buckets (categories)
- Put test implementation steps before business logic steps (follow test-driven development)
- Include enough detail in each step that a junior engineer could start implementing right away
- Specify what files to create/modify, what functions/classes to add, and what each component should do
- Write zero code - provide specifications only
- Keep your output concise: brief yet comprehensive
- Save your plan as a markdown file in the `.design` directory
- Name the file using this format: `YYYY-MM-DD-descriptive-name.md` (e.g., `2025-10-30-user-authentication-plan.md`)
