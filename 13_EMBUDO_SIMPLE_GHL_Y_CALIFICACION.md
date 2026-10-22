> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# 13 · EMBUDO ÚNICO, CLASIFICACIÓN PROGRESIVA Y AUTOMATIZACIONES GHL
**Meta:** convertir a desconocidos en alumnos que regresan y, por separado, atender solicitudes de compradores avanzados de Cénit. Una sola base de contactos; distintas etapas y consentimientos. Arquitectura sugerida, NO configurada en GoHighLevel.

## 1. Arquitectura: un punto de entrada, no un embudo nuevo por contenido
```text
YouTube largos / Shorts / Radar / Google / Brújula / colaboraciones
                       ↓
joseluisola.com/empieza (o ruta factible) = HUB PÚBLICO
         ┌─────────────┴─────────────────────┐
         │                                   │
  «Quiero aprender IA»                 «Ya vendo, quiero sistema»
  clase 0 + HTML gratis               Etics Academy (página actual)
         ↓                                   ↓
  Formulario universal 3 preguntas    Autoevaluación comercial corta
         ↓                                   ↓
  GHL contacto + nivel + UTM           Interés Cénit declarado
         ↓                                   ↓
  correo entrega inmediato            Webinar/taller existente
         ↓                                   ↓
  Brújula solo con consentimiento      Cita opcional, solo si tiene sentido
         ↓                                   ↓
  reto voluntario / comunidad          Pre-call → llamada → oportunidad
         ↓                                   ↓
  próximo vídeo y nivel                compra/seguimiento/no-show
```
**Un sitio con múltiples artículos NO es un embudo complejo.** El hub centraliza la captura y los datos; las URLs indexables de la biblioteca se mantienen y pueden llevar al mismo formulario. Los 2 HTML actuales continúan como recursos, sin crear una landing individual para cada uno.

## 2. Formulario inicial ultraligero (para todo público)
**Campos esenciales:** nombre opcional, email obligatorio y consentimiento comercial **separado** del acto de entregar el recurso. No pedir teléfono por defecto.

**Preguntas, con opciones simples:**
1. «¿Cuánto has usado herramientas como ChatGPT, Copilot o Claude?» (Nunca / 1–2 veces / Las uso a menudo).
2. «¿Qué te gustaría resolver primero?» (Escribir mensajes / Crear anuncios o imágenes / Atender clientes / Ordenar oportunidades / Otro).
3. «Hoy, ¿cuál es tu situación?» (Estoy explorando / Vendo por mi cuenta / Tengo negocio o equipo / Presto servicios a negocios).

**Rama educativa:** Nunca + explorar → recurso nivel 0; `LEVEL_0`. Usa a menudo + vende → contenidos 1–3 o **enlace no obligatorio** a ruta comercial. Nada de rechazo por facturación ni promesas de ingreso.

**Rama avanzada, solo si el usuario hace clic en «Quiero conocer Cénit» o «Solicitar diagnóstico»:** preguntas condicionales adicionales: producto/servicio; problema prioritario (captación / mensajes / automatización / anuncios); situación de inversión o facturación en **rangos opcionales y amplios**; horizonte (explorando / próximo trimestre / este mes). No utilizar ingresos como criterio único de admisión; quien no encaje puede recibir webinar, formación gratuita o lista de espera adecuada.

**Microcopy de captura:** «Te envío el laboratorio HTML para abrirlo en Chrome y el vídeo con el ejercicio. Puedes aprender sin comprar. Marca aparte si también deseas recibir Brújula». Mostrar privacidad, finalidad y baja; revisar legislación aplicable.

## 3. Modelo de datos sugerido (crear antes de disparar workflows)
| Campo/tag | Tipo sugerido | Qué recoge | Cuándo |
|---|---|---|---|
| `OLA_IA_NIVEL` | custom single select | `0`, `1`, `2`, `3+` | Autoevaluación (revisable) |
| `OLA_INTERES` | custom multiselect | mensajes, creativos, atención, seguimiento, anuncios | Captura |
| `OLA_SITUACION` | custom single select | explora, vendedor, pyme, prestador | Captura |
| `OLA_INTENCION` | custom single select | aprendizaje, evalúa Cénit, pide cita, cliente | Por eventos explícitos |
| `OLA_RECURSO_ULTIMO` | custom text | código HTML (`HTML_001`) | Entrega |
| `OLA_ULTIMO_EP` | custom text | identificador (`EP001`) | Si es trazable |
| `OLA_ACEPTA_NEWS` | campo opt-in rastreable | consentimiento, origen, timestamp | Solo consentimiento válido |
| `OLA_PRECALL_ESTADO` | custom select | no aplica, reservado, asistió, no-show, canceló | Si cita |
| `OLA_SOURCE_FIRST / LATEST` | attribution GHL | fuente, campaña, contenido | Según captura disponible |
| `EDU_LEVEL_0`, `EDU_ACTIVE` | tags | entradas informativas | Con evento real |
| `INT_ETICS`, `CALL_BOOKED`, `CUSTOMER_CENIT` | tags | señales comerciales, no adivinadas | Acción real |

**No confundir** el campo `Source` del formulario con la atribución `utm_source`. GHL documenta la diferencia; comprobar ambos en contacto de prueba. Fuente: https://help.gohighlevel.com/support/solutions/articles/155000001506-source-field-in-forms-and-surveys .

