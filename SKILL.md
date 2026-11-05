---
name: "outcome-reconciler"
description: "Check the actual requested delivery outcome against observable acceptance criteria, distinguishing completed steps from incomplete or unverified results."
---

# Outcome Reconciler

Check the requested outcome against evidence of the current state.

Use this before reporting completion of a multi-step task or resuming work with an unclear final state. Keep checks proportional to the request.

## Define the delivery boundary

Translate the user's request into a short set of observable acceptance criteria. Keep the requested scope intact. If the user changes it, record that change rather than quietly dropping unfinished requirements.

Separate intermediate milestones from final outcomes. For a marketplace workflow, upload, approval, publication, and retrieval through the intended agent are different checks. For software, an edited file, passing unit tests, and a functioning user flow are different evidence.

For each criterion, identify the authoritative observation needed, dependencies on earlier criteria, and any relevant version or input identity. Gather that evidence with already authorized tools. Do not install a connector or widen access merely to clear the checklist.

Report each criterion as **verified**, **incomplete**, **blocked**, or **not checked**:

- **Verified:** a direct, relevant observation supports the criterion for the current inputs.
- **Incomplete:** the required result has not been reached.
- **Blocked:** a prerequisite or external condition prevents progress; name it.
- **Not checked:** there is no adequate observation yet.

An agent saying it succeeded is not independent proof. An external outage is not necessarily an implementation failure. Stale observations must be reopened, and a missing check must not disappear from the final report.

## Close with the useful result

State which acceptance criteria are met, what evidence supports them, what remains, and the next action that would resolve it. Claim the whole goal is complete only when all required criteria are verified. Preserve user-specific approval boundaries for any remaining writes.

Use [the delivery examples](references/examples.md) for marketplace, software, and connected-tool tasks.

## Boundaries

This is evidence reconciliation, not a deployment service or independent auditor. When the final state is inaccessible, report that limit. A checklist cannot make an inadequate test adequate.
