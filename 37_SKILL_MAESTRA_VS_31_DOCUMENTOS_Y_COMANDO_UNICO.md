# 37 · Arquitectura de skill: UN COMANDO y un paquete completo, sin meter 31 manuales en el prompt
**Decisión V3.5:** elegir **skill maestra compacta (orquestador) + referencias especializadas + índice de documentos contextuales**. No copiar/pegar 31 manuales en cada instrucción. Tampoco hacer una skill pequeña que obligue al usuario a ejecutar 18 módulos manualmente.

## Por qué este modelo es mejor para el usuario sin equipo
**El usuario escribe SOLO:** `PAQUETE_TOTAL | TÍTULO: Cómo usar ChatGPT para responder clientes desde cero | NIVEL: 0`
La skill identifica el modo PAQUETE_TOTAL, revisa su configuración fija y abre las referencias necesarias según el encargo. Una sola petición genera un **documento maestro** y, cuando el entorno permite guardar archivos, carpeta de entregables separados. No invoca recursos externos automáticamente ni obtiene métricas privadas si no hay acceso real.

## Capas técnicas (una sola fuente de verdad por decisión)
- `SKILL.md`: reglas fundamentales, modos, orden, precedencia, interfaz unificada.
- `references/01...20`: instrucciones especializadas por dominio; leer **solo las necesarias**.
- `context/00,01,05,32,34,35,36,37,38...`: decisiones y manuales operativos, bajo demanda. Los restantes documentos 02–33 son bibliografía/procesos y NO se cargan en cada vídeo.
- `plantillas/`: formato de entregables. **No prometer adjuntos inexistentes** ni meter textos genéricos por llenar espacio.
- `salidas/<slug>/`: paquete por vídeo generado a demanda (propuesta; la ejecución requiere herramienta de creación de archivos).

## Modos compatibles
- `PAQUETE_TOTAL`: produce todos los bloques aplicables (guion, shorts, newsletter, imagen conceptual de miniatura, SEO, ejercicio, comunidad, métricas y fuentes). Radar únicamente si el tema es noticia relevante; no generar live ficticio por obligación.
- `CLASE`: guion y materiales pedagógicos.
- `RADAR`: investigación actual, contraste de fuentes, guion directo, recortes y actividad.
- `SEO`: título, capítulos reales cuando haya vídeo final, descripción, playlists, portada y página hub mínima.
- `GHL`: instrucciones no destructivas, DNS/indexación y seguimiento.
- `REVISION`: evaluar resultados si el usuario facilita exportaciones; no simular métricas.

## Entregables de PAQUETE_TOTAL (en un único documento o archivos)
1. Ficha editorial: título candidato, keyword/intención, público y nivel, problema, resultado esperado, fuentes actualizadas y hechos no comprobados.
2. 3 opciones de título útiles (señalar favorito), 3 conceptos de miniatura con texto corto, guion completo 15–18 min **mediante demostración viable** y apoyo audiovisual.
3. Descripción optimizada YouTube + capítulos **propuestos** (no publicar tiempos hasta grabar) + enlaces como `PENDIENTE DE URL REAL` si no existe + playlist/nivel.
4. Tres Shorts propios: hook, guion, tomas, CTA al vídeo largo, subtítulos recomendados.
5. Brújula (modalidad editorial o Lab), asunto, CTA educativo y ejercicio de comunidad; **no forzar lead magnet nuevo cada semana**.
6. Recurso HTML para Chrome **solo cuando es útil y el usuario lo desea**; especificación y archivo funcional si el entorno puede generarlo. Si ya existe un HTML, enlazar/reutilizar antes de inventar otro.
7. Bloque mínimo para `/aprende`: título, nivel, resumen de dos frases, thumbnail y URL (sin landing individual). Posible guía SEO **solo** si lo justifican búsquedas y tiempo.
8. Registro de métricas y experimento 7/30 días, estimación de esfuerzo, QA de hechos/compliance, CTA a Cénit condicionado a nivel e intención.
9. Checklist de publicación, tareas mínimas «copiar/pegar», estado `LISTO/REVISAR/PENDIENTE`.

## Reglas duras para la generación integral
- Si solo se da título, construir propuestas adaptadas, **no fingir que se verificó la pantalla exacta de una aplicación ni que existe vídeo publicado**.
- Usar una fuente real de UI/cambios (web si disponible) cuando la interfaz importa. Herramientas, precios, límites pueden cambiar.
- No inventar transcripción real, marcas de tiempo exactas, estadísticas, conversiones, ROI ni URLs del canal.
- Incluir contenidos finales completos para los componentes pedidos, no solo esquemas, **pero** evitar 30 páginas de relleno; el usuario puede escoger `PAQUETE_TOTAL BREVE` o `PAQUETE_TOTAL PROFUNDO`.
- En un vídeo para nivel cero, no pedir teléfono, ingresos ni presupuesto publicitario para descargar recursos.
- Señalar cuándo una automatización comercial requiere consentimiento y recursos técnicos no configurados.
- Al finalizar, entregar un resumen de 1 página con **orden de ejecución** y archivos realmente creados.

## Cómo iniciar
Ver `38_COMANDO_UNICO_PRODUCCION_YT_COPIAR_PEGAR.md`, `39_PLANTILLA_ENTREGABLE_PAQUETE_TOTAL.md` y en la skill el **MODO PAQUETE_TOTAL**. Para implementar correctamente con archivos, el agente debe tener acceso al kit y capacidad de escritura, y se le debe solicitar generar archivos locales/adjuntos.
