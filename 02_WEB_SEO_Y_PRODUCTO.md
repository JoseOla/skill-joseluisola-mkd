> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.


> **ACTUALIZACIÓN V3.4 (prioridad máxima):** El usuario prefiere un único hub `www.joseluisola.com/aprende` en el hosting actual (si lo permite el editor real), con vídeos alojados en YouTube y playlists enlazadas/incrustadas, **sin crear un post/landing por vídeo**. `aprende.joseluisola.com` y una web nueva GHL quedan como alternativas, no la solución predeterminada. GHL se utiliza para CRM, newsletter, laboratorios, comunidad y Cénit. Antes de proponer el subdominio anterior, consultar `32_DECISION_SIMPLE_YOUTUBE_BLOG_POST_URL_APRENDE.md`. H1 elegido: «No necesitas una agencia de 20 para empezar a vender con IA». NO alterar DNS ni sitio de producción automáticamente.

# Arquitectura web indexable en GHL: joseluisola.com como biblioteca y herramienta educativa

## 0. Decisión SEO y límites reales
**Sí conviene**, porque el activo público debe ser tu dominio personal; complementa YouTube y captura búsquedas de «cómo hacer...» sin depender únicamente del algoritmo de vídeo. **PERO** GHL no debería reemplazar el sitio público existente sin antes confirmar dónde está alojado y si la migración es segura. Para los primeros 90 días, priorizar una biblioteca con GHL Websites/Blog si tu dominio ya está correctamente conectado; si no, instalar en staging/subdominio y migrar con plan. El área privada de la comunidad se ofrece en `comunidad.eticsacademy.com` (nombre de subdominio **propuesto**), no indexar su contenido de pago ni copiar transcripciones en páginas privadas como sustituto del SEO público.

## 1. Observación de Borja Girón (comparación sin exagerar)
En **https://borjagiron.com/podcast/** observamos un **archivo de podcast** con lista paginada, filtro/buscador de entradas y categorías visibles de aprendizaje: «Empieza desde 0», «Más visitas», «Más participación» y «Más ventas». También ofrece enlaces a newsletters y recursos. Eso da pistas útiles: inventario evergreen, categorización por problemas y oferta editorial relacionada. **No se confirmó** que tenga buscador de texto dentro de todas las transcripciones con salto al segundo exacto. Por tanto: replicar de entrada archivo/blog y filtros; desarrollar búsqueda de pasajes solo después de probar su necesidad.

## 2. Menú ideal y rutas que proponemos
**No prometer estas URLs exactas:** la función Blog GHL puede imponer slugs (`/b/<slug>` y variantes) según dominio/configuración. Son objetivos funcionales; validarlos en la subcuenta antes de escribir redirecciones.

| Página / slug deseado | Acceso | Contenido | CTA principal |
|---|---|---|---|
| `/` | Público | Promesa para principiantes + selector «Nunca usé IA / ya la uso / quiero Cénit» | Empezar clase gratuita |
| `/empieza-aqui/` | Público | Ruta guiada niveles 0 a 3, primer vídeo, instrucciones sin jerga | Completar reto 1 |
| `/aprende/` | Público | Blog GHL de guías y fichas de episodios, buscador nativo, categorías | Ver clase + recurso |
| `/episodios/` | Público | Landing índice curado en GHL con lista de episodios y accesos al blog | Reproducir episodio |
| `/radar/` | Público | Calendario próximo live, replay, ediciones | Activar recordatorio |
| `/guias/` | Público | Índice evergreen de dudas prácticas, enlazado al blog | Abrir guía |
| `/herramientas/` | Público | Catálogo HTML para descargar en Chrome | Descargar plantilla |
| `/brujula/` | Público | Suscripción y ediciones con backlinks internos | Suscribirse |
| `/comunidad/` | Público | Beneficios y acceso a GHL Comunidad gratis | Registrarse |
| `/casos/` | Público | Diagnósticos consentidos / simulaciones muy bien rotuladas | Ver análisis |
| `/sobre-mi/` | Público | Experiencia, metodología, credenciales verificables, políticas | Conocer a José |
| `comunidad.eticsacademy.com` | Login | Comunidad + Learning de GHL + retos y alumnos | Completar clase |
| `eticsacademy.com` | Público venta | Método Cénit avanzado, webinar, precios, condiciones | Comprar / asistir |

