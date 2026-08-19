# 🤖 WhatsApp Bot — Vendedor Automatizado con IA

> Bot de WhatsApp que simula un vendedor humano con estrategia de negociación por fases, impulsado por **Google Gemini AI**. Diseñado para automatizar ventas de servicios sin revelar que es un bot.

---

## 📸 Capturas de Pantalla

<!-- Agrega tus capturas aquí -->
| Conversación en WhatsApp | Excel de resultados |
|---|---|
| ![Chat](./assets/captura-chat.png) | ![Excel](./assets/captura-excel.png) |

---

## ✨ Características Principales

- 🧠 **Inteligencia Artificial** con Google Gemini como motor de conversación
- 🎭 **Personaje de vendedor humano** — nunca revela ser un bot
- 📊 **Estrategia de negociación por fases** (Exploración → Negociación → Cierre)
- 💰 **Sistema de precios dinámico** con mínimos y máximos configurables
- 📝 **Registro de resultados** en archivo Excel (`.xlsx`)
- 🔄 **Estado de conversación** rastreado por mensaje
- 🇲🇽 **Lenguaje casual mexicano** para naturalidad
- 📱 **Conexión por QR** (sin necesidad de API oficial de WhatsApp)

---

## 🛠️ Tecnologías

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

| Librería | Uso |
|---|---|
| **whatsapp-web.js** | Conexión con WhatsApp via QR |
| **@google/generative-ai** | Motor de conversación con IA (Gemini) |
| **xlsx** | Exportación de resultados a Excel |
| **qrcode-terminal** | Escaneo QR en consola |

---

## 🔄 Flujo de Conversación

```
Bot conecta via QR
        ↓
[FASE 1: EXPLORACIÓN]
Pregunta si ofrecen el servicio
        ↓
[FASE 2: NEGOCIACIÓN]
Revela que es proveedor, ofrece precio
Negocia entre precio mínimo y máximo
        ↓
[FASE 3: CIERRE / SIN_VENTA]
Registra resultado en Excel
```

---

## 📊 Estados del Sistema

| Estado | Descripción |
|---|---|
| `EXPLORANDO` | Descubriendo si el contacto usa el servicio |
| `NEGOCIANDO` | En proceso de negociación de precio |
| `CERRANDO` | Contacto interesado, cerrando venta |
| `REGISTRADO` | Venta cerrada exitosamente |
| `SIN_VENTA` | Sin éxito, se despide naturalmente |
| `DESPEDIDA` | Conversación terminada |

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Funcional-brightgreen?style=flat-square)
![Tipo](https://img.shields.io/badge/Tipo-Automatización-purple?style=flat-square)
![IA](https://img.shields.io/badge/IA-Google%20Gemini-4285F4?style=flat-square&logo=google)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
