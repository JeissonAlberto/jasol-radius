# Jasol Group - Network Manager (RADIUS)

## Visión de Ingeniería (Top 0.01%)
Este repositorio ha sido diseñado bajo los principios de **Zero-Trust**, **Alta Disponibilidad** y **Experiencia de Usuario Simplificada**. No es solo un clon de daloRADIUS; es una implementación endurecida para producción.

### Arquitectura Seleccionada:
- **Base de Datos:** MariaDB 11.8 (LTS) con Healthchecks nativos para prevenir fallos de arranque en frío.
- **Engine:** FreeRADIUS 3.x con logs persistentes para auditoría.
- **Frontend:** daloRADIUS optimizado con PHP-FPM y branding inyectado de Jasol Group.

### Despliegue Rápido (Perfecto y Funcional):

1.  **Requisitos:** Tener Docker y Docker Compose instalados.
2.  **Configuración:**
    ```bash
    cp .env.example .env
    # Edita el .env solo si necesitas cambiar las llaves maestras
    ```
3.  **Lanzamiento:**
    ```bash
    docker compose up -d --build
    ```

### Accesos:
- **URL:** `http://localhost` (o la IP de tu servidor).
- **Usuario Default:** `administrator`
- **Password Default:** `radius` (Se recomienda cambiar inmediatamente en el primer login).

### Blindaje Implementado:
- **Resiliencia:** El sistema se reinicia automáticamente ante cualquier fallo del kernel o caída del servicio.
- **Seguridad:** Los contenedores corren con privilegios restringidos (`no-new-privileges`).
- **Zona Horaria:** Sincronizado nativamente con `America/Bogota` para reportes precisos.

---
*Desarrollado por Zapia para Jasol Group.*
