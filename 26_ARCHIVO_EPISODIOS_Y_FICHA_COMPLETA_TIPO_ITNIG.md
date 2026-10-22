> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.


> **ACTUALIZACIÓN V3.4 (prioridad máxima):** El usuario prefiere un único hub `www.joseluisola.com/aprende` en el hosting actual (si lo permite el editor real), con vídeos alojados en YouTube y playlists enlazadas/incrustadas, **sin crear un post/landing por vídeo**. `aprende.joseluisola.com` y una web nueva GHL quedan como alternativas, no la solución predeterminada. GHL se utiliza para CRM, newsletter, laboratorios, comunidad y Cénit. Antes de proponer el subdominio anterior, consultar `32_DECISION_SIMPLE_YOUTUBE_BLOG_POST_URL_APRENDE.md`. H1 elegido: «No necesitas una agencia de 20 para empezar a vender con IA». NO alterar DNS ni sitio de producción automáticamente.

# 26 · Archivo de episodios y ficha de cada vídeo (inspiración funcional Itnig, sin copiar)
**Versión 3.3 | No es una extracción de código propietario**

## A. Archivo de episodios: una biblioteca segura y útil
Itnig ofrece un archivo de cientos de episodios con **campo de búsqueda**, **filtro por tipo**, fecha, título y acceso a una página individual. Nosotros vamos a empezar con **UNO a TRES episodios reales**, sin simular un catálogo de cientos. La presencia de un archivo en la web no obliga a llenar veinte casillas vacías.

### Esqueleto de `/episodios/` (URL en el subdominio)
```
[HEADER] Marca José Luis Ola | Empieza aquí | Aprender | Radar | Herramientas | Brújula | Comunidad
[BREADCRUMB] Inicio > Episodios
[H1] Clases y episodios para aprender IA desde cero
[ENTRADA] Busca lo que necesitas resolver hoy: mensajes, atención, ideas, clientes.
[BUSCADOR] "Buscar clases" (activar buscador nativo GHL y PROBAR su alcance real)
[FILTROS] Nivel 0 · Ventas cotidianas · Prompts · Diseño · Organización · Radar
[FICHA DESTACADA] Vídeo reciente real: miniatura, título, resultado, dificultad, duración
[TARJETAS] Publicaciones reales existentes, orden nuevas primero (sin placeholders públicos)
[BLOQUE] ¿Es tu primera vez? -> Empieza aquí
[CTA BRÚJULA] Recibe el ejercicio de cada semana (opt-in voluntario)
[FOOTER] Políticas / Etics avanzado / contacto
```
**Metadatos de cada tarjeta:** `thumbnail con alt`, `título`, `nivel`, `tarea`, `fecha`, `duración` (si se verificó), `tipo` (Clase/Radar), `Ver clase y transcripción`. Solo etiquetas cuya fuente sea verdadera. Colocar buscador después de 3–5 episodios si las pruebas son suficientes; con uno puede mostrar solo una tarjeta y una guía de inicio sin el contador.

### Controles editoriales para un catálogo pequeño
- 1 episodio: título `Biblioteca de clases`, una tarjeta publicada + CTA “Empieza por aquí”; ocultar campos de búsqueda vacíos/filtros con 0 resultados.
- 2–5 episodios: habilitar categoría `Nivel 0` y botón `Ver todas las clases`. Considerar buscador nativo si supera pruebas.
- 6–15: desplegable `Nivel`, `Temática` y búsqueda real. Si la UI de GHL no soporta filtros combinados, NO simularlos; usar una navegación por categorías y buscador independiente.
- 16+: explorar buscador por fragmentos de transcripción **solo si** la búsqueda actual no resuelve preguntas y hay demanda medida.

