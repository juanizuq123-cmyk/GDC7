# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.16-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.16-beta.1).

Para reparar una copia cuyo actualizador falló: cerrar GDC7 y abrir `GDC7-Reparar-Actualizador-V2.cmd`. Comprueba y respalda tres archivos conocidos de la copia instalada, admite la reparación V1 y abre GDC7 para descargar, verificar, aplicar y reiniciar automáticamente. No requiere administrador. Las instrucciones de restauración están en `GDC7-0.1.16-Validacion.md`; el log del reparador queda junto al CMD.

La 0.1.16 aplica las actualizaciones con un ayudante JavaScript mediante el GDC7.exe preparado y verificado. Ya no usa PowerShell para aplicar actualizaciones. Conserva SHA-256, firma original Ed25519, progreso por bytes, respaldo y restauración ante fallos. PowerShell integrado se usa solamente en el reparador inicial. No se alteran las protecciones de Windows.

Se mantiene el diseño, JUGAR con preparación automática y barra de progreso, el menú centrado del cliente, las cuentas, los ajustes y la carpeta de juego. Minecraft 1.21.11, Fabric 0.19.5, Java 21 y el pack visual mantienen sus versiones.

Portable: extraer completo `GDC7-0.1.16-Portable-Windows.zip` y abrir GDC7.exe. Código editable: `GDC7-0.1.16-Codigo.zip`; los Source code automáticos de GitHub contienen este repositorio de distribución.

Validación: 131 pruebas Node, siete comprobaciones del reparador en PowerShell Linux y 1000 restricciones del pack aprobadas. Se verificaron por descarga pública los ocho adjuntos y sus hashes. El verificador y preparador de 0.1.13 aceptan la firma original y los 181 archivos. Los archivos del reparador coinciden con los incluidos en la beta. La clave privada no se publica.

La ejecución del reparador y el recorrido completo de la actualización en Windows siguen pendientes de comprobar en la PC. Los resultados y hashes están en la publicación. El canal es [updates/beta.json](updates/beta.json).
