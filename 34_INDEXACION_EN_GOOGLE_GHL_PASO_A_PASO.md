# 34 · SEO técnico y Google: cómo publicar, descubrir e indexar páginas GHL
**V3.5 · Fecha:** 18/10/2026. Manual operativo para José Luis Ola, GoDaddy y HighLevel.

## Respuesta esencial: GHL no tiene botón mágico «publicar en Google»
**Publicar una página** significa servirla en una URL pública desde el proveedor web. **Permitir indexación** significa que la URL responde correctamente y Google puede rastrearla. **Solicitar indexación** se hace mediante Google Search Console, propiedad del dominio/URL, no mediante el campo de SEO de GHL. **Posicionar** requiere contenido útil y señales adicionales; no es automático ni garantizado.

## Fase A — Determinar dónde vive la página, antes de SEO
1. Probar la URL final con navegador anónimo en móvil y escritorio. Copiar la URL final tras redirecciones. No basta que GoDaddy gestione el dominio: el hosting de cada host puede ser GoDaddy, HighLevel u otro.
2. Si la URL final es `https://www.joseluisola.com/aprende`, publicar y editar en **el sistema que sirve `www.joseluisola.com`**. Si ese host está conectado a GHL, puede usarse GHL en la ruta. Si el host sigue publicado por otro constructor, crear la ruta allí o utilizar subdominio para GHL.
3. Si la URL final es `https://aprende.joseluisola.com/`, configurar solo ese subdominio en GHL y conservar raíz y `www`. Probar que la URL resuelve y presenta SSL válido.
4. Durante construcción, mantener borradores privados y/o `noindex` donde proceda. Antes de solicitar indexación retirar el `noindex`, restricciones y páginas vacías. Las páginas de comunidad con login NO son páginas SEO públicas.

## Fase B — SEO ON PAGE en GHL (si GHL sirve la URL)
1. Abrir la subcuenta → **Sites → Websites/Funnels** → seleccionar web → página → **Edit**.
2. Abrir **SEO Meta Data** (icono/panel SEO). Título SEO descriptivo y humano. Ej.: `Aprende IA desde cero para vender | José Luis Ola`. Evitar repetir keywords. Meta descripción original: `Clases y ejercicios de IA para escribir mensajes, atender clientes y vender mejor. Empieza con ChatGPT, Copilot o Claude paso a paso.`
3. Revisar H1 único y visible: `No necesitas una agencia de 20 para empezar a vender con IA.` Mantener el subtítulo educativo aprobado.
4. URL slug limpio (`aprende` si ese host admite la ruta), encabezados H2 y párrafos originales que resuelvan las dudas del lector. No dejar SOLO imágenes y botones hacia YouTube: aportar texto de contexto que Google pueda leer.
5. Miniaturas optimizadas y accesibles con `alt` natural. Botones normales `<a href="...">` (no solo eventos JS) hacia listas de YouTube y recursos. HTTPS, buen funcionamiento móvil y velocidad aceptable.
6. Verificar canonical real apuntando a la URL final preferida. No mezclar canonicals del subdominio con los del host principal sin motivo. Comprobar que `robots` NO contiene `noindex` en páginas destinadas a Google.
7. Publicar en URL final y revisar con sesión privada que responde HTTP 200; no redirige a otro URL sin querer, no exige login ni se oculta por JS. El panel SEO **no es** el mecanismo para enviar la página a Google.

