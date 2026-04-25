# 🎮 Automatización de Recomendación de Videojuegos con n8n

## 📌 Descripción

Este proyecto automatiza la búsqueda, análisis y almacenamiento de videojuegos utilizando n8n, la API de RAWG, OpenAI y Google Sheets.

El flujo realiza las siguientes acciones:

- Consulta videojuegos desde la API de RAWG.
- Filtra títulos según su calificación.
- Obtiene información detallada de cada videojuego.
- Genera una descripción breve utilizando inteligencia artificial.
- Evalúa automáticamente si el juego es recomendado.
- Guarda únicamente las mejores recomendaciones en Google Sheets.
- Registra errores automáticamente en un workflow independiente.

---

## ⚙️ Tecnologías Utilizadas

- n8n
- OpenAI GPT-5 Mini
- RAWG Video Games Database API
- Google Sheets
- JavaScript

---

## 🚀 Funcionalidades

- Ejecución manual o programada diariamente.
- Consumo de APIs externas.
- Transformación y combinación de datos.
- Clasificación inteligente mediante IA.
- Persistencia de datos en Google Sheets.
- Manejo centralizado de errores.

---

## 📂 Archivos Incluidos

- `Videojuegos reseñas.json` - Workflow principal.
- `Registro de errores.json` - Workflow de manejo de errores.

---

## 🔄 Flujo General

Schedule Trigger / Manual Trigger
→ RAWG API
→ Transformación de Datos
→ Consulta Detallada
→ Merge
→ Filtro por Rating
→ OpenAI (Descripción)
→ OpenAI (Decisión)
→ Google Sheets

---

## 👨‍💻 Autor

Nicolás Chacón

Proyecto académico desarrollado con n8n.