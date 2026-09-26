# Historial de cambios

## [5.0.1] - 2026-09-26
### 🚀 Nuevo sistema de actualizaciones
- **Actualizaciones desde GitHub:** Las nuevas versiones se descargan desde GitHub Releases, más rápido y fiable que el sistema anterior.
- **Instalación automática:** Al pulsar **Actualizar ahora** la actualización se instala sola y la aplicación se reinicia ya actualizada.
- **Descargas verificadas:** Cada actualización se comprueba antes de instalarse para evitar archivos dañados.

### 🛠️ Instalador y estabilidad
- **Instalador renovado:** El instalador descarga siempre la versión más reciente directamente desde GitHub, sin necesidad de permisos de administrador.
- **Tu configuración se conserva:** Ajustes, favoritos, carpeta de descargas y herramientas se guardan en `%APPDATA%\X Downloader V3` y ya no se pierden al actualizar.
- **Descarga de FFmpeg reparada:** Corregido el error al extraer FFmpeg en rutas con espacios.
- **Descargas más seguras:** Una descarga interrumpida de `yt-dlp` o FFmpeg ya no deja archivos dañados.

## [5.0.0]
### ✨ Agregado - Compatibilidad con xHamster y Auto-Update
- **Soporte xHamster:** Ahora puedes descargar vídeos de xHamster directamente con soporte completo de metadatos e iconos personalizados en la interfaz.
- **Auto-Actualización de yt-dlp:** La aplicación ahora verifica y actualiza automáticamente el motor de descarga `yt-dlp` al inicio, asegurando compatibilidad constante con todos los sitios sin intervención del usuario.
- **User-Agent de Navegador:** Implementado un sistema de evasión de bloqueos mediante User-Agent de Chrome 121, permitiendo descargas en sitios con restricciones estrictas para bots.

### 🎥 Mejoras - Reproductor de Video Pro
- **Ajuste de Vídeo Inteligente (Vertical Fix):** Los vídeos verticales ahora se muestran correctamente con proporciones exactas (`object-fit: contain`), eliminando el zoom excesivo y asegurando que se vean perfectos en cualquier pantalla.
- **Control de Interfaz (Sidebar Toggle):** Nuevo botón y atajo de teclado (**tecla 'B'**) para ocultar o mostrar el panel lateral de contenido relacionado a voluntad, permitiendo una experiencia de cine a pantalla completa.
- **Feedback Visual de Controles:** Los botones de **Aleatorio**, **Repetir** y **Autoplay** ahora cuentan con indicadores luminosos de estado (dots brillantes) para saber exactamente qué función está activa de un vistazo.
- **Navegación Fluida:** Los botones de navegación previa/siguiente ahora son más visibles y tienen prioridad sobre el escenario del vídeo.

### 🛠️ Soluciones Técnicas e Instalador
- **Web Installer v5.0 (Omni-Compatible):** El instalador ligero (<1MB) soporta caracteres especiales (Unicode) y tiene metadatos de seguridad mejorados para reducir advertencias de Windows SmartScreen y Smart App Control.
- **Corrección de Error de Extracción:** Se han reparado los errores de "Falta parámetro Path" en el instalador mediante un nuevo sistema de escapado de rutas para PowerShell, permitiendo instalaciones en carpetas con espacios.
- **Persistencia de Referer:** Corregido un error que causaba cierres (Error 1) en descargas de sitios para adultos al no enviar la cabecera de origen correcta.
