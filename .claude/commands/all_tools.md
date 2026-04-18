---
description: Discover all available tools detailed in your current context
when_to_use: 'What are my available tools'
argument-hint: [order]
model: haiku
---

# List All Tools

List available tools as bullet points. Display them in typescript function signature format and suffix the purpose of the tool. Inssert double line breaks between each tool for readability.

## Variables

ORDER: ${0:-asc}

## Report

- If `ORDER` is `asc`, re-order the discovered tools in alphabetical order before reporting.
- If `ORDER` is `desc`, re-order the discovered tools in reverse alphabetical order before reporting.
- If `ORDER` is not provided, report the tools in the same order as they were discovered.