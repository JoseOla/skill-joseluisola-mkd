> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# 29 · Seguridad, propiedad intelectual, SEO y QA antes de publicar

## 1. Riesgos concretos y protección
| Riesgo | Consecuencia | Control verificable |
|---|---|---|
| Conectar `@`/`www` por error desde GHL/GoDaddy | La web actual podría dejar de funcionar | Solo registro `aprende`, respaldo zona DNS y doble verificación |
| Sobrescribir MX/TXT | Correo o verificación roto | No editar MX/SPF/DKIM/DMARC; verificar envío y recepción luego |
| Pruebas indexadas por Google | Duplicados/fragmentos inacabados | Aislar staging; noindex en páginas públicas de prueba, retirar al lanzamiento final |
| Pestañas vacías | Desconfianza/abandono | Navegación gradual sin links a borradores |
| Repostear transcripciones ajenas | Reclamos de derechos | Solo contenido propio o autorización por escrito; enlazar fuentes de terceros |
| Copiar la estética/código de Itnig | Riesgo de PI y mala diferenciación | Inspiración de **funciones**, diseño, copys, HTML, iconos y marca originales |
| Publicar datos de clientes en pantalla | Exposición de PII | Usar datos sintéticos e inspeccionar vídeo/audio/transcripción/capturas |
| HTML descargable inseguro | Ejecución de script no deseado en Chrome | Auditoría de archivos, no incluir JS externo, secretos, tracking ni acceso a cuentas |
| Suscripción por descargar archivo | Marketing sin consentimiento adecuado | Enviar recurso solicitado por separado; casilla opcional sin premarcar para Brújula |
| Links afiliados no marcados | Pérdida de confianza / incumplimientos | Disclosure donde existan, transparentar patrocinio |
| SEO artificioso | Indexación pobre o sanción | Texto con valor real, sin versiones casi idénticas ni contenido generado sin revisión |
| Automatizaciones disparadas incorrectamente | Mensajes no deseados | Test contacto ficticio y workflows limitados a consentidos |

## 2. Política HTML-Labs
Archivo HTML del usuario se abre en Chrome con su contenido local. No afirmar que Chrome impide todo riesgo por ser local. Auditar que no haya scripts externos, exfiltración de datos, `eval`, credenciales, iframes terceros, enlaces con datos personales en querystrings ni almacenamiento innecesario. Si el editor no sirve `.html` descargable, empaquetar en **ZIP** y entregar una guía “Extraer archivo → abrir `.html` en Chrome”; comprobar antivirus, integridad, sistemas móviles y explicación de incompatibilidades. Los ZIP nunca contienen ejecutables. Para compartir resultados usar texto anonimizado voluntario, no recogida silenciosa desde archivo local.

## 3. Ficha de consentimiento
- Email de entrega de recurso: finalidad transaccional, breve, sin automatizar campaña comercial ajena a la solicitud.
- Newsletter: casilla clara separada (no premarcada) para Brújula; texto indica frecuencia, finalidad y cancelación.
- Invitación a comunidad: registro voluntario, reglas y política de privacidad, sin publicación automática de email.
- Etics Academy: solo flujo de compra/cita cuando exista intención explícita; no hacer lead scoring opaco con datos sensibles.
- Analítica/cookies: revisar normativa según audiencia/ubicación real, consentimiento para tecnologías no esenciales cuando aplique; cumplir políticas de proveedores.

## 4. Controles de SEO y Google
1. Verificar que el blog no use canonical a `joseluisola.com` si la página real es `aprende.joseluisola.com`.
2. Revisar `<title>`, H1 único, descripción, slug, canonical, alt, enlaces `<a href>`, `lang=es`, accesibilidad y contenidos reales.
3. Google Search Console: agregar propiedad verificada, sitemap real GHL que incluya solo URLs finales públicas; inspección de portada/episodios, errores, reportes de vídeo.
4. Datos estructurados `VideoObject` con atributos auténticos en páginas de vídeo visible, sin copiar cifras de YouTube sin revisar; testar Rich Results Test.
5. Búsqueda interna no sustituye indexabilidad; cada entrada debe ser enlazable por URLs limpias y razonables.
6. Link entre raíz (sin tocar hasta permiso), portal y Etics solo después de aprobación; evitar duplicación extensa de textos de ventas.
7. Vigilar cambios de interfaz de ChatGPT, Claude, Copilot y GHL: revisar guías antiguas cada 60–90 días.

## 5. Pruebas a realizar
**Probar en Chrome desktop + Safari/Chrome mobile si disponibles:** menú, CTA, fuente tipográfica, 360 px sin scroll lateral, lector de pantalla (estructura de H), enlaces al minuto, vídeo YouTube público, relación contraste, formulario, emails, opt-out, recurso ZIP/HTML, acceso comunitario, Etics aparte, sitemap robots/canonical, 404, velocidad imágenes, footer legal. Comprobar idiomas: interfaz **únicamente español**; no selector escondido.

**Go/No-Go**: no publicar si rota vídeo, entrega HTML, consentimiento, dominio existente o DNS de correo. No prometer indexación ni “método probado” sin datos.

## Fuentes relevantes
- https://help.gohighlevel.com/support/solutions/articles/48001073924-custom-meta-tags
- https://help.gohighlevel.com/support/solutions/articles/155000005132-connecting-your-domain-on-ghl-a-guide
- https://help.gohighlevel.com/support/solutions/articles/48001216629-media-storage-file-types-limits-advanced-features
- https://developers.google.com/search/docs/appearance/video


## QA extra V3.5
No eliminar DNS actual para publicar un path; inspeccionar SSL/servidor/302/canonical/noindex. Google Search Console no publica contenido. No utilizar Google ping de sitemap, discontinuado. Comunidad accesible solo a autorizados, HTML sin terceros ni datos sensibles, opt-in newsletter independiente del acceso al recurso.
