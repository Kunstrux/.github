# Pull Request Summary

## Description
<!-- Provide a brief summary of the changes in this PR -->

---

# 1. Risk Assessment

**Testing Requirement Level**

- 🔴 Mandatory
- 🟡 Encouraged
- 🟢 Not Applicable

**Why?**

<!-- Explain the risk level and testing expectations for this change -->

---

# 2. What I'm Testing

## Classes / Components Tested

List the classes, endpoints, services, or business logic covered by tests and where the tests are located.

### Examples

- `ProjectController.cs` → `ProjectControllerTests.cs`
- `ProjectService.cs` → `ProjectServiceTests.cs`

### Coverage Notes

Describe what behaviors, endpoints, or scenarios are being validated.

<!-- Example:
- GET /projects returns expected results
- POST /projects validates required fields
- Service handles duplicate project names correctly
-->

### Justification for Untested Code

If any code was not tested, explain why.

**Required when using:**

- `[ExcludeFromCodeCoverage]`
- Legacy code constraints
- Third-party dependencies
- UI-only changes

<!-- Explanation -->

---

# 3. Scenarios Covered

## Edge Cases

- [ ] Boundary values (zero, negative, max, empty, null)
- [ ] Invalid inputs
- [ ] Empty collections
- [ ] Large datasets
- [ ] Other:

### Notes

<!-- Describe edge cases covered -->

---

## Error / Invalid State Paths

- [ ] Exception handling
- [ ] Validation failures
- [ ] Dependency failures
- [ ] Unauthorized/forbidden scenarios
- [ ] Other:

### Notes

<!-- Describe error paths covered -->

---

## Data-Driven Test Cases

> Backend teams should use `[Theory]` where applicable.

- [ ] Multiple input variations tested
- [ ] Parameterized test coverage included
- [ ] Business rule permutations validated

### Notes

<!-- Describe theory/data-driven scenarios -->

---

# 4. Out of Scope

List items intentionally excluded from testing or review.

### Examples

- Pure layout/UI change, no logic modified
- Existing technical debt
- Functionality covered by separate work item

<!-- Out-of-scope details -->

---

# 5. Ready for QA Checklist

> **All items must be completed before moving to Ready for QA.**

- [ ] Tests added or updated for all changed logic
- [ ] All Acceptance Criteria (ACs) are covered by tests
- [ ] Tests are meaningful and would fail if logic breaks
- [ ] No assertion-free, trivial, or tautological tests
- [ ] Tests are deterministic (no flaky, time-based, random, or network-dependent behavior)
- [ ] All tests pass locally
- [ ] PR description clearly lists covered areas
- [ ] AI-assisted tests are disclosed and manually validated

---

# Reviewer Notes

## Areas to Focus On

<!-- Optional: Call out high-risk logic, architectural decisions, or areas where reviewer feedback is specifically requested -->

## Testing Evidence

<!-- Optional: Include screenshots, test output, coverage reports, pipeline links, etc. -->
