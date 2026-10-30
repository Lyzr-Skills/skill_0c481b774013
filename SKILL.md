---
name: intervention-flagger
description: Use this to combine missing, repeated and thin-report results into one list of employees who need the leader's attention, with evidence.
---

# Intervention Flagger

## Purpose
Give the leader one clear list of who needs attention and why, based on the results of the missing-report checker, repetition detector and thin-report detector.

## Rules
- Any one red flag from the three checks makes the employee RED FLAG.
- An employee with no red flags is HEALTHY.
- Every flag must show evidence: dates and the employee's own wording. If evidence is missing, write "insufficient data" instead of guessing.
- Describe patterns, not personality. Use neutral words.

## Priority order (most urgent first)
1. Repeated unresolved issue or pending payment combined with missed days.
2. Repeated unresolved issue or pending payment alone.
3. Two or more missed days.
4. A single missed day.
5. Thin reports.

## Steps
1. Gather the three results for each employee.
2. Decide RED FLAG or HEALTHY.
3. Sort red-flag employees by the priority order.
4. For each, write a one-line reason and list the evidence.
5. Suggest an action in one line, for example "Ask about the pending Pune vendor payment."

## Output
A list with these fields:
- Employee
- Status
- One-line reason
- Evidence (dates and wording)
- Suggested action
Then a short list of HEALTHY employees.