## B. Página individual de episodio: estructura completa
Lo observado en Itnig: vídeo incrustado, enlace al original, fecha, título, descripción, duración, contador de participantes/temas/referencias cuando corresponde, pestañas/anchors, secciones de participantes, temas con tiempos, entidades mencionadas y transcripción extensa con enlaces a instantes; búsqueda textual de la transcripción y episodios relacionados. **No copiar CSS/JS/HTML de Itnig**. Diseñar estructura propia, priorizando primer contacto educativo.

### Plantilla de URL
`https://aprende.joseluisola.com/[RUTA_REAL_DE_BLOG_CONFIGURADA_POR_GHL]/[SLUG_REAL]`
*La ruta final se obtiene del constructor/blog de GHL; no prometer `/episodios/slug` si el blog usa otra estructura.*

### Plantilla editorial completa (MVP)
1. **SEO Head:** `<title>` único, meta descripción, canonical absoluto propio, OG básico, `lang="es"`, imagen real; `VideoObject` únicamente si datos reales **y la plantilla/sitio GHL permite incorporarlo**, porque editor de blog post no garantiza código personalizado.
2. **Header + breadcrumbs** a `Inicio > Aprender IA > Nivel 0 > [Clase]` (sin rutas inexistentes).
3. **Ficha compacta**: `Clase 001 | Nivel 0 | 16 min [verificados] | Última actualización: fecha real`.
4. **H1** promesa específica: `Cómo escribir tu primer mensaje de venta con ChatGPT desde cero`.
5. **Introducción / resultado**: a quién ayuda, lo que logrará, requisitos (móvil/PC), tiempo estimado honesto, versiones gratis/de pago necesarias.
6. **Vídeo YouTube** con el elemento de vídeo GHL, o iframe permitido, miniatura correcta, sin autoplay intrusivo, subtítulos disponibles; botón `Ver en YouTube`.
7. **Ruta dentro del vídeo**: 00:00 qué haremos · 01:45 pantalla inicial · 05:30 primer prompt · 10:10 variaciones · 14:30 ejercicio. **Capítulos reales, no inventados**; enlaces con `&t=segundos` a YouTube.
8. **Resumen original** de 100–250 palabras (no pegar una transcripción repetitiva como artículo completo).
9. **Guía de ejecución**: pasos numerados, capturas originales cuando sea necesario, errores frecuentes, privacidad y verificación del resultado.
10. **Comparativa opcional**: alternativa Copilot/Claude, gratuita/pago y límites según verificación a fecha de publicación.
11. **Laboratorio de Chrome**: contexto, qué datos introduce, si funciona sin internet, botón descargar `.zip` o archivo que el hosting admita, enlace de ayuda, política de no recopilar datos cuando aplique.
12. **Transcripción revisada**: texto accesible, encabezados, altavoz cuando haya más de una persona; marcas de tiempo reales; “Buscar en esta transcripción” solo si hay buscador realmente operativo.
13. **Fuentes y referencias**: documentación primaria de herramientas, actualización y enlaces afiliados identificados, si los hay.
14. **Pregunta de participación** para comunidad o comentarios sin datos sensibles: `¿Qué mensaje probaste? Comparte un ejemplo anonimizado`.
15. **Continuar aprendiendo**: módulo anterior y siguiente **publicados**; si siguiente aún no existe, enlace a `/empieza-aqui/`, no `#` ni 404.
16. **Brújula**: CTA al formulario opt-in en **página independiente GHL** o componente global probado, porque el editor de Blog Post consultado **no admite incrustar Forms/Surveys dentro del post**; la descarga del ZIP no equivale al consentimiento para marketing.
17. **Mini-bloque Cénit** opcional **solo si** el nivel del episodio justifica formación avanzada; nunca eclipsar la actividad nivel cero.
18. **Footer/legal**: responsable, privacidad, cookies, contacto, términos y aviso de afiliación vigente.

