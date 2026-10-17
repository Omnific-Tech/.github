## Outcome
<!-- Describe the problem and before/after behavior. Link the issue or agreed
requirements when available. Keep the description proportional to the change. -->

## Approach
<!-- Explain the key change and non-obvious tradeoffs. Avoid a file-by-file log. -->

## Verification
<!-- Report actual results. Prefer repeatable E2E evidence for complex behavior.
For documentation-only changes, describe inspection instead. Never imply an
unexecuted check passed. Evidence must identify the revision it verifies. -->
- Tested commit:
- Scenario and command:
- Result:
- Evidence: <!-- CI run/artifact, trace, recording, or report accessible to reviewers -->
- Not verified: <!-- Mocked boundaries, environment limits, skipped or failed checks -->

## Risk and rollout
<!-- State breaking changes, migrations, configuration, deployment order, and
rollback steps where relevant. Otherwise explain briefly why risk is low. -->

## Agent participation
<!-- Use exact model IDs from runtime/Telos records when available. Do not infer
model identity from the tool name. Write "Unknown — not exposed" if unavailable.
List material contributors; add rows for handoffs/fallbacks. Combine roles for
small changes. For human-only work, state "Human-only" and remove the table. -->
Human owner: <!-- Accountable maintainer; identify if unassigned -->
Telos task/run: <!-- Reference and source revision, or "Not used" -->

| Role | Agent/tool | Model | Scope |
| --- | --- | --- | --- |
| Orchestrator | | | Requirements, planning, coordination |
| Implementer | | | |
| Reviewer | | | |
| Verifier | | | Check execution and artifact inspection |

Review independence: <!-- Separate session/context or shared implementation context;
state when review was self-review or not performed. -->
Review result: <!-- Resolved findings, remaining findings with severity/disposition,
and review evidence. "Not performed" is valid; do not invent approval. -->
Human review: <!-- Pending, or link to actual human review -->
Acceptance criteria: <!-- Who defined them and who changed them; explain any
changes after implementation began. Link the history when available. -->

## Reviewer focus
<!-- Optional: specific assumptions or decisions needing scrutiny.
Delete this section when unnecessary. Link longer design/review records. -->
