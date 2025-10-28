# Deploy rápido (Render)

1) https://render.com → New → Web Service → **Upload Folder** deste ZIP.
2) Build: `npm install`
3) Start: `node server/server.js`
4) Environment: crie as variáveis do `.env.example`.

# Conectar com a sua landing (Hostinger)
- Suba `site/index.html` no `public_html`.
- Se o servidor estiver em outro domínio (onrender.com), adicione antes de </head> na sua página:
  <script>window.API_URL="https://SEU-APP.onrender.com";</script>

# Webhook Mercado Pago
POST https://SEU-APP.onrender.com/api/mp_webhook