**URL final de cada episodio:** al iniciar será un **post del blog GHL** con título, vídeo incrustado y material útil. Desde la landing `/episodios/` enlazar al post real (probablemente ruta definida por GHL). NO forzar `/episodios/slug` si GHL no lo admite.

## 3. Plantilla para cada página de episodio (SEO y persona principiante)
1. Ruta/migas: Inicio > Aprende > Nivel 0 > Tema.
2. H1 centrado en pregunta real («Cómo pedirle a ChatGPT que te escriba un mensaje de WhatsApp»).
3. Subtítulo nivel, fecha de revisión, tiempo del vídeo y qué podrá hacer hoy.
4. Vídeo de YouTube visible cerca del primer scroll, un único vídeo principal.
5. Bloque de «Antes de comenzar» con términos definidos y material necesario.
6. Los **5–7 pasos resumidos** en texto original; fotos/capturas propias y texto alternativo.
7. Tabla de diferencias entre herramientas si se comparan (precios solo con fecha verificada).
8. Errores frecuentes y cómo solucionarlos.
9. Capítulos y **transcripción corregida** (si el post lo permite sin contenido oculto para bots); enlazar a tiempo real en YouTube.
10. Ejercicio de 10–15 minutos y HTML descargable del capítulo; informar si funciona offline.
11. Preguntas frecuentes basadas en dudas reales; no inventar reseñas ni FAQs falsamente preguntadas.
12. «Qué viene después» → capítulo siguiente, Radar o comunidad GHL gratuita.
13. CTA avanzado separado, discreto: «¿Ya manejas clientes y anuncios? Conoce Cénit».

## 4. Cómo construir en GHL, paso a paso y sin romper lo existente
**Antes de tocar DNS (día 1):** 1) determinar si joseluisola.com está alojado en GHL o en otro proveedor; 2) exportar/preservar HTML/copy, imágenes, formularios, estadísticas y listado completo de URLs con títulos; 3) revisar DNS y registros de correo SPF/DKIM/DMARC; 4) comprobar canonical actual www/no-www, SSL, robots.txt/sitemap, 404; 5) abrir entorno de pruebas. No cambiar A/CNAME/MX a ciegas.

**Ruta A, sitio ya en GHL:**
1. GHL subcuenta → `Sites > Websites` (o Funnels existentes). Crear o modificar páginas públicas conservando homepage.
2. `Sites > Blogs > Create Blog`; configurar título **Aprende IA y Ventas con José Luis Ola**, dominio y slug real; categorías: `Empieza desde 0`, `Prompts útiles`, `IA para WhatsApp`, `Creativos y Canva`, `Radar IA`, `Ventas y seguimiento`, `Camino a Cénit`.
3. Editar plantilla de blog y posts; activar buscador nativo del blog y navegación por categorías donde estén disponibles.
4. Para cada post: URL slug, categoría, autor, SEO title, meta description, imagen+alt, canonical correcto, vídeo, texto propio, recurso y enlaces a contenido relacionado.
5. Insertar Blog Post List donde corresponda y enlazar `/episodios/` a las fichas publicadas.
6. `Sites > Domains` o configuración de dominios: localizar sitemap y añadir entradas relevantes; generar/publicar sitemap según opciones reales de la cuenta (GHL puede actualizarlo tras publicar posts).
7. Probar URL anónima móvil, indexabilidad, tamaño de fuente, vídeo y formularios.

**Ruta B, sitio NO alojado en GHL:** no rehacerlo sin diagnóstico. Crear en staging/subdominio o migrar después de demostrar una primera página. Si optas por un subdominio público (`aprende.joseluisola.com`) tendrá identidad y seguimiento propios; preferible una ruta del dominio principal si la arquitectura lo permite. Preservar URLs originales y aplicar 301 individual por cada URL cambiada.

### Qué sí admite GHL según documentación oficial (octubre 2026)
- Blog y posts con campos SEO, slug, canónica, categorías y elemento de listado.
- Buscador nativo de **posts del blog** y navegación de categorías.
- Sitemap automático del blog, generado desde opciones del dominio.
- Campos y metaetiquetas para webs/funnels.

### Qué NO doy por hecho
- Búsqueda «muéstrame dónde dijo en el minuto 13:42 ...» **en todas las transcripciones**: requiere índice de texto segmentado con tiempos, validación de UI y posiblemente back-end externo.
- Generación en una acción de todo el portal mediante prompt: GHL puede asistir en contenido/diseño, pero configurar páginas, automatizaciones, redirecciones, SEO y permisos exige acciones y pruebas manuales.
- SEO garantizado por insertar un vídeo de YouTube: indexar una página requiere contenido accesible y útil, no solo un iframe.

