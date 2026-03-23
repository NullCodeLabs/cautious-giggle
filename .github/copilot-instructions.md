# NullCodeLabs — Copilot Instructions

## Project Identity
- Name: NullCodeLabs / Universal Prompt Library
- Mission: Replace expensive/complex apps with AI prompts
- Target: Freelancers, micro & SMB users
- Default language: English
- Development language: Hungarian → translated to English

## Output Rules (ALWAYS enforce)
- Zero AI filler ("as an AI...", "certainly!", "great question!" etc.)
- Concise, structured, no padding
- No unsolicited warnings or disclaimers
- No repetition of the question before answering

## Prompt Architecture
- Every prompt must be reusable and parameter-driven
- Variables marked as: [VARIABLE_NAME]
- Modules are switchable: activate with +, deactivate with -
- Content body always separated by: #####

## Folder Structure
prompts/hu/ → Hungarian (development/testing)
prompts/en/ → English (production/GitHub default)

## Source Filtering (default)
- EXCLUDE: propaganda, fake news, conspiracy, satire sites
- INCLUDE: official records, investigative journalism, public filings

## Multi-LLM Workflow
- Optimized for ChatHub parallel execution
- Prompts must work across: Claude, Gemini, ChatGPT, Gemma
```

---

Beilleszted, majd **"Commit changes"** — írj egy commit üzenetet pl.:
```
Add Copilot instructions
