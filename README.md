# Mundial 2026 Predictor

Modelo predictivo del Mundial 2026 con aprendizaje automático.

## Características

- 48 equipos con sus datos reales
- Predicción de resultado, goles (Over/Under 2.5) y corners (Over/Under 8.5)
- Banco de prueba con 48 amistosos pre-Mundial
- Aprendizaje automático de los resultados
- Bracket completo (grupos + eliminatorias)
- Análisis IA con Gemini (con fallback local)
- Backup manual con un solo botón 💾
- **Datos persistentes en localStorage** — no se borran al cerrar

## Para correr localmente

```bash
npm install
npm run dev
```

## Para desplegar en Vercel

1. Subir esta carpeta a un repositorio de GitHub
2. Ir a vercel.com y conectar el repo
3. Vercel detecta Vite automáticamente y lo despliega
4. Te da una URL tipo `tunombre.vercel.app`

## Storage

Todos los datos se guardan en localStorage del navegador y persisten entre sesiones.
Para hacer backup manual, usar el botón 💾 en el header.
