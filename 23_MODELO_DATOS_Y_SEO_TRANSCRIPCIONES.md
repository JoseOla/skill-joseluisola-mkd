> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.


> **ACTUALIZACIÓN V3.4 (prioridad máxima):** El usuario prefiere un único hub `www.joseluisola.com/aprende` en el hosting actual (si lo permite el editor real), con vídeos alojados en YouTube y playlists enlazadas/incrustadas, **sin crear un post/landing por vídeo**. `aprende.joseluisola.com` y una web nueva GHL quedan como alternativas, no la solución predeterminada. GHL se utiliza para CRM, newsletter, laboratorios, comunidad y Cénit. Antes de proponer el subdominio anterior, consultar `32_DECISION_SIMPLE_YOUTUBE_BLOG_POST_URL_APRENDE.md`. H1 elegido: «No necesitas una agencia de 20 para empezar a vender con IA». NO alterar DNS ni sitio de producción automáticamente.

# 23 · Modelo de datos, SEO y transcripciones para José Luis Ola — v3.3
**Solo español · sin traducción, `hreflang` ni rutas por idioma.** El URL definitivo del episodio lo determina la configuración real del Blog GHL en el subdominio nuevo.

## Contrato editorial (no es un objeto que GHL acepte automáticamente)
```json
{
  "id": "EP001",
  "estado": "borrador",
  "idioma": "es",
  "tipo": "clase",
  "nivel": 0,
  "tituloReal": null,
  "slugGHL": null,
  "urlCanonicaReal": null,
  "fechaPublicacion": null,
  "youtubeIdReal": null,
  "duracionSegundos": null,
  "miniaturaAutorizada": null,
  "objetivo": "UNA TAREA OBSERVABLE",
  "resumenOriginal": null,
  "participantes": [],
  "temas": [],
  "referencias": [],
  "capitulos": [],
  "transcripcionCorregida": [],
  "urlRecursoHtmlZip": null,
  "urlSiguientePublicado": null,
  "autorizaTranscripcion": false,
  "seo": {"title": null, "description": null, "canonical": null}
}
```

## Estructura HTML SEMÁNTICA (concepto de bloques GHL, no pegar documento entero)
`<main><article><header>` ficha/H1/nivel `</header>` → `<section>` vídeo YouTube embed → `<section>` resumen → `<section>` guía con `<ol>` → `<nav>` capítulos → `<section>` herramienta/ZIP → `<section>` transcripción corregida con timestamps → `<aside>` fuentes → `<nav>` siguiente/Brújula → `</article></main>`. Asegurar `lang="es"`, orden H1→H2→H3, links navegables y `<title>` SEO. Contenido real y original.

## Clip links, no falsas funciones
Capítulos con enlaces `https://www.youtube.com/watch?v=ID_PUBLICO&t=90s` solo para ID de vídeo real y tiempo comprobado. **GHL Search** busca posts (sujeto a pruebas); no equivale a buscar cada segundo de transcripción. Si se necesita más adelante, índice adicional `{idVideo, inicioSegundos, hablante, textoCorregido}` con motor custom indexable sólo si corresponde.

## VideoObject mínimo (plantilla NO publicable hasta completar)
```html
<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "VideoObject",
 "name": "TITULO_REAL",
 "description": "RESUMEN_REAL",
 "thumbnailUrl": ["URL_ABSOLUTA_REAL"],
 "uploadDate": "FECHA_ISO8601_REAL",
 "embedUrl": "https://www.youtube.com/embed/ID_REAL",
 "mainEntityOfPage": "URL_CANONICA_REAL_GHL"
}
</script>
```
Solo implementar JSON-LD si la plantilla/sitio GHL permite insertar código; según FAQ actual el editor de blog posts no admite código personalizado. Validar en Google Rich Results Test y GSC; rich result no garantizado. Fuentes Google: https://developers.google.com/search/docs/appearance/structured-data/video y https://developers.google.com/search/docs/appearance/video

## QA al publicar
Vídeo público propio, derechos transcripción, título/meta reales, enlaces sin 404, ZIP/HTML seguro, consentimientos, URL final a subdominio, sitemap, móvil y ruta siguiente. Ver modelo de ficha extensivo `26_ARCHIVO_EPISODIOS_Y_FICHA_COMPLETA_TIPO_ITNIG.md`.


## Simplificación V3.5
El modelo de datos de episodio individual se conserva como **capacidad futura**, no requisito de producción. El MVP del hub usa: id YouTube, título, playlist por nivel, miniatura, 2 frases descriptivas, CTA a vídeo y recurso. Tiempo de capítulos se registra en YouTube tras grabación. Google solo puede indexar páginas propias existentes (hub/guías selectivas).
