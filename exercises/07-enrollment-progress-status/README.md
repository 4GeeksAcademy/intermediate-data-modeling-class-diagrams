# 07 - Enrollment Progress and Status

Spanish version: [README.es.md](./README.es.md)

## Scenario

The platform tracks how far a student progressed and whether the enrollment is still active.

## Instructions

Extend **`Enrollment`** with:

| Property | Type | Notes |
|----------|------|-------|
| `progressPercent` | `int` | 0–100 |
| `status` | `string` | Document allowed values in a note: `active`, `completed`, `dropped` |

diagram.4geeks.com may not have an enum type — **`string` plus a short note** on the class is correct.

## Checklist

- [ ] `Enrollment` has progress and status fields with types shown.
- [ ] You documented what `status` values mean (note or README for yourself).

## Next step

**08 - Student Profile One to One**
