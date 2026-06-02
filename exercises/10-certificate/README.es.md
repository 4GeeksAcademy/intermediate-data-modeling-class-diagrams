# 10 - Certificado

Version en ingles: [README.md](./README.md)

## Escenario

Cuando una matricula se completa, la plataforma emite un registro de certificado.

## Instrucciones

1. Agrega **`Certificate`** con:

| Propiedad | Tipo |
|-----------|------|
| `id` | `int` |
| `issuedAt` | `date` |
| `certificateCode` | `string` |

2. Enlaza **`Certificate`** con **`Enrollment`** (recomendado): etiqueta **`Enrollment` `1`** — **`Certificate` `0..1` o `1`**. Una matricula completada puede tener un certificado.

Si la herramienta facilita muchos a uno, enlaza solo certificado–enrollment — evita una linea duplicada estudiante–certificado.

## Lista de verificacion

- [ ] `Certificate` se vincula a la matricula (o claramente a estudiante+curso via enrollment).
- [ ] La cardinalidad usa etiquetas de texto.

## Siguiente paso

**11 - Resenas**
