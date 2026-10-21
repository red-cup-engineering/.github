## Original work and receiving owner

Link the original Work/issue and requirement. Name the implementing service/proper repository, ordinary consumer and receiving owner. Preserve unresolved original work; say unknown rather than inventing an identity or approval.

## Source and capability

Describe the concrete before/after behavior, exact source revisions and affected paths. Account for distinct variants and preserved capabilities. Link dependencies and the original return route.

## Evidence and limits

Link immutable evidence, actual commands/results and independent receiving. Distinguish source tests, publication, installation and useful operation. Record refusals, missing evidence, workflow effects and remaining obligations. Green checks or a completed checklist do not confer integration authority.

## Qualified source handoff

Use the [owning service specification](https://github.com/red-cup-engineering/.github/blob/main/CONTRIBUTING.md#qualified-source-handoff) when that service advertises this opt-in transport. A PR body or issue form is not a handoff. An independently qualified receiver whose numeric GitHub ID is allowlisted by the original service posts one separate comment on the original ready PR. The service authenticates the actual comment author; a name or ID written in its body grants nothing.

Copy only the following block's contents into that separate comment, with every example coordinate replaced by the exact current repository ID, PR number, head/default SHA and actual receiving evidence. Do not include the Markdown fence. Do not post the example unchanged.

```text
github.source-qualified-handoff.v1
{"schema":"github.source-qualified-handoff.v1","repository":"owner/repository","repositoryId":123,"number":1,"headSha":"<40 lowercase hex>","defaultSha":"<current default 40 lowercase hex>","idempotencyKey":"unique-qualified-source-lot","consumerEvidence":["https://github.com/owner/repository/pull/1#issuecomment-123"]}
```

The original service checks the authenticated author, exact current repository/PR/head/default, evidence and applicable receiving requirements/checks/protection before an effect. An immutable key cannot be reused with changed input. Changed source needs a new qualified disposition; unknowns or an uncertain outcome are not permission to retry. Publish the durable comment once; the original monitor can discover it when enabled without copying a local queue or waiting for an agent to relay it. The service's result comment reports actual source-integration custody; it does not imply native Work/Cell admission, package publication, installation or operating acceptance.
