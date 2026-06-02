# 04 - Instructor Courses

Spanish version: [README.es.md](./README.es.md)

## Scenario

One instructor may teach several courses; each course has one primary instructor in this model.

## Instructions

1. Draw a **one-to-many (1:N)** link from **`Instructor`** to **`Course`**.
2. Add **text labels** on the connector ends: `1` on the instructor side, `N` or `*` on the course side.
3. Optional label on the line: `teaches`.

## Checklist

- [ ] Cardinality is visible as text on the relationship.
- [ ] Every `Course` in your diagram links to one `Instructor`.

## Next step

**05 - Lessons**
