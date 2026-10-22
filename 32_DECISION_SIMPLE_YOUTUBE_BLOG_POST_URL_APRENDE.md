> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# 32 · V3.4 — Web sencilla, vídeos enlazados, SEO selectivo y ruta /aprende
**Decisión editorial vigente · 18 de octubre de 2026**

## 0. Resumen decisional (corrección de la v3.3)
1. **No crear una landing manual por vídeo**. 30 vídeos pueden ser **30 enlaces de YouTube y 0 páginas nuevas** en la web. YouTube aloja las clases, capítulos, subtítulos y monetización del canal.
2. Una ficha de GHL Blog sí se publica como **una URL individual**, pero se crea como **un post dentro de una única plantilla**, no como website/landing separada. No hay obligación de publicar 30 entradas. Crear solo 1 artículo evergreen/guía cuando justifique búsqueda de Google, por ejemplo 1 de cada 4–6 vídeos, según datos reales.
3. La ruta preferida por el usuario es `https://www.joseluisola.com/aprende`. **Solo podrá alojarse como sección efectiva si el servidor que ya atiende `www.joseluisola.com` crea esa página o enruta esa ruta**. Que GoDaddy gestione el dominio NO prueba qué software/hosting sirve el contenido. **GHL separado no controla una carpeta `/aprende` del hosting GoDaddy solo con pegar el enlace o cambiar un DNS**. Opción simple si GoDaddy Websites + Marketing: crear página `/aprende` en el mismo editor, sin migrar ni sustituir home. Si WordPress, crear página allí; si HTML/cPanel, ruta y archivo/route en ese hosting. Evitar proxys complejos para un proyecto de una persona. En todos los casos hacer copia antes de publicar, comprobar URL real y el canonical.
4. GHL es el **back office**: comunidad Etics IA · Desde Cero, formularios, newsletter, CRM, automatizaciones y ventas Cénit. La web de educación inicial **puede vivir en GoDaddy**. `aprende.joseluisola.com` permanece como alternativa únicamente si el hosting actual no admite la ruta deseada o si en el futuro se decide operar el portal entero con GHL.
5. **No fingir SEO**: vídeos enlazados no crean, por sí solos, 30 páginas posicionables en Google en el dominio propio. Priorizar SEO on-YouTube; en la web, optimizar `/aprende`, añadir texto útil y crear guías selectivas. Google indexa por criterio propio.
6. Mantener H1 propuesto: **«No necesitas una agencia de 20 para empezar a vender con IA»**. Subtítulo aprobado sobre clases y herramientas gratuitas. Menú progresivo, sin pestañas vacías, solo español.

## 1. Arquitectura simple recomendada
- `www.joseluisola.com/` = presentación de José, Brújula, Antibriefing, puerta a principiantes y a la academia.
- `www.joseluisola.com/aprende` = hub de niveles 0–6, **vídeos de YouTube** enlazados o playlist oficial incrustada, clase 1 destacada, laboratorios HTML, CTA educativo a GHL.
- Canal YouTube = alojar vídeos, subtítulos, capítulos, descripciones útiles, listas de reproducción, Shorts relacionados, lives Radar.
- GHL = contactos, entrega de laboratorios, emails y comunidad; sus direcciones reales pueden ser externas, pero mantienen coherencia visual y marca.
- `eticsacademy.com` = Sistema Cénit, oferta avanzada.
- Opcional selectivo (más adelante): blog GoDaddy existente o GHL Blog en dominio separado real, o migración programada si hay argumentos SEO/operativos; no mezclar rutas de diferentes servidores sin resolver enrutamiento.

## 2. Qué publicar con 1, 5 y 30 vídeos
| Catálogo | Inicio simple | Blog SEO GHL |
|---|---|---|
| 1 vídeo | Primer vídeo incrustado, enlace a YouTube, HTML y siguiente clase cuando exista | ninguno necesario |
| 2–5 | 3 tarjetas manuales + playlist ordenada + Brújula | 0–1 guía selectiva |
| 6–15 | 1 hub con secciones por nivel, playlist que se actualiza en YouTube, 3 vídeos destacados manuales | 1–3 guías según búsquedas |
| 16–30 | una sola página de catálogo con listas por nivel y links a playlists; filtros solo si son útiles | 3–6 guías realmente diferenciadas, NO obligatoriamente 30 |

## 3. ¿Cómo incorporar vídeos sin rehacer página cada semana?
**Opción mínima A (recomendada):** en `/aprende` insertar una playlist de YouTube. Mantener la playlist desde YouTube Studio y los episodios aparecen allí sin agregar tarjetas por cada vídeo. Si la herramienta de página no acepta la URL de playlist como sección de vídeo, usar una sección HTML con código `iframe` oficial de YouTube y probar en móvil, política de cookies y HTTPS. Probar en el propio constructor GoDaddy. Si el embed no funciona, poner botón hacia la playlist y 3 tarjetas manuales que se refrescan mensual, no semanal.

