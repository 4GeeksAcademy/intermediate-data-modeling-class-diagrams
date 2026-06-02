# 08 - Student Profile One to One

Spanish version: [README.es.md](./README.es.md)

## Scenario

Optional profile data (avatar, timezone) lives in a separate class so `Student` stays lean.

## Instructions

1. Add **`StudentProfile`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `avatarUrl` | `string` |
| `timezone` | `string` |

2. Link **`Student`** and **`StudentProfile`** with **1:1** labels on the connector.

## Checklist

- [ ] Each student maps to one profile in your model.
- [ ] Cardinality `1` / `1` is written on the link.

## Next step

**09 - Categories**
