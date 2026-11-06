# TalentOS Premium 2.4.1 — Orion

Plataforma independiente de inteligencia de competencias, evaluación profesional y desarrollo de talento.

## Estado técnico

- **Catálogo multiprofesional:** 70 perfiles y 120 competencias en Tecnología, Comercial y Finanzas.
- **Assessment Studio:** 3 instrumentos iniciales, 12 ejercicios, rúbricas de 5 niveles, revisión y calibración.
- **Backend personal:** Supabase Orion, proyecto `kgffaxiiyynshclenlxe`.
- **Frontend provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web
- **Actualización operativa 2.4.1:** registro de cuenta pendiente de aprobación, confirmación por correo, recuperación de contraseña, alta automática de perfiles pendientes sin privilegios, servicio de administración actualizado.
- **Calidad:** 44/44 pruebas automáticas y recorridos Chromium de interfaz con servicios simulados.
- **Seguridad:** controles RLS y JWT; el asesor Supabase no reportó alertas en la última revisión.

## Pendientes para operación real

1. **Visibilidad GitHub:** este repositorio permanece público. El código fuente se mantiene fuera del repositorio hasta pasarlo a privado.
2. **Usuarios:** la activación inicial requiere identidad personal confirmada y bootstrap manual de administrador; todavía no se completó una prueba real con identidades.
3. **Netlify:** falta conectar la cuenta de hosting personal y configurar las URL autorizadas de Supabase Auth y el origen CORS.
4. **Validación externa:** sigue pendiente comprobar el acceso al portal y el correo transaccional desde una red externa.

La documentación de activación y el código completo se entregaron en el archivo de liberación 2.4.1. No se incorporaron credenciales privilegiadas, datos reales ni expedientes procedentes de otras organizaciones.
