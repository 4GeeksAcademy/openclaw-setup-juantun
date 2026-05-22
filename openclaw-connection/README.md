# openclaw-connection

Carpeta para almacenar archivos relacionados con conexiones de OpenClaw.

## Propósito

Esta carpeta está destinada a almacenar:
- Configuraciones de conexión
- Credenciales (si es seguro)
- Scripts de conexión
- Documentación de integraciones

## Estructura recomendada

```
openclaw-connection/
├── README.md (este archivo)
├── configs/      # Archivos de configuración
├── scripts/      # Scripts de conexión
├── docs/         # Documentación
└── examples/     # Ejemplos de uso
```

## Seguridad

⚠️ **Importante:** Nunca commits credenciales sensibles directamente en el repositorio.
Usa variables de entorno o sistemas de gestión de secretos.

## Uso

1. Para agregar una nueva conexión, crea un subdirectorio con el nombre del servicio.
2. Documenta la configuración en un archivo README dentro del subdirectorio.
3. Asegúrate de seguir las mejores prácticas de seguridad.

---

**Creado:** 22 de mayo de 2026  
**Última actualización:** 22 de mayo de 2026