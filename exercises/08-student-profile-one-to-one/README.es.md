# 08 - Perfil de estudiante uno a uno

Version en ingles: [README.md](./README.md)

## Escenario

Datos opcionales de perfil (avatar, zona horaria) van en una clase aparte para mantener `Student` simple.

## Instrucciones

1. Agrega **`StudentProfile`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `avatarUrl` | `string` |
| `timezone` | `string` |

2. Enlaza **`Student`** y **`StudentProfile`** con etiquetas **1:1** en el conector.

## Lista de verificacion

- [ ] Cada estudiante corresponde a un perfil en tu modelo.
- [ ] Cardinalidad `1` / `1` escrita en el enlace.

## Siguiente paso

**09 - Categorias**
