# 🤖 J.A.R.V.I.S. — Bot de Telegram con IA

> Bot de Telegram con personalidad de **J.A.R.V.I.S.** (Just A Rather Very Intelligent System) que integra **Google Gemini 2.0** para conversación, análisis de imágenes, transcripción de voz, análisis de PDFs, búsqueda en Wikipedia, traducción y más. Funciona en chats privados y **grupos**.

---

## 📸 Vistas del Sistema

| Panel de Control + Voz | Visión IA + Wiki | Análisis de PDF |
|---|---|---|
| ![Panel](./assets/panel-control-voz.png) | ![Vision](./assets/vision-wiki.png) | ![PDF](./assets/analisis-pdf.png) |

---

## ✨ Características

### 🧠 Conversación con IA
- Responde a cualquier mensaje con **Google Gemini 2.0 Flash**
- Activación en grupos con la palabra clave `Jarvis ...`
- Personalidad de asistente fiel: *"¿Sí, señor?"*

### 🎙️ Procesamiento de Voz
- Acepta **notas de voz** de Telegram
- Las transcribe y responde con IA
- Comando `/habla [texto]` — el bot responde en audio

### 👁️ Visión Artificial
- Analiza **fotos** enviadas al chat
- Describe el contenido de la imagen con precisión
- Ejemplo: foto de muffins → *"Esos parecen muffins de chocolate"*

### 📄 Análisis de PDFs
- El usuario envía un PDF y el bot lo analiza completo
- Genera **resumen**, extrae información clave y responde preguntas sobre el documento
- Ejemplo: catálogo de precios de streaming → resumen detallado con servicios y precios

### 📚 Comandos Disponibles

| Comando | Función |
|---|---|
| `/menu` | Abre el panel de control con botones |
| `/wiki [texto]` | Busca información en Wikipedia |
| `/habla [texto]` | J.A.R.V.I.S. responde en audio |
| `/traducir` | Traduce el mensaje respondido |
| `/resumen` | Resume el mensaje respondido |
| `/mi_id` | Muestra el ID del chat |
| `Jarvis ...` | Para usar en grupos |

### 🎲 Mini-juegos
- **Dado** — tira un dado desde el panel

---

## 🛠️ Tecnologías

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

| Librería | Uso |
|---|---|
| **python-telegram-bot** | Framework del bot |
| **google-generativeai** | Google Gemini 2.0 Flash (chat, visión, PDFs) |
| **Flask** | Servidor keep-alive para deploy en la nube |

---

## 📁 Estructura

```
MiBotTelegram/
├── bot.py               ← Bot básico (local)
├── LA NUBE/
│   ├── bot.py           ← Bot completo (deploy en la nube)
│   └── requirements.txt
└── USERBOT SPAM/        ← Módulo de userbot separado
    └── userbot.py
```

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)
![IA](https://img.shields.io/badge/IA-Gemini_2.0_Flash-blue?style=flat-square&logo=google)
![Deploy](https://img.shields.io/badge/Deploy-Nube-orange?style=flat-square)
![Grupos](https://img.shields.io/badge/Grupos-Soportado-green?style=flat-square&logo=telegram)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
