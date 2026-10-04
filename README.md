# Proyecto de seguridad en GitHub

Repositorio de equipo creado para la actividad **RA6.f - Seguridad en GitHub: organización, permisos, ramas y secretos**.

## Descripción

Este proyecto simula el trabajo de una pequeña empresa de desarrollo. El objetivo es aplicar medidas básicas de seguridad en un repositorio compartido: gestión de permisos, protección de la rama principal, revisión de cambios mediante Pull Request y protección de información sensible.

## Equipo

| Usuario | Rol en el repositorio |
|---|---|
| Marcosgarpu | Admin |
| adiejul | Maintain |
| mcarmoy | Write |
| Alexlm13 | Triage |

## Normas de trabajo

- La rama `main` está protegida: no se puede escribir directamente en ella.
- Todo cambio se realiza en una rama y se integra mediante **Pull Request**.
- Cada Pull Request necesita al menos **1 aprobación** antes de fusionarse.
- Las tareas se reparten mediante **Issues**.

## Seguridad

- No se suben contraseñas, tokens, claves privadas ni datos reales.
- Los archivos `.env` reales están excluidos mediante `.gitignore`.
- Las variables de entorno necesarias se documentan en `.env.example`.
- Los problemas de seguridad se comunican según lo indicado en `SECURITY.md`.

## Próximos pasos

Conexión segura al repositorio mediante SSH para clonar el proyecto y trabajar con `git push` y `git pull`.
