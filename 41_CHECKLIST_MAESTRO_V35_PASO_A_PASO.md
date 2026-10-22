# CHECKLIST MAESTRO DE IMPLEMENTACIÓN — KIT JOSÉ LUIS OLA V3.5

> **Estado real de partida:** todos los pasos de plataforma se consideran **PENDIENTES DE VERIFICACIÓN**. Los documentos del kit describen un plan y no prueban que se hayan configurado cuentas, automatizaciones, dominios, transmisiones, cobros o indexación.

**Fecha del material:** 18 de octubre de 2026 · **Total:** 213 tareas en 16 fases.

## CÓMO USAR ESTE CHECKLIST (OBLIGATORIO)
1. Empieza por **P00 y P01**. No publiques ni modifiques DNS hasta resolver qué sistema sirve `www` y la ruta `/aprende`.
2. Marca una tarea como **Hecho** solo después de comprobar la columna **Prueba / criterio de terminado**.
3. Estados: `Pendiente`, `En curso`, `Bloqueado`, `Hecho`, `Omitido` (este último requiere razón).
4. Si una tarea está bloqueada, escribe el obstáculo y deja para después las dependientes.
5. Toma **un bloque por vez**. Después de cada bloque, comprueba la **PUERTA DE SALIDA** de la fase.
6. Conserva el ZIP V3.5 original; usa este checklist para la operación, sin dar por implementado lo documentado.

## DECISIONES FIJADAS EN EL KIT

- Audiencia 25–55 con foco 30–55, empezando en IA nivel cero, sin tratar al adulto como niño.
- H1 del hub: **No necesitas una agencia de 20 para empezar a vender con IA**; subtítulo aprobado.
- Hub único `/aprende` preferido **solo si el host admite esa ruta**; subdominio `aprende.` es alternativa diferente.
- **Un vídeo largo semanal**, 2–3 Shorts, Brújula semanal, Radar inicialmente quincenal. Ajustar a tus horas reales.
- **ETICS IA · DESDE CERO** gratis durante fase inicial: preguntas, retos, práctica y feedback; no duplicar YouTube.
- Primeros recursos: dos HTML para Chrome; revisar antes de distribuirlos.
- **Una skill + 20 módulos** bajo demanda; comando: `PAQUETE_TOTAL | TÍTULO: ... | NIVEL: 0`.
- Método Cénit permanece para avanzados. Resultados sin maquillaje propios, en pausa hasta disponer de prueba suficiente y revisar D90.
- Google indexa a su criterio: publicar en GHL o verificar Search Console **no garantiza** indexación ni ranking.

## MAPA DE FASES Y PUERTAS DE SALIDA

| Fase | Bloque | Cuándo | Evidencia para avanzar | Tareas |
|---|---|---|---|---:|
| P00 | Seguridad, fuente de verdad y tablero | S1 | Avanzar si existe copia del kit, control de accesos y checklist maestro con responsables. | 12 |
| P01 | Diagnóstico DNS, hosting y ruta /aprende | S1 | No avanzar con URLs públicas si no sabemos quién sirve el host www y la ruta prevista. | 12 |
| P02 | Posicionamiento, diseño y recorrido del alumno | S1 | H1 y subtítulo claros; principiante encuentra lección 1 en menos de dos clics. | 8 |
| P03 | YouTube: creación, seguridad y estructura | S1-S2 | Canal verificado con 1 vídeo piloto no listado y playlists operativas. | 16 |
| P04 | Portal mínimo /aprende e integración YT | S1-S2 | Página móvil publicada, sin tarjetas rotas ni espacios vacíos, con vídeo o playlist funcional. | 17 |
| P05 | SEO de Google y medición web | S2-S3 | Google propiedad verificada, URL inspeccionada y sitemap correcto o causa documentada. | 14 |
| P06 | GHL CRM, formulario, consentimiento y automatizaciones | S1-S3 | Tres pruebas completas exitosas: no opt-in; opt-in; avanzado. | 20 |
| P07 | Lead magnets HTML Chrome seguros | S2 | Un HTML real probado, enlazado desde clase y entregado con instrucciones claras. | 10 |
| P08 | Brújula del Solopreneur | S2-S3 | Primera edición enviada únicamente a quien dio consentimiento; clics y respuestas medidos. | 10 |
| P09 | ETICS IA · DESDE CERO — comunidad GHL | S3-S5 | Registro real, normas y reto #001 probados en un usuario de prueba. | 12 |
| P10 | Skill V3.5 y fábrica de clases desde un título | S1-S13 | EP001 producido con PAQUETE_TOTAL, revisado y publicado con evidencia. | 16 |
| P11 | Shorts con puente al vídeo largo | S2-S13 | Cada Short publicado tiene puente correcto al largo y se mide por separado. | 9 |
| P12 | Radar de Negocios IA en vivo | S3-S13 | Ensayo no listado y emisión #001 finalizada con replay, recurso y aprendizaje. | 16 |
| P13 | Etics Academy: rutas de monetización avanzadas | S5-S9 | Oferta y formulario avanzados funcionan por separado; venta y coste se pueden registrar. | 11 |
| P14 | Métricas, atribución, economía y aprendizaje | S1-S13 | Tablero con valores iniciales reales y revisión de 7/30 días por formato. | 14 |
| P15 | Lanzamiento seguro, validación y expansión controlada | S2-S13 | Persona principiante completa VER → APLICAR → COMPARTIR → REGRESAR sin ayuda. | 16 |

## PRIMERAS 48 HORAS (SECUENCIA EXACTA)

**Sesión 1 (60–90 min):** abre el ZIP V3.5 original; lee README, 40, 34 y 35; guarda copia; abre el Excel adjunto; ejecuta P00-01, P00-02, P00-03 y P00-04.

**Sesión 2 (60–90 min):** entra a GoDaddy **sin cambiar registros**, observa DNS; entra a GHL > Domains y observa la asociación del host; abre la web desde cuatro variantes con/sin www, http/https; realiza P01-01 a P01-04.

**Sesión 3 (30–45 min):** elige y documenta uno de estos escenarios:
- **A**: `www` servido por GHL → crear la página `/aprende` en ese Website/funnel, sin tocar el dominio de producción hasta validar en borrador.
- **B**: `www` servido por otro constructor → crear `/aprende` en ese constructor y usar GHL para CRM/captura.
- **C**: no viable A/B → conectar `aprende.joseluisola.com` a GHL mediante DNS **solo del subdominio**, dejando root/www/MX sin cambios.

**Sesión 4 (45–60 min):** aprobar H1, subtítulo, menú mínimo y primer EP001; preparar borrador del hub. No añadir secciones vacías.

El primer hito es **probar una URL de aprendizaje** y el **primer formulario**, no terminar una web de 15 pestañas.

## P00 · SEGURIDAD, FUENTE DE VERDAD Y TABLERO

**Objetivo:** Evitar duplicados, cambios a producción y trabajo invisible.

**Ventana:** S1 · **Documentos del kit:** `README; 40; 19; SKILL.md`

- [ ] **P00-01 — Guardar el kit V3.5 original sin editar** · `P0` · 15 min
  - **Acción exacta:** Conservar ZIP original y trabajar siempre sobre copia operacional
  - **Prueba / terminado:** ZIP original copiado y marcado V3.5
  - **Depende de:** `Ninguna`

- [ ] **P00-02 — Abrir y leer orden de precedencia** · `P0` · 30 min
  - **Acción exacta:** Leer README, 40 y 34-40 antes de documentos antiguos
  - **Prueba / terminado:** Regla V3.5 escrita en notas
  - **Depende de:** `P00-01`

- [ ] **P00-03 — Crear carpeta única operativa** · `P0` · 20 min
  - **Acción exacta:** Separar 01_Estrategia 02_YT 03_GHL 04_HTML 05_Brujula 06_Radar 07_Analytics 08_Etics
  - **Prueba / terminado:** Estructura verificable
  - **Depende de:** `P00-01`

- [ ] **P00-04 — Abrir checklist y asignar fechas reales** · `P0` · 20 min
  - **Acción exacta:** Definir fecha de arranque y estatus: Pendiente, En curso, Bloqueado, Hecho, Omitido
  - **Prueba / terminado:** Hoja con fecha de inicio
  - **Depende de:** `P00-01`

- [ ] **P00-05 — Inventariar accesos sin guardar contraseñas** · `P0` · 25 min
  - **Acción exacta:** Confirmar quién administra GoDaddy, GHL, YouTube, correo y Search Console
  - **Prueba / terminado:** Inventario sin credenciales sensibles
  - **Depende de:** `Ninguna`

- [ ] **P00-06 — Activar 2FA y recuperación** · `P0` · 30 min
  - **Acción exacta:** Activar autenticación multifactor y cuentas de recuperación en plataformas
  - **Prueba / terminado:** Capturas sin secretos
  - **Depende de:** `P00-05`

- [ ] **P00-07 — Registrar infraestructura actual** · `P0` · 30 min
  - **Acción exacta:** Anotar URL principal, redirecciones www, editor web, hosting, DNS y correo
  - **Prueba / terminado:** Ficha de estado antes del cambio
  - **Depende de:** `P00-05`

- [ ] **P00-08 — Guardar respaldo disponible de la web actual** · `P0` · 45 min
  - **Acción exacta:** Exportar o duplicar con función del proveedor; capturar rutas y formularios
  - **Prueba / terminado:** Backup revisable y fecha
  - **Depende de:** `P00-07`

- [ ] **P00-09 — Crear registro de cambios** · `P0` · 15 min
  - **Acción exacta:** Cada cambio debe tener fecha, estado, respaldo y camino de reversión
  - **Prueba / terminado:** Bitácora creada
  - **Depende de:** `P00-04`

- [ ] **P00-10 — Definir restricciones de publicación** · `P0` · 10 min
  - **Acción exacta:** No tocar DNS, enviar correos ni activar cobros durante pruebas sin validar
  - **Prueba / terminado:** Regla en bitácora
  - **Depende de:** `P00-09`

