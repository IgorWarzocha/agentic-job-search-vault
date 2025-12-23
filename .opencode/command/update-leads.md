# Leads Quick Review

Lightweight command for weekly lead reviews. For full market analysis use the `market-research` skill.

<usage>
`/update-leads` - review active leads
`/update-leads [source]` - add new leads from a specific source

Examples:
- `/update-leads` - show status of all active leads
- `/update-leads LinkedIn` - review new offers from LinkedIn
- `/update-leads cleanup` - remove outdated leads
</usage>

<workflow>
1. Read current leads from `03-Job-Market-Research/Active-Leads/`
2. Summarize statuses and priorities
3. Identify leads requiring action (deadline, follow-up)
4. Propose next steps
</workflow>

<output>
Short summary:
- High priority: X leads (list)
- Action required: Y leads (deadline/follow-up)
- To archive: Z outdated
</output>

<rules>
- MUST NOT create full market reports (use `market-research` skill)
- MUST NOT conduct deep company research (use `research-company` skill)
- Focus on quick review and prioritization
</rules>
