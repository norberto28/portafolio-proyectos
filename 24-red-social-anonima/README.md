# 🤫 Red Social Universitaria Anónima

> Plataforma web modular diseñada para la interacción y comunicación anónima dentro de una comunidad universitaria. Al manejar contenido sensible, la arquitectura se centra en la seguridad de los usuarios, el rendimiento en tiempo real y herramientas avanzadas de moderación remota.

*(Nota: Las capturas de interfaz se han omitido de este portafolio público para proteger la privacidad de la comunidad y los datos confidenciales alojados en la plataforma).*

---

## ✨ Estructura Modular de la Red Social

A diferencia de un simple foro, el sistema fue dividido en micro-módulos interactivos para segmentar el tráfico y mejorar la experiencia de usuario:

- **💬 El Muro (`muro.html`):** Feed principal estilo Twitter para confesiones y avisos rápidos.
- **🔍 Se Busca (`sebusca.html`):** Módulo dedicado a conexiones universitarias y "crushes".
- **📊 Versus & Califica (`versus.html`, `califica.html`):** Sistemas interactivos de votación en tiempo real.
- **📌 Cartelera y Dudas:** Espacios para anuncios académicos y apoyo estudiantil.

---

## 🛡️ "Modo Dios": Panel de Moderación (Admin)
Para mantener un entorno seguro y libre de toxicidad, se desarrolló un panel de administración oculto (`admin.html`) con altos privilegios.
- **Borrado Efímero y Permanente:** Herramientas para ocultar posts reportados o eliminarlos de la base de datos (Ghosting).
- **Control de Medios:** Supervisión de las imágenes inyectadas en la plataforma.

---

## 🛠️ Arquitectura y Tecnologías

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

| Herramienta | Uso en la Arquitectura |
|---|---|
| **Firebase Cloud** | Base de datos en tiempo real para sincronizar los "likes", comentarios y nuevos posts al instante. |
| **Vite** | Bundler ultra rápido para compilar el frontend y optimizar los "assets" para conexiones móviles. |
| **ImgBB API** | Integración de API externa para el alojamiento de imágenes, evitando saturar el servidor principal y manteniendo el anonimato. |
| **Scripts CJS** | Automatización de parches (`patch_*.cjs`) para desplegar actualizaciones, inyectar estilos y aplicar correcciones sin tirar el servidor. |

---

## 📌 Estado del Proyecto

![Estado](https://img.shields.io/badge/Estado-Activo%20%2F%20Privado-red?style=flat-square)
![Uso](https://img.shields.io/badge/Tipo-Red_Social_PWA-blue?style=flat-square)
![DB](https://img.shields.io/badge/Base_de_Datos-Firebase_NoSQL-yellow?style=flat-square)

---

## 🔗 Volver al Portafolio

[← Regresar al índice principal](../README.md)
