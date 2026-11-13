# GEXE — Actualizaciones para Windows

Repositorio oficial de distribución de GEXE para Windows de 64 bits.

Versión estable actual: **1.1.5**. Precios mostrados: **USD 28,15 por mes** y **USD 201,09 por pago único**. Verificada en Windows: once comprobaciones funcionales, extracción del instalador y apertura de las pantallas de Inicio y Planes con los nuevos importes.

[Descargar actualización de GEXE](https://github.com/goztpy-a11y/GEXE-actualizaciones./releases/latest/download/GEXE-Update.zip)

Extraé **todo** el ZIP a una carpeta, cerrá GEXE y ejecutá `GEXE-Setup.exe` con los otros archivos del instalador al lado. Actualiza la app en su ubicación habitual y conserva los libros y la configuración Google local.

El paquete pequeño usa el .NET Desktop Runtime 10 que ya requiere GEXE 1.1.1. En una computadora nueva sin ese componente hay que instalar [el runtime oficial de Microsoft](https://dotnet.microsoft.com/download/dotnet/10.0). El instalador todavía no tiene firma digital comercial.

GEXE consulta `gexe-update.json` de la última versión publicada y ofrece su descarga cuando es más nueva que la instalada. También se puede buscar desde Ayuda. La instalación requiere cerrar la app y ejecutar el instalador.

La prueba gratis dura cinco días desde el primer inicio de la versión que implementa la prueba en ese perfil de Windows. Al vencer se requiere licencia para editar o sincronizar; los libros se conservan y se permite guardar una copia y descargar actualizaciones.

La versión y el estado de cobros se detallan en [Releases](https://github.com/goztpy-a11y/GEXE-actualizaciones./releases). El titular confirmó el cambio de importes del proveedor de pagos. No se realizó una compra de prueba ni se verificó una transacción. La versión 1.1.5 conserva los identificadores de producto y la integración pública de prueba de 1.1.4; esta actualización no habilita por sí sola cobros reales.

El paquete público 1.1.5 incluye únicamente el identificador público Google. La conexión de cuentas nuevas sin secreto incluido requiere comprobación adicional. Este paquete de actualización no contiene libros de usuarios, contraseñas, el secreto de cliente Google ni tokens de sesión.

El [código recuperado de Windows](recuperacion/windows-1.1.5/GEXE-Codigo-Recuperado-1.1.5.zip) queda disponible para continuar el desarrollo. Se reconstruyó desde la versión pública 1.1.4 y puede no contener cambios posteriores guardados solo en otros dispositivos. La candidata histórica de recuperación fue seguida por la publicación estable 1.1.5 tras las comprobaciones en Windows.

Android permanece pendiente de recuperar su proyecto, APK y firma. El borrador de su canal no se publicó ni se modificó durante esta actualización Windows.
