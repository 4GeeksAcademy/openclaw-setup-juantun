# Notes - Problemas encontrados

## Problema con Google Docs
1. Conexión inicial no activa - necesitaba autenticación OAuth
2. Requería crear conexión específica para Google Docs y Google Drive
3. Necesitaba esperar confirmación de usuario tras compartir enlaces de autenticación

## Problema con Git Push a GitHub
1. Autenticación HTTPS falló - "could not read Username"
2. Cambio a SSH requerido - reconfigure remote URL
3. Host key verification inicial falló - necesitaba ssh-keyscan
4. Finalmente funcionó con clave SSH existente

## Problema con mcporter/Composio
1. Formato de JSON incorrecto en primeros intentos con COMPOSIO_MULTI_EXECUTE_TOOL
2. Necesidad de usar session_id consistente en todas las llamadas
3. Validación estricta de argumentos en herramientas