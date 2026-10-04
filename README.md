# GDC7

Canal público de distribución y actualizaciones del launcher GDC7 para Windows.

## Beta disponible

[GDC7 0.1.19-beta.1](https://github.com/juanizuq123-cmyk/GDC7/releases/tag/v0.1.19-beta.1).

Incluye el JAR suministrado gdc7-client-0.1.0.jar, sin modificar ni recompilar, con GDC7 Protocol 1.0.0 integrado. JUGAR instala automáticamente el mod, verifica su integridad y lo repara si falta o está dañado; después inicia Minecraft. La barra debajo del botón indica fase, archivo y progreso.

Conserva el diseño oscuro y rojo de 0.1.18, el logo oficial y JUGAR en el centro. No hay controles de Pack del cliente. El menú dentro de Minecraft conserva la versión 0.1.2.

Para actualizar desde 0.1.18: cerrá Minecraft y Prism; Opciones → Actualizaciones de GDC7 → Buscar actualización → Reiniciar y actualizar. Después pulsá JUGAR. Conserva la firma Ed25519 original, el ayudante interno, los respaldos y los datos personales.

Para una copia portable nueva: extraé completo GDC7-0.1.19-Portable-Windows.zip en su propia carpeta y abrí GDC7.exe. Código editable: GDC7-0.1.19-Codigo.zip. Contiene el código del launcher y el JAR integrado; los fuentes Java del mod suministrado no fueron proporcionados. Los Source code automáticos de GitHub contienen este repositorio de distribución.

Validación: 137 pruebas Node y 1018 restricciones de dependencias. El actualizador de 0.1.18 acepta la firma y prepara los 186 archivos del paquete. Las pruebas de instalación comprueban el JAR exacto, reutilización, reparación, preservación de archivos personales y detección de conflictos. No ejecutan Minecraft ni el recorrido completo en Windows; la prueba dentro del juego y la conexión con GDC7 Core están pendientes. GDC7 Core se instala por separado en el servidor.

Minecraft 1.21.11, Fabric 0.19.5, Fabric API 0.141.6+1.21.11 y Java 21 mantienen sus versiones. Instrucciones, validación y hashes acompañan la publicación. La clave privada no se publica.

El canal firmado está en [updates/beta.json](updates/beta.json).
