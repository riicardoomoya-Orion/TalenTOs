# TalentOS

Plataforma independiente de evaluación de competencias y desarrollo profesional. Propiedad y recursos bajo la cuenta personal **riicardoomoya-Orion**.

## Estado de la infraestructura

- **GitHub:** repositorio creado. Antes de cargar el código completo debe configurarse como **privado**.
- **Supabase Orion:** proyecto `kgffaxiiyynshclenlxe` operativo, migraciones y catálogo 2.0.0 aplicados.
- **Catálogo:** 58 perfiles y 88 competencias.
- **Servicios:** `evaluate-assessment`, `manage-users`, `manage-professionals` desplegados con JWT obligatorio.
- **Web provisional:** https://kgffaxiiyynshclenlxe.supabase.co/functions/v1/talentos-web (publicación técnica; validación funcional con usuario real pendiente).
- **Web definitiva prevista:** Netlify de la cuenta personal enlazado a este repositorio.

## Accesos y protección de datos

El frontend se ofrece como contenido público estático. Todas las evaluaciones y operaciones sobre profesionales requieren iniciar sesión y autorización por rol. Aún no hay usuario administrador creado. No se han migrado expedientes ni CVs del entorno anterior.

## Próximos controles

Cambiar la visibilidad del repositorio a privado; aprovisionar el primer usuario mediante el panel de Auth del Supabase personal; darlo de alta como administrador con control explícito; conectar la publicación Netlify y completar pruebas E2E.
