> **V3.5 — DECISIÓN VIGENTE (18/10/2026).** 1) No crear página/landing por vídeo: índice `/aprende` con playlists, miniaturas selectivas y enlace a YouTube. 2) `www.joseluisola.com/aprende` es **RUTA**, no subdominio. Puede publicarse desde GHL **si GHL sirve `www`**; si otro host lo sirve, allí mismo o alternativa `aprende.joseluisola.com` en GHL. DNS no enruta carpetas. 3) Google: GHL SEO Meta Data + sitemap real + Search Console; sin garantía de indexación. 4) Comunidad ETICS IA · DESDE CERO = aplicación, retos y feedback, no duplicar YouTube. 5) SKILL con comando único `PAQUETE_TOTAL | TÍTULO: ...` y carga de referencias según necesidad. Consultar **34–40** antes que consejos anteriores contradictorios. No cambiar web/DNS/GHL sin autorización.

# 18 · PROMPTS LISTOS PARA COPIAR EN PLANIFICACIÓN / BUILDER GHL
**Nota operativa:** estas instrucciones producen especificaciones, HTML o guías según tu entorno; pegarlas en GHL no garantiza que el sistema cree automáticamente páginas, campos, automations, eventos o DNS. Siempre instalar/probar de forma manual o mediante un agente con acceso autorizado. No tocar landing Etics actual salvo indicación expresa.

## Prompt A — Hub único de aprendizaje
```text
Actúa como arquitecto UX y de captación en GoHighLevel. Diseña una landing pública nueva de José Luis Ola /empezar (ajusta slug a infraestructura existente SIN romper URLs) para hombres y mujeres de 30 a 55 años que no conocen IA (entrada desde 25), en español claro y adulto. Objetivo: ver EP001 gratuito y conseguir el HTML offline «Mi primer prompt para vender», sin prometer facturación ni exponer servicios avanzados como prerequisito. Incluye hero, demostración visual del HTML, requisitos (Chrome y alternativa móvil), tres beneficios demostrables, pregunta frecuente de privacidad, formulario de opt-in con consentimiento newsletter SEPARADO, sección siguiente vídeo y CTA discreto «¿Ya trabajas con ventas y sistemas? Conoce Método Cénit». Una sola puerta de captura, no múltiples landings por herramienta. Devuelve wireframe, textos, campos, estructura de bloques GHL, estados de éxito/error, SEO meta para no duplicar artículos, checklist QA. Señala toda URL no confirmada como PENDIENTE.
```

## Prompt B — Formulario ramificado sencillo
```text
Configura sobre el papel un formulario GHL con Conditional Logic v2: email obligatorio, nombre opcional, pregunta 1 nivel IA (nunca / probé / uso frecuente), pregunta 2 necesidad (mensajes / anuncios / clientes / organización / otro), pregunta 3 situación (explorando / vendedor / pyme / servicios). Casilla separada no preseleccionada para Brújula, privacidad y envío transaccional de recurso. Si principiante: mostrar gracias+recurso+EP001 y NO preguntar facturación. Si usuario explícitamente quiere Cénit: redirigir a evaluación aparte con 3–4 preguntas comerciales, rangos opcionales, sin rechazar a quien no desea responder. Devuelve tabla de campos, etiquetas, valores, condiciones, flujo por casos y 12 tests. No enviar SMS sin permiso y habilitación legal.
```

## Prompt C — Workflow W01/W02 sin spam
```text
Escribe una guía de construcción de Workflows GHL: W01 cuando se envía formulario principal -> crear/actualizar contacto (sin duplicados), clasificar nivel/interés, enviar email de entrega HTML y link vídeo, guardar origen UTMs si se captura, marcar recurso enviado; W02 separado solo cuando consiente recibir Brújula -> email bienvenida -> entrega newsletter; al darse de baja bloquear correos promocionales. Incluye trigger, filtros, if/else, acciones, reentrada, deduplicación, fallback si link no funciona y pasos de QA con un contacto nuevo, duplicado, no opt-in, opt-out, error de email. NO asumir que mirar un vídeo de YouTube es evento de contacto GHL.
```

## Prompt D — Ruta comercial y pipeline
```text
Diseña el flujo de interés comercial para Etics Academy existente sin modificar precios/oferta: sólo quien pulsa «Conocer Cénit» elige webinar/taller o pide diagnóstico, añade etiqueta INT_ETICS. Si pide llamada, formulario de necesidad, crear oportunidad en pipeline comercial y mostrar calendario; si solo solicita material, no abrir oportunidad. Etapas: SOLICITÓ_INFO, CITA_CONFIRMADA, ASISTIÓ, OFERTA_ENVIADA, GANADO, NO_COMPRÓ, NO_SHOW, NO_ENCAJA. Crea matriz trigger-acción-condición-pausa, asignación humana y tests para cancelación, reserva duplicada y compra. Mantén rutas educativas para no calificados.
```

## Prompt E — Página pre-call sin presión
```text
Diseña pre-call page GHL para comprador avanzado que YA reservó una reunión solicitada. Texto cercano, profesional, sin falsas escaseces: confirmar fecha y zona horaria del calendario real, explicar duración/objetivo, 3 elementos opcionales a preparar sin datos sensibles, expectativas honestas (puede que no exista oferta adecuada), enlace para reprogramar/cancelar, resumen real de Cénit y FAQ sobre para quién NO es. Incluye bloques desktop/mobile, campos dinámicos PENDIENTES, aviso privacidad y prueba de que no se crean slots ficticios.
```

## Prompt F — Recordatorios y no-show
```text
Describe workflows GHL activados por Customer Booked Appointment y Appointment Status: email al reservar, email 24h antes y 2h antes si cabe, SMS solo si consentimiento/legalidad y canal aprobado, y comprobar cada vez si canceló o reprogramó. Si Showed: registrar asistencia real y siguiente paso consultivo. Si No-show: un mensaje cordial con reprogramación, no cadencia agresiva. Si compra: salir de flujo comercial. Asegura zona horaria, no duplicados con notificaciones nativas y tests para reserva <24h, cancelación, no-show, asistió y comprador.
```

## Prompt G — Scorecard editorial, funnel y negocio
```text
Genera un cuadro semanal PARA REGISTRO MANUAL O GA4/GHL/YouTube Studio con columnas: EP, tema T1–T4, nivel, costo-horas, vistas por formato, CTR por fuente, retención, Shorts que conducen a largo, visitas hub, formularios, opt-in Brújula, recursos entregados, retos completados autodeclarados, visitas orgánicas Google, interés Cénit declarado, reservas, asistencia, ventas cobradas, devoluciones, ads YPP si disponible. Fórmulas con denominadores claros y «SIN DATO» cuando no haya evento confiable. No inventar KPI ni dar objetivos de conversión universal.
```

## Prompt H — Experimento con rigor
```text
Diseña un experimento que cambie SOLO UNA VARIABLE de la landing o correo, por ejemplo CTA «Descargar HTML» vs «Crear mi primer mensaje». Define hipótesis, audiencia, criterio de éxito (completó formulario + abrió recurso), ventana temporal, capacidad de medición real en GHL, control de tráfico por canal, tamaño de muestra suficiente o alternativa cualitativa si hay pocos datos, plan de reversión y qué harías si los resultados son inconclusos. Nunca prometer conversión garantizada.
```
