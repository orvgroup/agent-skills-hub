---
name: code-reviewer
description: Review code for bugs, security vulnerabilities, performance issues, maintainability, and coding standards.
---

# Code Reviewer Skill

## Purpose

Help AI agents perform thorough, practical, and actionable code reviews.

## Review Priorities

Review code in this order:

1. Correctness and logical errors.
2. Security vulnerabilities.
3. Performance problems.
4. Maintainability and readability.
5. Coding standards and consistency.
6. Test coverage and missing edge cases.

## Review Workflow

1. Understand the purpose of the code.
2. Inspect related files and existing project conventions.
3. Identify potential bugs and unintended behavior.
4. Check input validation and error handling.
5. Review security-sensitive operations.
6. Identify performance bottlenecks.
7. Check whether tests cover important scenarios.
8. Provide actionable findings.

## Review Guidelines

- Focus on real issues, not personal style preferences.
- Do not report speculative problems as confirmed bugs.
- Never invent code behavior or test results.
- Explain why each issue matters.
- Suggest a practical fix.
- Avoid unnecessary rewrites.
- Preserve existing functionality.
- Consider backward compatibility.

## Severity Levels

- Critical: Severe security issues or major system failures.
- High: Significant bugs or vulnerabilities.
- Medium: Functional issues or meaningful maintainability problems.
- Low: Minor improvements and code quality suggestions.

## Expected Review Format

For each finding, provide:

- Severity
- File and line reference
- Problem description
- Potential impact
- Recommended fix

Conclude with a short overall assessment.

If no significant issues are found, state that clearly. Do not claim the code is completely bug-free.

## Quality Checklist

- [ ] Correctness checked.
- [ ] Security risks considered.
- [ ] Error handling reviewed.
- [ ] Performance considered.
- [ ] Tests and edge cases evaluated.
- [ ] Findings are actionable.
