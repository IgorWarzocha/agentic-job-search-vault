# Repository Setup Standard Operating Procedure (SOP)

**Purpose:** This document guides AI agents and users through the initial configuration of the Job Search Repository.

## For the Agent

When a user initializes this repository, you MUST follow this procedure to populate the `CANDIDATE-PROFILE.md` file and configure the agents.

### Phase 1: Scan and Identify

1.  Read `CANDIDATE-PROFILE.md`.
2.  **Identify Placeholders:** Scan for all text enclosed in brackets `[...]`.
    *   *Examples:* `[Your Name]`, `[Job Title]`, `[Skill 1]`.
3.  Create a mental checklist of the missing data points.

### Phase 2: Interactive Interview (Profile)

1.  Greet the user and explain that you need to fill in the `CANDIDATE-PROFILE.md` to power the system.
2.  **Iterate through the sections.** Group related questions (e.g., "Let's start with your Contact Info", then "Tell me about your Current Role").
3.  **Prompting Strategy:**
    *   Use the placeholder text itself as the prompt.
    *   For lists (e.g., `[Skill 1]`), ask for a comma-separated list.
    *   For `[Narrative sections]`, offer to draft the text based on bullet points the user provides.

### Phase 3: Population (Profile)

1.  **Replace** the bracketed placeholder `[...]` with the user's provided content.
2.  **Save** the file after each major section is completed.

### Phase 4: Agent Configuration

After the profile is complete, you MUST configure the active agents.

1.  **Job Application Automator** (`.opencode/agent/job-application-automator.md`):
    *   Locate the `<user_preferences>` block.
    *   **Ask:** "Do you have specific style preferences or pet peeves for your documents? (e.g., 'Never use the word synergy', 'Prefer bullet points over paragraphs')."
    *   Replace `[Preference X]` placeholders with user's specific rules.

2.  **Research Specialist** (`.opencode/agent/researcher.md`):
    *   Locate the `<user_context>` block.
    *   **Ask:** "What are your specific job search parameters? (e.g., 'Remote only', 'Fintech industry', 'Salary > $X')."
    *   Replace `[Context X]` placeholders with user's criteria.

### Phase 5: Verification

1.  Ask the user to review the generated `CANDIDATE-PROFILE.md`.
2.  Run a test: Ask the `job-application-automator` to "Check if the profile is ready".

---

## Key Files to Check

*   `CANDIDATE-PROFILE.md`: The primary source of truth.
*   `.opencode/agent/*.md`: Agent definitions requiring configuration.
*   `AGENTS.md`: Ensures you follow the "No AI Slop" style rules during the interview.