- [ ] **P00-11 — Separar demostraciones y datos reales** · `P0` · 20 min
  - **Acción exacta:** Establecer etiquetas SIMULACIÓN, CASO PÚBLICO, RESULTADO PROPIO
  - **Prueba / terminado:** Plantilla de evidencia
  - **Depende de:** `P00-04`

- [ ] **P00-12 — Guardar enlaces y fuentes oficiales** · `P1` · 20 min
  - **Acción exacta:** Crear lista de documentación de GHL, Google y YouTube que se revisará antes de usar
  - **Prueba / terminado:** Archivo FUENTES actualizado
  - **Depende de:** `P00-04`

**PUERTA DE SALIDA P00:** Avanzar si existe copia del kit, control de accesos y checklist maestro con responsables.

---

## P01 · DIAGNÓSTICO DNS, HOSTING Y RUTA /APRENDE

**Objetivo:** Elegir UNA arquitectura viable, sin afectar el dominio y correo existentes.

**Ventana:** S1 · **Documentos del kit:** `25; 27; 32; 33; 35`

- [ ] **P01-01 — Comprobar proveedor que sirve la portada** · `P0` · 30 min
  - **Acción exacta:** Determinar si www y raíz se sirven en GHL, GoDaddy Web Builder, WordPress u otro
  - **Prueba / terminado:** Captura del panel y URL final
  - **Depende de:** `P00-07`

- [ ] **P01-02 — Comprobar redirección raíz y www** · `P0` · 20 min
  - **Acción exacta:** Abrir http/https con y sin www y registrar la canónica efectiva
  - **Prueba / terminado:** Tabla de 4 URLs y su destino
  - **Depende de:** `P01-01`

- [ ] **P01-03 — Inventariar DNS A CNAME MX TXT** · `P0` · 30 min
  - **Acción exacta:** Ver GoDaddy DNS sin modificar nada, anotar solo registros necesarios
  - **Prueba / terminado:** Captura redactada sin datos privados
  - **Depende de:** `P00-07`

- [ ] **P01-04 — Comprobar dominio conectado en GHL** · `P0` · 15 min
  - **Acción exacta:** Settings > Domains o ubicación equivalente y activo que lo usa
  - **Prueba / terminado:** Captura de lista de dominios GHL
  - **Depende de:** `P01-01`

- [ ] **P01-05 — Decidir escenario A /aprende en GHL** · `P0` · 20 min
  - **Acción exacta:** Si GHL sirve el host y admite el slug sin colisión, crear ruta en ese Website
  - **Prueba / terminado:** Decisión A documentada o descartada
  - **Depende de:** `P01-01`

- [ ] **P01-06 — Decidir escenario B /aprende en constructor actual** · `P0` · 20 min
  - **Acción exacta:** Si GHL no sirve host, crear ruta en el constructor actual y conectar GHL para CRM
  - **Prueba / terminado:** Decisión B documentada o descartada
  - **Depende de:** `P01-01`

- [ ] **P01-07 — Decidir escenario C aprende.subdominio en GHL** · `P0` · 20 min
  - **Acción exacta:** Solo si A y B no encajan, elegir host independiente sin tocar www o MX
  - **Prueba / terminado:** Decisión C documentada o descartada
  - **Depende de:** `P01-01`

- [ ] **P01-08 — Registrar URL pública oficial de Aprender** · `P0` · 15 min
  - **Acción exacta:** Escribir URL exacta que realmente se abrirá; no suponer www ni slash
  - **Prueba / terminado:** URL principal validada
  - **Depende de:** `P01-05`

- [ ] **P01-09 — Comprobar colisiones de rutas** · `P0` · 20 min
  - **Acción exacta:** Buscar si /aprende ya existe en GHL u otro CMS; no sobrescribir
  - **Prueba / terminado:** Captura sin conflicto
  - **Depende de:** `P01-08`

- [ ] **P01-10 — Preparar entorno de prueba** · `P0` · 30 min
  - **Acción exacta:** Crear borrador o ruta temporal no indexable antes de exponer cambios
  - **Prueba / terminado:** Preview accesible solo en prueba
  - **Depende de:** `P01-08`

- [ ] **P01-11 — Comprobar impacto sobre email** · `P0` · 25 min
  - **Acción exacta:** Verificar que no se tocaron MX/SPF/DKIM/DMARC en proceso de publicación
  - **Prueba / terminado:** Correo de prueba entregado
  - **Depende de:** `P01-10`

- [ ] **P01-12 — Crear procedimiento de reversión** · `P0` · 20 min
  - **Acción exacta:** Si publicar rompe ruta: volver a anterior página/activo DNS concreto y comprobar web/correo
  - **Prueba / terminado:** Rollback documentado
  - **Depende de:** `P01-10`

**PUERTA DE SALIDA P01:** No avanzar con URLs públicas si no sabemos quién sirve el host www y la ruta prevista.

---

## P02 · POSICIONAMIENTO, DISEÑO Y RECORRIDO DEL ALUMNO

**Objetivo:** Conservar el gancho comercial y explicar de inmediato la puerta educativa.

**Ventana:** S1 · **Documentos del kit:** `00; 01; 10; 28; 30`

- [ ] **P02-01 — Aprobar el H1 del portal** · `P0` · 10 min
  - **Acción exacta:** Usar No necesitas una agencia de 20 para empezar a vender con IA
  - **Prueba / terminado:** H1 literal registrado
  - **Depende de:** `P00-02`

- [ ] **P02-02 — Aprobar subtítulo consensuado** · `P0` · 10 min
  - **Acción exacta:** Clases prácticas, herramientas gratuitas y demostraciones reales...
  - **Prueba / terminado:** Subtítulo aprobado
  - **Depende de:** `P02-01`

- [ ] **P02-03 — Definir público y no público** · `P0` · 30 min
  - **Acción exacta:** Adultos 30-55 y entrada 25, IA nivel 0; avanzado va a Cénit
  - **Prueba / terminado:** Ficha avatar y lenguaje
  - **Depende de:** `P00-02`

- [ ] **P02-04 — Definir promesa verificable** · `P0` · 20 min
  - **Acción exacta:** Aprender una tarea útil por clase y poder practicar, sin promesas de ingresos
  - **Prueba / terminado:** Promesa de página escrita
  - **Depende de:** `P02-03`

- [ ] **P02-05 — Definir 4 ejes repetibles** · `P0` · 20 min
  - **Acción exacta:** Escribir, presentar/vender, atender/organizar, decidir/medir
  - **Prueba / terminado:** Mapa de temas final
  - **Depende de:** `P02-03`

- [ ] **P02-06 — Definir diseño móvil y accesibilidad** · `P1` · 35 min
  - **Acción exacta:** Contraste, tamaño de texto, botones grandes, subtítulos y navegación simple
  - **Prueba / terminado:** Mini design system
  - **Depende de:** `P02-01`

- [ ] **P02-07 — Definir los CTA por nivel** · `P0` · 25 min
  - **Acción exacta:** Nivel 0: ver clase; nivel 1: HTML; avanzado: Cénit opcional
  - **Prueba / terminado:** Matriz CTA por usuario
  - **Depende de:** `P02-03`

- [ ] **P02-08 — Validar copy ético del gancho** · `P0` · 15 min
  - **Acción exacta:** No afirmar que realmente se supera a agencia de 20; usar como invitación a aprender
  - **Prueba / terminado:** Nota de sustento y límites
  - **Depende de:** `P02-01`

**PUERTA DE SALIDA P02:** H1 y subtítulo claros; principiante encuentra lección 1 en menos de dos clics.

---

## P03 · YOUTUBE: CREACIÓN, SEGURIDAD Y ESTRUCTURA

**Objetivo:** Dejar el canal preparado para publicar, orientar y medir.

**Ventana:** S1-S2 · **Documentos del kit:** `02; 05; 10; 15; 38`

- [ ] **P03-01 — Crear o verificar canal con cuenta controlada** · `P0` · 30 min
  - **Acción exacta:** Elegir cuenta Google con 2FA, permisos y recovery
  - **Prueba / terminado:** Canal y acceso documentados
  - **Depende de:** `P00-06`

- [ ] **P03-02 — Establecer identidad y @handle** · `P0` · 45 min
  - **Acción exacta:** Nombre José Luis Ola, foto, banner y enlaces reales
  - **Prueba / terminado:** Perfil visible completo
  - **Depende de:** `P03-01`

- [ ] **P03-03 — Escribir descripción de canal SEO humana** · `P0` · 35 min
  - **Acción exacta:** Quién aprende y qué aplica, sin sobrepromesas; link al hub real
  - **Prueba / terminado:** Descripción publicada
  - **Depende de:** `P02-04`

- [ ] **P03-04 — Configurar país/idioma y funciones** · `P0` · 25 min
  - **Acción exacta:** Revisar país de residencia y funciones avanzadas pertinentes
  - **Prueba / terminado:** Panel comprobado
  - **Depende de:** `P03-01`

- [ ] **P03-05 — Verificar canal y estado de transmisión** · `P0` · 20 min
  - **Acción exacta:** YouTube Studio > configuración/funciones, activar live si es posible
  - **Prueba / terminado:** Confirmación de aptitud o bloqueo documentado
  - **Depende de:** `P03-01`

- [ ] **P03-06 — Crear playlist Nivel 0** · `P0` · 20 min
  - **Acción exacta:** No pública vacía si no tiene contenido; preparar título y descripción
  - **Prueba / terminado:** Playlist al menos con EP001 al publicar
  - **Depende de:** `P03-02`

- [ ] **P03-07 — Definir niveles 1-6** · `P0` · 20 min
  - **Acción exacta:** Crear estructura editorial, publicar playlist solo al disponer de clases
  - **Prueba / terminado:** Mapa 0-6 guardado
  - **Depende de:** `P02-05`

- [ ] **P03-08 — Crear plantillas de descripción** · `P0` · 30 min
  - **Acción exacta:** Incluye resultado, audiencia, recurso real, capítulos REALES y siguiente clase
  - **Prueba / terminado:** Plantilla de texto validada
  - **Depende de:** `P03-03`

