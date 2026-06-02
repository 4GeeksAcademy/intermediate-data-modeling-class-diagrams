# 06 - Enrollment Association

Spanish version: [README.es.md](./README.es.md)

## Scenario

Students enroll in many courses over time; each course has many students. Resolve **many-to-many** with a concrete class.

## Instructions

1. Add class **`Enrollment`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `enrolledAt` | `date` |

2. Connect **`Student`** → **`Enrollment`** → **`Course`** with labels:
   - `Student` `1` — `N` `Enrollment`
   - `Enrollment` `N` — `1` `Course`

3. Do **not** draw a direct `Student`–`Course` line without `Enrollment`.

## Checklist

- [ ] `Enrollment` sits between student and course.
- [ ] Cardinality text appears on both links.

## Next step

**07 - Enrollment Progress and Status**
