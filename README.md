<p align="center">
  <img src="https://raw.githubusercontent.com/DeezTW/SumpDownloader/main/assets/sump-icon.svg" alt="SUMP" width="110">
</p>

# SUMP

Aplicación para Windows y Android que descarga vídeos, música e imágenes de X (Twitter), YouTube, YouTube Music, Instagram,
Facebook, TikTok, Reddit, Bilibili y Spotify, con reproductor integrado, buscador de música, convertidor de archivos y
biblioteca de descargas.

## ⬇️ Descargar

**[Descargar el instalador de SUMP para Windows (última versión)](https://github.com/DeezTW/SumpDownloader/releases/latest/download/SUMP-Setup.exe)**

**[Descargar SUMP para Android (última versión)](https://github.com/DeezTW/SumpDownloader/releases/latest/download/SUMP-Android.apk)**
· para teléfonos antiguos de 32 bits:
[SUMP-Android-armv7.apk](https://github.com/DeezTW/SumpDownloader/releases/latest/download/SUMP-Android-armv7.apk)

Todas las versiones y sus novedades están en la sección
[Releases](https://github.com/DeezTW/SumpDownloader/releases).

## Requisitos

- Windows 10 u 11 de 64 bits
- Conexión a internet durante la instalación y el primer arranque

## Instalación

1. Descarga y ejecuta `SUMP-Setup.exe`. No es necesario instalarlo como administrador.
2. Elige el idioma del instalador (español o inglés) y acepta la licencia.
3. Elige dónde instalarlo (o deja la carpeta propuesta) y pulsa **Instalar**. El instalador
   descarga automáticamente la versión más reciente. Los próximos instaladores encuentran SUMP
   en la carpeta que elegiste.
4. En el primer arranque, SUMP descarga las herramientas que necesita (`yt-dlp` y `FFmpeg`) y te
   guía por sus ajustes principales: tema, carpeta de descargas, calidad, marca de agua, segundo plano y
   el botón «Descargar con SUMP» para la barra de marcadores de tu navegador.

> **Aviso de Windows SmartScreen:** si aparece *"Windows protegió su PC"*, pulsa
> **Más información → Ejecutar de todas formas**. Aparece porque el instalador no tiene
> una firma digital de pago.

## Android

1. Abre `SUMP-Android.apk` en el teléfono. Si Android lo pide, permite instalar apps de este origen
   (tu navegador o tu gestor de archivos) y pulsa **Instalar**.
2. En el primer arranque, SUMP te pide acceso a tus archivos para guardar las descargas en
   **Descargas/SUMP**, donde las ven la galería y tus apps de música. Si no se lo das, las guarda en su
   propia carpeta.
3. Para descargar desde otra app (YouTube, X, Instagram, TikTok, el navegador…), pulsa **Compartir** y
   elige **SUMP**: el enlace aparece en la barra, listo para descargar. También puedes pegarlo.

Requiere Android 7.0 o posterior. Las descargas siguen aunque cambies de app o bloquees el teléfono, y SUMP
se actualiza solo. Los vídeos de X, Instagram, TikTok y Facebook se descargan a través del servidor de SUMP
(como el atajo de iOS), así que el contenido sensible de X funciona sin conectar tu cuenta de X; YouTube,
YouTube Music, Reddit y Bilibili se descargan en el propio teléfono.

## Vídeos y Música

SUMP tiene dos espacios, para que los vídeos y la música no se mezclen. Cambia entre ellos arriba en la
barra lateral o con `Ctrl + 1` y `Ctrl + 2`. Cada uno tiene sus estantes, su historial y su calidad de
descarga.

- **Música:** tus canciones con carátula, artista, álbum y duración, y vistas de *Álbumes*, *Artistas* y
  *Favoritas*. Pulsa una canción para escucharla en la barra de abajo, o reproduce todo en aleatorio.
- **Buscador de YouTube Music:** en *Música → Buscar* (o escribiendo en la barra de arriba) encuentras
  canciones, álbumes, playlists y artistas, y los descargas sin salir de SUMP.
- **Spotify:** pega el enlace de una canción, un álbum o una playlist pública de Spotify. Eliges qué canciones
  quieres y SUMP busca cada una en YouTube Music y la descarga con el título, los artistas, el álbum y la
  carátula de Spotify (el audio de Spotify está protegido, así que no se descarga de ahí). Los álbumes llegan
  completos; de las playlists se leen las primeras 100 canciones.

## Convertidor

En *Herramientas → Convertidor* (o con clic derecho en un archivo) conviertes vídeos a MP4, WebM, MKV, MOV,
AVI o GIF, sacas el audio de un vídeo o cambias el formato de una canción (MP3, M4A, Opus, OGG, FLAC, WAV).
El archivo original no se toca.

## Tu biblioteca

- **Carpetas:** las subcarpetas de tu carpeta de descargas aparecen como carpetas en SUMP. Puedes
  crear nuevas, mover vídeos arrastrándolos o con clic derecho, y borrar carpetas (si tienen contenido,
  SUMP te deja sacarlo a la carpeta principal o enviarlo a la papelera).
- **Favoritos:** pulsa la estrella de un vídeo para tenerlo a mano en la vista *Favoritos*.
- **Buscador:** busca por nombre del vídeo o del creador (también con `Ctrl + F`).
- **Marca de agua opcional:** en *Ajustes* puedes desactivar el texto «Plataforma: @creador» para que
  las descargas terminen mucho más rápido.

## Tema claro u oscuro

Cambia entre los dos con el botón del sol y la luna (abajo a la izquierda) o en *Ajustes → Apariencia*.

## Calidad y formatos

- **Vídeo:** cada vídeo te muestra las calidades que tiene de verdad, de 360p a 8K (2K, 4K, 5K…).
- **Solo audio:** MP3, M4A, Opus, OGG, FLAC o WAV, con la carátula original y las etiquetas de la
  canción (WAV no admite carátula).
- **Varios enlaces a la vez:** pégalos como quieras; si van pegados sin espacio, SUMP los separa solo.
- **YouTube a ritmo seguro:** SUMP espacia las descargas de YouTube para no llegar a su límite, y si YouTube
  pide una pausa, la descarga espera y sigue sola.

## Cuenta de X (opcional)

Para descargar contenido marcado como sensible, abre *Cuenta de X*, elige tu navegador y pulsa
**Iniciar sesión en X**: se abre una ventana de tu propio navegador (Edge, Chrome, Brave o Vivaldi)
donde inicias sesión, y SUMP la cierra sola en cuanto detecta tu sesión. Con Firefox, inicias sesión
en Firefox y pulsas **Conectar**. SUMP nunca ve ni guarda tu contraseña.

## Actualizaciones

Son automáticas: al abrir SUMP, si hay una versión nueva verás sus novedades y podrás actualizar
con un clic. También puedes comprobarlo cuando quieras haciendo clic en el número de versión.
Tu configuración, favoritos y descargas se conservan.

## Tus datos

La configuración y las herramientas se guardan en `%APPDATA%\SUMP_UserData`.
Los vídeos se guardan en la carpeta de descargas que elijas en la aplicación.

## Desinstalar

Desde **Configuración → Aplicaciones → SUMP → Desinstalar** (o el Panel de control), o ejecutando
de nuevo el instalador y eligiendo **Desinstalar**. El desinstalador te pregunta antes y te deja
elegir si borrar también tus ajustes; tus descargas nunca se borran.

## Novedades

Consulta el [historial de cambios](CHANGELOG.md).

## Licencia

SUMP es software propietario de Altavera Digital. Se licencia para uso personal según su
[acuerdo de licencia de usuario final (EULA)](LICENSE): no se puede revender, sublicenciar,
redistribuir ni modificar. Todos los derechos reservados.
