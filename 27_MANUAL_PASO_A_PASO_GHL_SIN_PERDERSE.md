> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.


> **ACTUALIZACIÓN V3.4 (prioridad máxima):** El usuario prefiere un único hub `www.joseluisola.com/aprende` en el hosting actual (si lo permite el editor real), con vídeos alojados en YouTube y playlists enlazadas/incrustadas, **sin crear un post/landing por vídeo**. `aprende.joseluisola.com` y una web nueva GHL quedan como alternativas, no la solución predeterminada. GHL se utiliza para CRM, newsletter, laboratorios, comunidad y Cénit. Antes de proponer el subdominio anterior, consultar `32_DECISION_SIMPLE_YOUTUBE_BLOG_POST_URL_APRENDE.md`. H1 elegido: «No necesitas una agencia de 20 para empezar a vender con IA». NO alterar DNS ni sitio de producción automáticamente.

# 27 · MANUAL DE LECTURA: construir el portal en GHL, pantalla por pantalla, sin tocar GoDaddy
**v3.3 — Guía operativa, únicamente español**

## Qué SÍ es nativo en GHL y qué NO debes dar por hecho
| Función | Capacidad de partida | Qué comprobar |
|---|---|---|
| Crear web nueva y páginas | **Nativa** `Sites > Websites` | Tu cuenta, plantillas y ruta exacta del menú |
| Guardar páginas sin enseñar al público | Editar sin publicar / staging | Probar con incógnito si realmente está inaccesible; `noindex` no protege datos |
| Blog con categorías y artículos | **Nativa** `Sites > Blogs` | URLs reales, layout y post publicado |
| Buscador de entradas / navegación categoría | **Nativa, con límites** | Qué campos y acentos busca, y si funciona con tu plantilla |
| Mostrar “últimos vídeos” automáticamente desde YouTube | **No asumirlo** | Usar `Blog Post Element` con entradas de vídeo o tarjetas manuales |
| YouTube insertado en página | **Nativa** elemento `Video` | Permitir reproducción, consentimiento/embed, tamaños móviles |
| Transcripción y capítulos escritos | Contenido del post | Revisar formato de enlaces al segundo |
| Formulario insertado dentro de un post de blog | **GHL documenta que no se puede en el editor de posts consultado** | Enlace CTA desde el post a página GHL con formulario o usar secciones globales si disponibles y probado |
| Código/JSON-LD por cada post | **No dar por supuesto en editor de posts** | Usar funciones de plantilla/sitio si existen; si no, posponer esquema custom, sin alterar contenido |
| Buscador por palabra dentro de una transcripción y salto a segundo | **NO nativo confirmado** | Desarrollar aparte cuando haya volumen real |
| Formulario, contacto y workflows | GHL nativo | Campos, etiquetas, consentimiento y entrega |
| Comunidad / curso gratis | GHL comunidades/cursos | Permisos, nombres y accesos sin coste |
| Descarga `.html` | **No confirmado en Media Storage** | Probar `.zip` HTML offline y descarga por URL real; no prometer HTML alojado |
| Indexar Google | Google decide; GHL prepara contenido y sitemap | Verificar Search Console; no indexación garantizada |

## Orden exacto (no saltarse pasos)

### PASO 0 — Preparar y proteger
- [ ] Entrar a GoDaddy y confirmar qué hosting usa la web actual, quién controla DNS y registrar copia del zone file (sin compartir credenciales).
- [ ] Documentar webs activas: `joseluisola.com`, `www.joseluisola.com`, `eticsacademy.com`; probar formularios, correo y compras.
- [ ] No cambiar DNS `@`, `www`, MX, TXT de correo, nameservers, hosting ni redirecciones.
- [ ] Definir nuevo nombre `aprende.joseluisola.com` **solo como objetivo** y confirmar que no esté ocupado.
- [ ] Preparar 1 vídeo real, transcripción propia, portada real y 1 archivo HTML de Chrome dentro de ZIP seguro.

### PASO 1 — Crear sitio nuevo en GHL
1. Entrar en subcuenta GHL correcta.
2. Menú **Sites → Websites** → **+ New Website** (si cambia la interfaz, buscar opción equivalente).
3. Nombre interno: `José Luis Ola | Portal educativo ES | staging`.
4. Seleccionar plantilla sencilla o “from blank”, fondo claro, alto contraste, ancho máximo adecuado a lectura, **solo español**.
5. Crear página **Inicio**, slug de portada, título para SEO de staging neutro. No usar dominio productivo existente.
6. Guardar y usar previsualización de GHL. **No enviar a público ni hacer campañas todavía**.
7. Cuando exista URL temporal, implementar protección/`noindex` si aplica a páginas GHL; inspeccionar cabecera de HTML y Search Console si hubo publicación involuntaria. La opción `noindex` bajo SEO Metadata no equivale a password.

