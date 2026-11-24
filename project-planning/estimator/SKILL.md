---
name: estimator
description: Estimate software development effort, delivery time, and cost for freelancers and agencies. Use for a new build, a change to existing software, or a revision to a client estimate.
---

# Estimator

An estimate ties a defined release to three quantities. **Effort** is labor hours. **Delivery** is elapsed time given staffing and dependencies. **Cost** uses the supplied rates and currency. Check the inputs before estimating.

## 1. Confirm the inputs

Read the brief, earlier answers, and relevant project materials. Check what the user wants delivered and which outputs they requested. For a full estimate, confirm the release scope, hourly rate and currency for each priced role, and effective weekly availability for each person doing the work. An effort-only request needs enough scope to size the work.

Ask one missing-input question per turn and wait for the answer. When both are missing, ask these in this order on separate turns:

1. **Hourly rate.** “What hourly rate and currency should I use?”
2. **Availability.** “How many hours per week can you commit to this project?”

Adapt each question to the team when needed. Use inputs already supplied and skip their questions. Ask any remaining scope question that could materially change feasibility or the estimate. Give a recommended scope assumption when that helps the user decide.

An intake turn ends with the question. Wait for the user's reply before giving any numbers, including preliminary effort, a delivery range, a price, or a milestone estimate. After each answer, check which inputs are still missing. Start estimating when the requested outputs have the necessary inputs or the user explicitly narrows the request.

Define what the release lets users do, how the client can verify it, and what is excluded. If the user confirms a dependency cannot be resolved yet, define a timeboxed discovery task with a specific question and deliverable. Keep the blocked implementation outside the estimate and size independent work where supported.

## 2. Size work people can verify

Group work around observable outcomes. Add shared work once where it belongs. Check whether access, permissions, data migration, operational failures, QA, release, or handoff change the scope. Include only applicable work.

For each package, record the outcome, labor hours by role, dependencies, and the evidence behind the range. Prefer actuals from comparable work and explain the adjustment. Label judgment-based ranges as provisional. Size both ends against plausible conditions for the same scope. Price mutually exclusive scope choices separately and account for each risk once.

The breakdown is ready when every acceptance criterion maps to an included package and the upper end has a concrete explanation.

## 3. Schedule the work

Place packages in dependency order using each person's effective project capacity. Roles held by the same person share one calendar. Overlap packages only when dependencies and staffing permit it. Include review work in labor hours and approval queues as elapsed time.

Build the low and high schedules separately. Identify the sequence that determines the finish, the kickoff conditions, and any external waits.

## 4. Calculate cost

Multiply the effort endpoints by the supplied rate. For different rates, total hours by role and sum the respective cost endpoints. Give the currency and separate one-time fees from recurring charges. Keep an unpriced dependency visible.

For a **fixed-price request, budget cap, or change to an earlier estimate**, read [quoting and revisions](references/quoting-and-revisions.md).

## 5. Deliver the estimate

Lead with the release, effort, delivery, and cost. Follow with a breakdown, milestones, assumptions, exclusions, and the open decisions that could change the numbers. Mark conditional or provisional figures where they appear.

Before sharing, reconcile the low and high sums, verify that schedules honor dependencies and available capacity, and make sure excluded work is absent from the headline totals. For an example of the calculations, read [worked estimate](references/worked-estimate.md).
