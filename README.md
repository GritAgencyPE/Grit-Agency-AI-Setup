# Grit Agency — Gerente Comercial AI

Chat en vivo conectado a GoHighLevel para el equipo de ventas.

## Setup para un cliente nuevo

1. Duplicar el workflow en n8n
2. Cambiar: `N8N_WEBHOOK_URL` en `index.html`
3. Cambiar: logo, nombre, colores
4. Subir a Netlify

## Estructura

```
index.html    → Chat principal (auto-contenido)
```

## Conexión

El chat se conecta al webhook de n8n via POST.
El flujo de n8n debe estar **activo** (publicado).