## 5. Buscador: dos niveles
**MVP 0–90 días:** buscador nativo GHL Blogs (títulos/contenido según implementación) y filtro por categorías. Etiquetar «Buscar clases»; comprobar qué campos busca de verdad con al menos 5 posts y búsquedas de prueba, no atribuirle salto a segundos.

**Fase 2, si se demuestra demanda:** índice transcript por fragmentos `{episode_id,start_seconds,speaker,text,source_url}` y motor que busque texto, devuelva `fragmento + minuto`, y enlace `youtube.com/watch?v=ID&t=SECONDSs`; considerar servicio externo ligero/JSON estático o búsqueda alojada. Páginas individuales públicas canónicas, no crear miles de URLs finas autogeneradas para posicionar. Controlar seguridad y privacidad.

## 6. Indexar el dominio en Google: receta de 0 a 100
0. Aclaración: **Google no exige registro para poder aparecer**, pero Search Console da visibilidad. Indexación ≠ primeros puestos.
1. Entrar en **Google Search Console**, crear **propiedad de DOMINIO** `joseluisola.com` y `eticsacademy.com` por separado; si se requiere, añadir propiedad URL-prefijo para depurar.
2. Verificar control por registro DNS **TXT** en proveedor del dominio (no eliminar SPF, MX u otros registros). Esperar propagación y verificar.
3. Revisar `/robots.txt`, URL sitemap real generado y `/sitemap.xml` si corresponde. Un sitemap no debe incluir URLs redirigidas, privadas, `noindex` o error 404.
4. Usar Search Console `Sitemaps` → añadir URL exacta del sitemap; comprobar si es accesible sin iniciar sesión y el estado de procesamiento.
5. En `Inspección de URL`: colocar home y post publicado → verificar indexabilidad, canonical, `200 OK`, estado de rastreo; usar «Probar URL publicada» y «Solicitar indexación» cuando proceda.
6. Comprobar `<title>`, `<meta name=description>`, H1, `canonical`, enlaces HTML `<a href>` reales, `alt`, transcripción texto y velocidad móvil. No depender de JS para que aparezca todo.
7. Añadir `VideoObject` JSON-LD **solo con valores auténticos** de vídeo (título, miniatura, fecha, embed URL); usar Rich Results Test y el informe de vídeo de Search Console.
8. Conectar GA4 y eventos vía GHL/Google Tag Manager conforme a consentimiento; separar visitas del blog de la comunidad privada.
9. Crear enlaces desde homepage, `/empieza-aqui/`, listas por nivel y newsletter; enlazar siempre al vídeo original en YouTube.
10. Cada semana publicar el episodio con guía única; revisar indexación/queries en Search Console a 7/30 días; actualizar guía cuando cambia herramienta.
11. Medir impresiones y clics Google, no confundir `site:dominio` con reporte completo; no insistir en solicitar indexación diaria.
12. Si una página no entra en el índice, revisar primero valor propio, canónica, duplicados, HTTP, noindex, enlazado interno y que no esté oculta por login.

**Tiempo esperado:** variable e incierto, no prometer que indexará en 48 horas ni que superará a blogs establecidos.

## 7. Datos estructurados mínimos (plantilla; nunca publicar con placeholders)
```html
<script type="application/ld+json">
{
 "@context":"https://schema.org",
 "@type":"VideoObject",
 "name":"TÍTULO REAL Y VISIBLE",
 "description":"DESCRIPCIÓN REAL VISIBLE",
 "thumbnailUrl":["URL_ABSOLUTA_REAL_DE_MINIATURA"],
 "uploadDate":"FECHA_REAL_ISO8601",
 "embedUrl":"https://www.youtube.com/embed/ID_REAL",
 "mainEntityOfPage":"URL_FINAL_CANÓNICA_REAL"
}
</script>
```
No añadir `BroadcastEvent` a cada VOD como si siguiera vivo; en directos comprobar reglas específicas. Validar en Google Rich Results Test y revisar resultados. Un snippet no indexa por sí solo.

## 8. Diseño UX 30–55
- Contraste WCAG, tipografía cuerpo ≥16px, títulos claros, botones grandes y texto simple.
- Un solo CTA principal por pantalla; volver al índice fácil y ruta «Nunca he usado IA» visible.
- Subtítulos, velocidad de reproducción, capturas legibles para móvil, transcripción disponible.
- Contenido accesible sin registro como mínimo para comprender cada episodio.
- Para HTML descargable ofrecer explicación «es un archivo que abres con Chrome, funciona sin instalar nada» y alternativa web si muchos acceden desde móvil.

