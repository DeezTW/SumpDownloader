<p align="center">
  <img src="https://raw.githubusercontent.com/DeezTW/SumpDownloader/main/assets/sump-icon.svg" alt="SUMP" width="110">
</p>

# SUMP

Aplicación para Windows que descarga vídeos e imágenes de X (Twitter) y otros sitios compatibles,
con reproductor integrado y biblioteca de descargas.

## ⬇️ Descargar

**[Descargar el instalador de SUMP (última versión)](https://github.com/DeezTW/SumpDownloader/releases/latest/download/SUMP-Setup.exe)**

Todas las versiones y sus novedades están en la sección
[Releases](https://github.com/DeezTW/SumpDownloader/releases).

## Requisitos

- Windows 10 u 11 de 64 bits
- Conexión a internet durante la instalación y el primer arranque

## Instalación

1. Descarga y ejecuta `SUMP-Setup.exe`. No es necesario instalarlo como administrador.
2. Acepta la licencia y pulsa **Instalar**. El instalador descarga automáticamente la versión
   más reciente.
3. En el primer arranque, SUMP descarga las herramientas que necesita (`yt-dlp` y `FFmpeg`).
   Puede tardar unos minutos según tu conexión.

> **Aviso de Windows SmartScreen:** si aparece *"Windows protegió su PC"*, pulsa
> **Más información → Ejecutar de todas formas**. Aparece porque el instalador no tiene
> una firma digital de pago.

## Tu biblioteca

- **Carpetas:** las subcarpetas de tu carpeta de descargas aparecen como carpetas en SUMP. Puedes
  crear nuevas, mover vídeos arrastrándolos o con clic derecho, y borrar carpetas (si tienen contenido,
  SUMP te deja sacarlo a la carpeta principal o enviarlo a la papelera).
- **Favoritos:** pulsa la estrella de un vídeo para tenerlo a mano en la vista *Favoritos*.
- **Buscador:** busca por nombre del vídeo o del creador (también con `Ctrl + F`).
- **Marca de agua opcional:** en *Ajustes* puedes desactivar el texto «Plataforma: @creador» para que
  las descargas terminen mucho más rápido.

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

La configuración y las herramientas se guardan en `%APPDATA%\X Downloader V3`.
Los vídeos se guardan en la carpeta de descargas que elijas en la aplicación.

## Desinstalar

Desde **Configuración → Aplicaciones → SUMP → Desinstalar**, o ejecutando de nuevo el
instalador y eligiendo **Desinstalar**.

## Novedades

Consulta el [historial de cambios](CHANGELOG.md).

## Licencia

[MIT](LICENSE)
