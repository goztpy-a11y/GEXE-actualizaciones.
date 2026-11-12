# GEXE — Actualizaciones para Windows

Repositorio oficial de distribución de GEXE para Windows de 64 bits.

[Descargar actualización de GEXE](https://github.com/goztpy-a11y/GEXE-actualizaciones./releases/latest/download/GEXE-Update.zip)

Extraé **todo** el ZIP a una carpeta, cerrá GEXE y ejecutá `GEXE-Setup.exe` con los otros archivos del instalador al lado. Actualiza la app en su ubicación habitual y conserva los libros y la configuración Google local.

El paquete pequeño usa el .NET Desktop Runtime 10 que ya requiere GEXE 1.1.1. En una computadora nueva sin ese componente hay que instalar [el runtime oficial de Microsoft](https://dotnet.microsoft.com/download/dotnet/10.0). El instalador todavía no tiene firma digital comercial.

GEXE consulta `gexe-update.json` de la última versión publicada y ofrece su descarga cuando es más nueva que la instalada. También se puede buscar desde Ayuda. La instalación requiere cerrar la app y ejecutar el instalador.

La prueba gratis dura cinco días desde el primer inicio de la versión que implementa la prueba en ese perfil de Windows. Al vencer se requiere licencia para editar o sincronizar; los libros se conservan y se permite guardar una copia y descargar actualizaciones.

La versión y el estado de cobros se detallan en [Releases](https://github.com/goztpy-a11y/GEXE-actualizaciones./releases). Al publicar GEXE 1.1.4, ambas páginas de pago siguen en modo de prueba; todavía no hay cobros reales habilitados.

El paquete público 1.1.4 incluye únicamente el identificador público Google. La conexión de cuentas nuevas sin secreto incluido requiere comprobación adicional. Este paquete de actualización no contiene libros de usuarios, contraseñas, el secreto de cliente Google ni tokens de sesión.
