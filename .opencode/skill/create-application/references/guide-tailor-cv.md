# Guide: Tailor CV

<rules>

- **Format:** Clean Markdown. No separators (`---`).
- **Length:** Max 2 pages (ideally 1.5).
- **Tone:** "Short. Punchy. Action." The agent MUST NOT use "I didn't just X, I did Y".
- **Source:** All facts MUST be verified against `CANDIDATE-PROFILE.md`.

</rules>

<workflow>

## Step 1: Strategy

1. Read job description from the user request.
2. Select Strategy (Mode A, B, or C) based on role type.

## Step 2: Assembly

1. Load `references/master-pattern.md`.
2. Fill blocks using data from `CANDIDATE-PROFILE.md`.
3. **Crucial:** Adapt bullet points to match keywords from the offer (e.g., "Content Strategy" vs "Copywriting"), but MUST NOT invent facts.

## Step 3: Verification

1. Check against "No AI Slop" rules.
2. Ensure dates/companies match the Profile exactly.
3. Remove any Markdown artifacts like tables or complex formatting.

## Step 4: Output

Save as `CV-tailored.md` in the application directory.

</workflow>
