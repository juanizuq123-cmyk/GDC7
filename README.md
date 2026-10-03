# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.17-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.17-beta.1).

Inicio con paisaje a pantalla completa, logo centrado y JUGAR / OPCIONES / SALIR. Se elimina la página y las tarjetas de Pack del cliente. JUGAR verifica e instala los componentes administrados que falten y después inicia el juego; la barra debajo del botón muestra fase, archivo y progreso. Cuenta, memoria, carpeta, servidor, actualizaciones y diagnóstico están en Opciones.

Corrige la lectura de ajustes durante las actualizaciones: las consultas de estado continúan disponibles, las escrituras esperan a que termine y la versión visible corresponde al paquete instalado. Conserva el ayudante interno de 0.1.16, la firma original Ed25519, hashes, respaldos y restauración ante fallos.

Desde 0.1.16: cerrar Minecraft y Prism, Opciones → Actualizaciones de GDC7 → Buscar actualización → Reiniciar y actualizar. La búsqueda y descarga al abrir dependen del ajuste automático; aplicar requiere reiniciar desde el botón. No requiere reinstalar. Ajustes, cuentas, mundos, opciones y mods personales se conservan.

Para una copia portable nueva: extraer completo GDC7-0.1.17-Portable-Windows.zip en su propia carpeta y abrir GDC7.exe. Código editable: GDC7-0.1.17-Codigo.zip. Los Source code automáticos de GitHub contienen este repositorio de distribución.

Validación: 133 pruebas Node, 1000 restricciones del pack y la interfaz del mismo renderer en Chromium Linux a tres tamaños. La preparación y cancelación visual se verifican mediante datos controlados; estas pruebas no ejecutan Minecraft ni una sesión Microsoft real. Los verificadores y preparadores de 0.1.16 aceptan los 183 archivos del paquete firmado. Los diez adjuntos públicos coinciden en tamaño y digest SHA-256 con los originales verificados.

La 0.1.16 se actualizó en la PC según el usuario. La 0.1.17 aún requiere comprobar allí el recorrido completo en Windows. Resultados, instrucciones, capturas y hashes están en la publicación. Minecraft 1.21.11, Fabric 0.19.5, Java 21, el pack y el menú 0.1.2 conservan sus versiones. La clave privada no se publica.

El canal firmado está en [updates/beta.json](updates/beta.json).
