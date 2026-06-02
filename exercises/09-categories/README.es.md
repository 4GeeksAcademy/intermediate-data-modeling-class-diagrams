# 09 - Categorias

Version en ingles: [README.md](./README.md)

## Escenario

Los cursos se agrupan (Desarrollo, Diseno, Datos) para navegar el catalogo.

## Instrucciones

1. Agrega **`Category`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `name` | `string` |
| `slug` | `string` |

2. Enlaza **`Category`** → **`Course`** con etiquetas **1:N** (`1` en categoria, `N` o `*` en curso). Etiqueta opcional: `groups`.

En este modelo simplificado un curso pertenece a **una** categoria.

## Lista de verificacion

- [ ] `Category` existe con propiedades tipadas.
- [ ] Hay un segundo patron **1:N** visible (instructor–curso y categoria–curso).

## Siguiente paso

**10 - Certificado**
