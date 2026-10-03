# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.15-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.15-beta.1).

- **Reparar el actualizador de 0.1.13/0.1.14:** cerrá GDC7 y abrí `GDC7-Reparar-Actualizador.cmd` de la publicación. Comprueba y respalda tres archivos de la copia existente, aplica la corrección y vuelve a abrir GDC7. No requiere reinstalar ni administrador. Después, en Opciones → Actualizaciones, buscá/descargá la beta y pulsá Reiniciar y actualizar.
- **Desde una copia ya reparada:** la actualización a la 0.1.15 mantiene la corrección del actualizador. Conserva cuentas, ajustes y carpeta de juego.
- **Portable:** extraé completo `GDC7-0.1.15-Portable-Windows.zip` y abrí GDC7.exe.
- **Código editable:** `GDC7-0.1.15-Codigo.zip` contiene el launcher, pruebas, fuente Java del menú y reparador. Los Source code automáticos de GitHub contienen este repositorio de distribución.

La nueva entrada del ayudante PowerShell conserva rutas Unicode y registra errores de inicio. La espera utiliza progreso real durante la verificación SHA-256 y GDC7 permanece abierto hasta recibir la confirmación para reiniciar. Se mantienen las verificaciones de rutas, los respaldos y la restauración de la actualización. El reparador guarda su log junto al CMD y sus respaldos en la carpeta de datos del launcher; las instrucciones para deshacerlo están en `GDC7-0.1.15-Validacion.md`.

Se conserva el inicio visual y JUGAR de la 0.1.14, la preparación automática del cliente con barra debajo de JUGAR y el menú centrado 0.1.2. Minecraft 1.21.11, Fabric 0.19.5, Java 21 y el pack visual mantienen sus versiones.

El canal [updates/beta.json](updates/beta.json) conserva la clave pública Ed25519 de la 0.1.13. Se verificaron los ocho adjuntos por descarga pública y SHA-256; el verificador y preparador originales de la 0.1.13 aceptan la nueva firma y los 180 archivos. Los tres archivos del reparador coinciden exactamente con los incluidos en la beta. La clave privada queda fuera de la entrega.

Validación: 125 pruebas Node, 1.000 restricciones del pack y comprobaciones PowerShell en Linux de entrada real, hash, progreso, reparación, repetición, restauración y fallo parcial. Falta comprobar la ejecución del reparador y el recorrido completo de la actualización en Windows. Los resultados y hashes están en la publicación.