## Fase C — Google Search Console, una sola vez por host o dominio
1. Ir a `https://search.google.com/search-console/` e iniciar sesión con la cuenta propietaria de las webs.
2. Crear propiedad **Dominio** `joseluisola.com` cuando sea posible: normalmente requiere añadir un registro DNS **TXT** de verificación al panel de la zona DNS, sin cambiar el A/CNAME que mantiene la web. Un TXT de verificación no traslada tráfico web; requiere cuidado para no borrar otros TXT (SPF/DKIM, etc.). Alternativa: propiedad **Prefijo de URL** con el host exacto, como `https://www.joseluisola.com/` o `https://aprende.joseluisola.com/`.
3. Abrir «Inspección de URL» y pegar URL pública final. Consultar si «Google puede indexarla». Ejecutar «Probar URL publicada» cuando proceda. Si la URL está lista, usar «Solicitar indexación» para pocas URLs importantes.
4. Obtener URL del sitemap **real**, no inventada: en GHL revisar `Settings → Domains` y su menú XML Sitemap; normalmente ruta `/sitemap.xml`, pero comprobar en navegador. Habilitar páginas públicas relevantes. La URL GHL `/sitemap.xml` aplica al host que realmente sirva GHL, NO a la web GoDaddy por el simple hecho de compartir registrador.
5. En Search Console → «Sitemaps», enviar la **ruta correcta** del sitemap que pertenece al host/propiedad. Para pocas URLs no es obligatorio, pero sirve para seguimiento. Si la página `/aprende` está en GoDaddy, localizar el sitemap de ese CMS.
6. Revisar informes **Páginas** y **Rendimiento** semanalmente al inicio: estado indexación, consultas, impresiones, clics, CTR por consulta/página; los cambios pueden tardar días o semanas. No repetir solicitudes continuamente.
7. Si Search Console muestra «Rastreada: actualmente sin indexar», confirmar que la página ofrece utilidad autónoma (explicación, niveles, FAQs honestas, acceso real a clases) antes de hacer cambios cosméticos.

## Fase D — Un hub con miniaturas, ¿qué puede posicionar?
- El hub público `/aprende` puede indexarse como **una sola URL**. Google NO obtiene 30 páginas propias por enlazar 30 vídeos externos. Los vídeos también pueden descubrirse y posicionarse directamente en YouTube/Google.
- Si solo hay 30 tarjetas con imagen, título y enlace, la página tiene poca explicación propia. Añadir H2 por nivel, introducción de ~2–4 frases por grupo y descripción corta de cada clase, accesible como texto HTML.
- Recomendar **1 hub con 3–6 playlists**, 1 vídeo destacado y 3 miniaturas; sin 30 cambios manuales. Los nuevos vídeos se agregan principalmente en **YouTube Studio a sus playlists**.
- Guías SEO selectivas de GHL Blog se publican cuando de verdad añaden procedimientos, ejemplos propios, decisiones y fuentes. Blog Posts de GHL muestra **posts**, no últimas subidas de YouTube automáticamente.

## Analítica mínima
Conectar GA4 si ya está configurado, medir evento clic externo `click_youtube`, registro `lead_principiante`, descarga `html_download`, entrada `community_join` solo cuando el evento sea real; UTM en enlaces desde newsletter/YouTube hacia GHL; no poner UTM en la URL canónica. Enlazar GA4 y Search Console si procede y se dispone de acceso. Respetar consentimiento para cookies o marketing según jurisdicción.

## Errores que evitar
- Confundir «publicar» con «indexar». Google determina si indexa.
- Usar `noindex` en la página final; `robots.txt` bloquear rutas públicas; sitemap de otro host; canonical erróneo; URL no pública.
- Creer que un `TXT` de verificación o un DNS CNAME puede direccionar la **carpeta** `/aprende`.
- Seguir el método antiguo `https://www.google.com/ping?sitemap=...`: **Google lo descontinuó** y devuelve 404 (la documentación de GHL conserva referencias antiguas, pero debe prevalecer Google Search Central).

## Fuentes oficiales verificadas
- GHL: SEO Metadata https://help.gohighlevel.com/support/solutions/articles/48001073924-custom-meta-tags
- GHL: sitemap https://help.gohighlevel.com/support/solutions/articles/48001182524-xml-sitemaps
- GHL: blogs sitemap https://help.gohighlevel.com/support/solutions/articles/155000002453-how-to-add-blog-sitemap-
- Google: empezar Search Console https://developers.google.com/search/docs/monitor-debug/search-console-start
- Google: crear/enviar sitemap https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- Google: volver a rastrear https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
- Google: ping discontinuado https://developers.google.com/search/blog/2023/06/sitemaps-lastmod-ping