**Opción B:** añadir 3 fichas manuales de episodios destacados, enlazadas al vídeo de YouTube (no 30). Tiempo por vídeo: actualizar listado en YouTube; en web, reemplazar como mucho una tarjeta cuando aparezca nuevo contenido destacado.

**Opción C:** GHL Blog Post Element, solo cuando exista blog **alojado en un dominio/ruta verdaderamente servido por GHL**. El bloque extrae posts GHL publicados ordenados por Recent Posts, Category o Author y los muestra como tarjetas. NO recupera la playlist/feed de YouTube. Crear un post breve o extenso sigue siendo tarea editorial, aunque GHL ofrece plantillas y carga por CSV.

## 4. Blog Post GHL: funcionamiento paso a paso y limitaciones
1. Abrir subcuenta → `Sites → Blogs → Create Blog`; elegir título y slug sin conectar accidentalmente el dominio productivo GoDaddy.
2. Crear el primer post **solamente si** hay una guía útil que merezca indexarse: `Sites → Blogs → [blog] → New Post`. Redactar 600–1200 palabras **como orientación editorial, nunca como criterio SEO fijo**; incluir pasos propios y enlaces al vídeo/ejercicio. Publicar transcripción íntegra no es requisito.
3. `Continue` → slug, autor/categoría, título SEO, descripción, portada y alt, canonical real → publicar o programar.
4. En la página GHL que sirva el blog: `Sites → Websites → Edit → Add Elements → Blog Posts` → seleccionar Blog Site → orden `Recent Posts` → número de entradas visibles, CTA y estilo → guardar/publicar.
5. Comprobar con un nuevo post de prueba que cambia el bloque **sin editar la home**. Comprobar URL pública, indexación, slug/canonical y links.
6. **GHL Blog Post ≠ API YouTube**. No confundir su catálogo con feed dinámico de vídeos. La documentación de GHL indica que post individual dispone de su propia URL y que los formularios/código custom no se presuponen admitidos dentro del editor del post; usar enlace hacia registro GHL o sección de la plantilla probada.

## 5. Estrategia de vídeo YouTube sin duplicación
Cada vídeo incluye título centrado en problema, 2 líneas iniciales que explican beneficio, capítulos con `00:00`, enlaces a playlist/siguiente clase, un CTA educativo a `/aprende` o recurso GHL y fuentes cuando proceda. Subtítulos corregidos y vídeo relacionado desde Shorts. No llenar tags ni repetir keywords artificialmente.

**Modelo de descripción:**
```
Hoy aprenderás [resultado específico] con [herramienta], desde cero y sin tecnicismos.
Practica con el laboratorio gratuito: [URL REAL Y PUBLICADA]
Empieza desde cero: https://www.joseluisola.com/aprende [SOLO CUANDO EXISTA]

CAPÍTULOS
00:00 Qué resolveremos
01:20 Entrar en la herramienta
03:10 Primera demostración
08:30 Ejemplo práctico para ventas
13:40 Errores y alternativas
16:10 Ejercicio y siguiente clase

▶ Sigue con esta lista de clases: [PLAYLIST REAL]
🧭 Brújula del Solopreneur: [URL REAL]
```
Usar marcas temporales reales: no publicar las del ejemplo sin contrastar duración/contenido.

## 6. Página `/aprende` sin deuda editorial
1. H1 aspiracional elegido y subtítulo aprobado; CTA `Ver primera clase`.
2. Ruta de nivel 0 a 6: tarjetas informativas, solo niveles con contenidos son clicables.
3. Vídeo 001 destacado o playlist incrustada; CTA a YouTube con todos los vídeos.
4. Primer HTML para Chrome, explicado y con acceso opcional por email según decisión vigente.
5. Bloque «Próximos pasos» que lleve a playlist nivel cero y Brújula.
6. Mini-bloque Radar IA cuando exista primera emisión real.
7. Comunidad Etics IA · Desde Cero, solo si está realmente abierta.
8. Opción avanzada discretísima a Etics Academy.

## 7. SEO público de joseluisola.com: auditoría observable y no verificada
**Observado en páginas públicas indexadas/crawl 18/10/2026:** título de documento principal visible como `José Luis Ola | Solopreneur · Marketing Digital con IA` en una captura pública reciente; H1 original comparativo; nav principal centrada en «Sobre mí», «Antibriefing», «Etics Academy», «Webinar», «Newsletter»; newsletter como CTA prioritario; ediciones Brújula y textos orientados a usuarios Meta Ads/embudos; FAQ comerciales; referencias a testimonios, casos y +1.200 suscriptores en una versión renderizada. Esto confirma que el contenido promocional es más avanzado que el objetivo nivel cero.

