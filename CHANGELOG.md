# Historial de cambios

## [5.3.0] - 2026-09-28
### 🌐 Más plataformas
- **YouTube, Instagram, Facebook, TikTok y Reddit:** Ahora puedes pegar enlaces de estas redes además de X. Funcionan vídeos normales, Shorts, Reels y enlaces cortos como `youtu.be`, `fb.watch` o `vm.tiktok.com`.
- **Cola con iconos por red:** Cada enlace de la cola muestra el icono de su plataforma.
- **Portapapeles más inteligente:** Al copiar un enlace de vídeo de cualquiera de estas redes, SUMP te ofrece descargarlo. Copiar un perfil o una página de inicio ya no lo activa.

### 🛠️ Correcciones
- **Vídeos que no se abrían en el reproductor:** Los vídeos cuyo nombre lleva `#` (muy común en TikTok) ahora se reproducen dentro de la app.
- **Nombres con acentos y emojis:** Los títulos ya no se guardan con caracteres rotos como `I�ll`; se conservan acentos, apóstrofes y emojis.

## [5.2.2] - 2026-09-28
### ⚡ Interfaz mucho más fluida
- **Biblioteca hasta 5 veces más rápida al abrir:** Los vídeos se cargan por páginas mientras te desplazas, en lugar de pintar cientos de tarjetas de golpe.
- **Desplazamiento fluido:** Se eliminaron los efectos de desenfoque de cada tarjeta y el fondo que se repintaba al desplazarte. En una biblioteca de 800 vídeos el desplazamiento pasó de 15 a más de 60 fotogramas por segundo.
- **Favoritos al instante:** Marcar o quitar un favorito actualiza solo esa tarjeta, sin recargar la biblioteca.
- **Miniaturas sin tirones:** Las miniaturas nuevas aparecen una a una en su tarjeta, en lugar de recargar toda la galería cada pocos segundos.
- **Lectura de la carpeta en segundo plano:** Leer una biblioteca grande ya no bloquea la aplicación.

## [5.2.1] - 2026-09-28
### 🎨 Progreso de descarga rediseñado
- **Se ve bien de nuevo:** La tarjeta de descarga mostraba el nombre cortado, el porcentaje pegado al texto y la barra de progreso no aparecía. Ahora el nombre ocupa todo el ancho y la barra se ve siempre.
- **Estados claros:** Mientras SUMP busca el vídeo verás una barra animada; al descargar, el porcentaje real; al terminar, la tarjeta se pone en verde, y si algo falla, en rojo con el motivo del error.
- **Cola de descargas:** El contador (por ejemplo «2 de 5») aparece junto al estado.

## [5.2.0] - 2026-09-28
### 🔐 Inicio de sesión en X, arreglado
- **Funciona con Edge, Chrome, Brave y Vivaldi:** Estos navegadores ahora cifran sus cookies y no dejaban conectar la cuenta. Ahora pulsas **Iniciar sesión en X**, se abre una ventana de tu navegador, inicias sesión y SUMP la cierra sola en cuanto detecta tu sesión. No hace falta cerrar el navegador.
- **Tu contraseña sigue siendo tuya:** El inicio de sesión ocurre en tu navegador; SUMP nunca la ve ni la guarda.
- **Descargas de contenido sensible más fiables:** Cuando hace falta usar yt-dlp, SUMP usa la sesión que conectaste en lugar de intentar leer las cookies de cada navegador.

### 📁 Carpetas y favoritos
- **Carpetas:** Las subcarpetas de tu carpeta de descargas aparecen como carpetas. Crea nuevas con **+ Nueva carpeta** y mueve vídeos arrastrándolos sobre una carpeta, con clic derecho → **Mover a** o seleccionando varios.
- **Borrado seguro de carpetas:** Una carpeta con contenido no se borra directamente: SUMP te deja sacar su contenido a la carpeta principal o enviarlo a la papelera.
- **Favoritos:** Pulsa la estrella de cualquier vídeo y encuéntralo en la vista **★ Favoritos**.
- **Selección múltiple:** Marca varios vídeos para moverlos, añadirlos a favoritos o eliminarlos a la vez (van a la Papelera de reciclaje).

