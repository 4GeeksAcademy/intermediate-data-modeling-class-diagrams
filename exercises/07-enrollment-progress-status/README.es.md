# 07 - Progreso y estado del enrollment

Version en ingles: [README.md](./README.md)

## Escenario

La plataforma registra el avance del estudiante y si la matricula sigue activa.

## Instrucciones

Amplía **`Enrollment`** con:

| Propiedad | Tipo | Notas |
|-----------|------|-------|
| `progressPercent` | `int` | 0–100 |
| `status` | `string` | Documenta valores permitidos: `active`, `completed`, `dropped` |

diagram.4geeks.com puede no tener tipo enum — **`string` mas una nota corta** en la clase es correcto.

## Lista de verificacion

- [ ] `Enrollment` tiene progreso y estado con tipos visibles.
- [ ] Documentaste el significado de `status` (nota en el diagrama o para ti).

## Siguiente paso

**08 - Perfil de estudiante uno a uno**
