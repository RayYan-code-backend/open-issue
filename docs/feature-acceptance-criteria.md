# Feature Acceptance Criteria

Use this short checklist when a feature issue needs clear acceptance criteria.

## Required Fields

- Feature summary: one sentence describing the requested behavior.
- User outcome: the observable result a user or reviewer should see.
- Acceptance criteria: bullet points that can be checked one by one.
- Verification: the command, screenshot, or manual path used to confirm the result.

## Review Standard

A feature issue is ready for implementation when every acceptance criterion is:

- Observable from the repository, UI, API response, or documentation.
- Specific enough that two reviewers would reach the same pass/fail result.
- Limited to the stated feature scope.

## Example

```markdown
Feature: Add a visible status label to the issue list.

Acceptance criteria:
- Each listed issue shows one status label.
- Empty status values fall back to "unknown".
- The reviewer can verify the label from the issue list screen.
```
