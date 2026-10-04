# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.18-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.18-beta.1).

Launcher oscuro y rojo basado en la referencia: logo oficial a la izquierda y JUGAR en el centro. Inicio y Opciones quedan en la navegación. Abajo aparecen solo Configuración y Carpeta del juego; se elimina Pack del cliente. El menú dentro de Minecraft conserva su versión 0.1.2.

JUGAR verifica e instala automáticamente los componentes administrados que falten y luego inicia Minecraft. La barra debajo del botón indica fase, archivo y progreso; permite cancelar antes del arranque. Cuenta, memoria, servidor, actualizaciones y diagnóstico continúan en Opciones.

Desde 0.1.17 o 0.1.16: cerrá Minecraft y Prism; Opciones → Actualizaciones de GDC7 → Buscar actualización → Reiniciar y actualizar. Con la búsqueda automática activa, descarga al abrir. No requiere reinstalar. Conserva el ayudante interno de 0.1.16, la firma Ed25519 original, los respaldos y los datos personales.

Para una copia portable nueva: extraé completo GDC7-0.1.18-Portable-Windows.zip en su propia carpeta y abrí GDC7.exe. Código editable: GDC7-0.1.18-Codigo.zip. Los Source code automáticos de GitHub contienen este repositorio de distribución.

Validación: 133 pruebas Node, 1000 restricciones del pack e interfaz del mismo renderer en Chromium Linux a 1200 × 820, 940 × 700 y 800 × 560. Preparación y cancelación verificadas con eventos controlados; estas pruebas no ejecutan Minecraft ni una sesión Microsoft real. El verificador y preparador de 0.1.17 aceptan los 183 archivos del paquete firmado. El recorrido completo en Windows requiere comprobación en la PC.

Instrucciones, capturas, validación y hashes acompañan la publicación. Minecraft 1.21.11, Fabric 0.19.5, Java 21 y el menú 0.1.2 mantienen sus versiones. La clave privada no se publica.

El canal firmado está en [updates/beta.json](updates/beta.json).