- [ ] **P03-09 — Configurar valores por defecto de carga** · `P0` · 30 min
  - **Acción exacta:** Idioma, categoría, licencia, comentarios, visibilidad borrador y derechos
  - **Prueba / terminado:** Captura de configuración
  - **Depende de:** `P03-03`

- [ ] **P03-10 — Crear plantilla visual de miniaturas** · `P0` · 60 min
  - **Acción exacta:** 1280x720 proporción 16:9, 2-4 palabras, historia visual y contraste
  - **Prueba / terminado:** 3 variantes de prueba exportadas
  - **Depende de:** `P02-06`

- [ ] **P03-11 — Grabar piloto privado/no listado** · `P0` · 60 min
  - **Acción exacta:** Probar imagen, audio, pantalla, derechos y edición
  - **Prueba / terminado:** Reproducción comprobada en móvil
  - **Depende de:** `P03-01`

- [ ] **P03-12 — Crear protocolo de capítulos** · `P0` · 20 min
  - **Acción exacta:** Capturar marcas desde grabación, no inventar timestamps
  - **Prueba / terminado:** Plantilla y EP piloto validado
  - **Depende de:** `P03-08`

- [ ] **P03-13 — Preparar playlist final y pantallas finales** · `P1` · 25 min
  - **Acción exacta:** Enlaces entre lecciones publicadas, no futuras
  - **Prueba / terminado:** Plan de sesión y ejemplo
  - **Depende de:** `P03-06`

- [ ] **P03-14 — Abrir YouTube Analytics y registrar base** · `P0` · 20 min
  - **Acción exacta:** Capturar valores cero / N.D. según existan
  - **Prueba / terminado:** Baseline con fecha
  - **Depende de:** `P03-01`

- [ ] **P03-15 — Inspeccionar derechos musicales y multimedia** · `P0` · 15 min
  - **Acción exacta:** Solo imágenes/audio propios, autorizados o licenciados
  - **Prueba / terminado:** Registro por episodio
  - **Depende de:** `P03-11`

- [ ] **P03-16 — Revisar YPP vigente y reforma 2027** · `P1` · 20 min
  - **Acción exacta:** Antes de prometer anuncios verificar sección Monetización/Ingresos y política oficial
  - **Prueba / terminado:** Captura de estado elegibilidad
  - **Depende de:** `P03-04`

**PUERTA DE SALIDA P03:** Canal verificado con 1 vídeo piloto no listado y playlists operativas.

---

## P04 · PORTAL MÍNIMO /APRENDE E INTEGRACIÓN YT

**Objetivo:** Crear UNA página útil sin 30 landings, con rutas por nivel y CTA correcto.

**Ventana:** S1-S2 · **Documentos del kit:** `27; 28; 32; 33; 35`

- [ ] **P04-01 — Crear página /aprende en sitio correcto** · `P0` · 35 min
  - **Acción exacta:** Según resolución P01, sin cambiar home actual
  - **Prueba / terminado:** Borrador visible en panel correcto
  - **Depende de:** `P01-08`

- [ ] **P04-02 — Aplicar H1 y subtítulo aprobado** · `P0` · 35 min
  - **Acción exacta:** Hero H1, párrafo, botón de primera clase
  - **Prueba / terminado:** Hero hecho y legible móvil
  - **Depende de:** `P04-01`

- [ ] **P04-03 — Poner una única CTA primaria** · `P0` · 20 min
  - **Acción exacta:** Comenzar primera clase; secundaria Brújula o Radar solo real
  - **Prueba / terminado:** Un CTA claro y probado
  - **Depende de:** `P04-02`

- [ ] **P04-04 — Construir Ruta 0-6** · `P0` · 45 min
  - **Acción exacta:** Mostrar niveles próximos como itinerario, NO enlazar vacíos
  - **Prueba / terminado:** Mapa visual con Nivel 0 activo
  - **Depende de:** `P03-07`

- [ ] **P04-05 — Incrustar vídeo 001 o playlist nivel 0** · `P0` · 30 min
  - **Acción exacta:** Usar código de embed proporcionado por YouTube; no autoplay innecesario
  - **Prueba / terminado:** Vídeo reproducible desktop y móvil
  - **Depende de:** `P03-11`

- [ ] **P04-06 — Crear sección últimos vídeos minimalista** · `P0` · 30 min
  - **Acción exacta:** Inicialmente 1 destacado, luego máximo 3; enlazar directamente a YT
  - **Prueba / terminado:** Tarjetas con enlaces reales
  - **Depende de:** `P04-05`

- [ ] **P04-07 — Configurar miniaturas optimizadas** · `P1` · 25 min
  - **Acción exacta:** Texto alternativo, carga apropiada y sin enlaces rotos
  - **Prueba / terminado:** Test imágenes carga
  - **Depende de:** `P04-06`

- [ ] **P04-08 — Incluir recursos HTML reales** · `P0` · 30 min
  - **Acción exacta:** Mostrar solo herramientas validadas, enlace y para qué sirven
  - **Prueba / terminado:** Descarga abre en Chrome
  - **Depende de:** `P07-04`

- [ ] **P04-09 — Incluir bloque Brújula** · `P0` · 40 min
  - **Acción exacta:** Formulario genuino o enlace al formulario; privacidad y consentimiento
  - **Prueba / terminado:** Alta de prueba recibida
  - **Depende de:** `P06-09`

- [ ] **P04-10 — Incluir comunidad sin enlace ficticio** · `P1` · 20 min
  - **Acción exacta:** Publicar cuando GHL acceso probado, o bloquear del menú sin página vacía
  - **Prueba / terminado:** Acceso correcto o sección oculta
  - **Depende de:** `P09-09`

- [ ] **P04-11 — Incluir Radar solo si existe fecha/replay** · `P1` · 25 min
  - **Acción exacta:** Mostrar próximo directo real y/o archivo; no anunciar fechas ficticias
  - **Prueba / terminado:** Enlace probado
  - **Depende de:** `P12-06`

- [ ] **P04-12 — Incluir vínculo discretamente a Etics Academy** · `P1` · 20 min
  - **Acción exacta:** Solo para usuarios preparados; no confundir formación avanzada con nivel 0
  - **Prueba / terminado:** CTA comercial opcional comprobado
  - **Depende de:** `P02-07`

- [ ] **P04-13 — Crear navegación por fases** · `P0` · 30 min
  - **Acción exacta:** Inicio/Aprende/Brújula y más menús solo cuando haya contenido
  - **Prueba / terminado:** 0 páginas públicas vacías
  - **Depende de:** `P04-01`

- [ ] **P04-14 — Revisar versión móvil y accesibilidad** · `P0` · 40 min
  - **Acción exacta:** En iPhone/Android validar botones, vídeo, formularios y scroll
  - **Prueba / terminado:** QA móvil firmado
  - **Depende de:** `P04-05`

- [ ] **P04-15 — Probar velocidad sin inflar embeds** · `P1` · 35 min
  - **Acción exacta:** No incrustar 30 vídeos en una sola página; priorizar 1 player y tarjetas
  - **Prueba / terminado:** Carga satisfactoria observada
  - **Depende de:** `P04-05`

- [ ] **P04-16 — Probar todos los enlaces** · `P0` · 25 min
  - **Acción exacta:** Usar modo incógnito para rutas y external links; 0 404
  - **Prueba / terminado:** Checklist de enlaces
  - **Depende de:** `P04-13`

- [ ] **P04-17 — Publicar con control de cambios** · `P0` · 30 min
  - **Acción exacta:** Solo una vez completado QA; registrar URL final, rollback y fecha
  - **Prueba / terminado:** URL real pública y backup
  - **Depende de:** `P04-16`

**PUERTA DE SALIDA P04:** Página móvil publicada, sin tarjetas rotas ni espacios vacíos, con vídeo o playlist funcional.

---

## P05 · SEO DE GOOGLE Y MEDICIÓN WEB

**Objetivo:** Que Google pueda descubrir el hub y tú puedas medirlo, sin promesas de ranking.

**Ventana:** S2-S3 · **Documentos del kit:** `02; 09; 23; 29; 34; 35`

- [ ] **P05-01 — Elegir URL canónica y título SEO** · `P0` · 25 min
  - **Acción exacta:** Evitar duplicados www/sin-www y títulos repetidos
  - **Prueba / terminado:** URL definitiva y title únicos
  - **Depende de:** `P04-17`

- [ ] **P05-02 — Escribir meta descripción original** · `P0` · 20 min
  - **Acción exacta:** Beneficio real, IA desde cero, herramientas y marca
  - **Prueba / terminado:** Meta description publicada
  - **Depende de:** `P05-01`

- [ ] **P05-03 — Validar H1 único y jerarquía H2** · `P0` · 20 min
  - **Acción exacta:** Texto comprensible, encabezados ordenados, enlaces descriptivos
  - **Prueba / terminado:** Revisión HTML visual
  - **Depende de:** `P04-02`

- [ ] **P05-04 — Comprobar indexabilidad de página final** · `P0` · 35 min
  - **Acción exacta:** HTTP 200, HTTPS, sin noindex/robots bloqueantes, sin login
  - **Prueba / terminado:** Live Test accesible
  - **Depende de:** `P04-17`

- [ ] **P05-05 — Verificar propiedad Search Console** · `P0` · 45 min
  - **Acción exacta:** Propiedad Dominio o prefijo URL; TXT si es necesario, sin modificar MX
  - **Prueba / terminado:** Consola propiedad verificada
  - **Depende de:** `P01-08`

- [ ] **P05-06 — Comprobar sitemap real del host** · `P0` · 35 min
  - **Acción exacta:** GHL Settings/Domains/XML sitemap según versión; no asumir ruta
  - **Prueba / terminado:** Sitemap abre y contiene URL
  - **Depende de:** `P04-17`

