# TalentOS Premium 2.3

Plataforma independiente de inteligencia de capacidades profesionales en **Orion**. Este repositorio corresponde al proyecto personal, sin dependencia operativa de otros entornos.

## Estado de versión

- **Catálogo multiprofesional:** 70 perfiles y 120 competencias — Tecnología (58), Comercial (6) y Finanzas (6).
- **Supabase Orion:** `kgffaxiiyynshclenlxe`, 13 tablas con RLS y 7 funciones Edge activas.
- **Catálogo vigente:** `2.3.0`. Se conserva `2.0.0` para evaluaciones anteriores.
- **Editor premium:** borradores de rúbricas, edición por nivel y peso, creación de variantes, versionado y publicación administrada.
- **Evaluación:** prediagnóstico documental por perfil/nivel, con revisión humana obligatoria.
- **Pruebas:** 25 de 25 automatizadas y smoke Chromium exitoso con servicios simulados.
- **Auditoría de seguridad Supabase:** cero alertas.

**Portal web provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web

## Condiciones operativas pendientes

- El repositorio **aún es público**. Por eso se mantiene **sin código fuente completo** hasta que sea cambiado a privado. La versión fuente se entregó en paquete ZIP fuera de GitHub.
- No se han registrado usuarios reales (0 en Auth). Falta activar el primer administrador y validar segregación con un segundo evaluador.
- La apertura HTTP desde una red externa no pudo verificarse en el entorno de ejecución.
- El despliegue definitivo Netlify personal está pendiente.
- Los catálogos Comercial y Finanzas son taxonomías iniciales, pendientes de calibración por especialistas; los puntajes documentales no son certificaciones ni decisiones laborales automatizadas.

## Modelo de compatibilidad

El catálogo tecnológico anterior conserva sus identificadores. En 2.3.0 se corrigió una competencia duplicada del perfil `technology-program-manager` (`leadership` en núcleo y apoyo), lo cual puede modificar su cobertura documental: los reportes deben identificar siempre la versión del catálogo utilizada.
