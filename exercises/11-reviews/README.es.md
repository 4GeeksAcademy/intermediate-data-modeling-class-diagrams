# 11 - Resenas

Version en ingles: [README.md](./README.md)

## Escenario

Tras tomar un curso, el estudiante puede dejar puntuacion y comentario.

## Instrucciones

1. Agrega **`Review`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `rating` | `int` |
| `comment` | `string` |
| `createdAt` | `date` |

2. Conecta **`Student`** → **`Review`** → **`Course`** con enlaces etiquetados (patron similar a `Enrollment`):
   - Un estudiante escribe muchas resenas.
   - Cada resena apunta a un curso.

Opcional: nota de que `rating` suele ser 1–5.

## Lista de verificacion

- [ ] `Review` enlaza estudiante y curso sin omitir la entidad resena.
- [ ] Hay al menos **seis** clases distintas en el lienzo.

## Siguiente paso

**12 - Modelo final** — pulir y comparar con el diagrama de referencia.