- [ ] **P05-07 — Enviar sitemap solo si existe** · `P1` · 15 min
  - **Acción exacta:** Search Console > Sitemaps; registrar resultado
  - **Prueba / terminado:** Sitemap enviado y estado conocido
  - **Depende de:** `P05-06`

- [ ] **P05-08 — Inspeccionar la URL /aprende** · `P0` · 20 min
  - **Acción exacta:** Probar URL publicada y Solicitar indexación cuando corresponde
  - **Prueba / terminado:** Solicitud o error anotado
  - **Depende de:** `P05-04`

- [ ] **P05-09 — Insertar enlace desde web principal** · `P0` · 35 min
  - **Acción exacta:** Añadir menú o CTA Aprender IA GRATIS hacia hub verdadero
  - **Prueba / terminado:** Click desde home funciona
  - **Depende de:** `P04-17`

- [ ] **P05-10 — Analizar SEO del home sin destruirlo** · `P1` · 60 min
  - **Acción exacta:** Revisar title/descripción, claridad, CTAs, enlaces e intención de búsqueda
  - **Prueba / terminado:** Lista de 5 mejoras priorizadas
  - **Depende de:** `P01-01`

- [ ] **P05-11 — Configurar GA4 si necesario** · `P1` · 50 min
  - **Acción exacta:** Crear flujo del host real; consentimiento conforme jurisdicción
  - **Prueba / terminado:** Páginas vistas verificadas
  - **Depende de:** `P04-17`

- [ ] **P05-12 — Normalizar UTM de YouTube** · `P1` · 20 min
  - **Acción exacta:** Crear patrón consistent: utm_source=youtube y campaña episodios
  - **Prueba / terminado:** URL modelo y prueba GHL
  - **Depende de:** `P06-07`

- [ ] **P05-13 — Revisar Google a 14 y 30 días** · `P1` · 30 min
  - **Acción exacta:** Impresiones, consultas, indexación; no confundir ausencia de datos con fracaso
  - **Prueba / terminado:** Reporte con fecha
  - **Depende de:** `P05-08`

- [ ] **P05-14 — Crear criterio para futura guía SEO** · `P2` · 30 min
  - **Acción exacta:** Solo transformar vídeos con demanda y ángulo propio, no todos
  - **Prueba / terminado:** Matriz sí/no por vídeo
  - **Depende de:** `P10-15`

**PUERTA DE SALIDA P05:** Google propiedad verificada, URL inspeccionada y sitemap correcto o causa documentada.

---

## P06 · GHL CRM, FORMULARIO, CONSENTIMIENTO Y AUTOMATIZACIONES

**Objetivo:** Entregar HTML, segmentar por nivel sin forzar llamadas y respetar preferencias.

**Ventana:** S1-S3 · **Documentos del kit:** `06; 07; 08; 09; 13; 14; 18`

- [ ] **P06-01 — Auditar la subcuenta GHL actual** · `P0` · 45 min
  - **Acción exacta:** Verificar contactos, dominios, formularios, sender, pagos y automations existentes
  - **Prueba / terminado:** Inventario sin borrar activos
  - **Depende de:** `P00-05`

- [ ] **P06-02 — Evitar duplicar contactos y tags** · `P0` · 25 min
  - **Acción exacta:** Auditar registros y convenciones antes de crear nuevos
  - **Prueba / terminado:** Lista de nombres sin colisiones
  - **Depende de:** `P06-01`

- [ ] **P06-03 — Crear campos OLA_IA_NIVEL y OLA_INTERES** · `P0` · 30 min
  - **Acción exacta:** Single select y multi-select según necesidades actuales
  - **Prueba / terminado:** Campos probados en contacto de prueba
  - **Depende de:** `P06-02`

- [ ] **P06-04 — Crear campos OLA_SITUACION e INTENCION** · `P0` · 30 min
  - **Acción exacta:** Explorando/vendedor/pyme/servicios y aprendizaje/interés Cénit
  - **Prueba / terminado:** Campos y opciones documentadas
  - **Depende de:** `P06-02`

- [ ] **P06-05 — Crear etiquetas esenciales** · `P0` · 25 min
  - **Acción exacta:** EDU_LEVEL_0, NEWS_OK, INT_ETICS, CALL_BOOKED, CUSTOMER_CENIT solo en condiciones reales
  - **Prueba / terminado:** Tags con definiciones
  - **Depende de:** `P06-02`

- [ ] **P06-06 — Preparar una captura ligera** · `P0` · 45 min
  - **Acción exacta:** Email obligatorio, nombre opcional, tres preguntas educativas, enlace privacidad
  - **Prueba / terminado:** Formulario construido
  - **Depende de:** `P06-03`

- [ ] **P06-07 — Separar newsletter de descarga** · `P0` · 30 min
  - **Acción exacta:** Casilla voluntaria de marketing sin preseleccionar; consentimiento registrable
  - **Prueba / terminado:** Dos tests de consentimiento
  - **Depende de:** `P06-06`

- [ ] **P06-08 — Decidir entrega del archivo HTML** · `P0` · 30 min
  - **Acción exacta:** Thank You page + link o envío transaccional permitido; reducir fallos
  - **Prueba / terminado:** Acceso a descarga funcional
  - **Depende de:** `P06-06`

- [ ] **P06-09 — Crear W01 Form Submitted entrega** · `P0` · 60 min
  - **Acción exacta:** Disparador filtrado al formulario correcto; no duplicación; recurso correcto
  - **Prueba / terminado:** Test end-to-end nuevo contacto
  - **Depende de:** `P06-08`

- [ ] **P06-10 — Crear W02 Brújula opt-in** · `P0` · 50 min
  - **Acción exacta:** Solo correos a NEWS_OK, baja válida, bienvenida una vez
  - **Prueba / terminado:** Test suscripción/baja
  - **Depende de:** `P06-07`

- [ ] **P06-11 — Crear W03 seguimiento suave 3/7 días** · `P1` · 45 min
  - **Acción exacta:** Solo si hay permiso de marketing aplicable; nunca declarar actividad no medida
  - **Prueba / terminado:** Emails de prueba correctos
  - **Depende de:** `P06-10`

- [ ] **P06-12 — Crear W04 interés explícito Cénit** · `P1` · 45 min
  - **Acción exacta:** Solo si se pulsa registro comercial/solicitud; sin crear pipeline de novatos
  - **Prueba / terminado:** Contacto se segmenta bien
  - **Depende de:** `P06-04`

- [ ] **P06-13 — Preparar W05 citas solo cuando se requieran** · `P2` · 45 min
  - **Acción exacta:** Customer Booked Appointment, confirmación, recordatorio, show/no-show
  - **Prueba / terminado:** Reserva de prueba y precall
  - **Depende de:** `P06-12`

- [ ] **P06-14 — Revisar dominio de envío email** · `P0` · 60 min
  - **Acción exacta:** SPF/DKIM/DMARC aplicables según proveedor y sin tocar entradas a ciegas
  - **Prueba / terminado:** Test Gmail/Outlook entregado
  - **Depende de:** `P06-01`

- [ ] **P06-15 — Crear página de privacidad y bajas** · `P0` · 45 min
  - **Acción exacta:** Texto legal adaptado a ubicación y datos tratados; enlace en formularios
  - **Prueba / terminado:** URLs verificables
  - **Depende de:** `P06-06`

- [ ] **P06-16 — Test nuevo sin newsletter** · `P0` · 20 min
  - **Acción exacta:** Registra, descarga, NO recibe marketing
  - **Prueba / terminado:** Comportamiento observado
  - **Depende de:** `P06-09`

- [ ] **P06-17 — Test nuevo con newsletter** · `P0` · 20 min
  - **Acción exacta:** Recibe bienvenida una vez; sabe darse de baja
  - **Prueba / terminado:** Comportamiento observado
  - **Depende de:** `P06-10`

- [ ] **P06-18 — Test contacto repetido y baja** · `P0` · 25 min
  - **Acción exacta:** No duplica correo ni reactiva suscripción no consentida
  - **Prueba / terminado:** Comportamiento observado
  - **Depende de:** `P06-09`

- [ ] **P06-19 — Test error descarga y móvil** · `P0` · 30 min
  - **Acción exacta:** Botón existe, no revela datos de otros, HTML funciona
  - **Prueba / terminado:** QA móvil/Chrome
  - **Depende de:** `P07-04`

- [ ] **P06-20 — Test flujo avanzado voluntario** · `P1` · 25 min
  - **Acción exacta:** Acceso Cénit sí, novatos nunca pasan pipeline sin interés
  - **Prueba / terminado:** QA comercial
  - **Depende de:** `P06-12`

**PUERTA DE SALIDA P06:** Tres pruebas completas exitosas: no opt-in; opt-in; avanzado.

---

## P07 · LEAD MAGNETS HTML CHROME SEGUROS

**Objetivo:** Asegurar que recurso útil y sencillo funcione sin almacenar datos personales sensibles.

**Ventana:** S2 · **Documentos del kit:** `07; 10; 29; lead_magnets/`

- [ ] **P07-01 — Inventariar 2 HTML existentes** · `P0` · 15 min
  - **Acción exacta:** Abrir Laboratorio de prompts y Calculadora, comprobar versión fuente
  - **Prueba / terminado:** Inventario HTML_001 / HTML_002
  - **Depende de:** `P00-01`

- [ ] **P07-02 — Probar HTML_001 en Chrome** · `P0` · 40 min
  - **Acción exacta:** Abrir offline, generar prompt, copiar, resetear, no errores consola
  - **Prueba / terminado:** Prueba funcional registrada
  - **Depende de:** `P07-01`

- [ ] **P07-03 — Probar HTML_002 en Chrome** · `P0` · 35 min
  - **Acción exacta:** Validar matemáticas con 3 ejemplos, indicar simulación y unidades
  - **Prueba / terminado:** Casos de prueba registrados
  - **Depende de:** `P07-01`

- [ ] **P07-04 — Analizar accesibilidad y móvil** · `P1` · 40 min
  - **Acción exacta:** Texto, focus, labels, teclado y uso con pantalla pequeña
  - **Prueba / terminado:** QA de interfaz
  - **Depende de:** `P07-02`

