# 🎵 Sayto Studio — Motor IA de Producción Musical en Vivo

> Aplicación de escritorio personalizada (Wrapper) diseñada para transmisiones de TikTok LIVE. Proporciona una interfaz gráfica estilo "DJ Deck" para el stream, mientras que en segundo plano utiliza automatización de navegadores (Headless Browser) para interactuar secretamente con la IA de Suno y generar canciones en tiempo real sin revelar el proceso al público.

---

## 📸 Interfaz Personalizada (Overlay para Stream)

| Interfaz Base de Generación | Reproducción Simultánea (Decks A y B) |
|---|---|
| ![Sayto Base](./assets/sayto-1.png) | ![Sayto Play](./assets/sayto-2.png) |

---

## ✨ Arquitectura y Características

### 🤖 Automatización Invisible (Headless)
El verdadero núcleo del proyecto es su motor de automatización. El usuario describe una canción en la interfaz gráfica y el sistema usa **Puppeteer Stealth** para:
1. Abrir una instancia oculta del navegador.
2. Inyectar las credenciales y evadir sistemas Anti-Bot.
3. Enviar el "Prompt" de la canción al motor real de Suno AI.
4. Extraer el `.mp3` y las portadas (Covers) generadas, devolviéndolas a la interfaz local.

### 🎧 Interfaz de Producción (Sayto Studio)
- Diseño original estilo software de DJ (Decks independientes para reproducir la Pista A y la Pista B).
- **Biblioteca Musical:** Gestor local que enlista las canciones generadas y permite cargarlas a los reproductores de forma instantánea.
- **Generador de Letras Integrado:** Permite solicitar la estructura lírica a la IA antes de renderizar la pista final de audio.

### 💻 Cliente de Escritorio
Empaquetado como un ejecutable nativo de Windows (`.exe`), garantizando un rendimiento estable para transmisiones de larga duración utilizando OBS Studio.

---

## 🛠️ Tecnologías

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/Frontend-HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)

| Herramienta | Uso |
|---|---|
| **Electron** | Compilación del entorno web y el motor de Node en una app `.exe` |
| **Puppeteer (Stealth)** | Navegación Headless para el Web Scraping y manipulación del DOM de Suno AI de forma invisible |
| **Vanilla JS** | Lógica de los reproductores de audio, listas de reproducción y manipulación de UI |

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)
![Uso](https://img.shields.io/badge/Arquitectura-API_Wrapper%20%2F%20Scraper-blue?style=flat-square)
![Interactivo](https://img.shields.io/badge/Tipo-Herramienta_Streaming-black?style=flat-square)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
