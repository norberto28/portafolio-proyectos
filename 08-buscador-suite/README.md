# 🎵 Suite Tools — Suite de Descargas y Extracciones Multimedia

> Aplicación de escritorio con **Plan Pro** que permite descargar audio y video desde **más de 1800 plataformas**, extraer playlists completas, convertir formatos y generar tarjetas visuales de Spotify. Sistema de suscripción con límite de descargas mensuales.

---

## 📸 Vistas del Sistema

| Dashboard Principal |
|---|
| ![Dashboard](./assets/dashboard.png) |

| Confirmación de Descarga | Extraer Playlist (26 videos) |
|---|---|
| ![Descarga](./assets/confirmar-descarga.png) | ![Playlist](./assets/extraer-playlist.png) |

| Generar Tarjetas Spotify | Extraer Playlist (1800+ plataformas) |
|---|---|
| ![Tarjetas](./assets/tarjetas-spotify.png) | ![Plataformas](./assets/extraer-playlist-2.png) |

| Resultado — Tarjetas Spotify generadas |
|---|
| ![Resultado Tarjetas](./assets/resultado-tarjetas.png) |

---

## ✨ Características

### 📊 Dashboard
- Estadísticas en tiempo real: MP3, MP3 Premium, MP4, MP4 HD, Extracciones, Tarjetas
- Historial de **últimas descargas** con fecha y hora
- Espacio total en disco usado
- Sistema de **Plan Pro** con descargas ilimitadas mensuales

### 🔧 Herramientas Base
- 🔍 **Búsqueda Individual** — busca y descarga canciones/videos por nombre
- 📋 **Extraer Playlist** — extrae listas completas de **más de 1800 plataformas** (Spotify, YouTube, TikTok y más)
- 🔄 **Conversor MP4 → MP3** — convierte videos a audio

### 📥 Descargas por Lote
| Modo | Calidad |
|---|---|
| MP3 Básico | Audio estándar |
| ⭐ MP3 Premium | Alta calidad de audio |
| MP4 Rápido | Video rápido |
| 🎬 MP4 HD | Video alta definición |
| 🌐 Descarga Masiva (URL) | Múltiples URLs a la vez |

### ⚡ Descargas Simultáneas
- Procesa **1, 2 o 3 descargas al mismo tiempo** configurables por el usuario

### 🎨 Herramientas de Imagen
- 🎵 **Códigos Spotify** — genera códigos escaneables de canciones
- 🃏 **Tarjetas Spotify** — crea imagen combinada (portada + código de barras escaneable)
- 🖼️ **Descargar Portadas** — descarga las carátulas de alta calidad

### 🔑 Sistema de Licencias
- Plan Pro con contador de descargas mensuales
- Días restantes de suscripción visible en el panel
- Soporte vía WhatsApp integrado en la app

---

## 🛠️ Tecnologías

![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

| Herramienta | Uso |
|---|---|
| **Electron** | App de escritorio multiplataforma |
| **Node.js** | Backend y lógica de descargas |
| **yt-dlp** | Motor de descarga (1800+ plataformas) |
| **FFmpeg** | Conversión de formatos (MP4→MP3) |
| **HTML/CSS** | Interfaz oscura tipo dashboard |

---

## 📁 Estructura

```
buscador-suite/
├── main.js              ← Proceso principal Electron
├── renderer/            ← Interfaz (HTML/CSS/JS)
├── src/
│   ├── downloader.js    ← Motor de descarga
│   ├── converter.js     ← Conversor MP4→MP3
│   ├── spotify.js       ← Tarjetas y códigos Spotify
│   └── license.js       ← Sistema de licencias
├── build_secure.js      ← Build con ofuscación
└── dist/                ← Ejecutable final
```

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)
![Versión](https://img.shields.io/badge/Versión-1.1.23-blue?style=flat-square)
![Plan](https://img.shields.io/badge/Plan-Pro%20(ilimitado)-gold?style=flat-square)
![Plataformas](https://img.shields.io/badge/Plataformas-1800%2B-purple?style=flat-square)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
