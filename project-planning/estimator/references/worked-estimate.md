# Worked estimate

## Brief

Add a CSV export for filtered orders to an existing admin dashboard. Admins can export the filtered list with the existing access controls. The CSV includes the fields in the approved specification. The export applies the correct escaping to commas, quotes, and line breaks.

The client uses the existing infrastructure. The client reviews one staging release within two working days.

One developer and one designer each have six project hours per working day. The developer rate is USD 90 per hour. The designer rate is USD 75 per hour. Work starts after the client gives access to the repository and the staging environment.

## Client estimate

**66 to 96 labor hours, 11 to 15 working days from the start of work, and USD 5,760 to 8,370 for labor.**

The estimate assumes that the release can use the existing order filters and access controls. The high value allows for differences between the dashboard filters and the export filters. It also allows for corrections after tests in the staging environment.

| Work package | Role | Effort | Depends on |
| --- | --- | ---: | --- |
| Confirm the fields, filters, and acceptance criteria | Developer | 6–12 h | Start of work and access |
| Design the export control and its feedback states | Designer | 12–18 h | Confirmed scope |
| Add the endpoint for the filtered CSV export | Developer | 12–18 h | Confirmed scope |
| Connect the export interface. Add feedback for download errors. | Developer | 18–24 h | Design and endpoint |
| Test the output, filters, and access in the staging environment | Developer | 12–18 h | Connected export interface |
| Release the export. Transfer it to the client. | Developer | 6 h | Client approval of the staging release |
| **Total** | | **66–96 h** | |

## Delivery milestones

- **Scope confirmation takes 1 to 2 working days.**
- **The design and endpoint are ready by working day 3 to 5.** The packages run in parallel. Each package takes 2 to 3 days.
- **The staging release is ready by working day 8 to 12.** Connection of the export interface takes 3 to 4 days. Tests and corrections then take 2 to 3 days.
- **The release and handover are complete by working day 11 to 15.** The schedule allows two working days for client review and one day for the release. The wait for the review adds two days and zero labor hours.

## Cost

| Role | Effort | Rate | Labor cost |
| --- | ---: | ---: | ---: |
| Developer | 54–78 h | USD 90/h | USD 4,860–7,020 |
| Designer | 12–18 h | USD 75/h | USD 900–1,350 |
| **Total** | **66–96 h** | | **USD 5,760–8,370** |

The existing infrastructure has no expected new third-party fees. The scope excludes scheduled exports, new permissions, and custom CSV templates. If large exports need background processing, estimate that work separately after the user confirms the expected number of rows.
