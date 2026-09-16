# 📺 NovaPlay | Channel Manager

Gestor web avanzado para la administración centralizada de canales, categorías y notificaciones del ecosistema **NovaPlay**.

## 🚀 Características Principales

*   **Gestión de Canales (CRUD)**: Creación, edición y eliminación de canales con soporte para múltiples URLs, cabeceras HTTP personalizadas (Referer, Origin, User-Agent) y protección DRM.
*   **Organización Dinámica**: Ordenamiento de categorías y canales mediante arrastrar y soltar (Drag & Drop) gracias a **SortableJS**.
*   **Acciones en Masa (Bulk Actions)**: Selección múltiple para mover canales entre categorías, cambiar estados de activación o eliminación masiva.
*   **Gestor de Notificaciones (Eventos)**: Control centralizado de avisos globales y ventanas emergentes (Pop-ups V2) para la APK, con sistema de auto-incremento de versiones.
*   **Galería de Iconos Integrada**: Buscador directo que conecta con el repositorio de activos para asignar logotipos con un solo clic.
*   **Modo Inactivos**: Sección dedicada para la recuperación y gestión de señales fuera de servicio.
*   **Seguridad STAFF**: Acceso protegido mediante token de sesión vinculado a servicios de seguridad privados.
*   **Optimización Web (PWA)**: Aplicación web instalable en escritorio y dispositivos móviles para un acceso instantáneo.

## 🛠️ Tecnologías Utilizadas

*   **Frontend**: HTML5, CSS3 (Modern Dark Theme), JavaScript (Vanilla).
*   **Librerías**: 
    *   [SortableJS](https://sortablejs.github.io/Sortable/) (Drag & Drop).
    *   [FontAwesome 6](https://fontawesome.com/) (Iconografía).
    *   Google Fonts (Inter).
*   **Backend & API**: Servicios privados de procesamiento (Serverless).
*   **Almacenamiento**: GitHub (JSON & APKs) / Cloud Storage.

## 📁 Estructura del Proyecto

*   `index.html`: Núcleo de la aplicación y lógica de administración.
*   `manifest.json`: Configuración de la Progressive Web App (PWA).
*   `sw.js`: Service Worker para soporte offline y carga optimizada.

---
**Desarrollado por MSGT**  
© 2026 NovaPlay TV - Infraestructura de Contenidos.
