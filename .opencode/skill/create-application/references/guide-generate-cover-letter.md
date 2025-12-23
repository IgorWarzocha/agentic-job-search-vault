# Guide: Generate Cover Letter

<rules>

**Zero "AI Slop" Policy:**
- **BANNED:** "I didn't just X, I did Y", "testament to", "bridge the gap", "thrilled to apply", "perfect match".
- **BANNED:** Semicolons (;), em-dashes (—).
- **REQUIRED:** "Short. Punchy. Action." rhythm. Human voice.

</rules>

<workflow>

## Step 1: Template Selection

1. Analyze the job offer from the user request.
2. Select template from `references/templates.md`:
   - **Template A:** Tech / Senior / Direct.
   - **Template B:** NGO / Culture / Mission.
   - **Template C:** Process / Implementation.

## Step 2: Content Generation

1. Load `CANDIDATE-PROFILE.md`.
2. Fill placeholders `[...]` with specific facts from the Profile.
3. **Tailoring:** The "Why Company" and "Why Role" sections MUST specifically address the job offer.

## Step 3: Style Review

1. Check against Banned phrases list.
2. Verify rhythm (Short sentences).
3. Ensure signature matches: `[Candidate Name] + LinkedIn`.

## Step 4: Output

Save as `Cover-letter.md` in the application directory.

</workflow>
