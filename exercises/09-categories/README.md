# 09 - Categories

Spanish version: [README.es.md](./README.es.md)

## Scenario

Courses are grouped (Development, Design, Data) for browsing.

## Instructions

1. Add **`Category`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `name` | `string` |
| `slug` | `string` |

2. Link **`Category`** → **`Course`** with **1:N** labels (`1` on category, `N` or `*` on course). Optional label: `groups`.

A course belongs to **one** category in this simplified model.

## Checklist

- [ ] `Category` exists with typed properties.
- [ ] Second **1:N** pattern is visible (instructor–course and category–course).

## Next step

**10 - Certificate**
