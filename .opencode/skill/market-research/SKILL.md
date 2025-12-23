---
name: market-research
description: Automates collecting and analyzing job market data and trends. Use for cyclical monitoring of sectors, salaries, and skills demand.
---

# Job Market Research

<workflow>

## Step 1: Define Research Scope

1. Determine parameters from the user request:
   - **Sectors:** As defined in Profile.
   - **Locations:** Target Locations from Profile.
   - **Levels:** Junior, Mid, Senior, Lead.
   - **Salaries:** Range expectations.

## Step 2: Market Data Collection

1. Systematically collect data:
   - Number of job offers in each category.
   - Required skills and qualifications.
   - Salary ranges.
   - Requirement trends.
   - Hot companies and sectors.

## Step 3: Trend Analysis and Insights

1. **Skills:** Identify growing vs. declining requirements.
2. **Salaries:** Collect data ranges and compare with Candidate expectations.
3. **Competition:** Analyze the competitive landscape and entry barriers.

## Step 4: Market Report Creation

1. Create a monthly report using the template in `references/templates.md`.
2. Save to: `/03-Job-Market-Research/Market-Analysis/YYYY-MM-Market-Report.md`.

## Step 5: Strategy Update

1. Based on insights, SHOULD suggest updates to:
   - Application priorities.
   - Candidate positioning.
   - Skill development plan.

</workflow>