### PASO 2 — Crear navegación pública mínima
Publicar al principio solo enlaces con destinos **funcionales y contenido real**:
```
Inicio | Empieza aquí | Aprende IA | Brújula | [Botón: Primera clase gratis]
```
Crear páginas de borrador para Radar, Herramientas, Comunidad y otros niveles, pero **no agregarlas al menú visible** hasta tener contenido y CTA válido. Un menú con 12 pestañas vacías perjudica confianza y recorrido. El documento 28 contiene el calendario de activación.

### PASO 3 — Montar portada usable desde un vídeo
1. Añadir `Hero` (eyebrow “El poder de 1 solopreneur + IA”, H1 recomendado, subtítulo aprobado, CTA primera clase).
2. Debajo: “¿Por dónde comienzo?” tres tarjetas (nunca he usado IA / ya probé ChatGPT / listo para sistemas). La tercera puede enlazar a Etics Academy en dominio intacto.
3. Añadir “Últimas clases”: **opción manual inmediata** con 1–3 tarjetas enlazadas a **páginas de episodios reales**, no miniaturas sueltas sin enlaces; consulta Paso 6.
4. Ruta de aprendizaje visible, con nivel 0 activo y niveles superiores como texto “Lo que aprenderás después” **sin enlaces rotos ni 9 bloques bloqueados**.
5. Sección Brújula con opt-in real, en línea con web actual.
6. Footer legal y enlaces a Etics avanzada y web personal vigente. No duplicar frases legales sin revisarlas.

### PASO 4 — Crear el archivo de episodios con GHL Blogs
1. Ir a **Sites → Blogs → Create Blog**.
2. Nombre: `Biblioteca José Luis Ola` / sitio de blog: `Clases y episodios`; dominio GHL puede conectarse después.
3. Definir slug/ruta de blog **según GHL**, anotar URL final antes de incrustar enlaces. No asumir que se puede forzar `aprende.joseluisola.com/episodios/[slug]` con el constructor.
4. Crear autor `José Luis Ola` (sin credenciales ni premios inventados).
5. Crear categorías inicialmente **solo** `Nivel 0` y `Radar` si tienes un Radar real. Después añadir `Prompts`, `Ventas cotidianas`, `Atención`, `Organización`; evitar categorías vacías públicamente.
6. **New Post** para EP001. Añadir contenido del documento 26: introducción, **reproductor YouTube mediante icono de vídeo del editor de Posts** (documentado por GHL), resumen, pasos, marca de tiempo, HTML, transcripción y siguiente clase (si está publicada).
7. Al publicar definir **slug, categoría, autor, meta title, meta description, alt, canonical absoluto real**. Si algo no es configurable en esa plantilla, documentarlo y no afirmar que está hecho.
8. Revisar **Preview → Mobile** y después usar URL de prueba. Verificar que se ven video, transcripción y capítulos en Chrome e incógnito.
9. Enlazar EP001 desde `/empieza-aqui/`, portada y, cuando corresponda, Brújula.

### PASO 5 — Activar búsqueda, pero probar sus limitaciones
1. Entrar **Sites → Blogs**, abrir el blog, seleccionar **Edit Site**.
2. Activar opción **Blog Search** que documenta GHL y/o elemento `Category Navigation`.
3. Probar antes de dejarlo visible: título exacto, palabra dentro del cuerpo, término acentuado, categoría y una palabra inexistente.
4. Tomar nota de qué indexa. **El buscador de posts no equivale al buscador de transcripciones enlazadas a cada segundo.**
5. Cuando haya un solo post, puede permanecer oculto: la primera experiencia debe ser “ver la primera clase”, no “0 resultados”.

