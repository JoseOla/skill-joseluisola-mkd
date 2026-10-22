> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.


> **ACTUALIZACIÓN V3.4 (prioridad máxima):** El usuario prefiere un único hub `www.joseluisola.com/aprende` en el hosting actual (si lo permite el editor real), con vídeos alojados en YouTube y playlists enlazadas/incrustadas, **sin crear un post/landing por vídeo**. `aprende.joseluisola.com` y una web nueva GHL quedan como alternativas, no la solución predeterminada. GHL se utiliza para CRM, newsletter, laboratorios, comunidad y Cénit. Antes de proponer el subdominio anterior, consultar `32_DECISION_SIMPLE_YOUTUBE_BLOG_POST_URL_APRENDE.md`. H1 elegido: «No necesitas una agencia de 20 para empezar a vender con IA». NO alterar DNS ni sitio de producción automáticamente.

# 25 · Decisión de marca, dominio y lanzamiento SIN tocar la web de GoDaddy
**Versión 3.3 | 18 oct 2026 | Estado: especificación, NO implementación**

## Decisión definitiva y lo que cambia de v3.2
- Web pública actual `https://joseluisola.com/`: **permanece intacta en GoDaddy**. No migrar, reemplazar, editar ni conectar el `@` ni `www` a GHL durante el piloto.
- Nuevo **portal educativo independiente** creado en GoHighLevel (GHL), primero como sitio de prueba y después bajo una **subdirección técnica separada**: `aprende.joseluisola.com` (nombre sugerido, aún no creado). No es una subcarpeta `/aprender/` del sitio de GoDaddy. `aprende.joseluisola.com` es un **subdominio**.
- `eticsacademy.com`: se conserva como producto de nivel avanzado y acceso a Método Cénit. Comunidad gratuita de GHL: nombre público **Etics IA · Desde Cero** y descriptor visible “La comunidad de Etics Academy para aprender inteligencia artificial desde el principio”. **No crear otra cuenta de GHL ni otra plataforma de pago.**
- Contenido **solo en español**. Eliminar del plan activo menús, `/en/`, `hreflang` y traducción futura. Si en otro momento se solicita, abrir un proyecto distinto.
- Antes de decidir si todo el portal se moverá algún día a la raíz, medir visitas, búsquedas, recursos y comunidad. **Hoy no hay autorización para sustituir la web actual.**

## Por qué el subdominio es la mejor opción provisional
Una web de GoDaddy y otra de GHL pueden convivir bajo el mismo dominio **si cada host se configura de manera independiente**. El subdominio no hereda automáticamente la autoridad SEO de la raíz como si fuese una subcarpeta. Habrá que construir enlaces y relevancia propios. Es el precio asumible por probar sin riesgos de cortar la web actual.

**No confundir** dominio registrado en GoDaddy, DNS gestionado por GoDaddy, hosting web contratado en GoDaddy y constructor web de GoDaddy: pueden ser servicios distintos. Antes de DNS confirmar quién administra los registros reales.

### Protección de operaciones
1. Capturar pantallas de la portada, formularios, política de privacidad y navegación actuales; exportar activos si el proveedor lo permite.
2. Guardar una **copia de seguridad/exportación** del sitio y copia legible de los registros DNS. Registrar `A`, `AAAA`, `CNAME`, `MX`, `TXT`, `CAA`, SPF, DKIM, DMARC, redirecciones y subdominios ya ocupados; comprobar que `aprende` no existe.
3. En GHL crear sitio **nuevo**, no duplicar la web productiva ni cambiar sus URLs.
4. Configurar el portal en la URL temporal de GHL; si esa URL queda accesible, evitar indexación de pruebas y contactos reales. Un `noindex` no es control de acceso. Usar aislamiento/contraseña si GHL lo admite y probar acceso en incógnito.
5. Después de QA, conectar sólo `aprende.joseluisola.com` siguiendo **exactamente** los registros DNS que muestre GHL para el subdominio. La opción de GoDaddy de conexión automática puede modificar DNS: preferir **revisión manual registro por registro** para un proyecto donde no queremos tocar la raíz.
6. **Jamás** modificar o borrar `@`, `www`, `MX`, SPF, DKIM, DMARC u otros TXT existentes por seguir una guía genérica de “conectar dominio”. No cambiar nameservers.
7. Verificar HTTPS/certificado para el subdominio y probar en una ventana privada que `joseluisola.com`, `www.joseluisola.com`, `eticsacademy.com` y el correo siguen funcionando.
8. Hacer público/indexable **solo** el portal de subdominio final cuando haya contenido real, enlaces válidos, meta `robots` correcto y consentimiento configurado. En staging eliminar cualquier `noindex` antes de solicitar indexación final y confirmar que no haya una canónica apuntando por error a la raíz.
9. Añadir un único enlace visible desde la web existente **más adelante, sólo con autorización explícita**. No hay necesidad de tocar la web de GoDaddy para que el subdominio funcione.
10. Mantener plan de reversión: quitar únicamente el registro `aprende` si falla la nueva web, sin interrumpir raíz ni correo.