## 4. Cinco automatizaciones imprescindibles en GHL
**W01 — Entrega educativa:** Trigger `Form Submitted` en captura principal → crear/actualizar contacto → establecer nivel/interés → enviar email transaccional de entrega HTML (si su configuración y base legal lo permiten) → mostrar página de gracias con enlace a vídeo #001 → registrar recurso. Si había contacto existente, actualizar sin duplicar etiquetas ni citas. No añadirlo automáticamente a newsletter de marketing sin consentimiento.

**W02 — Brújula consentida:** Trigger opt-in válido a newsletter → etiquetar `NEWS_OK` → enviar bienvenida una vez → Brújula jueves original o Lab HTML → escuchar desuscripción y detener comunicaciones promocionales. La baja debe funcionar de extremo a extremo.

**W03 — Ayuda educativa suave:** Si la persona eligió recibir correos educativos, tras 3 días enviar «¿Pudiste abrir el archivo? Aquí tienes instrucciones»; en día 7 sugerir siguiente vídeo. Nunca afirmar «vi que terminaste» sin evento real. Si no hubo permiso, mantener solo entrega y evitar secuencias comerciales.

**W04 — Interés Cénit explícito:** Trigger clic/solicitud identificable → tag `INT_ETICS` → ofrecer webinar/taller vigente y, **si quiere cita**, formulario breve de diagnóstico. Crear oportunidad en pipeline comercial únicamente cuando hay solicitud de compra, registro comercial calificado o reserva, NO por descargar HTML.

**W05 — Cita y poscita:** Trigger `Customer Booked Appointment` o estado real, confirmar, enviar pre-call, recordatorios apropiados, documentar estado `Showed / No-show / Cancelled / Closed`. Véase `14_PRECALL_VENTAS_Y_SEGUIMIENTO.md`.

GHL soporta lógica condicional v2 de formularios (mostrar/ocultar/redirigir) y workflows con condiciones. El método exacto de detección de un clic y entregas de archivo requiere **prueba real** en la subcuenta. Fuentes: https://help.gohighlevel.com/support/solutions/articles/155000001314-conditional-logic-v2-in-forms-and-surveys- y https://help.gohighlevel.com/support/solutions/articles/155000002048-automating-opportunities .

## 5. Regla de segmentación humana, no lead scoring agresivo
**Clasificar por estado, no por edad.** `APRENDIENDO` = quiere clases/HTML; `EXPLORANDO_SISTEMAS` = desea profundizar; `ETICS_READY` = pidió webinar/cita/solución avanzada; `CLIENTE` = pago confirmado. Los ingresos declarados jamás garantizan un buen ajuste. No asignar valor de ventas ficticio a un recurso educativo.

**Puntuación *experimental* opcional, a partir de día 46:** 1 punto por completar un ejercicio autodeclarado, 2 por asistir a webinar (comprobado), 3 por pedir diagnóstico. Nunca convertir un puntaje en solicitud de llamada no consentida. No sumar puntos indefinidamente; revisión mensual. La interacción con vídeos externos de YouTube **no se identifica con certeza a nivel de contacto GHL**; tampoco confundir vistas de un vídeo en un sitio GHL con todo lo que alguien hace en YouTube.

## 6. Tres rutas de navegación, un solo CRM
- **Ruta A — Novato:** EP001 → HTML001 → Brújula opcional → comunidad gratis → EP002. Único CTA: siguiente acción educativa.
- **Ruta B — Pequeño vendedor:** EP003 → HTML respuestas → nivel 1–2 → seguimiento; cuando exprese interés, webinar Cénit.
- **Ruta C — Preparado:** consulta comercial → Etics → webinar/taller → posible cita y pipeline de oportunidades. No imponer la misma secuencia al principiante.

## 7. Prueba QA de 12 escenarios (no publicar sin pasarla)
1. Nuevo sin experiencia; 2. contacto repetido; 3. elige «solo recurso» sin newsletter; 4. acepta Brújula; 5. retira consentimiento; 6. solicita Cénit; 7. no quiere indicar ingresos; 8. enlace HTML roto; 9. móvil que no abre `.html`; 10. viene desde Shorts con UTM; 11. Gmail cae en spam; 12. usuario solicita borrado de datos. Para cada caso registrar esperado / observado / responsable / corrección. Añadir comprobación de consentimientos e idioma.

## 8. Mapa UTM propuesto
| Origen | Ejemplo de parámetros |
|---|---|
| YouTube vídeo | `utm_source=youtube&utm_medium=organic_video&utm_campaign=ia0_t1&utm_content=ep001` |
| YouTube Short | `utm_source=youtube&utm_medium=short&utm_campaign=ia0_t1&utm_content=ep001_s1` |
| Directo Radar | `utm_source=youtube&utm_medium=live&utm_campaign=radar_001` |
| Google orgánico | Se atribuye por fuente orgánica donde sea capturable; no inventar UTM que Google no envió |
| Brújula | `utm_source=brujula&utm_medium=email&utm_campaign=ed_001` |

**Dos análisis distintos:** First Attribution = primer evento capturado; Latest Attribution = interacción atribuible reciente. No afirmar atribución causal de una venta solo por último clic. Fuente: https://help.gohighlevel.com/support/solutions/articles/155000002549-how-to-add-attribution-and-utm-parameters-as-filters-on-custom-widgets .

## 9. Qué NO hacer al comienzo
No lanzar landing por cada prompt, no comprar SMS de golpe, no rediseñar Etics hasta medir, no pedir ticket de compra en el email 1, no crear pipeline comercial para suscriptores gratuitos, no poner cuestionario largo delante del primer HTML. La simplicidad comercial vive **detrás** de una experiencia educativa simple.
