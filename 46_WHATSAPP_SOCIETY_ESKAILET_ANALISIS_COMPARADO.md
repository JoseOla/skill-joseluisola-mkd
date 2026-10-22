# 46 · Society Eskailet / Andrea Eskailet y estrategia WhatsApp–GHL
**Investigación pública:** octubre 2026. **Separar datos publicados, interpretación y propuesta.**

## Andrea Eskailet: qué está realmente documentado
- Su web `society.eskailet.com` presenta **Society Free** y **Society Plus**, además de «La Colmena» como itinerario de 24 semanas/6 meses sobre un caso ficticio recurrente llamado *Café Origen*.
- La portada publica cifras que deben tratarse como autodeclaraciones del sitio en la fecha de consulta (aprox. 15.292 miembros Free, 292 Plus) y ofrece Plus a 66 €/mes en la página consultada. Los precios y miembros cambian.
- Promueve «KAI», asistente que contesta dudas en **Discord**, con Andrea resolviendo asuntos que requieren criterio y directos semanales; Society presenta un volumen sustancial de contenidos gratuitos y módulos de pago.
- Publica módulos por temas, itinerario progresivo, directos archivados y recursos de sistemas con n8n/Claude Code.
- **No se verificó que Andrea gestione absolutamente sola todo su negocio.** La presencia de una fundadora visible más un asistente no demuestra ausencia de empleados, freelancers o colaboradores. No replicar volumen de clases/directos ni promesa 24/7 sin recursos.

### Lecciones aplicables a José Luis Ola
1. Aprendizaje por etapas con ejemplo común (p.ej. «Tienda Aurora» como negocio totalmente hipotético, siempre identificado como simulación): estudiante usa mismo caso para redactar mensaje, crear oferta, atender, hacer seguimiento.
2. Una biblioteca gratuita de inicio con lecciones cortas; producto pago avanzado distinto, no simple bloqueo de vídeos gratuitos.
3. Recurso de conocimiento/FAQ que convierte las preguntas repetidas en material reutilizable. Puedes crear FAQ público antes de construir agente IA.
4. Los directos resuelven dudas agrupadas; no consultas privadas ilimitadas.
5. La pertenencia y progresión importan más que contar miembros; adaptar a 1 vídeo y 1 reto semanales.
6. Society usa **Discord** en el modelo público examinado, no evidencia de que sincronice WhatsApp con una comunidad HighLevel.

## Las dos comunidades NO son la misma base técnica
**GHL Community** administra membresía, espacios, tareas, acceso y publicaciones. **WhatsApp Community o grupo** es una funcionalidad de WhatsApp; no se convierte automáticamente en una comunidad de GHL.
HighLevel puede conectar WhatsApp Business para conversaciones **1:1** y workflows cuando se configura la integración; **mensajes de grupos de WhatsApp no están soportados por su Business Platform API**. No prometer sincronización bidireccional de grupos, respuestas y miembros sin una integración real comprobada.

## Diseño recomendado si ya tienes grupo WhatsApp
**GHL = casa del aprendizaje**, **WhatsApp = campana de avisos opcional**.
- En GHL: alta a comunidad, lecciones, retos, FAQs, comentarios y enlaces al vídeo público.
- En WhatsApp existente: máximo 1–2 avisos semanales, p.ej. «Nueva clase disponible» o «Este martes: reto». Enlazar al reto en GHL; no reproducir tutoriales enteros ni abrir debate técnico paralelo.
- Si el WhatsApp es muy activo: considerar grupo sólo administradores para anuncios, o «Comunidad de WhatsApp» con su grupo de anuncios; esto se configura en WhatsApp, NO desde el editor GHL.
- Los miembros deben unirse voluntariamente y recibir información clara de privacidad (otros participantes pueden ver sus números en grupos, según configuración). Evitar añadir personas unilateralmente.
- Puede existir un botón de acceso a WhatsApp en la bienvenida GHL, pero NO permitir que estar en WhatsApp se interprete como consentimiento a newsletter, CRM o mensajes comerciales.

