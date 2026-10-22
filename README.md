# DIY-Sourcing-Agent--Github
Build your own Github Sourcing Agent
# Talent Sourcing Agent -- Github only (v3)

A GitHub-only AI sourcing prompt for finding and verifying technical talent
from public GitHub profiles, repositories and GitHub Pages sites.

**By Muthu.R, Wild Recruiters (Elysaian)**
LinkedIn: https://www.linkedin.com/in/muthumakesh

## What it does
- Searches only github.com and *.github.io (no LinkedIn, no other sites)
- Checks that a résumé or repo really belongs to the candidate before using it
- Tags every claim as STATED, DEMONSTRATED, CORROBORATED or INFERRED
- Scores candidates on a 100-point rubric, reported as Confirmed and Ceiling
- Reports gaps honestly instead of padding the list

## What it does not do
- It does not contact anyone or draft outreach messages
- It does not judge personality or culture fit
- It does not use personal data beyond what candidates published
- Its output is a lead for human review, not a screening decision

## Repository layout
| Folder | Purpose |
|---|---|
| `prompts/` | The current prompt and its archive |
| `intake/` | Blank intake template (fill in per search, never commit candidate data) |
| `learned_rules/` | Rules added from recurring errors |
| `evaluation/` | Golden set of judged profiles and regression results |
| `labelling/` | Labels used to grade each run |
| `docs/` | Recruiter guide |

## Quick start
1. Open `prompts/sourcing_agent_v3.md`.
2. Copy only the text between `<!-- PROMPT START -->` and `<!-- PROMPT END -->`.
3. Paste it into Gemini (or your approved tool).
4. Fill in the INTAKE block from `intake/intake_template.md`.
5. Paste the ALREADY REVIEWED list and review the ranked output.

See `docs/recruiter_guide.md` for the full workflow.

## Use and licence
Licensed under the MIT License (see `LICENSE`). You may use, copy and adapt
this work, provided the copyright notice is kept.

Candidate data, client names and your own exclusion lists are not covered by
this licence and must not be committed to a public copy. Check your local
data-protection rules before using any output.

## Contact
Muthu.R | Wild Recruiters | Elysaian
LinkedIn: https://www.linkedin.com/in/muthumakesh