### 🔎 Buscador
- **Busca por vídeo o creador** desde la barra de la biblioteca (también con **Ctrl + F**). No distingue mayúsculas ni tildes.

### ⚡ Marca de agua opcional
- **Nuevo panel de Ajustes** (botón del engranaje): desactiva la marca «Plataforma: @creador» y las descargas terminarán mucho más rápido, porque el vídeo ya no se vuelve a codificar.

### 🛠️ Otros
- El reproductor recorre los vídeos de la vista actual (carpeta, favoritos o resultados de búsqueda).
- Las miniaturas que fallan por archivos dañados ya no se reintentan cada vez que se actualiza la biblioteca.

## [5.1.0] - 2026-09-27
### ✨ Ahora se llama SUMP
- **Nueva identidad:** Nuevo nombre, logotipo e icono, y una interfaz renovada con la paleta azul de SUMP en la ventana principal, el reproductor, la pantalla de inicio, la ventana de actualización y el instalador.
- **Barra de estado:** La carpeta de descargas y el estado de tu cuenta de X aparecen como accesos rápidos bajo la cabecera; haz clic en ellos para cambiarlos.
- **Tus accesos directos se actualizan solos** al nuevo nombre, y tus descargas y ajustes se conservan.

### 🔐 Cuenta de X más segura
- **Inicio de sesión en tu propio navegador:** Ya no se abre una ventana de X dentro de la aplicación. SUMP abre x.com en tu navegador, inicias sesión allí y pulsas **Conectar**.
- **Sin contraseñas guardadas:** SUMP solo copia las cookies de x.com de ese navegador; nunca ve tu contraseña. Las credenciales que guardaban versiones anteriores se eliminan automáticamente.
- **Sin avisos del Firewall:** Se evita el aviso de "Firewall de Windows Defender bloqueó algunas características".

### 🎥 Reproductor
- **Vídeos verticales corregidos:** Los vídeos verticales se ven completos y centrados, en lugar de aparecer ampliados y recortados.

### 🛠️ Otros
- **Funciona sin conexión:** La tipografía y las animaciones van incluidas en la aplicación.

## [5.0.3] - 2026-09-27
### 🛠️ Instalador
- **Corregida la actualización de instalaciones anteriores:** El instalador no reemplazaba el núcleo de la aplicación al instalar sobre una versión antigua, por lo que seguía abriéndose la versión anterior. Ahora se sustituye por completo.
- **Comprobación final:** Al terminar, el instalador verifica que la versión instalada es la correcta y, si algo falla, te lo indica en lugar de dar la instalación por buena.
- **Instalaciones a medio desinstalar:** Si quedaron restos de una desinstalación anterior, el instalador los limpia antes de instalar.

## [5.0.2] - 2026-09-26
### ✨ Nuevo
- **Buscar actualizaciones cuando quieras:** Haz clic en el número de versión (arriba, junto al nombre) para comprobar al instante si hay una versión nueva.
- **Aviso de nuevas versiones sin reiniciar:** Si dejas la aplicación abierta, cada pocas horas comprueba si hay una versión nueva y te avisa con un botón para actualizar.
- **Novedades tras actualizar:** La primera vez que abres una versión nueva, la aplicación te lo indica y te ofrece ver qué ha cambiado.
- **Notificaciones de Windows:** Si la aplicación está minimizada o en segundo plano, te avisa cuando termina una descarga o toda la cola.

### 🛠️ Instalador
- **Actualiza instalaciones antiguas limpiamente:** Al instalar sobre una versión anterior se eliminan las entradas y accesos directos rotos del instalador antiguo.

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
### ✨ Agregado - Auto-Update
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
- **Persistencia de Referer:** Corregido un error que causaba cierres (Error 1) en descargas de algunos sitios al no enviar la cabecera de origen correcta.
