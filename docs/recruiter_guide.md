# Recruiter guide

Signed: Muthu.R | Wild Recruiters (Elysaian)
Contact: https://www.linkedin.com/in/muthumakesh

## Steps for each search
1. Copy `intake/intake_template.md` to `intake/searches/YYYY-MM-DD_role.md`
   and fill it in. Do not commit this file.
2. Open `prompts/sourcing_agent_v3.md` and copy the text between
   `PROMPT START` and `PROMPT END`.
3. Paste the prompt into Gemini (or your approved tool), then paste your
   filled INTAKE below it.
4. Paste the ALREADY REVIEWED list from earlier searches.
5. Read the ranked output. Check the URLs yourself before relying on them.
6. Never contact a candidate based on the output alone. A human check is
   always required.
7. Label each candidate using `labelling/label_template.md`.
8. Once a week, review the labels. If the same error appears twice,
   propose a rule change through a pull request.

## Things to remember
- Output is a lead, not a screening decision.
- Do not paste candidate personal details into Git.
- If a field says "Not found in permitted sources", that is not a rejection.
