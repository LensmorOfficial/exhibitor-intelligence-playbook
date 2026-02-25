# 02. Exhibitor Profiling

## Goal

Build a standardized, data-driven view of exhibitors so teams can prioritize outreach and onsite conversations.

## Core data dimensions

- **Company basics**: legal name, domain, HQ, size, revenue band.
- **Industry and sub-vertical**: primary category and specialization.
- **Product lines**: key offerings, differentiation, pricing tier.
- **Buying signals**: funding, hiring, partnerships, expansion.
- **Tech stack**: integrations, vendor ecosystem, platforms used.
- **Decision makers**: titles likely attending or exhibiting.
- **Procurement signals**: RFP history, vendor changes, compliance needs.
- **Growth velocity**: hiring rate, new locations, geographic expansion.

## Exhibitor scoring model

Use a weighted score (0–100) based on:

- ICP fit (30%)
- Intent signals (25%)
- Strategic value (20%)
- Budget capacity (15%)
- Competitive overlap (10%)

> Example: Score = (ICP fit * 0.30) + (Intent * 0.25) + (Strategic * 0.20) + (Budget * 0.15) + (Overlap * 0.10)

### Example scoring sheet

| Company | ICP fit (0-5) | Intent (0-5) | Strategic (0-5) | Budget (0-5) | Overlap (0-5) | Total |
| --- | --- | --- | --- | --- | --- | --- |
| ExampleCo | 5 | 4 | 4 | 3 | 2 | 18 |
| SampleCorp | 3 | 5 | 2 | 4 | 1 | 15 |

### Tiering rules

- **Tier A**: Total ≥ 18 (executive outreach + pre-booked meeting)
- **Tier B**: 14–17 (standard outreach + onsite priority)
- **Tier C**: ≤ 13 (lower-touch or walk-up list)

## High-value exhibitor identification

- Top 20% of scores form the priority outreach list.
- Add a 100/high-signal tier for onsite executive outreach (funding, M&A, or product launches).
- Flag partner or integration opportunities separately.

## Data enrichment and cleaning

- Use enrichment sources for domain, size, tech stack, and intent.
- Normalize titles and deduplicate contacts.
- Map subsidiaries to parent companies for consolidated targeting.
- Assign ownership and lifecycle stages for follow-up.

## Operational checklist

- Confirm legal entity and primary domain
- Validate category and product fit
- Confirm attendee roles and seniority
- Map competitive overlap
- Tag meeting priority

## Deliverable

A scored exhibitor master list with tiers, rationale, and recommended next actions.
