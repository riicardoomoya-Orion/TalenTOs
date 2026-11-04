# TalentOS Premium 2.2

Plataforma independiente de evaluación documental de competencias, expedientes profesionales, desarrollo 30/60/90, evidencias y gobierno de calidad. Propietario: `riicardoomoya-Orion`.

## Estado de la publicación

- **Backend Orion:** Supabase `kgffaxiiyynshclenlxe`, estado activo.
- **Web provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web — publicación 2.2 desplegada (función `talentos-web` versión 4).
- **Catálogo independiente:** 58 perfiles y 88 competencias.
- **Persistencia:** 12 tablas con RLS, 6 migraciones aplicadas.
- **Servicios Edge:** `evaluate-assessment`, `manage-users`, `manage-professionals`, `manage-development`, `manage-quality` (JWT obligatorio), `talentos-web` (contenido estático).
- **Seguridad:** permisos SQL de cliente restringidos a lectura sujeta a RLS, RPC protegidas, Supabase Advisor sin alertas.
- **Calidad:** 19 pruebas automatizadas y smoke test Chromium completados con servicios aislados.

### Capacidades incorporadas en Premium 2.2

Portafolio de evidencias, dictámenes de calidad con separación de funciones, observatorio de métricas, auditoría, control de versiones, seguimiento 30/60/90 y evolución longitudinal.

### Pendientes para uso con personas reales

1. Crear una identidad verificada y autorizar el primer administrador en Supabase Auth.
2. Probar con dos usuarios reales los controles de autorización y la segregación de funciones.
3. Comprobar acceso HTTP desde navegador externo y conectar Netlify personal.
4. **Convertir este repositorio a privado antes de subir el código fuente.** Por seguridad, este repositorio público contiene solamente documentación.

No se han trasladado CVs, usuarios ni expedientes de entornos anteriores. La evaluación documental no sustituye una certificación profesional.
