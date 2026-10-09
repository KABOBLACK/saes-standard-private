# SAES Project Checklists

Use these checklists before starting, while implementing, and before sign-off.

## Project readiness checklist

- [ ] Problem is defined in clear language.
- [ ] Users are identified.
- [ ] Functional requirements are documented.
- [ ] Non-functional constraints are documented.
- [ ] Acceptance criteria are measurable.
- [ ] Known risks are listed.
- [ ] Security requirements are reviewed.
- [ ] Data integrity concerns are considered.
- [ ] Dependencies are reviewed for compatibility.
- [ ] Scope and out-of-scope items are explicit.

## Design review checklist

- [ ] The architecture matches the actual problem.
- [ ] The solution is as simple as possible.
- [ ] The design considers reliability and failure modes.
- [ ] Security boundaries are defined.
- [ ] Inputs and outputs are validated.
- [ ] Key decisions are documented.
- [ ] Operational costs are acceptable.
- [ ] Recovery or rollback is possible.

## Coding checklist

- [ ] The change is small and targeted.
- [ ] Existing conventions are followed.
- [ ] Public interfaces were not changed unexpectedly.
- [ ] Error handling is explicit.
- [ ] Sensitive values are not logged or exposed.
- [ ] Input validation exists for untrusted data.
- [ ] The code remains understandable.
- [ ] The change does not add unrelated refactors.

## Quality and testing checklist

- [ ] Relevant tests were written or updated.
- [ ] Unit tests cover the changed behavior.
- [ ] Error cases are tested.
- [ ] Edge cases were reviewed.
- [ ] Type checks or linting were run if applicable.
- [ ] Build or production verification was performed if required.
- [ ] Regression risks were checked.

## Security checklist

- [ ] Secrets are stored outside source control.
- [ ] Authentication and authorization are validated.
- [ ] Sensitive data handling is minimized.
- [ ] User input is constrained and validated.
- [ ] Logging does not expose secrets or private data.
- [ ] Dependency risks were reviewed.
- [ ] Access boundaries and permissions are appropriate.

## Release readiness checklist

- [ ] Requirements are satisfied.
- [ ] Acceptance criteria pass.
- [ ] Documentation reflects the implementation.
- [ ] Regression risks are understood.
- [ ] Known limitations are documented.
- [ ] Security concerns were reviewed.
- [ ] Recovery steps are known.

## Final sign-off checklist

- [ ] The task is complete.
- [ ] The result was verified.
- [ ] The user-facing behavior is documented.
- [ ] Risks and limitations are disclosed.
- [ ] No critical issue remains unresolved.

Use these checklists as a practical guardrail to reduce mistakes and protect quality.