## Tres niveles de operación técnica
**A. Sin integrar WhatsApp API (MVP recomendado):** compartir ENLACE MANUAL desde WhatsApp a la comunidad GHL; usar los mismos títulos y calendarizar dos anuncios semanales. Mantener consentimiento y privacidad. Coste y complejidad mínimos.
**B. Integrar WhatsApp Business con HighLevel:** configurar Settings → WhatsApp; considerar coexistencia si se quiere conservar la app (eligibilidad y país); conectar CRM 1:1; mensajes salientes proactivos generalmente usan plantillas aprobadas fuera de ventana de 24h y pueden generar costes; opt-in independiente y DND.
**C. Grupo de WhatsApp bidireccional hacia GHL:** NO prometerlo; no hay soporte nativo de grupos mediante la API de plataforma de WhatsApp en la documentación consultada. Evitar bots no oficiales que pidan escanear QR para controlar grupos, por posibles riesgos de privacidad y suspensión.

## Flujo de alta recomendado
1. Persona llega de YouTube a `/aprende` → ve primer vídeo, prueba HTML.
2. Elige suscribirse a Brújula por email (consentimiento separado).
3. Elige entrar a ETICS IA · DESDE CERO en GHL; acepta reglas de comunidad y recibe primer reto.
4. Opcionalmente ve enlace a avisos por WhatsApp; se incorpora por sí misma a partir de invitación controlada.
5. Si es avanzada y pide Cénit, completar calificación comercial en un flujo DIFERENTE.
6. Darse de baja de newsletter, WhatsApp y comunidad por separado debe ser fácil y respetado.

## Mensajes mínimos listos
**WhatsApp anuncio martes:** «Esta semana en ETICS IA · DESDE CERO: [tema]. Te dejo un reto de 10 minutos y una explicación sencilla. Ejercicio: [URL REAL GHL]. Si estás empezando, no necesitas saber programar».
**WhatsApp anuncio viernes:** «Cierre del reto: aquí están los tres errores más repetidos y cómo corregirlos. Resumen completo: [URL REAL]. Próxima clase en YouTube: [URL REAL]».
**Bienvenida GHL:** «¡Bienvenido a ETICS IA · DESDE CERO! Primero mira esta clase [URL REAL], abre este laboratorio [URL REAL] y publica en Retos qué te salió. Paso a paso, sin prisa. Agrupo las dudas cada semana; no hay tutoría individual 24/7».

## Límites y precauciones
- WhatsApp recomienda comunicarte sólo con contactos que aceptaron el contacto, no agregar a personas sin permiso.
- WhatsApp Business API no soporta mensajes de grupo en la integración documentada por HighLevel.
- No confundir mensajería 1:1 mediante CRM con grupos/Comunidad WhatsApp.
- Fuera de ventana de atención de 24 horas, usar plantillas aprobadas; revisar costes y políticas actuales antes de mensajes automáticos.

## Fuentes públicas verificadas
- Society: https://society.eskailet.com/
- Society Free: https://society.eskailet.com/mi-area/modulo/society-free/
- Directos Society: https://society.eskailet.com/mi-area/modulo/sesiones-en-directo/
- Consultoría Andrea: https://eskailet.com/
- HighLevel tipos WhatsApp no soportados: https://help.gohighlevel.com/support/solutions/articles/155000007905-whatsapp-unsupported-message-type
- Coexistencia WhatsApp GHL: https://help.gohighlevel.com/support/solutions/articles/155000003417-whatsapp-coexistence-feature
- Plantillas WhatsApp GHL: https://help.gohighlevel.com/support/solutions/articles/155000001623-whatsapp-template-statuses-and-best-practice
- WhatsApp comunidades y anuncios: https://faq.whatsapp.com/742237357891080
- WhatsApp uso responsable: https://faq.whatsapp.com/361005896189245/
