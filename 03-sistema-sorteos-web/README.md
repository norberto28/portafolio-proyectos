# 🎟️ Plataforma Web de Sorteos y Rifas Automáticas

> Sistema web transaccional (E-commerce especializado) diseñado para la venta, gestión y validación de boletos para sorteos. Permite a los usuarios seleccionar sus números, generar reservas temporales y obtener comprobantes en PDF con medidas antifraude.

---

## 📸 Flujo del Cliente (Mobile First)

| Confirmación de Reserva | Generación de Ticket en PDF | Recuperación de Boletos |
|---|---|---|
| <img src="./assets/apartados.png" width="250"> | <img src="./assets/pdf-apartado.png" width="250"> | <img src="./assets/recuperar.png" width="250"> |

---

## ✨ Características Principales

### 🛒 Motor de Reservas y Expiración
- **Selección Múltiple:** Los usuarios pueden apartar múltiples números simultáneamente.
- **Temporizador de Pago:** El sistema otorga un lapso (ej. 12 horas) para liquidar la transferencia bancaria. Si el sistema no detecta la validación del administrador en ese tiempo, **los boletos se liberan automáticamente** al público.

### 📄 Generación Dinámica de Comprobantes (PDF)
- **Fichas de Pre-apartado:** Al reservar, el servidor compila en tiempo real un documento PDF descargable con los datos del folio, sorteo, costo y números elegidos.
- **Marca de Agua Anti-Fraude:** Los boletos no pagados incluyen una marca de agua inyectada en el PDF ("SIN VALOR OFICIAL") para evitar que usuarios reclamen premios sin haber liquidado.

### 🔍 Módulo de Seguimiento
- **Buscador Integrado:** Los clientes pueden rastrear el estado de su reserva ingresando su número de teléfono o folio asignado.
- **Integración con WhatsApp:** Botón de acción rápida que redirige al usuario a la API de WhatsApp para notificar su pago directamente al administrador, adjuntando la información de su orden.

---

## 🛠️ Tecnologías

![PHP](https://img.shields.io/badge/Backend-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![CSS3](https://img.shields.io/badge/Frontend-CSS_Mobile_First-1572B6?style=for-the-badge&logo=css3&logoColor=white)

| Herramienta | Uso en la Arquitectura |
|---|---|
| **PHP + Composer** | Lógica de enrutamiento y procesamiento de compras. |
| **Generador PDF** | Compilación de código HTML a Documentos PDF transaccionales. |
| **MySQL** | Prevención de doble venta (bloqueo de registros) e integridad de folios. |
| **WhatsApp API** | Creación de URLs dinámicas (`wa.me`) precargadas con los datos del pedido. |

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)
![Uso](https://img.shields.io/badge/Tipo-E--Commerce-blue?style=flat-square)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
