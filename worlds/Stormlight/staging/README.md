
# Claude Code Philosophy

Claude Code is NOT being used like ChatGPT.

Claude becomes a worker operating on a repository.

Claude should:

- read files
- write files
- update files
- call Python scripts
- follow prompts
- iterate through folders

The orchestration happens outside Claude.

---

# Why Not Feed Entire Books?

Never ask:

"Summarize this book."

Instead ask hundreds of very small questions.

Goal:

High recall.

Low hallucination.

Easy verification.

---

# Multi-Pass Extraction Philosophy

Every pass has ONE responsibility.

Never combine responsibilities.

This improves both completeness and consistency.

Each pass reads ONE chapter.

Produces ONE type of output.

Stores output.

Moves on.

---
