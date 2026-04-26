# erp-demo · evidencias multimedia

Repositorio público (solo assets, sin código) para evidencias de los tickets del proyecto privado [erp-demo](https://github.com/JefersonFlores/erp-demo).

Los archivos acá se referencian desde las subpáginas de evidencia en Notion (vía URL raw de GitHub).

## Estructura

- `tickets/ERP-N.png` — screenshot principal de cada ticket (Swagger UI o pantalla relevante).
- `flow/auth-N-*.png` — capturas paso a paso del flujo de autenticación end-to-end (Playwright).
- `videos/auth-flow.{gif,mp4,webm}` — video del flujo completo: redirect a login → validación → creds inválidas → login OK → home → logout.

Generados con [Playwright](https://playwright.dev/) + [ffmpeg](https://ffmpeg.org/) corriendo contra backend FastAPI + frontend Vite local.