> **Comprobación obligatoria:** un enlace a la nueva web no es migración. Si en el futuro se solicita cambio de dominio raíz se necesita un plan SEO/301/infraestructura nuevo y aprobación específica.

## Titulares: conservar el ADN, bajar la barrera de entrada
**Titular actual observado:** `1 solopreneur + IA vende más que una agencia de 20.` Es memorable y diferenciador, pero compara resultados de forma absoluta; mantenerlo en la landing de GoDaddy sin cambios y no presentarlo en el nuevo portal como un hecho probado sin evidencia suficiente.

**Recomendación para la portada educativa GHL:**
- **Eyebrow/sello:** `EL PODER DE 1 SOLOPRENEUR + IA`
- **H1 opción A (recomendada):** `No necesitas una agencia de 20 para empezar a vender con IA.`
- **H1 opción B (con curiosidad):** `¿Puede 1 solopreneur con IA competir con una agencia de 20?`
- **H1 opción C (más didáctica):** `Empieza con IA. Haz lo que antes parecía trabajo de un equipo.`
- **Subtítulo aprobado:** `Clases prácticas, herramientas gratuitas y demostraciones reales para que aprendas paso a paso, aunque nunca hayas utilizado IA.`
- **CTA dominante:** `Ver mi primera clase gratis` -> `/empieza-aqui/`
- **CTA secundario:** `Conocer Radar de Negocios IA` -> `/radar/` una vez exista emisión anunciada; antes usar “Qué es Radar IA” con explicación, nunca fecha inventada.
- **Microconfianza:** `Sin tecnicismos innecesarios · Ejercicios para Chrome · Aprende a tu ritmo`.

Prueba el H1 con usuarios reales: que una persona de 45 años sin experiencia entienda el beneficio en menos de 10 segundos. No dejar H1 abstracto ni prometer ventas automáticas.

## Nombre de comunidad
Candidatos y tratamiento: `Etics IA` (muy corto, genérico), **`Etics IA · Desde Cero`** (claro, elegido), `Etics Primeros Pasos` (más cálido), `Etics IA Inicial` (neutro). En menú se ve **“Comunidad”**; dentro el nombre de marca completo. No mezclar la comunidad gratuita con el acceso de pago al Método Cénit.

## Diferencia operativa entre «Guías» y «Brújula»
| Campo | Guías educativas | Brújula del Solopreneur |
|---|---|---|
| Qué es | Página web pública de consulta, orientada a resolver una búsqueda | Envío periódico por email a quienes optan por recibirlo |
| Cómo llega el usuario | Google, enlaces internos, YouTube | Suscripción voluntaria y CRM GHL |
| Vida útil | Evergreen: se actualiza cuando cambia la herramienta | Fecha/edición: reflexiva o Brújula-Lab, conserva registro histórico |
| Función | Mostrar pasos, definiciones, errores y ejercicios | Mantener relación, narrar aprendizaje y promover el siguiente ejercicio |
| CTA | Ver una clase / usar HTML / suscripción opcional | Volver al vídeo, responder al reto, explorar guía o HTML |

**Evitar duplicación SEO**: guías tienen cuerpo propio, útil y revisado; en el archivo de Brújula usar resúmenes únicos de cada edición o seleccionar canónica si se republica el email íntegro y queda equivalente a otra página. No añadir dos versiones indexables del mismo texto sin estrategia.

## Fuentes de comprobación
- HighLevel, conexión dominio/subdominio: https://help.gohighlevel.com/support/solutions/articles/155000005132-connecting-your-domain-on-ghl-a-guide
- HighLevel, metadatos `noindex`: https://help.gohighlevel.com/support/solutions/articles/48001073924-custom-meta-tags
- Sitio público existente: https://joseluisola.com/


## Corrección esencial V3.5
Que GoDaddy sea **registrador del dominio** no prueba que GoDaddy sea el constructor de la web. Si `www` YA está conectado a GHL y allí reside la landing actual, crear ruta GHL `/aprende` puede ser sencillo. Si `www` está servido por otra plataforma, DNS no permite dirigir solo el path. Ver `35_RUTAS_SUBDOMINIO_DNS_GODADDY_GHL_EXPLICADO.md`.
