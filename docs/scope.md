# Scope

## In scope for this Voyage (MVP)
- Create and manage number ranges, with the numbers inside them.
- Import numbers from CSV, with validation before acceptance.
- Move a range through the porting workflow, with dates and calculated
  deadlines.
- Flag ranges that are overdue or at risk.
- Attach the signed LOA and other evidence to a range.
- A dashboard with filters and an "action needed today" list.
- Export the current view to CSV.
- User accounts with roles, and an auditable history of status changes.

## Out of scope
- **Carrier API integration.** Every carrier is different and most have no
  public API. Submission stays manual; the product tracks it.
- **Multi-tenant.** One organisation per deployment.
- **Billing and cost tracking.** A separate concern, already covered by
  the finance system.
- **Native mobile app.** The web app must work on a phone browser, which
  is enough for Jonas on site.
- **Automated emergency-address validation.** Out of the porting domain.

## Assumptions
- Numbers are stored in E.164 format.
- A range belongs to exactly one city and one losing carrier.
- Regulatory lead times are configurable per country, defaulting to 45
  days for submission and 5 working days for carrier response.
