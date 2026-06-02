# 05 - Lessons

Spanish version: [README.es.md](./README.es.md)

## Scenario

Each course is split into ordered lessons (videos, readings, quizzes).

## Instructions

1. Add class **`Lesson`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `title` | `string` |
| `durationMinutes` | `int` |
| `orderIndex` | `int` |

2. Link **`Course`** to **`Lesson`** with **1:N** labels (`1` on course, `N` or `*` on lesson). Optional line label: `contains`.

## Checklist

- [ ] `Lesson` has four typed properties.
- [ ] One course can have many lessons in the diagram.

## Next step

**06 - Enrollment Association**
