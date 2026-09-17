# ðŸ“º NovaPlay | Channel Manager

Gestor web avanzado para la administraciÃ³n centralizada de canales, categorÃ­as y notificaciones del ecosistema **NovaPlay**.

## ðŸš€ CaracterÃ­sticas Principales

*   **GestiÃ³n de Canales (CRUD)**: CreaciÃ³n, ediciÃ³n y eliminaciÃ³n de canales con soporte para mÃºltiples URLs, cabeceras HTTP personalizadas (Referer, Origin, User-Agent) y protecciÃ³n DRM.
*   **OrganizaciÃ³n DinÃ¡mica**: Ordenamiento de categorÃ­as y canales mediante arrastrar y soltar (Drag & Drop) gracias a **SortableJS**.
*   **Acciones en Masa (Bulk Actions)**: SelecciÃ³n mÃºltiple para mover canales entre categorÃ­as, cambiar estados de activaciÃ³n o eliminaciÃ³n masiva.
*   **Gestor de Notificaciones (Eventos)**: Control centralizado de avisos globales y ventanas emergentes (Pop-ups V2) para la APK, con sistema de auto-incremento de versiones.
*   **GalerÃ­a de Iconos Integrada**: Buscador directo que conecta con el repositorio de activos para asignar logotipos con un solo clic.
*   **Modo Inactivos**: SecciÃ³n dedicada para la recuperaciÃ³n y gestiÃ³n de seÃ±ales fuera de servicio.
*   **Seguridad STAFF**: Acceso protegido mediante token de sesiÃ³n vinculado a servicios de seguridad privados.
*   **OptimizaciÃ³n Web (PWA)**: AplicaciÃ³n web instalable en escritorio y dispositivos mÃ³viles para un acceso instantÃ¡neo.

## ðŸ› ï¸ TecnologÃ­as Utilizadas

*   **Frontend**: HTML5, CSS3 (Modern Dark Theme), JavaScript (Vanilla).
*   **LibrerÃ­as**: 
    *   [SortableJS](https://sortablejs.github.io/Sortable/) (Drag & Drop).
    *   [FontAwesome 6](https://fontawesome.com/) (IconografÃ­a).
    *   Google Fonts (Inter).
*   **Backend & API**: Servicios privados de procesamiento (Serverless).
*   **Almacenamiento**: GitHub (JSON & APKs) / Cloud Storage.

## ðŸ“ Estructura del Proyecto

*   `index.html`: NÃºcleo de la aplicaciÃ³n y lÃ³gica de administraciÃ³n.
*   `manifest.json`: ConfiguraciÃ³n de la Progressive Web App (PWA).
*   `sw.js`: Service Worker para soporte offline y carga optimizada.

---
****  
Â© 2026 NovaPlay GO - Infraestructura de Contenidos.