━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
README.en.md (English)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

OneCopyThinker (English)

A one-copy multi-role prompt for ChatGPT, Claude, etc.
By pasting "prompts/multi-role-en.md" into the System message,
the AI will respond in four roles (L/C/H/I) across phases (0 to 3).

Directory Structure

OneCopyThinker/
README.md // Japanese documentation
README.en.md // This English documentation
LICENSE
prompts/
multi-role-ja.md // Japanese prompt
multi-role-en.md // English prompt (System text)

Usage (English prompt)

Open prompts/multi-role-en.md

Copy all content and paste it into your LLM's System message

Ask a question: the AI proceeds with (L)(C)(H)(I) in phases (0–3)

Insert optional lines like (A) Fact Check or S(doctor): ... if needed

The final answer is aimed to fit 1–2 screenfuls

Sample Output
Phase 1:
L: Data/facts...
C: Creative angle...
H: Ethical/emotional aspect...
I: Summarize key points

License
This project is under the MIT License (see LICENSE).

Japanese Version
For Japanese instructions, see README.md
(Japanese prompt at prompts/multi-role-ja.md)