**Cambios por prioridad:**
- **P0** En inicio, enlace visible `Aprende IA gratis` hacia `/aprende` real, sin quitar Brújula/Antibriefing ni oferta Etics. H1 nueva solo si se decide actualizar la home; la aprobación del titular es para la nueva propuesta, no permiso técnico para editar el sitio.
- **P0** Verificar que menú, 3 ediciones de Brújula, CTA de webinars y avisos legales resuelven páginas/acciones correctas en móvil. Los rastreadores pueden ver `0` para enlaces basados en JS; **no llamar rotos sin prueba manual**.
- **P0** Verificar que referencias a eventos tienen fecha futura correcta (si se muestra evento fechado) y que testimonios/resultados tienen sustento y autorización.
- **P1** Al publicarse `/aprende`: title sugerido `Aprende IA desde cero para vender | José Luis Ola`, descripción que mencione ChatGPT y ejercicios y URL canónica única; un solo H1; FAQ con respuestas reales; enlaces internos desde la home.
- **P1** Search Console sobre el dominio y registrar `/aprende`, comprobar accesibilidad/canonical/sitemap, revisar qué URLs están indexadas, consultas y clics. El acceso a Search Console no ha sido auditado; tampoco el código fuente HTML, robots ni sitemap se verificaron completamente.
- **P2** Guías evergreen solo sobre temas con intención de búsqueda recurrente. Medir tráfico a páginas y clic a YouTube/GHL por UTMs.

## 8. Diferencia crítica `/aprende` vs `aprende.`
| Deseo | ¿Cómo se logra? | Esfuerzo / riesgo |
|---|---|---|
| `www.joseluisola.com/aprende` | Crear una página real en el **mismo hosting/CMS** que publica `www` | Más simple si hay editor GoDaddy / WP, no modificar DNS |
| `aprende.joseluisola.com` | Crear website en GHL y conectar subdominio con registro DNS específico | Sin cambiar web `www`; un dominio nuevo a verificar Search Console |
| `www.joseluisola.com/aprende` servido por GHL mientras home sigue en GoDaddy | Enrutamiento a nivel reverse-proxy/CDN o mover el sitio padre a plataforma compartida | **No recomendado ahora**; no basta con un CNAME |

**Condición de partida:** confirmar si el sitio usa GoDaddy Websites + Marketing, WordPress administrado, cPanel/HTML u otro software. «Está en GoDaddy» por sí solo no lo resuelve.

## 9. Plan de 7 pasos sin equipo
1. Identificar editor que publica la homepage y exportar/respaldar web actual.
2. Crear página `Aprende IA` oculta del menú mientras se prepara, con URL/slug `aprende` si el editor lo permite.
3. Poner hero, ruta de aprendizaje y vídeo uno o playlist real; añadir su laboratorio.
4. Integrar formulario GHL para entrega, probar opt-in separado para marketing, automatización y descarga.
5. Publicar `/aprende` y enlazarlo desde menu y hero secundario de home cuando funcione.
6. Descripciones de YouTube con capítulos reales y enlaces a página y siguientes vídeos.
7. Search Console: inspeccionar, enviar sitemap si existe y medir 30 días antes de construir blog.

## 10. Fuentes utilizadas (verificar de nuevo antes de implementar)
- GoDaddy: add page https://www.godaddy.com/en-uk/help/add-a-page-to-my-website-24072
- GoDaddy: embed video https://www.godaddy.com/en-ca/help/add-a-video-section-to-my-websites-marketing-site-24586
- GoDaddy: HTML custom https://help-center.dc-aws.godaddy.com/help/add-html-or-custom-code-to-my-site-27252
- GHL Blog Post listing https://help.gohighlevel.com/support/solutions/articles/155000002776-add-blog-post-element-in-funnel-s-step-or-website-s-page
- GHL Blogs https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs-and-blog-posts
- YouTube playlist embeds https://support.google.com/youtube/answer/171780
- Google video SEO https://developers.google.com/search/docs/appearance/video


## Aclaración de infraestructura V3.5
La ruta puede perfectamente crearse **dentro de GHL** cuando `www.joseluisola.com` está servido por GHL, aunque el dominio se administre en GoDaddy. Lo imposible es dirigir una sola carpeta al servidor GHL **solo con una instrucción DNS**, mientras el mismo host sirve el resto desde otro proveedor. Ver documento 35.
