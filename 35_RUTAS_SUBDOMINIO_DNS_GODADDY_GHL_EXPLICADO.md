# 35 · www.joseluisola.com/aprende versus aprende.joseluisola.com: explicación sin confusiones
**V3.5 · No se han tocado GoDaddy, DNS, ni GHL.**

## Nombres correctos
- `www.joseluisola.com` es un **host/subdominio** llamado `www`.
- `www.joseluisola.com/aprende` = **ruta o carpeta virtual** del host `www`. NO es un subdominio.
- `aprende.joseluisola.com` = **otro host/subdominio** cuyo nombre DNS es `aprende`.
- Que ambos estén «en GoDaddy» puede significar únicamente que se compró/gestionó el dominio con GoDaddy. Eso NO garantiza que la web de `www` y la de `aprende` estén servidas por el mismo constructor.

## Por qué el DNS no selecciona una carpeta
El DNS resuelve **nombres de host** a servicios/direcciones; no conoce rutas HTTP como `/aprende`, `/brujula` o `/curso`. Conceptualmente:

```text
Navegador solicita https://www.joseluisola.com/aprende
  1. DNS resuelve www.joseluisola.com → servidor/plataforma A
  2. HTTPS conecta con esa plataforma A
  3. Solicitud HTTP incluye el path /aprende
  4. La plataforma A decide qué página devolver para /aprende
```

Si GHL sirve actualmente `www.joseluisola.com`, puedes crear en GHL la página con slug `/aprende` sin problema. **Si GHL NO sirve `www`**, crear `/aprende` dentro de GHL no altera la ruta del servidor A y cambiar un DNS afectaría a todo el host `www`, no solo a `/aprende`.

## Tres escenarios válidos y sus pasos
### Escenario A: www servido por GHL; GoDaddy solo registra el dominio
**Sí:** crear página en GHL → slug `/aprende` → publicar en ese Website/Funnel y mismo dominio conectado → probar URL y SEO. No se necesita nuevo registro DNS si www ya apunta correctamente a GHL. Crear la página no debe sobrescribir home ni otras rutas. Comprobar que el slug no colisiona.

### Escenario B: www servido por GoDaddy Website Builder / WordPress / otro hosting
**Sí:** crear `/aprende` allí mismo y enlazar GHL para formulario, newsletter y comunidad. No requiere tocar DNS para publicar esa ruta. Puede incrustarse una playlist YouTube y miniaturas con botones.

### Escenario C: www en GoDaddy y nuevo sitio de GHL separado
**Sí:** apuntar DNS solo de `aprende.joseluisola.com` a GHL (CNAME u otro registro según la instrucción ACTUAL de GHL, sin marcar www). Menú de `www` enlaza al nuevo host. Ambos conservan el mismo dominio registrable, pero `aprende.` no es `/aprende`. Se verifica Search Console como dominio global o host correspondiente.

### Cuarto escenario, no recomendado como MVP
Que `/aprende` de `www` apunte internamente a GHL mientras el resto del host está en otro proveedor **requiere una capa que reciba HTTP y lo enrute por path** (reverse proxy/CDN/rewrite en servidor); o mover www completo a GHL. Un enlace o redirección de `/aprende` hacia `aprende.` sí funciona, pero **la dirección visible cambia**. No es lo mismo que servir contenido GHL conservando la ruta.

## Comprobación en cinco minutos sin cambiar producción
1. Abrir panel GHL → Settings → Domains. ¿Está allí `www.joseluisola.com` realmente conectado a Website/Funnel GHL?
2. Abrir GoDaddy → Mis Productos: distinguir **Dominios** (registrador/DNS) de **Websites + Marketing**, **WordPress** o **Hosting**.
3. En GHL `Sites → Websites` ubicar el proyecto que publica hoy el dominio; comprobar la URL de la home sin editar/publicar cambios.
4. Abrir la web en navegador privado: comparar URL real con y sin `www` (podría haber redirección al dominio raíz).
5. Decidir entre escenario A, B o C; realizar copia/QA y solo entonces publicar. Si se usa Domain Connect automático, inspeccionar registros propuestos **antes de autorizar**, evitando «Also add www» si www debe mantenerse fuera de GHL.

## Seguridad GoDaddy
- Nunca borrar registros MX, TXT SPF/DKIM/DMARC o nameservers como parte de crear un subdominio.
- Si agregas subdominio en GHL, cambiar únicamente host solicitado; preservar @ y www si ya funcionan en otro proveedor.
- Verificar HTTPS, navegación, formulario y sistema de correo tras cambios.

## Referencias oficiales
- GHL configuración dominio/subdominio https://help.gohighlevel.com/support/solutions/articles/48001153720-how-to-set-up-root-domain-subdomain-for-your-funnels-websites-
- GHL conexión automática y advertencia www https://help.gohighlevel.com/support/solutions/articles/155000000734-how-to-use-the-domain-connect-feature-
- GoDaddy creación de página https://www.godaddy.com/es-es/help/agregar-una-pagina-a-mi-sitio-web-24072
