# Agentic Job Search Vault

An AI-powered workflow for high-impact job applications. Built for as an agentic Obsidian-style vault.

## What This Does

| Feature | Description |
|---------|-------------|
| **No-Slop Documents** | CVs and cover letters that sound human. Short sentences. Punchy rhythm. No corporate buzzwords. Ready in 2-3 prompts. |
| **Research-First Approach** | The agent researches the company before generating documents. Context makes tailoring precise. |
| **Browser Automation** | Built-in MCP for filling multi-page application forms (Workday, Greenhouse, Lever). You review. Then submit. |

## Requirements

- [opencode](https://opencode.ai/) (AI-powered terminal IDE)
- Chrome + [Playwriter Extension](https://chromewebstore.google.com/detail/playwriter-mcp/jfeammnjpkecdekppnclgkkffahnhfhe) (for form automation)

## Quick Start

### 1. Clone and Open

```bash
git clone https://github.com/igor-warzocha/agentic-job-search-vault.git
cd agentic-job-search-vault
opencode
```

### 2. Add Your Materials

Drop everything you have into `01-Core-Materials/`. The more you give, the better the output.

| Material | Folder | Why It Helps |
|----------|--------|--------------|
| All your CVs | `01-Core-Materials/CVs/` | Different versions show range |
| Cover letters | `01-Core-Materials/Cover-Letters/` | Captures your voice |
| LinkedIn export | `01-Core-Materials/Portfolio/` | Rich context, endorsements |
| Project write-ups | `01-Core-Materials/Portfolio/` | Technical depth |
| Performance reviews | `01-Core-Materials/Portfolio/` | How others describe your impact |
| Old job descriptions | `01-Core-Materials/Portfolio/` | What you were hired to do |

**Formats:** Markdown, PDF, Word, plain text. Anything works.

### 3. Run Setup

```
/setup
```

The setup agent will:
1. Read everything in `01-Core-Materials/`
2. Build your `CANDIDATE-PROFILE.md` automatically
3. Ask clarifying questions
4. Configure agents with your preferences

You do NOT fill in `CANDIDATE-PROFILE.md` manually. The agent does it.

### 4. Install Playwriter (Optional)

For automating long application forms:

1. Install the [Playwriter Chrome Extension](https://chromewebstore.google.com/detail/playwriter-mcp/jfeammnjpkecdekppnclgkkffahnhfhe)
2. Pin it to your toolbar
3. Click the icon on any application page (green = connected)

The MCP config is already in `opencode.json`.

## Workflow

Once set up, the cycle is simple:

**Research** → Share a job posting. The agent researches the company first.

**Generate** → Tailored CV and cover letter created in `02-Applications/YYYY-MM/Company-Name/`.

**Apply** → Use Playwriter to fill forms. Review. Submit.

**Prep** → Interview materials generated in `04-Interview-Prep/`.

## Repository Structure

```
01-Core-Materials/          # YOUR INPUT: Past CVs, letters, portfolio
02-Applications/            # OUTPUT: Generated application packages
03-Job-Market-Research/     # Company research and market data
04-Interview-Prep/          # Interview preparation materials
CANDIDATE-PROFILE.md        # Auto-generated profile (source of truth)
```

## Style Rules

All generated documents follow strict quality standards:

- **No AI Slop:** No "leverage synergies" or "passionate about". Human language only.
- **British English:** UK spelling throughout. (ask the agent to change before you customise, if needed.)
- **Rich Conciseness:** Maximum 2 pages. Every word earns its place.

## License

MIT
