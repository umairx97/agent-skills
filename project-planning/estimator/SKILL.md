---
name: estimator
description: Estimate software development effort, delivery time, and cost for freelancers and agencies. Use for a new build, a change to existing software, or a revision to a client estimate.
---

# Estimator

An estimate ties a defined release to three quantities. **Effort** is labor hours. **Delivery** is elapsed time given staffing and dependencies. **Cost** uses the supplied rates and currency. Give each quantity only to the extent the inputs support it.

## 1. Establish the release

Read the brief and inspect available code, designs, or integration docs when they can resolve a material question. For existing software, trace the affected workflow from entry point to stored data and verify which pieces can be reused. For a new build, define the smallest release that satisfies the requested outcome.

State who can do what at handoff, how the client can verify it, and what is excluded. Ask the question that would move the estimate most. Give a recommended assumption and say what changes if it is wrong. Ask dependent questions after their prerequisites are settled.

Proceed when each material unknown is verified, stated as a bounded assumption, or separated from the estimate. If an unknown could make the release infeasible or its effort unbounded, propose a timeboxed discovery task with a specific question to answer and an artifact to hand back. Estimate any independent work the client can still plan.

## 2. Size work people can verify

Group work around observable outcomes. Add shared work once where it belongs. Check whether access, permissions, data migration, operational failures, QA, release, or handoff change the scope. Include only applicable work.

For each package, record the outcome, labor hours by role, dependencies, and the evidence behind the range. Prefer actuals from comparable work and explain the adjustment. Label judgment-based ranges as provisional. Size both ends against plausible conditions for the same scope. Price mutually exclusive scope choices separately and account for each risk once.

The breakdown is ready when every acceptance criterion maps to an included package and the upper end has a concrete explanation.

## 3. Schedule the work

Place packages in dependency order using each person's effective project capacity. Roles held by the same person share one calendar. Overlap packages only when dependencies and staffing permit it. Include review work in labor hours and approval queues as elapsed time.

Build the low and high schedules separately. Identify the sequence that determines the finish, the kickoff conditions, and any external waits. If capacity is missing, give effort and ask for availability before giving a delivery window.

## 4. Calculate cost

Multiply the effort endpoints by the supplied rate. For different rates, total hours by role and sum the respective cost endpoints. Give the currency and separate one-time fees from recurring charges. Keep an unpriced dependency visible. If rate or currency is missing, share the supported effort and timeline, then ask for the missing pricing basis.

For a **fixed-price request, budget cap, or change to an earlier estimate**, read [quoting and revisions](references/quoting-and-revisions.md).

## 5. Deliver the estimate

Lead with the release, effort, delivery, and cost. Follow with a breakdown, milestones, assumptions, exclusions, and the open decisions that could change the numbers. Mark conditional or provisional figures where they appear.

Before sharing, reconcile the low and high sums, verify that schedules honor dependencies and available capacity, and make sure excluded work is absent from the headline totals. For an example of the calculations, read [worked estimate](references/worked-estimate.md).
