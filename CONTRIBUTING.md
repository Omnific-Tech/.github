# Contributing to Omnific-Tech

Keep each pull request focused on one coherent outcome. Use a short conventional
title such as `fix(api): handle expired tokens`. Explain the problem, resulting
behavior, key tradeoffs, verification, and rollout risks. Scale detail to the
change; a small documentation correction does not need an implementation diary.
Repository-specific contribution and engineering instructions take precedence.

## Shared pull request template

Use [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md). This public `.github`
repository supplies GitHub's default template for organization repositories,
including private repositories, when no repository-local template exists.
Local templates override the default; local `CONTRIBUTING.md` files also override
this guide. See [GitHub's default community health file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

Inherited files are not included in consumer repository clones. When preparing
a PR with an agent or CLI:

1. Read the target repository's engineering and contribution instructions.
2. Use its local PR template if present. Otherwise fetch the org default from
   `Omnific-Tech/.github` on `main`, for example:
   `gh api 'repos/Omnific-Tech/.github/contents/PULL_REQUEST_TEMPLATE.md?ref=main' -H 'Accept: application/vnd.github.raw+json'`.
3. Fill the template with actual results and attribution. Remove instructional
   comments and optional empty sections; explicitly label missing checks/reviews.
4. Supply the completed description with `gh pr create --body-file <path>`.
   Supplying a custom body does not ensure that it follows the inherited format.

## Verification evidence

State the tested commit and retain evidence reviewers can inspect and reproduce.
For complex behavior, prefer E2E checks with exact commands, environment details,
expected/observed outcomes, and a report, trace, recording, or transcript. Include
before/after screenshots for visual changes. For documentation-only changes,
record inspection and relevant link/path checks.

Distinguish real integrations from mocked boundaries, executed platforms from
cross-builds, and local checks from production verification. Explain checks that
failed or were not run. Claims that failures are pre-existing need baseline
evidence. Refresh relevant verification after behavior changes; label older
evidence with its original tested revision.

Link CI runs and artifact names rather than machine-local paths alone. State
retention or access limits when relevant. Keep private evidence in the target
repository's permitted review channels, never in this public defaults repository.

## Agent attribution and review

Record the accountable human owner, Telos task/run when used, and material agent
participants. Separate agent/tool identity from model identity. Prefer exact
model IDs from runtime or Telos records; if only a family/alias is exposed, label
it as such and mark the exact ID unavailable. Never guess hidden model IDs.

List orchestrator, implementer, reviewer, and verifier scopes. Add rows when
multiple agents or fallback models materially contributed. Combined roles are
fine for small changes; mark roles not performed. Link full records for larger
changes. Attribution describes participation and does not establish approval.

Describe whether review used a separate session/context, shared implementation
context, or was self-review. Different models alone do not establish independent
review. Distinguish code inspection, check execution, and artifact inspection.
Record resolved findings and remaining findings with severity, disposition, and
follow-up links. Mark human review pending until an actual human review exists.

Identify who defined acceptance criteria and who changed them. Explain changes
made after implementation began, especially reduced coverage or relaxed checks;
link the change history when available. For Telos work, use existing records
rather than reconstructing participation and decisions from memory. This guide
does not replace a repository's Telos verification or submission requirements.
