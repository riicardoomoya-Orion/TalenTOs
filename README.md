# TalentOS Premium 2.4 — Assessment Studio

Plataforma personal de inteligencia de capacidades multiprofesionales, en **Orion**.

## Despliegue técnico

- **Proyecto Supabase:** `kgffaxiiyynshclenlxe` (independiente).
- **Portal provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web
- **Versión web:** `talentos-web` v6.
- **Nuevo servicio:** `manage-assessment-studio` v1, JWT obligatorio.
- **Persistencia:** 16 tablas con RLS, 8 migraciones aplicadas.
- **Instrumentos prácticos iniciales:** Arquitectura Empresarial, Dirección Comercial y Planeación Financiera (12 ejercicios).
- **Catálogo profesional:** 70 perfiles / 120 competencias, versión 2.3.0, mantenido con historial.
- **Pruebas locales:** 38/38 unitarias; navegadores Chromium con mocks aislados para flujo nuevo y módulos anteriores.
- **Supabase Security Advisor:** sin alertas de seguridad.

## Flujo Premium 2.4

Instrumento versionado → asignación de profesional y evaluadores → respuestas y enlaces de evidencia → calificaciones independientes → detección de discrepancias → dictamen del administrador → auditoría.

Las rúbricas se publican mediante versiones nuevas. Las evaluaciones conservan una copia inmutable del instrumento utilizado. Se requiere segregación de funciones; la evaluación documental y la práctica se presentan por separado.

## Pendientes de producción operativa

- Registrar y aprobar las primeras identidades Supabase. Actualmente no hay usuarios reales.
- Certificar el flujo end-to-end con JWT y tres actores distintos (cuatro con segunda revisión).
- Verificar apertura HTTP desde navegador externo; la consulta por herramientas de investigación no pudo acceder al endpoint.
- **Cambiar este repositorio a privado.** Sólo se publicará el código fuente cuando su visibilidad esté protegida.
- Conectar Netlify personal como hosting definitivo.

Las rúbricas son instrumentos iniciales de evaluación profesional sujetos a calibración de expertos; sus resultados no deben automatizar decisiones de empleo.
