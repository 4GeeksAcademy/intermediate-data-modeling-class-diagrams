# 11 - Reviews

Spanish version: [README.es.md](./README.es.md)

## Scenario

After taking a course, a student may leave a rating and comment.

## Instructions

1. Add **`Review`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `rating` | `int` |
| `comment` | `string` |
| `createdAt` | `date` |

2. Connect **`Student`** → **`Review`** → **`Course`** with labeled links (similar pattern to `Enrollment`):
   - One student writes many reviews.
   - Each review targets one course.

Optional: add a note that `rating` is typically 1–5.

## Checklist

- [ ] `Review` links student and course without skipping the review entity.
- [ ] At least **six** distinct classes appear on the canvas.

## Next step

**12 - Final Model** — polish and compare with the reference diagram.
