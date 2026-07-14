# Monitor de Humedales Urbanos 🌿

Visualizador geoespacial interactivo de **humedales urbanos** y **generadores industriales** de Chile, construido como archivo único HTML.

## 🗺️ Demo

Abre `index.html` directamente en tu navegador — sin servidor, sin instalación.

## ✨ Funcionalidades

- **Mapa interactivo** con MapLibre GL JS (estilo oscuro CartoDB)
- **107 humedales urbanos** categorizados por región, proceso y superficie
- **9.176 generadores industriales** coloreados por rubro
- **Filtros en cascada** con zoom automático
- **Dashboard ECharts** con 12 vistas intercambiables (barras, donuts, histogramas, stacked)
- **Dashboard colapsable** con 3 estados: contraído / normal / expandido
- **Panel lateral retráctil** para maximizar el área del mapa
- **Exportación** a GeoJSON y Shapefile (.zip)
- **Áreas de influencia** (buffer) con Turf.js
- **Intersección espacial** entre capas (punto×polígono, polígono×polígono)
- **Procesamiento asíncrono** con lotes para no congelar la UI
- **Caché persistente** en IndexedDB
- **Popups hover** con estética cyber-hud
- **Cross-filtering** bidireccional mapa ↔ gráficos

## 🛠️ Tecnologías

- HTML5 + Vanilla JS (sin frameworks)
- Tailwind CSS vía CDN
- MapLibre GL JS
- ECharts v5
- Turf.js v6
- JSZip

## 📁 Estructura

| Archivo | Propósito |
|---------|-----------|
| `index.html` | Aplicación completa (HTML + CSS + JS) |
| `README.md` | Esta presentación |

## 📊 Datos

- **Humedales:** Ministerio del Medio Ambiente — Sistema de Humedales Urbanos
- **GI:** SINADER 2024 — Declaraciones de residuos industriales

## 🚀 Despliegue

El proyecto está publicado en GitHub Pages:

```
https://dgeoiacl.github.io/urban-wetlandMS-cl/
```
