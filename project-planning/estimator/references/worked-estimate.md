# Worked estimate

## Brief

Add a CSV export for filtered orders to an existing admin dashboard. Admins can export the filtered list using the existing access controls. The CSV includes the fields from the approved specification, with correct escaping for commas, quotes, and line breaks. The client will use existing infrastructure and review one staging release within two working days.

One developer and one designer each have six effective project hours per working day. The rates are USD 90/hour for development and USD 75/hour for design. Work starts once the client provides repository and staging access.

## Client estimate

**66–96 labor hours, 11–15 working days from kickoff, and USD 5,760–8,370 in labor.** The range assumes that the existing order filters and access controls can be reused. The upper end allows for differences between the filters used by the dashboard and the export, and for fixes found during staging validation.

| Work package | Role | Effort | Depends on |
| --- | --- | ---: | --- |
| Confirm fields, filters, and acceptance criteria | Developer | 6–12 h | Kickoff and access |
| Design export control and feedback states | Designer | 12–18 h | Confirmed scope |
| Implement filtered CSV export endpoint | Developer | 12–18 h | Confirmed scope |
| Connect export UI and handle download errors | Developer | 18–24 h | Design and endpoint |
| Test output, filters, and access on staging | Developer | 12–18 h | UI integration |
| Deploy and hand off | Developer | 6 h | Client staging approval |
| **Total** | | **66–96 h** | |

## Delivery milestones

- **Scope confirmed in 1–2 working days.**
- **Design and endpoint ready by working day 3–5.** These packages run in parallel and take 2–3 days on the available capacity.
- **Staging ready by working day 8–12.** UI integration takes 3–4 days, followed by 2–3 days for validation and fixes.
- **Deployment and handoff by working day 11–15.** Allow two working days for client review, then one for deployment. The review wait adds elapsed time and zero labor hours.

## Pricing

| Role | Effort | Rate | Labor cost |
| --- | ---: | ---: | ---: |
| Developer | 54–78 h | USD 90/h | USD 4,860–7,020 |
| Designer | 12–18 h | USD 75/h | USD 900–1,350 |
| **Total** | **66–96 h** | | **USD 5,760–8,370** |

No new third-party fees are expected with the existing infrastructure. Scheduled exports, new permissions, and custom CSV templates are outside scope. If large exports require background processing, estimate that separately when the expected row volume is confirmed.
