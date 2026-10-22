# 44 · PROMPT MAESTRO: WEB JOSÉ LUIS OLA EN GHL / CLAUDE
**Versión:** 3.5.2 · **Estado:** especificación de diseño, NO web publicada · **Idioma:** español · **Equipo:** una persona.

## Decisión arquitectónica
La versión de producción deseada es `https://joseluisola.com/` (canonical sin `www`, actualmente `www` redirige a ella). La ruta deseada para aprender es `https://joseluisola.com/aprende` **sólo si el host que atiende el dominio está configurado para servir esa ruta desde GHL**. GoDaddy como registrador no dirige rutas: el DNS no resuelve `/aprende`. Mantener la web actual intacta hasta probar borrador, formularios, SEO y rutas. Si el host actual no permite servir `/aprende` desde GHL, usar temporalmente `https://aprende.joseluisola.com/` y enlazar desde el menú actual, sin migraciones forzosas. No crear URLs falsas ni prometer indexación.

## PROMPT COMPLETO LISTO PARA PEGAR

```text
Actúa como director creativo senior, arquitecto UX/UI, redactor de conversión ético, especialista en SEO de Google y constructor experto de HighLevel. Desarrolla la propuesta visual y funcional de mi web pública de marca personal JOSÉ LUIS OLA. Debe poder ejecutarse por una única persona, por etapas, con bloques editables de GHL, reutilizando el ecosistema y sin generar contenidos ficticios. No publiques ni cambies dominios ni workflows sin mi aprobación.

CONTEXTO Y PROPÓSITO
Marca: José Luis Ola. Negocio avanzado: Etics Academy, Método Cénit. La web pública debe atraer personas de 30 a 55 años (también 25+) que no saben o saben poco de inteligencia artificial y quieren aprender a utilizarla para comunicarse, captar clientes, vender, atender y organizar un pequeño negocio. También debe respetar a visitantes avanzados que necesitan Cénit. No escribir con tono infantil, ni prometer ingresos o ventas garantizados.

PROMESA VISIBLE HERO (TEXTO EXACTO)
H1: «No necesitas una agencia de 20 para empezar a vender con IA».
Subtítulo: «Clases prácticas, herramientas gratuitas y demostraciones reales para que aprendas paso a paso, aunque nunca hayas utilizado IA».
CTA principal: «Empieza gratis, desde cero» → destino REAL de /aprende, o marcador PENDIENTE_URL_APRENDE.
CTA secundario: «Conoce el Método Cénit» → enlace real eticsacademy.com (confirmar URL exacta en la configuración).
No modificar el H1 ni sustituirlo por «Aprende inteligencia artificial desde cero»; esta frase sí puede utilizarse como texto explicativo y SEO.

ESTILO
Marca personal humana, educativa y profesional; editorial premium, navegación minimalista y muy accesible. Reutilizar logo, tipografías y colores reales si se proporcionan; si no, usar provisionalmente base blanco roto + tinta oscura + un color de acento coherente, sin fingir que es la identidad oficial. Botones contrastados, párrafos breves, textos grandes, tarjetas limpias, espacio en blanco, foco claro visible, responsive 360–1440 px, WCAG AA como objetivo, alto rendimiento móvil. Imágenes de José Luis y capturas auténticas sólo cuando se proporcionen. No fabricar retratos, números, resultados, testigos, testimonios, capturas de paneles ni logos de clientes. Usar placeholders explícitos y editables cuando falten materiales.

NAVEGACIÓN DEL LANZAMIENTO (sin pestañas vacías)
Logo José Luis Ola (Inicio) | Empieza aquí | Aprende IA | Brújula | Sobre mí | botón «Empieza gratis».
- Empieza aquí → sección de inicio dentro de /aprende (ancla funcional) o primera clase real.
- Aprende IA → /aprende (catálogo y playlists). No ficha web por cada vídeo.
- Brújula → /brujula (suscripción + archivo si hay contenido real).
- Sobre mí → ancla #sobre-mi en el home o página /sobre-mi con información auténtica.
- Enlaces «Etics Academy», «Antibriefing» y «Contacto» pueden estar en footer/área secundaria sin suprimirlos de la web que ya existe.
No mostrar Radar, Recursos, Blog, Eventos, Consultorio o Comunidad en el menú principal hasta que haya contenido o funcionamiento comprobado; sí se pueden preparar como borradores invisibles. ETICS IA · DESDE CERO será nombre de la comunidad y se mostrará como acceso contextual cuando el registro esté probado. Sólo español.

HOME / — COMPONER EN ESTE ORDEN
01. Encabezado fijo discreto + menú responsive. CTA principal en cabecera. No modal de suscripción automático.
02. HERO: H1 exacto indicado; subtítulo; 2 CTA; imagen real del fundador si disponible; microcopy «Empieza con una clase gratis. Sin experiencia previa».
03. TRES ENTRADAS, TITULAR «¿En qué punto estás?»:
    Tarjeta A «Nunca he usado IA» → Nivel 0.
    Tarjeta B «Ya uso ChatGPT o Copilot» → nivel 1–2.
    Tarjeta C «Quiero vender con un sistema» → Etics Academy.
    Que todas apunten a destinos funcionales o queden sin botón hasta completar su destino.
04. «Tu primera victoria con IA»: un resultado modesto en 15 minutos: elaborar un mensaje claro para responder a un cliente; pasos: ver clase → usar laboratorio HTML → probar → compartir el aprendizaje. Una clase destacada REAL o placeholder PENDIENTE_VIDEO_ID, nunca inventar miniaturas.
05. «Aprende a tu ritmo»: mapa de 7 niveles 0–6. El nivel 0 disponible tras publicar su primera clase; niveles posteriores como trayecto descriptivo, NO enlaces vacíos. Niveles: 0 Primer contacto; 1 Instrucciones y prompts; 2 Mensajes y ofertas; 3 Creativos y presentación; 4 Clientes y seguimiento; 5 Automatización y medición; 6 Cénit avanzado. Evitar títulos técnicos para niveles 0–2.
06. «Últimas clases»: 1 playlist de YouTube incrustada y opcionalmente 3 tarjetas curadas manuales con miniatura auténtica + título + enlace directo a la playlist o a YouTube. No pedir nuevas landings por vídeo. No declarar que GHL Blog Posts sincroniza YouTube (NO lo hace). Para reducir mantenimiento, priorizar playlist actualizada desde YouTube; los destacados son opcionales.
07. «Herramientas que te llevas»: presentar los laboratorios HTML offline para Chrome — Mi primer prompt para vender y Calculadora de ganancia real — solamente si los archivos están realmente disponibles y probados; tarjetas con propósito, nivel, instrucciones para abrir, política de datos, botón descargar.
08. «Radar de Negocios IA»: tarjeta de programa de directos con enfoque práctico y noticias verificadas. Sólo mostrar fecha y acceso a emisión si están confirmados; si no existe próxima fecha, enlazar a playlist Radar o mantener esta sección oculta en inicio.
09. «Brújula del Solopreneur»: newsletter principal. Promesa: «Una idea útil cada jueves. A veces, un laboratorio HTML para aplicar lo aprendido». Formulario de email nativo GHL; consentimiento claro; no suscribir automáticamente a WhatsApp o publicidad sin permiso adicional; enlazar archivo de ediciones reales cuando exista.
10. «ETICS IA · DESDE CERO»: explicar valor distinto de YouTube: retos semanales de 10–15 minutos, preguntas agrupadas, avances, materiales actualizados y comunidad GHL. No ofrecer soporte individual 24/7. CTA «Accede gratis a la comunidad» solo cuando alta y onboarding estén probados.
11. «Sobre José»: biografía y experiencia verificada, por qué enseña desde cero; método educativo VER → APLICAR → COMPARTIR → REGRESAR. No llenar de logotipos ni indicadores de ingresos que no estén documentados.
12. «Cuando quieras avanzar»: un bloque discreto para personas con experiencia: «¿Ya estás listo para construir tu sistema de captación y ventas?» + CTA al Sistema Cénit en eticsacademy.com. No convertir toda la home en webinar comercial.
13. FAQ útil: «¿Debo pagar por ChatGPT?», «¿Necesito saber programar?», «¿Qué aprenderé en la primera clase?», «¿Los recursos HTML se abren en Chrome?», «¿Qué diferencia hay entre comunidad y newsletter?». Responder sin inventar características o precios cambiantes.
14. Footer: marca, accesos funcionales, contacto real, redes existentes, enlace a Etics Academy, privacidad, términos, cookies y preferencias de consentimiento. Si las políticas actuales contienen datos/garantías inconsistentes, MARCAR PARA REVISIÓN, no asumir cumplimiento legal.

PÁGINA /APRENDE — UNA SOLA BIBLIOTECA QUE NO DUPLICA YOUTUBE
H1 «Empieza con IA desde cero. Una clase, un resultado». Introducción de 2 líneas. CTA «Ver mi primera clase»; Ruta educativa niveles 0–6; sección «Clases por nivel» con reproductor o botones a PLAYLISTS REALES de YouTube; «Empieza por aquí» 3 pasos; un reto gratuito; laboratorios HTML; Brújula; comunidad. No abrir páginas por vídeo. Usar una URL o ancla compartible por nivel sólo si GHL lo permite y se prueba; el contenido debe ser fácil de navegar en móvil. Si existe sólo 1 vídeo, mostrar sólo ese y el mapa educativo, NO tarjetas vacías.

PÁGINA /BRUJULA
Cabecera «Brújula del Solopreneur». Texto claro: ideas semanales y, cuando corresponda, Brújula-Lab con HTML asociado a vídeos. Un formulario de email GHL y confirmación útil. Archivo de ediciones sólo si existe, preferiblemente listado/Blog Posts filtrado por categoría si se publica en GHL Blogs; no usar Blog Posts como listado automático de YouTube.

PÁGINA /COMUNIDAD (BORRADOR HASTA QUE FUNCIONE)
Título «ETICS IA · DESDE CERO». Promesa: «Practica con ayuda y avanza a tu ritmo». 3 tarjetas: «Empieza aquí», «Preguntas y ayuda», «Reto semanal». Explicar: acceso gratuito, sin tutoría privada garantizada, respuesta del fundador agrupada en un hilo semanal, reglas de respeto, privacidad de datos y no subir datos reales de clientes. Formulario/CTA de alta al grupo real en GHL; no inventar enlaces. Los materiales duplicados en la comunidad deben consistir en enlaces a la clase pública + ejercicio, no en subida masiva de vídeos.

PÁGINA /SOBRE-MI (OPCIONAL EN MVP)
Narración simple y verificable de quién es José, por qué enseña, promesa del proyecto y acceso al recurso inicial. Evitar superlativos y promesas.

RESERVA DE FUTUROS CONTENIDOS (NO MENÚ EN LANZAMIENTO)
Radar IA /radar; Guías /guias (GHL Blogs, sólo guías seleccionadas con demanda real); Consultorio /consultorio; Eventos /eventos; Herramientas /herramientas; acceso a comunidad. Preparar componentes reutilizables y estructura, pero no indexar borradores vacíos.

SEO Y TÉCNICA
Meta title Home propuesto: «José Luis Ola | IA práctica para vender y trabajar mejor».
Meta description Home propuesto: «Descubre clases gratuitas para usar ChatGPT, Copilot y otras herramientas de IA en tus ventas y tu trabajo. Aprende desde cero, practica y avanza a tu ritmo».
Meta title /aprende: «Aprende IA desde cero gratis | Clases de José Luis Ola».
Meta description /aprende: «Aprende inteligencia artificial con clases gratuitas por niveles, vídeos en YouTube, ejercicios y herramientas HTML para ventas y pequeños negocios».
Solo un H1 por página, encabezados H2/H3 coherentes, enlaces HTML auténticos, imágenes con alt, lazy loading de vídeos no visibles, evitar autoplay, botones con etiquetas accesibles, velocidad móvil, favicon real. Open Graph. Canonical basado en host publicado, comprobar redirección `www`/sin `www`; staging noindex o restringido, retirarlo sólo del dominio publicado tras QA. Añadir sitemap sólo con páginas indexables, vincular Search Console y medir GA4/UTM si existen. No garantizar indexación o rich results. No crear FAQ Schema que no represente FAQ visible.

INTEGRACIÓN GHL
Construir web pública en Sites > Websites o con AI Studio/Funnel & Website AI si disponible. Formulario de suscripción nativo a GHL CRM. Etiquetas mínimas: `origen_youtube`, `origen_web`, `nivel_0`, `interes_comunidad`, `interes_cenit`, `brujula_optin`, `whatsapp_optin` (esta última SÓLO tras consentimiento específico). No capturar información financiera del principiante. Lead magnet HTML descargable sin scripts remotos ni datos enviados. Automatización de bienvenida por email comprobada antes de publicarla. Los miembros de la comunidad se administran en la plataforma de comunidades de GHL y los grupos de WhatsApp se administran aparte; NO PROMETER SINCRONIZACIÓN DE GRUPOS.

RESTRICCIONES DE SEGURIDAD
No tocar dominio actual, DNS, `www`, email, MX, pagos, consentimientos ni formularios de producción. Trabajar en copia/borrador con identificadores PENDIENTE. No crear páginas/indexaciones duplicadas en la web antigua y nueva. No generar opiniones, testimonios, casos de éxito, precios, cifras, fechas o vídeos falsos. Antes de ejecutar cualquier configuración persistente, mostrarme checklist y solicitar autorización.

ENTREGABLE QUE QUIERO DE LA IA
A) sitemap y navegación MVP vs futuro;
B) diseño completo Home con textos listos, no lorem ipsum;
C) diseño /aprende y /brujula;
D) página borrador /comunidad;
E) componentes reutilizables: hero, 3 tarjetas, playlist, CTA, laboratorio, pie legal;
F) especificación responsive y accesibilidad;
G) instrucciones específicas de montaje en GHL y conexiones por validar;
H) tabla de placeholders y enlaces PENDIENTE;
I) checklist QA previo a publicación.
No respondas sólo con recomendaciones: crea el diseño editable en la herramienta en la que estés operando, o entrega el código completo cuando la plataforma sea Claude y no tenga acceso a GHL. Antes de conectar dominio o publicar, detente para revisión.
```

