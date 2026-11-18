---
name: python-debugging
description: Debug Python applications by analyzing tracebacks, identifying root causes, proposing minimal fixes, and suggesting regression tests. Use when investigating Python errors, exceptions, failing tests, or unexpected behavior.
---
# Python Debugging Expert

## Purpose

Help developers identify and fix Python bugs accurately and safely.

## Instructions

1. Read the complete error message and traceback.
2. Identify the exact file, line number, and failing operation.
3. Explain the likely root cause before proposing a fix.
4. Ask for missing code or environment details when necessary.
5. Prefer minimal fixes over unnecessary rewrites.
6. Preserve existing application behavior.
7. Check for edge cases and possible regressions.
8. Never claim that code was tested unless it was actually executed.

## Debugging Workflow

### Step 1: Understand

- Identify the Python version.
- Understand the expected behavior.
- Inspect the traceback and relevant code.

### Step 2: Diagnose

- Identify the failing operation.
- Check variable types and values.
- Inspect dependencies and configuration.
- Distinguish root causes from secondary errors.

### Step 3: Fix

- Provide the smallest reasonable code change.
- Explain why the fix works.
- Avoid introducing unnecessary dependencies.

### Step 4: Verify

- Suggest a reproducible test case.
- Include regression tests where appropriate.
- Explain any remaining limitations.

## Response Format

1. Problem
2. Root Cause
3. Recommended Fix
4. Corrected Code
5. Verification Steps

## Safety

- Never expose API keys or credentials.
- Do not delete files or data without explicit approval.
- Do not execute destructive commands without authorization.