## 9. SEO editorial semanal
Por cada vídeo: keyword principal de intención («cómo escribir una respuesta en ChatGPT para WhatsApp»), 5 preguntas concretas, título fiel, miniatura contrastada, 1 página con ≥3 aportes que el vídeo solo no cubre (pasos, fotos, problemas comunes), transcript revisado, 2 links internos pertinentes, HTML opcional, fecha actualizada. Evitar duplicar transcripción en otras URLs indexables y artículos AI masivos sin utilidad.

## 10. Fuentes verificadas
- Google Search Console: https://developers.google.com/search/docs/monitor-debug/search-console-start
- Google VideoObject: https://developers.google.com/search/docs/appearance/structured-data/video
- Google video SEO: https://developers.google.com/search/docs/appearance/video
- HighLevel Blogs: https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs
- HighLevel Blog Search: https://help.gohighlevel.com/support/solutions/articles/155000002452-how-to-add-blog-search-and-category-navigation-
- HighLevel Sitemap: https://help.gohighlevel.com/support/solutions/articles/155000002453-how-to-add-blog-sitemap-
- HighLevel SEO blog: https://help.gohighlevel.com/support/solutions/articles/48001220287-how-to-add-and-edit-seo-information-for-blog-posts
- Borja Girón: https://borjagiron.com/podcast/

**Prompt integral listo para copiar y pegar:** `08_PROMPTS_GHL_COPIAR_PEGAR.md`.

## Adenda v3: «una captura» no implica «una URL»
El hub público de captura (`/empieza` o URL segura existente) será la **puerta común de formulario y UTM** para vídeos, Radar, newsletter, SEO y colaboraciones. Las páginas de episodio y blog seguirán siendo URLs originales e indexables con enlaces hacia el hub; NO canonicalizar todas al hub ni hacer redirección masiva. El destino de compra directa avanzada **Etics Academy** se conserva. El mapa del formulario/segmentación está en `13_EMBUDO_SIMPLE_GHL_Y_CALIFICACION.md`; los prompts GHL en `18_PROMPTS_GHL_CUALIFICACION_Y_PRECALL.md`.

## Actualización de arquitectura y SEO V3.3 (PRIORIDAD sobre migración anterior)
La web actual `joseluisola.com` sigue en GoDaddy. **No reemplazarla, no redirigirla y no cambiar `@`/`www`**. El sitio web educativo nuevo y blog nativo GHL se publicarán **solo cuando estén listos**, con subdominio `aprende.joseluisola.com`. Por eso **no se garantizan rutas de raíz** como `/episodios/` en el sitio de GoDaddy: se configuran dentro del sitio/subdominio nuevo y se respetan URLs finales que asigne GHL. Una única versión en español. SEO nuevo a través de Google Search Console y sitemap del subdominio.
- Antes de publicar: formulario de Brújula real, EP001, HTML/ZIP, canonical propio y eliminación del `noindex` de staging.
- La búsqueda nativa de GHL Blog debe probarse; el buscador por fragmentos con salto al segundo es un proyecto custom posterior.
- Guías evergreen diferenciadas de resúmenes de Brújula; evitar contenido casi idéntico.
- Home nuevo muestra “últimas clases” mediante tarjetas manuales o Blog Post Element que toma **posts GHL publicados**, no actualización automática por subir a YouTube.
Guía operativa: `27_MANUAL_PASO_A_PASO_GHL_SIN_PERDERSE.md`, sitemap progresivo `28_...`, plantilla `26_...` y riesgos `29_...`.


## Especificación que prevalece sobre el modelo anterior de biblioteca de episodios
**No exigir fichas ni transcripciones individuales por cada vídeo.** La opción adoptada para el emprendedor sin equipo es `/aprende` con texto editorial por niveles, links a playlists, un vídeo inicial incrustado y 3 destacados. SEO propio = indexar el hub + guías selectivas. GHL Blog Post solo se usa para publicaciones voluntarias, NO para capturar YouTube. Consultar `34_INDEXACION_EN_GOOGLE_GHL_PASO_A_PASO.md` y `35_RUTAS_SUBDOMINIO_DNS_GODADDY_GHL_EXPLICADO.md`.