- [ ] **P07-05 — Revisar seguridad de los HTML** · `P0` · 40 min
  - **Acción exacta:** No credenciales, localStorage de PII sin avisar, ni scripts remotos innecesarios
  - **Prueba / terminado:** Informe de inspección
  - **Depende de:** `P07-02`

- [ ] **P07-06 — Preparar descarga final** · `P0` · 30 min
  - **Acción exacta:** Nombre sencillo, versión, instrucciones, licencia y origen
  - **Prueba / terminado:** ZIP/HTML listo para Chrome
  - **Depende de:** `P07-05`

- [ ] **P07-07 — Crear página de entrega/Thank You** · `P0` · 40 min
  - **Acción exacta:** Guía abrir archivo; alternativa de copia online si móvil no soporta descarga
  - **Prueba / terminado:** Landing de gracias probada
  - **Depende de:** `P06-08`

- [ ] **P07-08 — Asociar HTML a EP001** · `P0` · 15 min
  - **Acción exacta:** Una clase, un ejercicio útil, un link verdadero
  - **Prueba / terminado:** Ficha EP001 con recurso
  - **Depende de:** `P10-10`

- [ ] **P07-09 — Documentar cambios y nuevas versiones** · `P1` · 20 min
  - **Acción exacta:** ID, fecha, comportamiento, privacidad, compatibilidad
  - **Prueba / terminado:** Changelog HTML
  - **Depende de:** `P07-06`

- [ ] **P07-10 — Publicar recurso solo si aporta** · `P1` · 15 min
  - **Acción exacta:** No imponer HTML nuevo semanal; reutilizar si es mejor
  - **Prueba / terminado:** Decisión pedagógica por episodio
  - **Depende de:** `P07-09`

**PUERTA DE SALIDA P07:** Un HTML real probado, enlazado desde clase y entregado con instrucciones claras.

---

## P08 · BRÚJULA DEL SOLOPRENEUR

**Objetivo:** Fidelizar sin crear un segundo canal de contenidos independiente.

**Ventana:** S2-S3 · **Documentos del kit:** `07; 09; 15; 36`

- [ ] **P08-01 — Auditar newsletter actual sin alterarla** · `P0` · 30 min
  - **Acción exacta:** Ver estructura de Brújula y enlaces reales, lista, periodicidad
  - **Prueba / terminado:** Edición y automatización actuales documentadas
  - **Depende de:** `P06-01`

- [ ] **P08-02 — Mantener dos formatos editoriales** · `P0` · 35 min
  - **Acción exacta:** Original: reflexión útil; Brújula-Lab: vídeo+HTML+reto
  - **Prueba / terminado:** Plantilla de cada formato
  - **Depende de:** `P08-01`

- [ ] **P08-03 — Definir calendario editorial mensual** · `P0` · 25 min
  - **Acción exacta:** Una edición jueves, alternar según valor, no por obligación HTML
  - **Prueba / terminado:** 4 fechas o secuencia
  - **Depende de:** `P08-02`

- [ ] **P08-04 — Crear plantilla de asunto y preheader** · `P1` · 15 min
  - **Acción exacta:** Sin clickbait, aprendizaje explícito
  - **Prueba / terminado:** 2 asuntos testeables
  - **Depende de:** `P08-02`

- [ ] **P08-05 — Redactar primer correo nivel 0** · `P0` · 50 min
  - **Acción exacta:** Una idea, enlace EP001, un ejercicio, respuesta fácil
  - **Prueba / terminado:** Email borrador revisado
  - **Depende de:** `P10-11`

- [ ] **P08-06 — Verificar campos y enlaces** · `P0` · 30 min
  - **Acción exacta:** Link HTML, vídeo, baja, privacidad y personalización
  - **Prueba / terminado:** Test email de escritorio y móvil
  - **Depende de:** `P08-05`

- [ ] **P08-07 — Enviar a segmento consentido** · `P0` · 20 min
  - **Acción exacta:** Solo NEWS_OK; guardar fecha y audiencia real
  - **Prueba / terminado:** Envio real registrado
  - **Depende de:** `P06-10`

- [ ] **P08-08 — Registrar clics, bajas y replies** · `P1` · 20 min
  - **Acción exacta:** No fiarse solo de aperturas por privacidad
  - **Prueba / terminado:** Datos de campaña en tabla
  - **Depende de:** `P08-07`

- [ ] **P08-09 — Responder comentarios útiles** · `P1` · 30 min
  - **Acción exacta:** Extraer preguntas reales para EP002 y Radar sin exponer identidad
  - **Prueba / terminado:** Banco de dudas anonimizado
  - **Depende de:** `P08-07`

- [ ] **P08-10 — Revisar valor semanal en 10 min** · `P1` · 15 min
  - **Acción exacta:** ¿Aprenden o solo clican? Continuar/ajustar frecuencia
  - **Prueba / terminado:** Nota de revisión
  - **Depende de:** `P08-08`

**PUERTA DE SALIDA P08:** Primera edición enviada únicamente a quien dio consentimiento; clics y respuestas medidos.

---

## P09 · ETICS IA · DESDE CERO — COMUNIDAD GHL

**Objetivo:** Crear espacio de aplicación que no replique clase, podcast ni newsletter.

**Ventana:** S3-S5 · **Documentos del kit:** `06; 10; 36; communities`

- [ ] **P09-01 — Comprobar Communities habilitado** · `P0` · 20 min
  - **Acción exacta:** Validar plan/permisos GHL de la subcuenta
  - **Prueba / terminado:** Panel Communities accesible
  - **Depende de:** `P06-01`

- [ ] **P09-02 — Crear comunidad con nombre exacto** · `P0` · 30 min
  - **Acción exacta:** ETICS IA · DESDE CERO y descripción de objetivo gratuito
  - **Prueba / terminado:** Comunidad borrador existente
  - **Depende de:** `P09-01`

- [ ] **P09-03 — Crear 3 espacios iniciales** · `P0` · 40 min
  - **Acción exacta:** Bienvenida y Avisos / Preguntas y Ayuda / Retos y Resultados
  - **Prueba / terminado:** Solo 3 canales, no 12 vacíos
  - **Depende de:** `P09-02`

- [ ] **P09-04 — Escribir normas y privacidad** · `P0` · 30 min
  - **Acción exacta:** No compartir datos de clientes, anuncios sensibles o credenciales; respeto
  - **Prueba / terminado:** Reglas públicas visibles
  - **Depende de:** `P09-02`

- [ ] **P09-05 — Preparar bienvenida y guía 5 min** · `P0` · 30 min
  - **Acción exacta:** Qué hacer hoy, dónde está primer vídeo, cómo presentar reto
  - **Prueba / terminado:** Post fijado y simple
  - **Depende de:** `P09-03`

- [ ] **P09-06 — Crear reto 001 aplicable 10-15 min** · `P0` · 30 min
  - **Acción exacta:** De EP001, subir mensaje anónimo o explicar mejora obtenida
  - **Prueba / terminado:** Reto publicado como borrador
  - **Depende de:** `P07-08`

- [ ] **P09-07 — Habilitar entrada gratuita controlada** · `P0` · 40 min
  - **Acción exacta:** Formulario/invitación, notificación, verificación acceso
  - **Prueba / terminado:** Prueba con cuenta alternativa
  - **Depende de:** `P09-02`

- [ ] **P09-08 — Decidir moderación y disponibilidad** · `P0` · 15 min
  - **Acción exacta:** Horario semanal de 1-2 bloques de respuestas; normas no prometer 24/7
  - **Prueba / terminado:** Política visible
  - **Depende de:** `P09-04`

- [ ] **P09-09 — Activar comunidad públicamente solo con QA** · `P0` · 30 min
  - **Acción exacta:** Botón desde hub y newsletter si ruta funciona
  - **Prueba / terminado:** Persona de prueba entra sin fricción
  - **Depende de:** `P09-07`

- [ ] **P09-10 — Publicar reto semanal vinculado a vídeos** · `P1` · 30 min
  - **Acción exacta:** Un ejercicio por clase, no otro curso paralelo
  - **Prueba / terminado:** Plan semanal aplicado
  - **Depende de:** `P09-09`

- [ ] **P09-11 — Medir miembros activos y aportes** · `P1` · 20 min
  - **Acción exacta:** Altas, preguntas resueltas, participación autodeclarada
  - **Prueba / terminado:** Tablero semanal
  - **Depende de:** `P09-09`

- [ ] **P09-12 — Mantener comunidad gratuita hasta revisión D90** · `P0` · 10 min
  - **Acción exacta:** No vender cuota por solo ver los vídeos públicos
  - **Prueba / terminado:** Política documentada
  - **Depende de:** `P09-02`

**PUERTA DE SALIDA P09:** Registro real, normas y reto #001 probados en un usuario de prueba.

---

## P10 · SKILL V3.5 Y FÁBRICA DE CLASES DESDE UN TÍTULO

**Objetivo:** Generar producción integral sin releer 41 documentos a mano ni inventar hechos.

**Ventana:** S1-S13 · **Documentos del kit:** `SKILL.md; references/01-20; 37; 38; 39`

- [ ] **P10-01 — Instalar skill maestra en entorno elegido** · `P0` · 50 min
  - **Acción exacta:** Subir carpeta SKILL.md+references+context donde la plataforma soporte skills
  - **Prueba / terminado:** Prueba de carga con comando
  - **Depende de:** `P00-01`

- [ ] **P10-02 — Confirmar 20 referencias presentes** · `P0` · 20 min
  - **Acción exacta:** Comparar módulo SKILL.md con files en references
  - **Prueba / terminado:** 20/20 archivos referenciados
  - **Depende de:** `P10-01`

- [ ] **P10-03 — Crear bitácora de títulos por nivel** · `P0` · 25 min
  - **Acción exacta:** ID EP001 en adelante y foco pedagógico único
  - **Prueba / terminado:** Registro de contenidos abierto
  - **Depende de:** `P02-05`

