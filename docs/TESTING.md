# Testing and Verification Guide

Testing is how we prove behavior and reduce surprises.

## Test strategy

Use the smallest test set that checks the changed behavior well.

Common test types:

- unit tests for logic and validation
- integration tests for component interaction
- end-to-end tests for user flows
- regression tests for bug fixes
- security tests for access and validation

## Minimum standards

Before claiming a task is complete:

- run the relevant tests
- check the actual result
- confirm changed behavior matches acceptance criteria
- inspect whether regressions appear in nearby behavior

## Failure-handling tests

Always test:

- invalid input
- missing data
- permission errors
- external service failures
- timeout conditions
- empty or malformed payloads

## Verification commands

The exact commands depend on the project, but typical checks include:

```bash
npm test
pytest
cargo test
go test ./...
```

Also consider:

- linting
- type checking
- migration validation
- build verification
- accessibility checks for UI work

## Good practice

- do not claim success without evidence
- do not suppress errors to make a test pass
- document any test limitation clearly
- separate known issues from assumptions

## Definition of verified work

A feature is verified only when:

- it passes relevant tests
- the result matches the requirement
- the behavior is understood under failure conditions
- the implementation is not hiding obvious issues

This keeps quality checks honest and practical.