### Bloques avanzados (NO necesarios en primera publicación)
- **Personas participantes**: biografía consensuada, contribución, empresa y recursos. En clases solo José no mostrar bloque artificial “1 participante”.
- **Temas**: índice de conceptos con enlace al minuto.
- **Herramientas y referencias citadas**: listado enlazado y explicación, sin afirmar afiliación inexistente.
- **Buscador dentro de transcripción**: necesita prueba de motor o JavaScript cuidadosamente desarrollado; NO confundir con buscador del blog.
- **Notas/correcciones**: sección “Actualizado en …; función de IA cambió …”, sin reescribir engañosamente el vídeo antiguo.
- **Descarga SRT** solo si el archivo es propio/revisado y sin datos sensibles.
- **Episodios relacionados**: reglas manuales por nivel/tarea y no solamente más recientes.

## Seguridad legal/editorial
- Publicar **solo transcripciones de vídeos propios o de terceros con licencia/autorización**; enlazar vídeos ajenos no otorga derechos para republicar su transcripción completa.
- Revisar nombres, emails, chats, pantallas de CRM, credenciales, números de clientes y contactos antes de subir vídeo/transcripción/capturas. Evitar datos reales de clientes en demos.
- No inventar número de episodios, resultados de alumnos, duración, participantes o testimonios. No reutilizar portada de Itnig, logos o fotos no autorizadas.
- No publicar un script que extraiga transcripciones de YouTube sin respetar derechos, permisos y condiciones de uso de APIs/servicios.
- Enlaces externos `target="_blank"` con `rel="noopener noreferrer"` al usar HTML propio; los editores gestionan enlaces según sus controles.
- Para páginas indexables: no bloquear por login, una sola canonical real, evitar duplicidad entre “guía”, “episodio” y “Brújula”.
- Herramientas HTML offline: no incluir scripts de terceros ni claves secretas; si GHL no permite servir `.html` como descargable, ofrecer `.zip` verificado o enlace a alojamiento estático de descarga con cabeceras correctas.

## Ejemplo de ficha para completar antes de publicar
```
ID EP001, ESTADO BORRADOR
Nivel: 0 | tipo: clase | categoría: Primeros pasos
YouTube ID: [pendiente] | título real: [pendiente] | URL GHL: [pendiente]
Qué sabrá hacer: [una tarea] | herramienta: [principal] | alternativa: [si conviene]
Duración: [verificar] | fecha publicación: [verificar] | capítulo(s): [verificar]
Transcripción: [edición revisada] | permiso: [propio/autoriza]
HTML: [archivo real] | envío newsletter consentido: [sí/no]
Artículos relacionados: [solo URLs existentes] | siguiente: [publicado o a /empieza-aqui/]
QA: video/embed, SEO, accesibilidad, móvil, consentimiento, UTM, links.
```

## Fuentes para validar implementación
- https://itnig.net/podcast/
- https://itnig.net/podcast/willyrex-explica-el-negocio-real-de-youtube-100-000-me-6bd9821397/
- https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs
- https://help.gohighlevel.com/support/solutions/articles/155000002452-how-to-add-blog-search-and-category-navigation-
- https://help.gohighlevel.com/support/solutions/articles/155000002776-add-blog-post-element-in-funnel-step-or-website-page

**Notas GHL verificadas:** editor de Blog Posts permite insertar vídeo YouTube con icono `Insert Video`: https://help.gohighlevel.com/support/solutions/articles/155000002450-create-blog-posts . FAQ de blogs documenta que *Forms/Surveys* y *Custom Code* no se pueden añadir directamente al post en la versión consultada: https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs-and-blog-posts .


## Cambio de alcance V3.5 — APARCADO
Esta plantilla detallada de episodio es una **opción posterior** para determinados vídeos de alto valor SEO. No convertir 30 vídeos en 30 publicaciones. Fase MVP: único `/aprende`, enlaces a listas oficiales y miniaturas seleccionadas; mejora Google con textos por nivel y páginas guías cuando se justifiquen.
