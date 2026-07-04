# physiquelogic-site

Sitio estático mínimo para Physique.Logic. Su único propósito actual es hostear una
Privacy Policy y Terms of Service reales, requisito para el audit de la TikTok Content
Posting API (y potencialmente útil para Meta más adelante).

Repo separado del proyecto principal ("Asistente Claude definitivo") a propósito: GitHub
Pages gratis requiere que el repo sea **público**, y el repo principal contiene contexto de
negocio que debe quedarse privado.

## Deploy
1. Crear repo público en GitHub llamado `physiquelogic-site` (o el nombre que prefieras).
2. Push de este contenido a `main`.
3. Settings → Pages → Source: `main` / `/ (root)`.
4. Settings → Pages → Custom domain: `physiquelogic.co` (ya existe el archivo `CNAME`).
5. Configurar DNS en Cloudflare apuntando a GitHub Pages (ver guía completa entregada por
   Claude Code, sesión 2026-07-03).
6. Esperar a que Pages confirme el certificado HTTPS (puede tardar hasta 24h).

## Páginas
- `index.html` — landing mínima
- `privacy-policy.html`
- `terms-of-service.html`
