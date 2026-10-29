# smarthydro_web

## Descripción
Sitio web SmartHydro.

## Arquitectura
Carpetas principales: (raíz).


## Setup local
1. Clonar el repo y copiar `.env.example` a `.env` (no versionar `.env`).
2. Completar las variables con valores de desarrollo (pedirlos a Felipe; nunca por chat ni en commits).
3. Instalar dependencias () y levantar el servicio.

## Variables de entorno
Solo nombres; valores en el servidor o en GitHub Secrets:
- (sin variables detectadas)

## Deploy
- Deploy **manual**; nada va a `production` sin aprobación de Felipe.
- No usar `down`, `--volumes` ni `prune` en servidores de producción.

## Runbook
- Revisar logs del contenedor/servicio antes de reiniciar; avisar antes de reiniciar servicios productivos.
- Ante un secreto filtrado: rotar, actualizar el servidor y ver `SECURITY.md`.
- Ante errores de CI: un solo re-run por PR.
