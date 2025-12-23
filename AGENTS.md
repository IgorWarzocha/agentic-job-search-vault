# SYSTEM_INSTRUCTIONS.md

Job Search Repository - AI-Assisted Application Framework

<purpose>
This repository serves as a structured framework for an AI-assisted job search. It is both a set of instructions for LLM agents and an organized archive of research and application materials.
</purpose>

<style_rules>
## Core Style Rules

**Assistant Communication:**
- Maintain a professional, direct, and concise tone.
- Avoid conversational filler.

**Punctuation:**
- Use only periods, commas, question marks, and exclamation marks.
- DO NOT use hyphens (-), em-dashes (—), semicolons (;), or ellipses (...) unless quoting.

**Content Language:**
- All application materials MUST be written in British English.
- System documentation (rules, guides) should remain consistent with the repository's primary language.

**File Management:**
- Save generated content to the appropriate directory:
  - CVs & Cover Letters → `02-Applications/YYYY-MM/Company-Name/`
  - Core Materials → `01-Core-Materials/`
  - Company Research → `03-Job-Market-Research/Company-Research/`
  - Active Leads → `03-Job-Market-Research/Active-Leads/`
  - Interview Prep → `05-Interview-Prep/Company-Specific/`
- **Strict Filename Convention:**
  - Standard Documents: `YYYY-MM-DD - [Name] - [Type].md`
  - Tailored CVs: `[Name]-CV.md` (within company folder)
  - Cover Letters: `[Name]-CL.md` (within company folder)
- Example: `2026-01-02 - Igor Warzocha - CV.md`
- **NEVER** use generic names like "tailored-cv.md" or "cover-letter.md". Always prepend the candidate's name.
</style_rules>

## Content Standards (STRICT RULES)

<no_ai_slop>
ABSOLUTE PROHIBITION of AI-sounding phrases.
- **BANNED:**
  - "I didn't just X, I did Y"
  - Semicolons (;), em-dashes (—).
  - "Bridge the gap", "Unlock potential", "Landscape", "Testament to".
  - "It is a perfect match", "I am thrilled to apply".
- **REQUIRED:**
  - Short sentences. "Short. Punchy. Action." rhythm.
  - Human voice: "You need X. I do X. Here is proof."
  - Directness: "I built an agent that reads news." (instead of "I architected a solution...")
- **FORMAT:** CV max 2 pages. Rich Conciseness. No `---` separators.
</no_ai_slop>

<narrative_lock>
Facts must align with the user's provided history in `Candidate-Profile.md`.
</narrative_lock>

## Repository Structure

<repository_structure>
```
01-Core-Materials/          # Input: Source materials
├── CVs/                    # Master CV patterns
├── Cover-Letters/          # Style guides and templates
└── Portfolio/              # Work samples and projects

02-Applications/            # Output: Active job applications
├── YYYY-MM/                # Monthly organization
│   ├── Company-Name/       # Per-company package
│   │   ├── [Name]-CV.md
│   │   ├── [Name]-CL.md
│   │   ├── Application-tracker.md
│   │   └── Research-notes.md
└── Archive/                # Past applications

03-Job-Market-Research/      # Process: Market intelligence
├── Active-Leads/           # Open opportunities
├── Company-Research/       # Detailed company dossiers
├── Sector-Analysis/        # Industry trends
└── Salary-Market-Data/     # Compensation benchmarks

04-Interview-Prep/          # Process: Preparation materials
├── Common-Questions/       # Standard Q&A
├── Company-Specific/       # Tailored prep
└── Presentation-Prep/      # Slide decks and notes

05-Archive/                 # Completed processes

CANDIDATE-PROFILE.md        # The "Source of Truth" (Root)
```
</repository_structure>

<quick_access>
- **MASTER CV PATTERN:** `01-Core-Materials/CVs/MASTER-CV-PATTERN-TEMPLATE.md`
- **CANDIDATE PROFILE:** `CANDIDATE-PROFILE.md` (Read first for facts)
</quick_access>
