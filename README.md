# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.14-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.14-beta.1).

- **Desde 0.1.13:** cerrá Minecraft y Prism; en GDC7 abrí Opciones → Actualizaciones → Buscar actualización → Descargar → Reiniciar y actualizar.
- **Si seguís en 0.1.11:** descargá GDC7-Setup-0.1.14.exe, cerrá los procesos e instalá en la carpeta habitual. Conserva ajustes y carpeta de juego.
- **Portable:** extraé completo GDC7-0.1.14-Portable-Windows.zip y abrí GDC7.exe.
- **Código editable:** GDC7-0.1.14-Codigo.zip incluye el launcher, pruebas y fuente Java del menú. Los archivos Source code automáticos de GitHub contienen este repositorio de distribución.

Inicio renovado con identidad GDC7 y JUGAR centrado. JUGAR comprueba e instala lo que falte, muestra fase y archivo en una barra debajo del botón y después inicia el cliente. Menú del juego 0.1.2: bosque y río al atardecer, logo centrado y botones nativos JUGAR / OPCIONES / SALIR. El menú anterior verificado se conserva en un respaldo antes de reemplazarlo. Microsoft sigue con Prism oficial y se conserva el usuario local.

Minecraft 1.21.11, Fabric 0.19.5, Java 21 y el pack visual mantienen sus versiones. Ajustes, mundos, capturas y cuentas se conservan.

El canal [updates/beta.json](updates/beta.json) usa la misma clave pública Ed25519 de la 0.1.13. Antes de activarlo se verificaron los ocho adjuntos por descarga pública y SHA-256 y se comprobó que el actualizador original 0.1.13 acepta la firma y prepara los 179 archivos de la nueva beta. La clave privada queda fuera de la entrega.

Validación: 117 pruebas automatizadas, interfaz real de Electron, 255 comprobaciones Java, 1.000 restricciones del pack y archivos del instalador verificados. Falta comprobar el recorrido completo en Windows: ejecución del instalador y del ayudante PowerShell, sesión Microsoft real, llegada al nuevo menú y conexión al servidor. Los resultados, instrucciones y huellas están en la publicación.
