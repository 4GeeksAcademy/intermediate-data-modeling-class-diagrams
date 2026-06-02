# 10 - Certificate

Spanish version: [README.es.md](./README.es.md)

## Scenario

When an enrollment is completed, the platform issues a certificate record.

## Instructions

1. Add **`Certificate`** with:

| Property | Type |
|----------|------|
| `id` | `int` |
| `issuedAt` | `date` |
| `certificateCode` | `string` |

2. Link **`Certificate`** to **`Enrollment`** (recommended): label **`Enrollment` `1`** — **`Certificate` `0..1` or `1`** on the connector. A completed enrollment may have one certificate.

If the tool makes many-to-one easier, link certificate to enrollment only — avoid a duplicate direct student–certificate line.

## Checklist

- [ ] `Certificate` is tied to the enrollment (or clearly to student+course through enrollment).
- [ ] Cardinality is expressed with text labels.

## Next step

**11 - Reviews**