### PASO 6 — SECCIÓN 3, «ÚLTIMOS VÍDEOS», DOS OPCIONES
**OPCIÓN A — recomendable desde cero y sin errores:** tarjetas manuales.
1. **Sites → Websites → José Luis Ola → Inicio → Edit**.
2. Añadir `Section` con título `Últimas clases` y subtítulo `Una tarea práctica en cada vídeo`.
3. Añadir 1 o 3 `Columns/Cards`: miniatura original de YouTube o imagen autorizada, categoría real `Nivel 0`, título del episodio, CTA `Ver clase y transcripción` → URL real del post GHL.
4. En páginas normales usar **Add Elements (+) → Video → YouTube → pegar URL pública real**; **en blog posts** utilizar el **icono Insert Video** dentro del editor de publicaciones GHL. GHL soporta YouTube y Shorts; no activar autoplay.
5. Cada semana actualizar tarjetas al publicar el episodio nuevo; mantener máximo 3 visibles, botón `Ver biblioteca` solo cuando la biblioteca esté publicada.
6. Prueba en móvil e incógnito; verificar 1 clic al artículo y reproducción correcta.
**OPCIÓN B — semi-automática con artículos de vídeo existentes:**
1. Publicar entradas GHL por cada clase (el blog es fuente de verdad, no YouTube automático).
2. Ir a editar Inicio → **Add Blog Post Element** → seleccionar blog `Biblioteca José Luis Ola`, filtrar por categorías `Clases`, ordenar recientes si la UI disponible lo permite, limitar nº de tarjetas visibles.
3. Revisar que SOLO aparecen publicaciones reales y el orden cumple. Confirmar si el widget permite mostrar portada, título, extracto; no garantizar funciones de filtros hasta probar.
4. El bloque cambia cuando publicas un post en **GHL**, no porque publiques un vídeo en YouTube; debes crear su ficha.
**OPCIÓN C — video destacado embebido directamente en portada**: elemento `Video` con 1 vídeo real + CTA a post; útil si todavía solo existe EP001, evitando 3 contenedores vacíos. Al aumentar a 3, cambiar a tarjetas o Blog Post Element.

### PASO 7 — «RUTA DE APRENDIZAJE», visible pero sin falsas lecciones
Nivel 0 Primeros pasos con ChatGPT/Copilot → Nivel 1 mensajes/atención → Nivel 2 creativos/ofertas → Nivel 3 clientes/organización → Nivel 4 sistemas básicos → Nivel 5 analítica/campañas → Nivel 6 Método Cénit avanzado.
- Mostrar solo `Nivel 0 — Empezar ahora` como CTA activo si es único publicado.
- Las siguientes etapas pueden verse como **mapa informativo**: “Próximamente” sin campos falsos `0% completado`, sin prometer fechas.
- Cada nivel activo debe tener página de resumen, prerequisitos, 1 vídeo real, ejercicio y siguiente nivel.
- Evitar nombrar niveles “primaria/secundaria” en la interfaz para un público adulto.

### PASO 8 — «RADAR» y «COMUNIDAD» cuando estén listos
- Radar: primero página `Qué es Radar`, primera fecha **solo cuando esté confirmada**, link real al directo o canal. Usar formato quincenal según plan previo y archivar emisiones como episodios tipo Radar.
- Comunidad: nombre `Etics IA · Desde Cero`. Crear comunidad en GHL, confirmar permisos y acceso gratuito. Enlace público `/comunidad/` solo cuando invitación/login funcione. Descripción simple y política de participación (no subir datos de clientes).
- Brújula original sigue siendo válida; Brújula-Lab ofrece `.zip` que contiene `.html` descargable. GHL Media Storage no declara el `.html` como formato verificado en su listado, por eso probar ZIP y descarga en Chrome antes de ofrecer.

### PASO 9 — Subdominio GoDaddy de forma SEGURA
1. Al acabar QA, en GHL **Sites → Settings → Domains → Connect a Domain** → elegir **Website/Blog**, ingresar `aprende.joseluisola.com` y revisar instrucciones.
2. Preferir **Add records manually** para no autorizar una modificación automática de todo GoDaddy sin entender su alcance.
3. En GoDaddy: `My Products → Domains → Manage DNS` (interfaz podría variar). Agregar **solo** el registro solicitado para host `aprende` con el valor exacto que GHL genere. Si GHL necesita más de un registro o encuentra conflicto, detenerse y revisar.
4. **No tocar `@`, `www`, `MX`, SPF/DKIM/DMARC, NS**. Captura del cambio antes y después.
5. Esperar propagación, validar certificado https y carga del subdominio en incógnito, desde móvil y otra red. Comprobar que web vieja y correos siguen operativos.
6. Asignar la web/blog al nuevo host según GHL; si hay errores de ruta entre blog/website, corregir antes de comunicar la URL.

