# 05 - Lecciones

Version en ingles: [README.md](./README.md)

## Escenario

Cada curso se divide en lecciones ordenadas (videos, lecturas, cuestionarios).

## Instrucciones

1. Agrega la clase **`Lesson`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `title` | `string` |
| `durationMinutes` | `int` |
| `orderIndex` | `int` |

2. Enlaza **`Course`** con **`Lesson`** con etiquetas **1:N** (`1` en curso, `N` o `*` en leccion). Etiqueta opcional: `contains`.

## Lista de verificacion

- [ ] `Lesson` tiene cuatro propiedades tipadas.
- [ ] Un curso puede tener muchas lecciones en el diagrama.

## Siguiente paso

**06 - Asociacion Enrollment**