- [ ] **P10-04 — Elegir EP001 de nivel 0** · `P0` · 30 min
  - **Acción exacta:** Mi primer mensaje comercial con ChatGPT o ejercicio equivalente
  - **Prueba / terminado:** Título y público definidos
  - **Depende de:** `P10-03`

- [ ] **P10-05 — Ejecutar comando único** · `P0` · 45 min
  - **Acción exacta:** PAQUETE_TOTAL + título + nivel; no prometer URLs ni capítulos reales antes de grabar
  - **Prueba / terminado:** Paquete generado completo
  - **Depende de:** `P10-04`

- [ ] **P10-06 — Verificar actualidad de herramientas** · `P0` · 40 min
  - **Acción exacta:** Abrir app real y confirmar funciones, precios/plan y resultados
  - **Prueba / terminado:** Prueba de UI con fecha
  - **Depende de:** `P10-05`

- [ ] **P10-07 — Validar guion 15-18 min** · `P0` · 45 min
  - **Acción exacta:** Una tarea, pasos pantalla, comparación opcional, errores, ejercicio
  - **Prueba / terminado:** Guion ejecutable
  - **Depende de:** `P10-06`

- [ ] **P10-08 — Crear escaleta y grabación** · `P0` · 90 min
  - **Acción exacta:** Guardar demo en pantalla, audio claro, pruebas originales
  - **Prueba / terminado:** Vídeo bruto y permisos
  - **Depende de:** `P10-07`

- [ ] **P10-09 — Editar sin inflar duración** · `P0` · 120 min
  - **Acción exacta:** Cortar esperas, zoom legible, subtítulos y música con derechos
  - **Prueba / terminado:** Export final
  - **Depende de:** `P10-08`

- [ ] **P10-10 — Ajustar capítulos reales** · `P0` · 25 min
  - **Acción exacta:** Marcas exactas derivadas de corte final; no de borrador
  - **Prueba / terminado:** Capítulos reales
  - **Depende de:** `P10-09`

- [ ] **P10-11 — Publicar con pack SEO YT** · `P0` · 40 min
  - **Acción exacta:** Título factual, miniatura, descripción, recurso link, playlist y final screen
  - **Prueba / terminado:** EP001 visible público
  - **Depende de:** `P10-10`

- [ ] **P10-12 — Crear 2-3 Shorts del mismo proyecto** · `P0` · 80 min
  - **Acción exacta:** Diferentes hooks, no 3 copias; preparar related video
  - **Prueba / terminado:** Guiones y 2-3 exportables
  - **Depende de:** `P10-09`

- [ ] **P10-13 — Crear Brújula y reto de EP001** · `P0` · 35 min
  - **Acción exacta:** Reusar investigación, ajustar al nivel y utilidad
  - **Prueba / terminado:** Borradores aprobados
  - **Depende de:** `P10-11`

- [ ] **P10-14 — Registrar tarjeta/enlace en hub** · `P0` · 20 min
  - **Acción exacta:** Si es destacado o primer episodio; playlist se actualiza en YT
  - **Prueba / terminado:** Hub coherente con canal
  - **Depende de:** `P10-11`

- [ ] **P10-15 — Registrar horas reales de producción** · `P0` · 10 min
  - **Acción exacta:** Tiempo investigación/guion/grabación/edición/distribución
  - **Prueba / terminado:** Costo por EP semanal
  - **Depende de:** `P10-11`

- [ ] **P10-16 — Repetir 1 EP semanal, no más por presión** · `P0` · 10 min
  - **Acción exacta:** Enfocar consistencia sostenible; si no hay tiempo reducir formatos
  - **Prueba / terminado:** Plan semanal realista
  - **Depende de:** `P10-15`

**PUERTA DE SALIDA P10:** EP001 producido con PAQUETE_TOTAL, revisado y publicado con evidencia.

---

## P11 · SHORTS CON PUENTE AL VÍDEO LARGO

**Objetivo:** Convertir descubrimiento en consumo profundo y ejercicios útiles.

**Ventana:** S2-S13 · **Documentos del kit:** `02; 05; 15; 38`

- [ ] **P11-01 — Definir 3 ángulos por vídeo** · `P0` · 20 min
  - **Acción exacta:** Problema / demostración / error frecuente, con valor autónomo
  - **Prueba / terminado:** Matriz de clips
  - **Depende de:** `P10-11`

- [ ] **P11-02 — Revisar gancho 0-2 segundos** · `P0` · 15 min
  - **Acción exacta:** Mostrar situación real y beneficio sin promesa engañosa
  - **Prueba / terminado:** Guion breve aprobado
  - **Depende de:** `P11-01`

- [ ] **P11-03 — Editar vertical 9:16** · `P0` · 45 min
  - **Acción exacta:** Subtítulos grandes, encuadre, audio y derechos
  - **Prueba / terminado:** Short revisado en móvil
  - **Depende de:** `P11-02`

- [ ] **P11-04 — Publicar primer Short posterior al largo** · `P0` · 15 min
  - **Acción exacta:** El largo tiene que existir antes del related video
  - **Prueba / terminado:** Publicación real
  - **Depende de:** `P10-11`

- [ ] **P11-05 — Añadir vídeo relacionado** · `P0` · 10 min
  - **Acción exacta:** YT Studio > Contenido > Short > Video relacionado (si hay acceso avanzado)
  - **Prueba / terminado:** Enlace correcto bajo el Short
  - **Depende de:** `P11-04`

- [ ] **P11-06 — Revisar CTA de puente** · `P0` · 10 min
  - **Acción exacta:** Ver explicación completa en el vídeo relacionado sin enlace inventado
  - **Prueba / terminado:** CTA audible o visible
  - **Depende de:** `P11-05`

- [ ] **P11-07 — Registrar desempeño a 7 días** · `P1` · 15 min
  - **Acción exacta:** Vistas Shorts, visto vs pasado, vínculo al largo donde disponible
  - **Prueba / terminado:** Tabla semanal
  - **Depende de:** `P11-04`

- [ ] **P11-08 — Ajustar hooks según datos propios** · `P1` · 25 min
  - **Acción exacta:** No comparar CTR de largos con Shorts directamente
  - **Prueba / terminado:** Decisión documentada
  - **Depende de:** `P11-07`

- [ ] **P11-09 — Crear colección de Shorts por playlist** · `P2` · 25 min
  - **Acción exacta:** Ordenar clips por su nivel al existir contenidos suficientes
  - **Prueba / terminado:** Playlist o sección del canal organizada
  - **Depende de:** `P11-04`

**PUERTA DE SALIDA P11:** Cada Short publicado tiene puente correcto al largo y se mide por separado.

---

## P12 · RADAR DE NEGOCIOS IA EN VIVO

**Objetivo:** Convertir actualidad práctica en encuentro recurrente y monetización futura.

**Ventana:** S3-S13 · **Documentos del kit:** `03; 04_referencia_skill; 16; 38`

- [ ] **P12-01 — Definir intención editorial del Radar** · `P0` · 25 min
  - **Acción exacta:** IA útil para ventas y pymes, no resumen genérico de noticias ni webinar de ventas
  - **Prueba / terminado:** Promesa Radar aprobada
  - **Depende de:** `P02-05`

- [ ] **P12-02 — Definir frecuencia de inicio** · `P0` · 15 min
  - **Acción exacta:** 1 directo cada 2 semanas, 35-45 minutos
  - **Prueba / terminado:** Calendario mensual realista
  - **Depende de:** `P12-01`

- [ ] **P12-03 — Verificar requisitos de YouTube Live** · `P0` · 25 min
  - **Acción exacta:** Canal verificado, sin restricciones y permiso para emitir
  - **Prueba / terminado:** Habilitación comprobada
  - **Depende de:** `P03-05`

- [ ] **P12-04 — Elegir medio de transmisión** · `P0` · 30 min
  - **Acción exacta:** Webcam o OBS si pantalla + micrófono; no comprar equipo por defecto
  - **Prueba / terminado:** Opción operativa decidida
  - **Depende de:** `P12-03`

- [ ] **P12-05 — Diseñar plantilla de emisión** · `P0` · 60 min
  - **Acción exacta:** Portada/agenda/demo/QR o enlace recurso/cierre simple
  - **Prueba / terminado:** Escena de prueba
  - **Depende de:** `P12-04`

- [ ] **P12-06 — Hacer ensayo privado/no listado** · `P0` · 40 min
  - **Acción exacta:** Test audio, captura, latencia, pantalla y privacidad escritorio
  - **Prueba / terminado:** Grabación de ensayo
  - **Depende de:** `P12-05`

- [ ] **P12-07 — Seleccionar 2 novedades verificadas** · `P0` · 45 min
  - **Acción exacta:** Fuentes primarias, fechas, limitaciones y usuario objetivo
  - **Prueba / terminado:** Ficha de investigación
  - **Depende de:** `P12-01`

- [ ] **P12-08 — Preparar una demo realmente probada** · `P0` · 60 min
  - **Acción exacta:** Evitar demo dependiente de herramienta con créditos expirados
  - **Prueba / terminado:** Guion demo y backup visual
  - **Depende de:** `P12-07`

- [ ] **P12-09 — Crear ejercicio de 10 minutos** · `P1` · 30 min
  - **Acción exacta:** HTML existente o micropráctica sin descargar software caro
  - **Prueba / terminado:** Recurso accesible
  - **Depende de:** `P12-08`

- [ ] **P12-10 — Programar Radar #001 con título verificable** · `P0` · 30 min
  - **Acción exacta:** Miniatura, descripción, link a clase/ejercicio, emisión con hora real
  - **Prueba / terminado:** URL real de evento
  - **Depende de:** `P12-06`

- [ ] **P12-11 — Avisar a inscritos voluntarios** · `P1` · 20 min
  - **Acción exacta:** Email a segmento consentido + comunidad, no SMS por defecto
  - **Prueba / terminado:** Mensaje enviado legalmente
  - **Depende de:** `P12-10`

