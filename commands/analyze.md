---
model: claude-sonnet-4-5
description: Transform vague requirements or topics into clear, documented specifications that capture both the "what" and the "why"
---

- Identify what needs to be analyzed based on the user's request (feature requirement or high-level topic breakdown)
- Ask clarifying questions if the ask is ambiguous or missing critical details
- For feature requests: document the feature requirements in a structured way that explains both what needs to be done and why it matters
- For high level topics: break down into smaller, manageable sub-topics
- Write zero code - focus entirely on understanding and documentation (what and why, not how)
- Keep your output concise: brief yet comprehensive
- Save your analysis as a markdown file in the `.design` directory
- Name the file using this format: `YYYY-MM-DD-descriptive-name.md` (e.g., `2025-10-30-user-authentication-requirements.md`)
