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

## Cuenta de X (opcional)

Para descargar contenido marcado como sensible, conecta tu cuenta de X desde el botón de cuenta:
SUMP abre x.com **en tu propio navegador**, inicias sesión allí y después pulsas **Conectar**.
SUMP solo copia las cookies de x.com de ese navegador; nunca ve ni guarda tu contraseña.

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