- [ ] **P12-12 — Emitir Radar #001** · `P0` · 60 min
  - **Acción exacta:** Inicio útil, actualidad, demo, costos y riesgos, Q&A, reto; CTA suave
  - **Prueba / terminado:** Emisión archivada
  - **Depende de:** `P12-10`

- [ ] **P12-13 — Editar replay a VOD** · `P0` · 40 min
  - **Acción exacta:** Corregir descripción, capítulos reales, resumen y enlaces
  - **Prueba / terminado:** Replay público de valor
  - **Depende de:** `P12-12`

- [ ] **P12-14 — Crear Shorts y Brújula del Radar** · `P1` · 50 min
  - **Acción exacta:** Hasta 2 clips, uno por utilidad, evitar duplicar clases
  - **Prueba / terminado:** Contenidos derivados
  - **Depende de:** `P12-13`

- [ ] **P12-15 — Medir 7 días después** · `P1` · 30 min
  - **Acción exacta:** Concurrencia, minutos vistos, recurso, registros, horas invertidas
  - **Prueba / terminado:** Reporte Radar #001
  - **Depende de:** `P12-13`

- [ ] **P12-16 — Revisar anuncios cuando YPP corresponda** · `P2` · 20 min
  - **Acción exacta:** Si autorizado: configuración de monetización live y pausas, sin garantizar impresiones
  - **Prueba / terminado:** Estado YPP real
  - **Depende de:** `P03-16`

**PUERTA DE SALIDA P12:** Ensayo no listado y emisión #001 finalizada con replay, recurso y aprendizaje.

---

## P13 · ETICS ACADEMY: RUTAS DE MONETIZACIÓN AVANZADAS

**Objetivo:** Permitir compra directa a usuarios preparados sin presionar alumnado de nivel 0.

**Ventana:** S5-S9 · **Documentos del kit:** `01; 13; 14; 16; 18`

- [ ] **P13-01 — Revisar landing Etics actual** · `P0` · 50 min
  - **Acción exacta:** Oferta, precios vigentes, links, fechas, testimonios y garantía
  - **Prueba / terminado:** QA comercial con capturas
  - **Depende de:** `P00-07`

- [ ] **P13-02 — Alinear promesa Cénit con nivel intermedio/alto** · `P0` · 35 min
  - **Acción exacta:** Cuatro pilares GHL, contenido IA, Make/n8n, Meta Ads sin tratarlo como nivel 0
  - **Prueba / terminado:** Mapa de transición
  - **Depende de:** `P02-03`

- [ ] **P13-03 — Colocar CTA opcional desde hub** · `P1` · 20 min
  - **Acción exacta:** Ya utilizo IA y busco sistema de ventas, enlace único a Etics
  - **Prueba / terminado:** Ruta avanzada útil y discreta
  - **Depende de:** `P04-12`

- [ ] **P13-04 — Crear formulario avanzado solo solicitado** · `P1` · 45 min
  - **Acción exacta:** Datos de negocio, problema y momento, facturación opcional en rangos
  - **Prueba / terminado:** Prueba formulario con consentimiento
  - **Depende de:** `P06-12`

- [ ] **P13-05 — Configurar pipeline para interesados reales** · `P1` · 45 min
  - **Acción exacta:** Etapas Solicitud/Reservó/Asistió/Propuesta/Cliente; no incluir novatos
  - **Prueba / terminado:** Pipeline con casos de prueba
  - **Depende de:** `P13-04`

- [ ] **P13-06 — Configurar agenda/pre-call si aplica** · `P2` · 60 min
  - **Acción exacta:** Página de preparación con agenda, qué aportar y políticas
  - **Prueba / terminado:** Reserva de prueba, URL verdadera
  - **Depende de:** `P13-05`

- [ ] **P13-07 — Implementar recordatorios apropiados** · `P2` · 45 min
  - **Acción exacta:** Email, SMS solo con permiso válido; detener por cancelación
  - **Prueba / terminado:** Casos QA no-show y cancelación
  - **Depende de:** `P13-06`

- [ ] **P13-08 — Verificar pago y fulfillment** · `P1` · 50 min
  - **Acción exacta:** Prueba de checkout y acceso a Cénit, reembolso y facturación
  - **Prueba / terminado:** Pedido prueba controlado
  - **Depende de:** `P13-01`

- [ ] **P13-09 — Definir ingresos por fuente** · `P1` · 25 min
  - **Acción exacta:** Etics/taller/consultoría/ads/afiliados como categorías separadas
  - **Prueba / terminado:** Planilla de ingresos
  - **Depende de:** `P13-08`

- [ ] **P13-10 — Definir referidos y patrocinios éticos** · `P2` · 25 min
  - **Acción exacta:** Afiliados con disclosure, solo herramientas realmente usadas
  - **Prueba / terminado:** Política de divulgación
  - **Depende de:** `P13-09`

- [ ] **P13-11 — Medir show rate y ventas reales** · `P1` · 20 min
  - **Acción exacta:** No atribuir ventas a descargas, registrar asistencia e ingresos cobrados
  - **Prueba / terminado:** KPIs comerciales activos
  - **Depende de:** `P13-05`

**PUERTA DE SALIDA P13:** Oferta y formulario avanzados funcionan por separado; venta y coste se pueden registrar.

---

## P14 · MÉTRICAS, ATRIBUCIÓN, ECONOMÍA Y APRENDIZAJE

**Objetivo:** Medir cuatro capas y costo real para tomar decisiones sin métricas vanidosas.

**Ventana:** S1-S13 · **Documentos del kit:** `09; 16; 19; 39`

- [ ] **P14-01 — Registrar línea base** · `P0` · 20 min
  - **Acción exacta:** Anotar ceros si lo son y N.D. si no hay acceso
  - **Prueba / terminado:** Tabla inicial fechada
  - **Depende de:** `P00-04`

- [ ] **P14-02 — Configurar YouTube Analytics rutina** · `P0` · 25 min
  - **Acción exacta:** Impresiones/CTR por fuente, retención, vistas, returning viewers
  - **Prueba / terminado:** Captura del panel
  - **Depende de:** `P03-14`

- [ ] **P14-03 — Configurar Search Console lectura semanal** · `P0` · 20 min
  - **Acción exacta:** Clics, impresiones, consultas y URL indexación
  - **Prueba / terminado:** Tabla /aprende semanal
  - **Depende de:** `P05-08`

- [ ] **P14-04 — Configurar medición GHL** · `P0` · 35 min
  - **Acción exacta:** Registros y tags, fuente declarada y UTM cuando existan
  - **Prueba / terminado:** Contador fiable de formularios
  - **Depende de:** `P06-09`

- [ ] **P14-05 — Definir eventos verificables** · `P0` · 30 min
  - **Acción exacta:** Clic en recurso ≠ uso de HTML; reto autodeclarado ≠ entrega objetiva
  - **Prueba / terminado:** Diccionario de eventos
  - **Depende de:** `P14-04`

- [ ] **P14-06 — Separar vistas Shorts, largos y Live** · `P0` · 20 min
  - **Acción exacta:** No sumar métricas de retención no comparables
  - **Prueba / terminado:** Pestañas o agrupaciones distintas
  - **Depende de:** `P03-14`

- [ ] **P14-07 — Registrar coste de producción** · `P0` · 20 min
  - **Acción exacta:** Horas propias y herramientas, sin suponer que el tiempo es cero
  - **Prueba / terminado:** Hoja de horas/costes
  - **Depende de:** `P10-15`

- [ ] **P14-08 — Registrar ingresos reales por fuente** · `P1` · 20 min
  - **Acción exacta:** Cobros confirmados, reembolsos, IVA/impuestos por separado donde aplique
  - **Prueba / terminado:** Tabla de ingresos validada
  - **Depende de:** `P13-09`

- [ ] **P14-09 — Definir reunión de 30 min viernes** · `P0` · 10 min
  - **Acción exacta:** 5 min cada capa y una decisión: mantener/ajustar/pausar
  - **Prueba / terminado:** Agenda semanal
  - **Depende de:** `P14-01`

- [ ] **P14-10 — Crear reporte D7 por EP** · `P0` · 30 min
  - **Acción exacta:** Mostrar hallazgos y acciones, sin benchmarks universales
  - **Prueba / terminado:** Scorecard EP001 semana 1
  - **Depende de:** `P10-11`

- [ ] **P14-11 — Revisión D30** · `P0` · 50 min
  - **Acción exacta:** Calidad/uso HTML/primer live/canales/navegación/SEO
  - **Prueba / terminado:** Acta de día 30
  - **Depende de:** `P14-10`

- [ ] **P14-12 — Revisión D60** · `P0` · 50 min
  - **Acción exacta:** Más de un ciclo, actividad comunidad, anuncios no prioritarios
  - **Prueba / terminado:** Acta día 60
  - **Depende de:** `P14-11`

- [ ] **P14-13 — Revisión D90** · `P0` · 90 min
  - **Acción exacta:** Sostenibilidad, tasas, monetización real, activar o no Resultados sin maquillaje
  - **Prueba / terminado:** Acta y plan siguiente trimestre
  - **Depende de:** `P14-12`

- [ ] **P14-14 — Revalidar requisitos YPP enero 2027** · `P1` · 20 min
  - **Acción exacta:** La fuente anuncia 8k horas/20M Shorts desde feb 2027 para nuevos solicitantes; contrastar con Studio
  - **Prueba / terminado:** Nota de cumplimiento con fecha
  - **Depende de:** `P03-16`

**PUERTA DE SALIDA P14:** Tablero con valores iniciales reales y revisión de 7/30 días por formato.

---

## P15 · LANZAMIENTO SEGURO, VALIDACIÓN Y EXPANSIÓN CONTROLADA

**Objetivo:** Asegurar que funciona el circuito completo y no crece la complejidad antes de tiempo.

**Ventana:** S2-S13 · **Documentos del kit:** `05; 17; 19; 29; 31; 40`

