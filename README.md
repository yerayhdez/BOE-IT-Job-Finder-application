# 🛎️ BOE IT Job Alert System

**BOE IT Job Alert System** es una aplicación web desarrollada con **React + TypeScript** que permite buscar y recibir alertas en tiempo real sobre publicaciones de empleo informático extraídas del [Boletín Oficial del Estado (BOE)](https://boe.es).

> 💡 Esta herramienta es ideal para profesionales TIC que quieren enterarse de oportunidades en el sector público español sin tener que revisar manualmente el BOE cada día.

---

## ⚙️ Tecnologías usadas

- 🧩 React 18
- ⚡ Vite (build rápido y moderno)
- ⛑️ TypeScript
- 📡 Comunicación con modelo IA (Gemini) para interpretación inteligente
- 🧠 `@google/generative-ai` API (requiere clave)
- 🌐 Fetch y análisis semántico de URLs

---

## 🚀 Funcionalidades

- Búsqueda por palabra clave dentro del contenido del BOE.
- Interpretación del texto con IA para filtrar si hay una oferta real de empleo TIC.
- Visualización clara y directa de resultados relevantes.
- Gestión de errores y carga mediante componentes `ErrorMessage` y `LoadingSpinner`.

---

## 📦 Instalación

Clona el repositorio y ejecuta:

```bash
npm install
