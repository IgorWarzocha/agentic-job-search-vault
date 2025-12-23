# Quick Application Tracker

Lightweight command for quick status updates. For full workflow use the `track-application` skill.

<usage>
`/track-application [company] [status]` or `/track-application [company] [note]`

Examples:
- `/track-application Aviva Interview Scheduled`
- `/track-application Graphcore Rejected`
- `/track-application McCann follow-up sent 2026-01-02`
</usage>

<workflow>
1. Find the tracker file: `02-Applications/YYYY-MM/Company-Name/Application-tracker.md`
2. Update the status or add an entry to the Timeline
3. Confirm the update to the user
</workflow>

<statuses>
- **Applied** - Application sent
- **Screening** - In screening process
- **Interview Scheduled** - Interview confirmed
- **Interview Completed** - Interview finished
- **Final Round** - Final stage
- **Offer** - Offer received
- **Rejected** - Application rejected
- **Ghosted** - No response
- **Withdrawn** - Application withdrawn
</statuses>

<rules>
- MUST NOT create new files (only update existing ones)
- For new applications use `create-application` skill
- For full tracking use `track-application` skill
</rules>