- [ ] **P15-01 — Probar visitante móvil anónimo** · `P0` · 25 min
  - **Acción exacta:** Entrar desde home a Aprende y reproducir EP001
  - **Prueba / terminado:** Ruta sin login y sin 404
  - **Depende de:** `P04-17`

- [ ] **P15-02 — Probar visitante con formulario sin marketing** · `P0` · 25 min
  - **Acción exacta:** Entrega HTML pero no secuencia comercial
  - **Prueba / terminado:** Captura de prueba
  - **Depende de:** `P06-16`

- [ ] **P15-03 — Probar visitante con newsletter aceptada** · `P0` · 25 min
  - **Acción exacta:** Recibe bienvenida, Brújula y baja
  - **Prueba / terminado:** Captura de prueba
  - **Depende de:** `P06-17`

- [ ] **P15-04 — Probar retos de comunidad con usuario externo** · `P0` · 30 min
  - **Acción exacta:** Puede postear pregunta sin revelar datos de clientes
  - **Prueba / terminado:** Reto 001 completo
  - **Depende de:** `P09-09`

- [ ] **P15-05 — Probar ruta avanzado sin contaminar CRM educativo** · `P1` · 25 min
  - **Acción exacta:** Interesado explícito encuentra Cénit y puede avanzar
  - **Prueba / terminado:** Prueba pipeline
  - **Depende de:** `P13-04`

- [ ] **P15-06 — Ejecutar QA SEO y enlaces** · `P0` · 45 min
  - **Acción exacta:** Revisar canonical, noindex, sitemap, móvil, contraste, enlaces, políticas
  - **Prueba / terminado:** Informe con 0 errores críticos
  - **Depende de:** `P05-08`

- [ ] **P15-07 — Ejecutar rollback ensayado** · `P0` · 15 min
  - **Acción exacta:** Documentar cómo restaurar ruta anterior en CMS/servidor
  - **Prueba / terminado:** Plan aprobado
  - **Depende de:** `P01-12`

- [ ] **P15-08 — Publicar /aprende y comunicar estreno** · `P0` · 30 min
  - **Acción exacta:** Solo después de pruebas; CTA desde web principal y descripción YT
  - **Prueba / terminado:** Captura publicación
  - **Depende de:** `P15-06`

- [ ] **P15-09 — Recabar feedback de 3 aprendices reales** · `P1` · 60 min
  - **Acción exacta:** Preguntar qué pudieron hacer sin ayuda, privacidad y claridad
  - **Prueba / terminado:** 3 hallazgos anónimos
  - **Depende de:** `P15-08`

- [ ] **P15-10 — Elaborar backlog priorizado** · `P0` · 25 min
  - **Acción exacta:** P0 errores, P1 fricciones, P2 SEO selectivo; quitar funciones vacías
  - **Prueba / terminado:** Backlog y responsables
  - **Depende de:** `P15-09`

- [ ] **P15-11 — No crear landing por episodio por defecto** · `P0` · 10 min
  - **Acción exacta:** Mantener playlist/hub; blog selectivo cuando haga falta
  - **Prueba / terminado:** Regla auditada cada mes
  - **Depende de:** `P10-16`

- [ ] **P15-12 — Decidir blogs selectivos tras 4+ vídeos** · `P2` · 30 min
  - **Acción exacta:** Solo temas que merecen guía original y búsqueda Google
  - **Prueba / terminado:** Lista 0-2 guías prioritarias
  - **Depende de:** `P05-14`

- [ ] **P15-13 — Abrir programa de auditorías cuando haya permisos** · `P2` · 60 min
  - **Acción exacta:** Consultar negocios voluntarios, sin resultados inventados
  - **Prueba / terminado:** Protocolo consentimiento
  - **Depende de:** `P14-12`

- [ ] **P15-14 — Revisar resultados sin maquillaje en D90** · `P1` · 30 min
  - **Acción exacta:** Publicar solo cifras propias documentadas o casos públicos bien identificados
  - **Prueba / terminado:** Acta de activación o prórroga
  - **Depende de:** `P14-13`

- [ ] **P15-15 — Valorar membresía de pago solo con señal de valor** · `P2` · 30 min
  - **Acción exacta:** No vender vídeos duplicados; incluir coaching si hay demanda
  - **Prueba / terminado:** Decisión con encuesta/uso
  - **Depende de:** `P14-13`

- [ ] **P15-16 — Congelar nueva funcionalidad si rompe consistencia** · `P0` · 15 min
  - **Acción exacta:** Si faltan vídeos, pausar buscador avanzado, podcast extra o app nueva
  - **Prueba / terminado:** Prioridades ajustadas
  - **Depende de:** `P15-10`

**PUERTA DE SALIDA P15:** Persona principiante completa VER → APLICAR → COMPARTIR → REGRESAR sin ayuda.

---

## SEMANAS 1–13: ENTREGABLES REALISTAS

| Semana | Prioridad central | Lo que debe quedar publicado o probado | Decisión |
|---|---|---|---|
| S1 | Seguridad, DNS/host, promesa, canal y skill | Arquitectura A/B/C, canal borrador, piloto EP001 | No migrar DNS sin QA |
| S2 | Hub y primer ciclo | `/aprende` real (o subdominio alternativo), EP001, HTML, formulario | ¿Una persona completa la tarea? |
| S3 | SEO/Search Console + 1er Radar | Search Console, EP002, Shorts, Radar #001 y Brújula | ¿Hay fricción técnica? |
| S4 | Constancia y medición D30 | EP003, newsletter, revisión de primeros datos | Corregir antes de escalar |
| S5 | Comunidad mínima | 3 espacios, reto semanal, EP004 | ¿Alguien pregunta/participa? |
| S6 | Repetir circuito | EP005, Brújula, Radar #002, Shorts | Registrar horas por entrega |
| S7 | Mejoras en clase/hub | EP006, primeros datos por nivel | Elegir próxima clase por dudas reales |
| S8 | SEO selectivo y D60 | EP007, 0–1 guía original si tiene sentido, tablero | No crear blog por obligación |
| S9 | Conversión solo si se solicita | EP008, enlace Cénit, QA oferta/checkout | Evitar funnel agresivo a nivel 0 |
| S10 | Fomentar retorno | EP009, Radar #3/#4 según capacidad, emails útiles | ¿Regresan o solo descargan? |
| S11 | Validar títulos/miniaturas | EP010, mejoras en packaging, Shorts puente | Cambiar una variable por vez |
| S12 | Preparar retrospectiva | EP011, revisión de contenidos, costes y SEO | Pausar elementos que resten consistencia |
| S13 | D90 y siguiente trimestre | EP012 si viable, auditoría de métricas, monetización y comunidad | Mantener / ajustar / pausar |

## RUTINA OPERATIVA DE UNA SOLA PERSONA

| Momento | Acción | Resultado |
|---|---|
| Lunes | Elegir una tarea educativa, investigar y ejecutar `PAQUETE_TOTAL` | Guion verificable + HTML reutilizable o nuevo |
| Martes | Grabar demo y editar vídeo largo | Archivo final y capítulos reales |
| Miércoles | Publicar largo y preparar Shorts | Vídeo/playlist + 1er Short y related video |
| Jueves | Enviar Brújula original o Lab; abrir reto | Email útil y aplicación sin duplicar clase |
| Viernes | Medir en 30 min; preparar Radar quincenal | Una decisión de mejora |
| Quincenal | Radar: fuentes, demo, emisión, replay | Directo y fuente de retorno |

## MÉTRICAS SIN INVENTAR DATOS

| Capa | Indicadores | Fuente |
|---|---|---|
| Descubrimiento | Impresiones, CTR por fuente, vistas Shorts, consultas Google | YouTube Studio, Search Console |
| Consumo | Retención primeros 30s, duración media, minutos live | YouTube Studio |
| Fidelización | Clics Brújula, respuestas, miembros activos, retos declarados | GHL, reportes de email, comunidad |
| Negocio | Interés Cénit expresado, citas, ventas cobradas, reembolsos | GHL/pagos |
| Economía | Tiempo y coste por EP, gastos software, ingresos por fuente | Registro propio |

## PUNTOS QUE SIGUEN SIN VERIFICAR EN TUS CUENTAS

- Constructor real que sirve `www.joseluisola.com` y URL canónica actual.
- Estado de verificaciones y funciones avanzadas de YouTube.
- Cuenta GA4/GSC, sitemap exacto y estado de indexación.
- Configuración actual del sender email, consentimiento y workflows GHL.
- Disponibilidad/plan de Communities y acceso real a Etics Academy.
- Precios/fechas vigentes de ofertas; elegibilidad y estado de YPP.

**No marcar como hechos los puntos anteriores por haber descargado este documento.**

## ENLACES DE DOCUMENTACIÓN PARA REVALIDAR

- HighLevel dominios: https://help.gohighlevel.com/support/solutions/articles/48001153720-set-up-a-root-domain-or-subdomain-for-highlevel-sites
- Sitemap GHL: https://help.gohighlevel.com/support/solutions/articles/48001182524-xml-sitemaps
- Blog Post Element (solo entradas GHL Blog): https://help.gohighlevel.com/support/solutions/articles/155000002776-add-blog-post-element-in-funnel-step-or-website-page
- Comunidades: https://help.gohighlevel.com/support/solutions/articles/155000000280-how-to-setup-customize-and-manage-your-communities
- Workflows de formulario: https://help.gohighlevel.com/support/solutions/articles/155000002550-workflow-trigger-form-submitted
- Search Console inspección: https://support.google.com/webmasters/answer/9012289?hl=es
- YouTube en vivo: https://support.google.com/youtube/answer/2474026?hl=es
- Shorts related video: https://support.google.com/youtube/answer/14075157?hl=es
- YPP cambios de febrero 2027: https://support.google.com/youtube/answer/12843009?hl=es

## CONTROL DE VERSIÓN

Este checklist es un **anexo operativo al Kit V3.5**. No actualiza automáticamente GHL ni la plataforma de skills. Si un documento histórico (00–33) contradice decisiones de V3.5, aplicar README, 40 y 34–40. No inventar URL /aprende sin comprobar host.
