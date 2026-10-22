> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# 14 · PRE-CALL, WEBINAR, CITAS, SHOW RATE Y PIPELINE CÉNIT
**Alcance limitado:** únicamente usuarios que solicitan atención comercial para Etics Academy. No aplicar llamadas ni SMS de venta a alumnos nivel cero que pidieron un HTML.

## 1. Dos recorridos comerciales distintos
**A) Autoservicio:** Etics Academy actual → webinar o taller existente → compra si la oferta es apta → onboarding. El objetivo NO es forzar una llamada para productos asequibles que se compran sin ella.

**B) Consultoría / acompañamiento:** Usuario manifiesta un problema avanzado → página de solicitud (3–5 campos, opciones amplias) → comprobación manual o por reglas simples → calendario → página pre-call → llamada de 20–30 minutos → oferta apropiada / recomendación gratuita / no encaja.

**Decisión fundamental:** una llamada debe reservarse para ofertas donde el valor y la necesidad de diagnóstico compensen el tiempo. No afirmar que todos los compradores de Cénit necesitan pasar por vendedor.

## 2. Pipeline de GHL (solo intención comercial)
`SOLICITÓ_INFO` → `APTO_PARA_WEBINAR` / `CITA_SOLICITADA` → `CITA_CONFIRMADA` → `ASISTIÓ` → `OFERTA_ENVIADA` → `GANADO` / `NO_COMPRÓ` / `NO_ENCAJA` / `NO_SHOW`.

Registrar como **Contact** a cada alumno; registrar como **Opportunity** solo un prospecto comercial real. Evitar duplicados, registrar fecha y oferta concreta. `No-show` no es «perdido» en automático. Usar motivo si la oportunidad cierra.

## 3. PRE-CALL PAGE: estructura lista para diseñar
**H1:** «Tu sesión sobre tu sistema de captación y ventas: así la vamos a aprovechar».

**Bloque 1, confirmación:** «Tu cita es el [fecha y zona horaria reales], [duración], [enlace privado]. También te hemos enviado la confirmación» (usar campos existentes, no escribir datos inventados).

**Bloque 2, qué recibirá:** «Revisaremos tu principal obstáculo comercial, qué probaste y qué siguiente paso es razonable. La llamada puede terminar en una recomendación gratuita o en una oferta si encaja».

**Bloque 3, prepara 3 cosas:** el problema prioritario; ejemplo de página/campaña o descripción sin información sensible; objetivo del próximo mes. Si algo no existe todavía, puede decir «aún no lo sé».

**Bloque 4, prueba sin engaños:** antecedentes verificables, metodología Cénit, ejemplos **etiquetados** (propios/con permiso/ilustrativos); FAQs honestas: «¿Se vende algo?», «¿Necesito invertir en anuncios?», «¿Para principiantes?», «¿Qué ocurre si no encajo?».

**Bloque 5, acciones:** confirmar calendario, reprogramar, cancelar, política de privacidad y enlace educativo si ahora no quiere comprar. Nunca usar falsa «plaza reservada» ni testimonios atribuidos a alumnos inexistentes.

## 4. Workflow GHL por estado (revisar menús de subcuenta)
**W05a Reserva:** Trigger `Customer Booked Appointment` filtrado por calendario comercial → comprobar si contacto tiene `INT_ETICS` / datos comerciales → marcar `CALL_BOOKED`, oportunidad en etapa `CITA_CONFIRMADA`, email transaccional con fecha, zona horaria, enlace de reprogramación y página pre-call; notificación al operador. Fuente: https://help.gohighlevel.com/support/solutions/articles/155000002675-workflow-trigger-customer-booked-appointment

**W05b Recordatorios**: 24 horas antes (email) y 2 horas antes (email o SMS *solo si autorizado, permitido y técnicamente habilitado*). Esperas relativas a hora de cita; si alguien reserva para menos de 24 horas, omitir recordatorio vencido. Chequear cancelado/reprogramado antes de cada mensaje; evitar duplicados por avisos nativos del calendario.

**W05c Asistió:** el asesor **marca asistencia real**. Workflow si status `Showed` → email breve con resumen personal aprobado y siguiente paso; ofertar solo lo relevante; campo `offer_sent_at` si aplica. Fuente: https://help.gohighlevel.com/support/solutions/articles/155000002619

**W05d No-show:** estado `No-show` real → un email cordial con enlace para reprogramar y una alternativa sin llamada; esperar 3 días; cerrar si no responde. No acosar ni enviar siete SMS.

**W05e Canceló:** estado `Cancelled` → detener recordatorios; ofrecer enlace para reprogramar si deseado; no contar como asistente.

**W05f Compró:** pago confirmado → tag cliente / registrar ingreso neto cobrado / iniciar onboarding Cénit / **detener secuencias de ventas del mismo programa**. Considerar reembolsos.

GHL documenta estados New, Confirmed, Cancelled, Showed y No-show, además de disparadores por reserva. Fuentes: https://help.gohighlevel.com/support/solutions/articles/155000003364-workflow-action-update-appointment-status y https://help.gohighlevel.com/support/solutions/articles/155000002619.

## 5. Guion consultivo de llamada de 25 minutos
- **0–3:** recordar objetivo y marco; pedir permiso para tomar notas.
- **3–9:** ¿qué estás vendiendo, quién compra, cómo llegan clientes hoy?
- **9–15:** identificar cuello de botella y qué datos se tienen realmente; distinguir diagnóstico de hipótesis.
- **15–20:** explicar 1–2 caminos, incluido hacer algo por su cuenta; confirmar si quiere conocer solución estructurada.
- **20–23:** si hay encaje, explicar programa vigente, límites, duración y precio auténtico; responder objeciones sin presionar.
- **23–25:** acordar siguiente paso verificable y dejar registro CRM.

## 6. Control comercial y definiciones (denominadores claros)
| Métrica | Fórmula | Nunca mezclar con |
|---|---|---|
| `Tasa reserva` | citas confirmadas / solicitudes comerciales elegibles | descargas de HTML |
| `Show rate` | citas efectivamente asistidas / citas programadas elegibles | registros webinar |
| `Cierre en llamada` | compras atribuidas a llamadas / llamadas asistidas | leads capturados |
| `Tasa de compra en webinar` | compradores / asistentes verificados | visitantes a página |
| `Ingreso neto cobrable` | ventas cobradas − devoluciones − comisiones | facturación atribuida estimada |
| `CAC comercial` | costos atribuibles de captación y ventas / compradores nuevos | simple CPL de formulario |

Ejemplo puramente ilustrativo: 20 reservas válidas, 12 asistentes = 60% show rate; 3 ventas de 12 = 25% cierre entre asistentes. **No son resultados tuyos ni benchmarks sectoriales.** No optimizar estas tasas con n<10; revisar fallos cualitativos primero.

## 7. La automatización no reemplaza la venta ética
Revisar legislación según país, finalidad y permiso para SMS/email; integrar opt-out de marketing; no hacer mensajes automatizados si el consentimiento o el canal no lo permite. Evitar cargar en herramientas IA información confidencial de clientes sin autorización. El formulario de citas no equivale automáticamente a consentimiento para campañas comerciales.

## 8. Prueba de aceptación antes de anunciar citas
Nuevo confirmado / agendó sin teléfono / cita en menos de 24h / reprogramó / canceló / asistió / no show / pidió no recibir marketing / comprador / duplicado. Para cada caso, verificar temporizadores, enlaces, zona horaria, resultado en pipeline y que no se mande ningún aviso tras cancelación o compra.