## SI LO GENERAS CON CLAUDE DESIGN / ARTIFACTS
Añade a continuación del prompt: «Entrégame un prototipo en HTML/CSS/JavaScript ligero, responsive, semántico, sin librerías remotas obligatorias, sin formularios que aparenten enviar sin backend. Separa componentes. Donde requiera GHL Form, Blog Post, Communities o CRM, agrega un bloque de integración PENDIENTE y explica dónde montarlo en GHL. No consideres el prototipo publicado hasta integrarlo y probarlo en GHL». Evitar copiar código propietario de webs externas.

## CON GHL AI STUDIO / FUNNEL & WEBSITE AI
1. Revisar si la subcuenta tiene habilitadas funciones AI en Labs; funcionalidad y acceso varían.
2. Crear sitio nuevo de prueba, no editar el existente.
3. Ejecutar prompt por partes si hay límite: Home → /aprende → /brujula → /comunidad → SEO.
4. Sustituir placeholders y enlaces, instalar formularios nativos, configurar workflows sólo tras QA.
5. Revisar móvil, publicación, sitemap, Search Console, consentimientos, redirecciones y `www`.
6. Sólo conectar dominio o cambiar producción previa aprobación expresa.

## Fuentes de referencia (consultadas octubre 2026)
- HighLevel AI Studio: https://help.gohighlevel.com/support/solutions/articles/155000007587-ai-studio-in-highlevel
- HighLevel Funnel & Website AI: https://help.gohighlevel.com/support/solutions/articles/155000006713-funnel-website-ai
- HighLevel Websites: https://help.gohighlevel.com/support/solutions/articles/155000001633
- HighLevel Blog Posts: https://help.gohighlevel.com/support/solutions/articles/155000002776-add-blog-post-element-in-funnel-step-or-website-page
- Google SEO Starter Guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
