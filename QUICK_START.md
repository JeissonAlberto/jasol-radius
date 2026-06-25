# 🚀 JASOL AXON - Quick Start Guide
**Developer:** Ing. Jeisson Alberto Sarmiento
**Organization:** Jasol Group

Bienvenido a **JASOL AXON**, tu sistema de inteligencia de red. Esta guía te ayudará a dominar las funciones gráficas clave desde el primer minuto.

## 1. Acceso al Sistema
- **URL Principal:** Puerto 80 de tu servidor.
- **Login:** `administrator` / `radius`.
- **⚠️ Primera Acción:** Ve a *Config -> Operators -> Password* y cambia tu contraseña inmediatamente.

## 2. Gestión de Usuarios (El Corazón del Sistema)
En el menú lateral encontrarás **"Management"**:
- **Users Listing:** Verás a todos tus clientes. El icono de 🟢 indica que están activos.
- **New User:** Para crear un cliente manualmente. Solo necesitas el "Username" y definir el tipo de "Check" (usualmente `Cleartext-Password`).
- **Batch Add:** Úsalo para crear cientos de usuarios o tarjetas de tiempo en segundos.

## 3. Control de Planes y Perfiles
En **"Profiles"** es donde defines la "magia":
- Crea un perfil llamado `Plan_10MB`.
- Añade el atributo `Mikrotik-Rate-Limit` con valor `10M/10M`.
- Asigna este perfil a tus usuarios para que el sistema controle su velocidad automáticamente.

## 4. Monitoreo en Tiempo Real
En **"Reporting"**:
- **Online Users:** Mira quién está navegando justo ahora, su IP y cuánto tiempo lleva conectado.
- **Last Connections:** Historial detallado para soporte técnico (ayuda a ver por qué falló una conexión).

## 5. Gráficas y Estadísticas
En el **"Dashboard"** principal verás:
- Gráfica de "Top Users" por consumo.
- Comparativa de conexiones por día/semana.

---
*Este documento es parte de la entrega oficial de JASOL AXON.*
