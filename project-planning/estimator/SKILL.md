---
name: estimator
description: Estimate the labor hours, delivery time, and cost of software work for freelancers and agencies. Use this skill for new software, changes to existing software, or revisions to a client estimate.
---

# Estimator

Effort is the number of labor hours. Delivery time is the elapsed time for the available staff and the specified dependencies. Cost depends on the applicable rates and currency.

## 1. Check the inputs

Read the brief, previous answers, and applicable project documents. Identify the requested release and the parts of the estimate that the user requests.

- For a full estimate, confirm the release scope. Confirm the hourly rate and currency for each priced role. Confirm the weekly project hours for each person.
- For an effort estimate only, confirm enough of the scope to estimate the labor hours.

Use the information that the user already gave. Ask one question about a missing input per turn. If the rate and weekly hours are missing, ask these questions in order, on separate turns:

1. “What hourly rate and currency should I use?”
2. “How many hours per week can you give to this project?”

If the estimate is for a team, change the questions as necessary. Ask a scope question if its answer can change feasibility or significantly change the estimate. If a proposed scope assumption can help the user make a decision, give that assumption.

End the turn after the question. Before you give any estimate figures, wait for the user's reply. This applies to preliminary effort, delivery time, cost, and milestone estimates. After each reply, check for missing inputs. Start the estimate when you have the necessary inputs or when the user explicitly limits the request.

Describe what users can do with the release. Specify how the client can check the release. List the work outside the release scope.

If the user confirms that a dependency must stay open, define a discovery task with a time limit. Specify the question and the result for that task. Exclude work that needs the open dependency. Estimate independent work if you have sufficient information.

## 2. Estimate the labor hours

Put work with a common result in one work package. Include each shared task in one applicable package.

Check which of these items affect the scope:

- Access and permissions
- Data migration
- Operational failures
- Quality assurance
- Release and handover

For each package, give the result, labor hours by role, dependencies, and the basis for the range. When possible, use actual hours from equivalent work. Explain each adjustment to those hours. Mark ranges based on judgment as provisional. Base the low and high values on possible conditions for the same scope.

Give a separate price for each scope option that excludes the other options. Include each risk only once.

Check that each acceptance criterion has a work package in the estimate. Give a specific reason for the high value.

## 3. Calculate the delivery time

Schedule the work packages in dependency order. Use the available project hours for each person. Use one schedule for a person with more than one role. Schedule packages in parallel only if the dependencies and the available staff permit it.

Include time spent on reviews in the labor hours. Include time spent waiting for approval in the elapsed time.

Prepare separate schedules for the low and high values. Identify the sequence of work that sets the finish date. Specify the conditions to start work. Identify any wait for an external party or system.

## 4. Calculate the cost

For one rate, multiply the low and high labor hours by that rate. For more than one rate, add the hours for each role. Multiply the low and high hours for each role by its rate. Add the low costs and the high costs separately.

Specify the currency. List one-time fees separately from recurring charges. List dependencies that have no price.

For a fixed price, budget cap, or change to an earlier estimate, read [quotes and revisions](references/quoting-and-revisions.md).

## 5. Give the estimate

Give the release, effort, delivery time, and cost first. Then give the work packages, milestones, assumptions, exclusions, and open decisions that can change the estimate. Mark conditional or provisional values where you give them.

Before you give the estimate, do these checks:

- Check the totals for the low and high values.
- Check the schedules against the dependencies and available project hours.
- Make sure that the totals exclude all work outside the scope.

For an example of the calculations, read [worked estimate](references/worked-estimate.md).