### PASO 10 — Indexación de Google
1. Verificar `aprende.joseluisola.com` y, si tiene acceso, propiedad de dominio `joseluisola.com` en Google Search Console. Verificar titularidad por DNS TXT **agregando** TXT, nunca borrando TXT de correo.
2. Confirmar que el portal no conserve `noindex` de staging, ni `canonical` a la web vieja. Confirmar HTTPS, `200 OK`, rutas sin login y enlaces HTML.
3. En GHL generar/consultar sitemap XML del dominio; revisar que incluya blog/entradas realmente públicas (GHL explica que hay que seleccionar blog home/posts), no drafts ni páginas `noindex`.
4. Añadir URL **real** del sitemap en Search Console → Sitemaps; usar inspección de URL para home, inicio y EP001; solicitar indexación si procede.
5. Validar datos estructurados `VideoObject` sólo con datos auténticos y herramienta de resultados enriquecidos. No garantiza aparición en Google ni en Video Search.
6. Configurar GA4 y tags cumpliendo consentimientos; registrar `page_view`, clic a vídeo, `resource_download`, opt-in y `episode_next_click` sólo cuando sea medible. No inferir automáticamente uso local del HTML.
7. Revisar Search Console a 7/30 días para detectar páginas excluidas, duplicadas y falta de contenido.

### PASO 11 — Piloto público con prueba de usuario real
Pedir a 3–5 personas del público objetivo que realicen sin asistencia: visitar Inicio → encontrar primera clase → reproducir → acceder a HTML → abrirlo en Chrome → localizar siguiente clase o Brújula. Registrar dónde se atascan y corregir la interfaz. No fingir visitas ni atribuir conversiones.

## TABLA DE ACEPTACIÓN (marcar solo si comprobado)
| Prueba | Condición de aprobado |
|---|---|
| GoDaddy intacto | Raíz `@`, `www`, formularios y correo sin cambios |
| Navegación | Ningún enlace visible conduce a 404, vacío o CTA ficticio |
| Primer aprendizaje | Hallar EP001 en 2 clics como máximo |
| Embeds | YouTube reproduce sin autoplay, sin overlay intrusivo y en móvil |
| Buscador | Buscar y filtrar como se describe; no prometer transcripción por segundo |
| Descarga | ZIP seguro abre HTML local en Chrome y no pide información innecesaria |
| Comunidad | Gratuita y login/invitación funciona si se anuncia públicamente |
| SEO | Página indexable en subdominio final, canonical correcto y sitemap revisado |
| Privacidad | Opt-in marketing independiente, políticas visibles y dato personal protegido |
| Nivel avanzado | Etics Academy vigente enlazada pero sin presión a principiantes |

## Referencias verificadas
- GHL Blog: https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs
- GHL Buscar/categorías: https://help.gohighlevel.com/support/solutions/articles/155000002452-how-to-add-blog-search-and-category-navigation-
- GHL Blog Post Element: https://help.gohighlevel.com/support/solutions/articles/155000002776-add-blog-post-element-in-funnel-step-or-website-page
- GHL Video element: https://help.gohighlevel.com/support/solutions/articles/155000008988-video-element-in-funnels-websites
- GHL conectar dominio: https://help.gohighlevel.com/support/solutions/articles/155000005132-connecting-your-domain-on-ghl-a-guide
- GHL Sitemap: https://help.gohighlevel.com/support/solutions/articles/155000002453-how-to-add-blog-sitemap-
- GHL custom meta robots: https://help.gohighlevel.com/support/solutions/articles/48001073924-custom-meta-tags
- Google VideoObject: https://developers.google.com/search/docs/appearance/structured-data/video

**Fuentes adicionales:** GHL insertar vídeo directamente en post https://help.gohighlevel.com/support/solutions/articles/155000002450-create-blog-posts ; GHL blog FAQ limitación para Forms/Surveys/Custom Code https://help.gohighlevel.com/support/solutions/articles/48001220286-getting-started-with-blogs-and-blog-posts ; GHL subdominio para no reemplazar root https://help.gohighlevel.com/support/solutions/articles/48001153720-set-up-a-root-domain-or-subdomain-for-highlevel-sites


## Ruta corta reemplazante V3.5
1. Verificar si el host `www` es servido por GHL o no. 2. Si sí: `Sites → Websites → page /aprende`, conservar home y SEO. Si no: crear /aprende en proveedor actual o subdominio para GHL. 3. Insertar 1 playlist o 3 cards + texto útil. 4. Publicar y comprobar privacidad/HTTPS. 5. Configurar **SEO Meta Data** en el constructor real. 6. Search Console→verificar dominio/host→URL inspection→sitemap. 7. Probar formularios GHL y comunidad. El proceso largo de portal tipo Itnig pasa a fase posterior.
