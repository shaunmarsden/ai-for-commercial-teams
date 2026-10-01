# AI Connection Check

Run this before a team connects an AI tool to another system, or treats a connector as ready for normal work.

## The Job

- [ ] The job is specific and happens often enough to matter.
- [ ] The current process and the intended improvement are written down.
- [ ] The result can be checked by the person responsible for the work.
- [ ] No one is using the connection to avoid deciding what good looks like.

## Data And Permissions

- [ ] We know exactly what information the connection can read.
- [ ] We know exactly what information it can write, send or change.
- [ ] Access is no broader than the test requires.
- [ ] We considered read-only access before write access.
- [ ] We understand the credentials, tokens and who owns the account.
- [ ] Customer, employer, personal and confidential information stays out unless that tool is approved for it.
- [ ] We understand retention, logging and third-party processing well enough for this use.

## Human Control

- [ ] A person approves external messages, CRM changes, records, commitments and other consequential actions.
- [ ] The connection cannot silently create a commitment or change a system of record.
- [ ] Failures, stale data and missing permissions are visible when they happen.
- [ ] The method has a named owner and a review date.

## Evidence

- [ ] The first test uses fictional or approved information.
- [ ] We recorded the source, version or access date.
- [ ] The team recorded what was useful, wrong, missing and corrected.
- [ ] The test showed enough value to justify another test.

If any essential box is unclear, mark the connection **test further** or **restrict**. Don't call it ready just because the demonstration looked impressive.
