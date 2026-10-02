# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.13-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.13-beta.1), reconstruida desde la 0.1.11 recuperada.

- **Instalar o actualizar la 0.1.11:** descargá `GDC7-Setup-0.1.13.exe`, cerrá Minecraft, Prism y GDC7 y ejecutá el instalador. Conserva los ajustes y la carpeta de juego.
- **Portable:** descargá `GDC7-0.1.13-Portable-Windows.zip`, extraelo completo y abrí `GDC7.exe`.
- **Código editable:** descargá `GDC7-0.1.13-Codigo.zip` en esa publicación. Los archivos Source code automáticos de GitHub contienen solamente este repositorio de distribución.

Incluye usuario local / no premium, Microsoft con Prism oficial, actualizaciones firmadas, jugador y skin guardados por Prism y mejoras de interfaz. Minecraft 1.21.11, Fabric 0.19.5, Java 21, el pack visual y el menú 0.1.1 se conservan.

El canal beta está en [updates/beta.json](updates/beta.json). El launcher verifica la firma Ed25519, el tamaño, SHA-256 y las rutas antes de preparar una actualización. La clave privada se conserva fuera del repositorio y de los archivos públicos.

Validación: 111 pruebas automatizadas, interfaz real de Electron y 1.000 restricciones del pack comprobadas. La ejecución del juego, el instalador y el ayudante de actualización deben comprobarse en Windows. Las instrucciones y resultados detallados están incluidos en la publicación.
