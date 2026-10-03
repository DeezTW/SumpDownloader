# Historial de cambios

## [6.5.0] - 2026-10-03
SUMP 6.5 te deja elegir la calidad real de cada vídeo y el formato de audio, y estrena instalador, desinstalador y una bienvenida guiada.

### 🎬 La calidad que tiene cada vídeo
- **Las calidades se desglosan según el vídeo:** si un vídeo está en 2K, 4K, 5K u 8K, esas opciones aparecen en la lista, en vez de saltar de 1080p a «Máxima».
- Cada vídeo muestra su calidad máxima («hasta 4K») y lo que pesará en la calidad elegida.
- Las películas con bandas negras (por ejemplo 1920×800) cuentan como lo que son, 1080p, igual que en YouTube.

### 🎵 Más formatos de audio
- Además de **MP3**, puedes descargar en **M4A, Opus, OGG, FLAC y WAV**, desde el selector de calidad o en el diálogo de los álbumes.
- Todos llevan la **carátula original** y las etiquetas de la canción (título, artista, álbum, pista, año). WAV no admite carátula, así que solo lleva las etiquetas.
- M4A y Opus guardan el audio original de YouTube tal cual, sin volver a comprimirlo.

### 🔗 Enlaces pegados sin espacio
- Si pegas varios enlaces juntos («…v=abchttps://…»), SUMP los separa solo, uno por línea.

### 👋 Bienvenida guiada
- La primera vez que abres SUMP, un asistente te ayuda a elegir la **carpeta de descargas**, la **calidad**, la **marca de agua** y qué hacer **en segundo plano**.
- **«Descargar con SUMP» en tu navegador con un clic:** SUMP añade el botón a la barra de marcadores de Chrome, Edge, Brave, Vivaldi u Opera por ti, sin arrastrar nada. Si el navegador está abierto, te pide cerrarlo y lo añade en cuanto lo cierras.
- Puedes volver a abrir el asistente cuando quieras en **Ajustes**, y el botón del navegador también está ahí.

### 📦 Instalador nuevo
- **En español o en inglés:** eliges el idioma al empezar, y la licencia aparece en ese idioma.
- **Elige dónde instalar SUMP.** El instalador lo deja registrado, así que los próximos instaladores lo encuentran aunque no esté en la carpeta de siempre. Si eliges otra carpeta, lo mueve allí sin tocar tus ajustes ni tus descargas.
- Te avisa si la carpeta no sirve (tiene otros archivos o necesita permisos de administrador).

### 🗑️ Desinstalador con el mismo diseño
- Al desinstalar SUMP desde **Configuración → Aplicaciones** o el Panel de control, se abre un desinstalador con el diseño del instalador y en tu idioma, en vez de un cuadro de Windows.
- Puedes elegir si borrar también tus ajustes y el historial. **Tus descargas nunca se borran.**

## [6.4.1] - 2026-10-03
Una versión pequeña de arreglos.

### 🧹 Arreglos
- **Las preguntas con tres botones ya se ven enteras.** En el aviso de «enlaces que ya están en tu biblioteca», el botón «Cancelar» se salía del cuadro. Ahora caben todos y, si la ventana es muy estrecha, pasan a una segunda línea.
- El título de ese aviso ya dice «1 de estos enlaces ya está en tu biblioteca», en singular.

### 📁 Carpeta de datos con el nombre de SUMP
- La carpeta donde SUMP guarda tus ajustes, tu sesión de X, el historial y sus herramientas ahora se llama **`SUMP_UserData`** (en `%APPDATA%`).
- Si ya usabas SUMP, tu carpeta anterior («X Downloader V3») se renombra sola la primera vez que abres esta versión, con todo dentro: no pierdes nada ni tienes que volver a iniciar sesión.
- Tus descargas no se mueven: siguen en la carpeta que elegiste en Ajustes.

## [6.4.0] - 2026-10-03
SUMP 6.4 descarga álbumes enteros de YouTube Music, con su carátula original.

### 💿 Álbumes y listas de YouTube Music
- **Pega el enlace de un álbum o de una lista** (de YouTube Music o de YouTube) y SUMP te muestra su portada, cuántas canciones tiene y cuánto duran en total, antes de descargar nada.
- Al pulsar Descargar eliges **qué canciones** quieres (las que ya tienes vienen desmarcadas), **dónde guardarlas** (una carpeta nueva con el nombre del álbum, una de tus carpetas o sin carpeta) y **el formato** (MP3 o vídeo).
- Cada canción se descarga por separado, así que puedes pausar, reintentar o cancelar una sin tocar las demás.
- Si pegas una canción que forma parte de un álbum, aparece un botón **«Todo el álbum»** para llevarte el disco completo.
- Antes, un enlace de álbum descargaba una sola canción y podía dejar SUMP trabado: eso ya no pasa.

### 🎨 La carátula original en cada MP3
- Al guardar una canción como MP3, SUMP **busca su carátula original** por el título y el artista y la incrusta en el archivo, en alta calidad.
- También guarda el **título, el artista, el álbum, el número de pista, el año y el género**, para que tu reproductor de música las ordene bien.
- Si no encuentra la carátula, usa la imagen del vídeo recortada en cuadrado.

### 🎬 Vídeos 4K grandes
- **Unir el vídeo y el audio de un 4K de varios GB ya no cuenta como «atascado»**: mientras el archivo avanza, la descarga sigue y la barra muestra el progreso de la unión.
- En **Ajustes → Descargas** eliges cuánto esperar antes de saltar una descarga que no avanza: 1, 3 (la nueva opción predeterminada), 5 o 10 minutos, o nunca.
- Si YouTube rechaza una descarga a la primera (error 403), SUMP lo reintenta una vez solo.

### 🔔 Aviso de nueva versión
- Cuando hay una versión nueva sin instalar, aparece un **botón «Nueva versión»** en la barra lateral que no se va hasta que actualizas. Un clic y se instala.
- También lo verás en el menú de la bandeja y en «Acerca de».

## [6.3.0] - 2026-10-02
SUMP 6.3 te deja seguir viendo o escuchando mientras navegas por tu biblioteca.

### 📺 Sigue viendo mientras buscas otro vídeo
- **Si sales del reproductor mientras un vídeo se reproduce** (con la ×, con Esc, haciendo clic fuera o con el nuevo botón «Seguir viendo mientras navegas»), el vídeo se encoge hasta una **tarjeta flotante abajo a la derecha** y sigue reproduciéndose sin cortes, como en YouTube.
- Al pasar el ratón por la tarjeta tienes anterior, reproducir/pausar, siguiente, una barra para avanzar, volver al reproductor y cerrar. Un clic en el vídeo lo vuelve a abrir en grande, en el mismo punto.
- **Tecla I:** minimiza el reproductor y lo vuelve a abrir (la misma que en YouTube).
- Si pausas antes de salir, el reproductor se cierra como siempre.

### 🎵 La música, en una barra abajo
- **Los MP3 siguen sonando en una barra a lo ancho de la ventana**, como en Spotify: portada, título y artista, favorito, aleatorio, anterior, reproducir/pausar, siguiente, repetir, una barra de progreso que puedes arrastrar, volumen, abrir en grande y cerrar.
- Al terminar una canción empieza la siguiente.
- Al abrir una canción, anterior y siguiente recorren solo canciones; al abrir un vídeo, solo vídeos.
- La biblioteca deja sitio a la barra, así que no tapa nada.

### ⌨️ Controles de Windows
- **Las teclas multimedia del teclado** (reproducir/pausar, siguiente, anterior) y el panel multimedia de Windows controlan lo que suena en SUMP. Los archivos privados aparecen ahí como «Archivo privado», sin su nombre.
- Mientras navegas, **Espacio** pausa o reanuda lo que suena.
- La música sigue sonando aunque cierres la ventana a la bandeja.

## [6.2.0] - 2026-10-02
SUMP 6.2 trae carpetas privadas de verdad, cifradas con tu contraseña, una forma rápida de ordenar todo lo que tienes suelto, y una ventana «Acerca de».

### 🔒 Carpetas privadas
- **Con contraseña y cifradas en tu PC (AES-256):** lo que guardes en privado se cifra; no es solo esconderlo. Desde el Explorador de Windows no se puede abrir, y en SUMP no aparece mientras esté bloqueado.
- **Se ven y se reproducen como siempre** al desbloquearlas: miniaturas, reproductor (incluido adelantar y retroceder), imágenes y favoritos. Nada se guarda descifrado en el disco para reproducirlo.
- **Para guardar algo en privado**, arrástralo a una carpeta privada del lateral o selecciónalo y usa «Mover a». También puedes convertir una carpeta entera con clic derecho → «Convertir en carpeta privada…». Para sacarlo, clic derecho → «Sacar de privado».
- **Se bloquean solas** al cerrar la ventana a la bandeja, al bloquear Windows, al suspender el PC o tras 10 minutos sin usarlo. También puedes bloquearlas cuando quieras desde el lateral.
- **Ocultarlas por completo:** en Ajustes puedes hacer que, bloqueadas, ni siquiera aparezcan en el lateral. Para abrirlas, pulsa **Ctrl + Shift + P**.
- Al guardar algo en privado también se borran su miniatura, su enlace de origen y su rastro en el historial.
- Puedes cambiar la contraseña cuando quieras. **Si la olvidas, no hay forma de recuperar lo que guardaste:** SUMP te avisa antes de crearlas.

### ✅ Seleccionar todo
- **«Seleccionar»** junto al número de archivos, o **Ctrl + A**, selecciona todo lo que estás viendo (una carpeta, «Sin carpeta», tus favoritos o el resultado de una búsqueda).
- Clic derecho en **«Sin carpeta»** → «Mover todo a una carpeta…», para ordenar de una vez todo lo que tienes suelto. En cualquier carpeta, clic derecho → «Seleccionar todo su contenido».

### ℹ️ Acerca de SUMP
- Nuevo botón **ⓘ** junto a Ajustes (y al final de Ajustes) con la versión, quién desarrolla SUMP, el sitio web, la página de versiones, la licencia y las versiones de yt-dlp, FFmpeg y Electron que usa tu equipo. Desde ahí también puedes buscar actualizaciones, ver las novedades o abrir la carpeta de datos de la app.

## [6.1.0] - 2026-10-02
SUMP 6.1 cambia por dentro cómo se descarga: ahora puedes elegir la calidad, ver lo que vas a bajar antes de hacerlo, controlar cada descarga y mandar enlaces a SUMP desde cualquier sitio, incluso con la ventana cerrada.

### 🎚️ Elige qué descargar
- **Calidad:** Máxima, 1080p, 720p, 480p o **solo audio (MP3)**, desde la barra de enlaces. SUMP recuerda tu elección, y la de los vídeos verticales se respeta igual que la de los horizontales.
- **Vista previa antes de descargar:** al pegar un enlace ves la miniatura, el título, el creador, la duración y cuánto ocupará en la calidad elegida. Puedes quitar un enlace de la lista con un clic.
- **Avisos de repetidos:** si ya tienes ese vídeo en tu biblioteca (aunque lo pegues con otra dirección, como twitter.com en vez de x.com), SUMP te lo dice y te deja verlo, saltarlo o descargarlo de nuevo.
- **Aviso de cuota:** si vas a añadir más enlaces de los que te quedan hoy o este mes, SUMP te lo dice antes de empezar. Los que no quepan esperan en la cola y siguen solos cuando la cuota se renueva.

### ⏯️ Control total de cada descarga
- **Varias a la vez:** hasta 3 descargas simultáneas (lo eliges en Ajustes).
- **Pausar, reanudar y cancelar** cada descarga, o todas juntas. Al reanudar, SUMP continúa desde donde iba cuando el sitio lo permite.
- **Si un enlace pasa 1 minuto sin avanzar, se salta** y empieza el siguiente. Lo puedes reintentar después con un clic.
- **Reintentar con un clic** las que fallaron, una por una o todas.
- Cada descarga muestra su miniatura, su velocidad y el tiempo que le queda, y también se ve el progreso en la barra de tareas de Windows.
- Lo que quede pendiente al cerrar SUMP vuelve a aparecer la próxima vez, sin empezar solo.

### 🪟 SUMP en segundo plano
- **Sigue en la bandeja al cerrar la ventana:** las descargas continúan, y desde su icono puedes pausarlas, descargar lo que tengas copiado o salir.
- **Atajo global (Alt + Shift + D):** copia un enlace en cualquier programa, pulsa el atajo y SUMP lo descarga. Puedes cambiar la combinación o desactivarlo en Ajustes.
- **Enlaces copiados:** con la ventana cerrada, SUMP te avisa cuando copias un enlace compatible para descargarlo con un clic. Si quieres, puede descargarlos solo, sin preguntar.
- **Botón «Descargar con SUMP» para tu navegador:** arrástralo desde Ajustes a tu barra de marcadores y descarga el vídeo que estés viendo con un clic.

### 📚 Biblioteca
- **Historial:** un nuevo estante con cada enlace que descargaste (o que falló), de dónde venía y cuándo. Desde ahí puedes abrir la publicación original, abrir el archivo o descargarlo otra vez, aunque ya lo hayas borrado.
- **Renombrar** con clic derecho o con **F2**, separando título y creador.
- **Recortar** un vídeo o audio desde el reproductor (botón de tijeras o tecla **T**): marca el inicio y el final con **I** y **O**, o arrastrando los tiradores, y SUMP guarda el fragmento como un archivo nuevo, sin tocar el original.
- **Audio en la biblioteca:** los MP3 aparecen con su portada y se reproducen en el mismo reproductor.
- Clic derecho → **Abrir la publicación original** o **Copiar el enlace original**, para lo que descargues desde ahora.
- Si descargas algo dos veces, la copia se llama «Título (2) - creador» y nunca se sobrescribe la anterior.

### 🛠️ Arreglos
- Las descargas en curso ya no aparecen como archivos sueltos en la biblioteca mientras se procesan.
- Varias descargas de X a la vez ya no se pisan entre sí.
- La marca de agua se añade más rápido.
- Los errores de descarga se explican en español y con el motivo real (vídeo privado, eliminado, con restricción de edad, sitio saturado…).
- La cuota del reservorio se actualiza al abrir la app, sin esperar a la primera descarga.

## [6.0.0] - 2026-10-01
SUMP 6 es un diseño completamente nuevo, hecho desde cero: no queda nada de la interfaz anterior. La idea detrás es sencilla: un *sump* es un reservorio, el lugar donde las cosas se juntan, y SUMP es el reservorio de lo que guardas de internet. Por eso ahora se ve y se usa como un archivo bien ordenado, no como un panel genérico.

### 🎨 Un SUMP nuevo, de principio a fin
- **Nueva identidad visual:** tonos tinta en lugar del azul marino, el azul de SUMP solo para lo importante y una tipografía de etiquetas condensada, como la de una caja de archivo.
- **Nueva pantalla de acceso**, la pantalla de arranque y la ventana de actualización, todas con el mismo diseño.
- **Las animaciones de los vídeos se mantienen:** el vídeo sigue creciendo desde su miniatura al abrirlo y vuelve a ella al cerrarlo, y los modales siguen naciendo del botón que los abre.

### 🗂️ Una biblioteca que se entiende de un vistazo
- **Barra lateral** con tus estantes (Todo, Favoritos, Sin carpeta) y tus carpetas. Puedes seguir arrastrando vídeos sobre una carpeta para moverlos.
- **Tarjetas con título y creador por separado** (por ejemplo «Mi vídeo» y *@creador*), además del peso, el formato y cuándo lo descargaste («hoy», «ayer», «hace 3 d»).
- **Agrupada por fecha:** Hoy, Ayer, Esta semana, Este mes y luego por meses.
- **Ordena** por más recientes, más antiguos, nombre o peso, y **cambia el tamaño de las miniaturas** (pequeñas, medianas o grandes). SUMP recuerda tu elección.
- El título de la biblioteca muestra dónde estás y cuántos archivos y espacio hay.
- **Barra flotante para la selección:** al seleccionar vídeos (Ctrl + clic) aparecen abajo las acciones de favoritos, mover y eliminar.

### 💧 El reservorio: tu cuota siempre a la vista
- En la barra lateral ves en todo momento cuántas descargas llevas **hoy** y **este mes**, como un tanque que se llena. Se pone ámbar cuando te acercas al límite y rojo al alcanzarlo.

### 🔗 Descargar es más cómodo
- **La barra de enlaces queda siempre arriba**, aunque bajes por la biblioteca.
- **Te dice al momento qué entendió:** al pegar enlaces ves cuántos son válidos y de qué sitio (X, YouTube, TikTok…), y el botón cambia a «Descargar 3» si pegaste varios.
- **Arrastra enlaces desde tu navegador** a la ventana de SUMP para añadirlos.
- **Nuevo atajo Ctrl + L** para ir directo a pegar un enlace. Todos los atajos están ahora en Ajustes.
- La descarga en curso y la cola se muestran juntas, con el estado de cada enlace.

### 🛠️ Arreglos
- Quitar un enlace de la cola ya no borra otro distinto cuando delante hay descargas terminadas.
- Soltar un enlace o un archivo sobre la ventana ya no puede sacar a SUMP de su pantalla.
- Los avisos y la cola muestran nombres de archivo y mensajes de error como texto, sin interpretarlos.

## [5.4.4] - 2026-10-01
### 🎨 Rediseño completo de la interfaz
- Se acabó el header de arriba y la fila de chips: ahora hay una **barra lateral** con tus carpetas como lista, y accesos directos a tu cuenta, X y ajustes.
- La barra de pegar enlaces y descargar ahora es una barra flotante tipo buscador, no un formulario.
- La Biblioteca pasó a tarjetas más grandes, con el nombre y el peso del archivo superpuestos sobre la miniatura (como una plataforma de streaming), en vez de ir en una franja aparte.
- Los modales (Ajustes, Cuenta de sump, Cuenta de X) ahora son paneles flotantes, más grandes y sin las líneas de formulario de antes — y siguen naciendo del botón exacto que los abre, con la misma animación que ya tenía el reproductor de vídeo.
- El reproductor de vídeo no cambió: sigue igual que antes.

## [5.4.3] - 2026-10-01
### 🔒 La clave deshabilitada ahora sí bloquea las descargas
- Antes, si deshabilitabas la clave de este equipo desde tu panel, un error de servidor con una redacción distinta a la esperada podía dejar pasar la descarga igual. Ahora se reconoce **cualquier** rechazo de autenticación del servidor, no solo mensajes con ciertas palabras, así que deshabilitar la clave bloquea la app de inmediato.

### 💻 Una clave por equipo, no una nueva en cada inicio de sesión
- Cerrar sesión y volver a iniciarla ya no crea una clave API nueva cada vez. SUMP ahora identifica tu equipo con un identificador estable del propio Windows (sobrevive a cerrar sesión e incluso a reinstalar la app), y el servidor reutiliza siempre la misma clave para ese equipo en vez de ir sumando una por cada login hasta agotar tu límite de dispositivos del plan.
- Si deshabilitas tu equipo desde el panel, al intentar iniciar sesión de nuevo verás un mensaje claro pidiéndote habilitarlo en "Claves API", en vez del confuso "alcanzaste el límite de dispositivos".

## [5.4.2] - 2026-09-30
### 🔑 Pantalla de login de pantalla completa
- **Iniciar sesión ya no es un modal sobre la app difuminada:** ahora es una pantalla dedicada de pantalla completa, con la identidad de SUMP, mientras no haya una cuenta conectada. El resto de la app no se ve hasta que inicias sesión.
- **El modal "Cuenta de sump" queda solo para verla ya conectada:** tu plan, tu cuota de descargas y cerrar sesión — el inicio de sesión vive en la nueva pantalla completa.
- **Si tu sesión se revoca mientras usas la app** (por ejemplo, deshabilitas el dispositivo desde tu panel), vuelve a aparecer esta misma pantalla completa para reconectar.

## [5.4.1] - 2026-09-29
### 🛠️ Corrección
- **Deshabilitar el dispositivo ahora sí bloquea la descarga:** Antes, si deshabilitabas SUMP desde tu panel web, la app igual descargaba (usando la cuota guardada en el equipo) y esa descarga no se sumaba a tu conteo. Ahora cada descarga se valida primero contra tu cuenta: si la deshabilitaste, se bloquea de inmediato y se cierra la sesión guardada en el equipo.

## [5.4.0] - 2026-09-29
### 🔑 Cuenta obligatoria para descargar
- **Inicia sesión para descargar:** SUMP ahora requiere una cuenta conectada para descargar. Pulsa **Iniciar sesión**, se abre tu navegador en la página real de inicio de sesión (con tu contraseña o con Google) y, al terminar, tu navegador reabre SUMP solo — como en Slack o GitHub Desktop.
- **SUMP nunca ve tu contraseña:** el inicio de sesión ocurre siempre en tu navegador, nunca dentro de la app.
- **Retoma lo que ibas a descargar:** si intentabas descargar algo sin sesión, en cuanto conectas tu cuenta la descarga (o la cola) continúa sola.
- **Tu cuota, siempre visible:** el chip de cuenta muestra cuántas descargas llevas hoy y este mes según tu plan.

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
