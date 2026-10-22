> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# Medición desde día 1: 4 capas + tablero de decisión

## Principio
Sin datos anteriores, primero medir línea base y observar comportamientos. No imponer «CTR óptimo» universal ni atribuir ventas a YouTube sin trazabilidad. Las cuatro capas constituyen indicadores operativos y **no indicadores de éxito económico garantizado**.

## CAPA 1 — Descubrimiento
YT Studio: impresiones por fuente, CTR **por superficie**, nuevos espectadores, búsquedas que traen vistas, Shorts feed mostrado vs visto, vistas Shorts y clicks al contenido relacionado cuando disponible. Google Search Console: impresiones/clics/query/página por marca vs no marca, URL indexadas. Diagnóstico: «¿la persona correcta encontró el tema?».

## CAPA 2 — Consumo
Retención de primeros 30 s, puntos de salida, duración media en minutos y %, vistas de series, final screens, asistencia al replay Radar y live pico/avg concurrente. Comparar vídeos por nivel y formato; al inicio muestras mínimas, inspección cualitativa.

## CAPA 3 — Fidelización
Altas Brújula, aperturas como orientación limitada (privacidad distorsiona opens), **clics medidos**, replies, asistencia siguiente Radar, registros/actividad comunidad, retos reportados voluntariamente, returning viewers YouTube. No contabilizar «descargar HTML» como «lo completó».

## CAPA 4 — Negocio
Leads preparados, visitas webinar, asistencias, ventas reales Cénit, reembolsos, costes de contenido y herramientas, margen por programa; ads YPP RPM/revenue **solo si aparece monetización aprobada**. Segmentar LEADS 0 vs ETICS_READY para no suponer que cada principiante debe comprar.

## Instrumentación paso a paso
1. **Línea base fecha 19/oct/2026:** guardar pantallazos/export de YouTube Studio si ya existe, GHL contacts, Search Console (si ya configurado), visitas web y newsletter. Si son cero o desconocidos escribirlo.
2. **GA4**: propiedad y flujo para dominio público. Configurar consentimiento de cookies según jurisdicción y carga de script segura; comprobar eventos con DebugView; evitar duplicar Pixel/tag.
3. **Search Console**: propiedad DOMINIO `joseluisola.com`, `eticsacademy.com`, revisar verificación y sitemaps, no confundir «inspeccionado» con «indexado».
4. **GHL**: hidden fields/UTM preservados al registro cuando sea posible, fuentes reales en contacto: `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`, `landing_page`, `level_self_report` y fecha.
5. **Click HTML**: evento `resource_click` en la página web/enlace del correo, con `resource_id` sin datos personales; no intentar rastrear el archivo offline sin consentimiento.
6. **Participación**: usar encuesta o respuesta voluntaria `challenge_completed_self_reported` a nivel CRM, no presumir completitud.
7. **Compra**: separar lead, asistencia, reserva, pago confirmado, cancelación y reembolso; atribución con ventana y fuente definidas, no conteos duplicados.
8. **Directos**: registrar manualmente tiempo dedicado, gastos, fuentes, concurrencia, vistas 7 días y coste por publicación; cuando YPP activo registrar ads en campo separado.

## Convenciones UTM (ejemplos adaptables)
- Short → vídeo largo: relación YT nativa; no añadir URL ficticia a overlays.
- YouTube largo → HTML: `?utm_source=youtube&utm_medium=organic_video&utm_campaign=ia_cero_s01&utm_content=ep001`
- Radar → comunidad: `?utm_source=youtube&utm_medium=live&utm_campaign=radar_001`
- Brújula → siguiente episodio: `?utm_source=newsletter&utm_medium=email&utm_campaign=brujula_001`
- Google blog → formulario: conservar campo fuente `organic_search` según medición; no añadir UTM inventados a tráfico orgánico sin necesidad.

## Plantilla del tablero semanal (copiar cada viernes)
| Semana | Video ID | Nivel | Fuente | Impresiones | CTR fuente | Vistas | Retención 30s | Recurso clics | Leads | Reto autodeclarado | Regresan | Coste/horas | Decisión |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 2026-W44 | EP001 | 0 | Búsqueda YT | N/D | N/D | N/D | N/D | N/D | N/D | N/D | N/D | N/D | Recopilar |

**Completar 4 niveles**: 1 tablero vídeo; 2 Radar; 3 contenidos web SEO (GSC); 4 CRM y ventas. No publicar públicamente PII.

## Criterios orientativos de acción (NO benchmarks de la industria)
- Muchas impresiones, bajo CTR vs tus propios vídeos similares → investigar título/miniatura de esa fuente y promesa.
- Buen CTR, salida fuerte primeros 30 s → mejorar claridad/intro, no prometer menos de lo que muestra.
- Muchos clics HTML, casi ninguna respuesta al reto → simplificar instrucciones o pedir un ejercicio de menor esfuerzo.
- Buenas vistas Shorts, pocas visitas al largo → revisar conexión `related video` y puente temático; no concluir éxito por vistas Shorts.
- Muchos registros pero poca interacción → reducir número de canales GHL, onboarding simple y guías.
- Posts no indexadas → revisar valor, HTTP, canonical, sitemap, enlaces internos; Google no garantiza indexación.
- Ventas atribuidas a anuncios Meta vs fuentes YouTube → contabilidad separada con UTM y fuentes; incertidumbre de atribución.

## Reunión editorial fija de 30 minutos (semanal)
- 5 min: datos en 4 capas. 5 min: comentario real de principiante. 5 min: diferencia de valor del HTML. 5 min: estado de SEO. 5 min: coste del proceso. 5 min: decisión `seguir / ajustar / pausar`, responsable y fecha.

## Revisión estratégica 30, 60 y 90 días
- **D30:** comprobar tutorial #001 fácil, live habilitado, CTA, primera indexación (o diagnóstico honesto).
- **D60:** dos Radar, biblioteca y comunidad con señales de actividad; segmentación y email no invasivos.
- **D90:** decidir segunda temporada, coste por episodio, abrir o no membresía, activar o no reportaje de resultados según evidencias y revisar requisitos YPP 2027.

## Fuentes
YT Analytics: https://support.google.com/youtube/answer/9314416 ; YPP: https://support.google.com/youtube/answer/94522 ; Google Search Console: https://developers.google.com/search/docs/monitor-debug/search-console-start ; GHL Communities: https://help.gohighlevel.com/support/solutions/articles/155000000280-how-to-setup-customize-and-manage-your-communities

## Adenda v3: de atención a economía
A las cuatro capas base se agrega **una quinta vista comercial** SOLO para leads que pidieron ayuda avanzada: solicitudes expresas → reservas → asistencia → ventas cobradas y reembolsos. No sumar como oportunidades a todos los alumnos gratuitos. Medir first/latest touch con dudas de atribución, costes/horas reales, y canales de ingresos por separado. Ver `16_ECONOMIA_DEL_ECOSISTEMA_Y_MONETIZACION.md` y plantilla `plantillas/03_SCORECARD_SEMANAL.md`.


## Medición adicional V3.5
SEO: consultas/impresiones/clics por URL en Search Console de cada host real, no contar 30 páginas creadas si solo existe un hub. Embudo: clic del hub→YouTube, visualización→recurso, email opt-in→uso, comunidad activada a 7 días→reto, consulta avanzada→Etics. Registrar `PENDIENTE` donde no existan datos verificables.
