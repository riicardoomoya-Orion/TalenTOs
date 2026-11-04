# TalentOS Premium 2.4 · Assessment Studio

Plataforma independiente de inteligencia de competencias y desarrollo profesional de la cuenta `riicardoomoya-Orion`.

## Estado técnico

- **Catálogo:** 70 perfiles y 120 competencias en Tecnología, Comercial y Finanzas.
- **Assessment Studio 2.4:** tres instrumentos publicados con doce ejercicios prácticos, rúbricas de cinco niveles y vinculación a competencias.
- **Flujo:** asignación por profesional, captura, revisión independiente, calibración opcional, dictamen y auditoría.
- **Versión reproducible:** rúbrica inmutable por expediente y publicación de nuevas versiones por autorización administrativa.
- **Supabase Orion:** proyecto `kgffaxiiyynshclenlxe`, 16 tablas con RLS y 8 Edge Functions activas (incluidas `manage-assessment-studio` con JWT y `talentos-web`).
- **Web provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web
- **Calidad del paquete:** 40 pruebas unitarias aprobadas y smoke de Chromium para Assessment Studio y regresión funcional.

## Actividades pendientes para operación productiva

1. Crear los usuarios reales de Supabase y completar el flujo con al menos autor, revisor y validador distintos.
2. Verificar que el portal abra mediante HTTP externo desde navegadores y dispositivos reales.
3. Configurar Netlify personal y CI/CD desde el repositorio.
4. Revisar las rúbricas con especialistas y validar su fiabilidad y equidad.

**Este repositorio debe hacerse privado antes de importar el código fuente.** Mientras su visibilidad sea pública, permanece limitado a la documentación. No contiene datos personales, credenciales ni respaldos del entorno anterior.

Los resultados de evaluación requieren criterio humano y no constituyen certificación ni decisiones automáticas de empleo.
