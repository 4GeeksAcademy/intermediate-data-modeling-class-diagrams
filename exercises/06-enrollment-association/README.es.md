# 06 - Asociacion Enrollment

Version en ingles: [README.md](./README.md)

## Escenario

Los estudiantes se matriculan en muchos cursos; cada curso tiene muchos estudiantes. Resuelve **muchos a muchos** con una clase concreta.

## Instrucciones

1. Agrega la clase **`Enrollment`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `enrolledAt` | `date` |

2. Conecta **`Student`** → **`Enrollment`** → **`Course`** con etiquetas:
   - `Student` `1` — `N` `Enrollment`
   - `Enrollment` `N` — `1` `Course`

3. **No** dibujes una linea directa `Student`–`Course` sin `Enrollment`.

## Lista de verificacion

- [ ] `Enrollment` queda entre estudiante y curso.
- [ ] Hay texto de cardinalidad en ambos enlaces.

## Siguiente paso

**07 - Progreso y estado del enrollment**
