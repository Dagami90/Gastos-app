# Sincronización con Google Drive

La app puede seguir funcionando sin conexión y guardar una copia en Google Drive.

## Configuración
1. Abre https://script.google.com/ y crea un proyecto nuevo.
2. Copia `GoogleAppsScript_Code.gs` al editor.
3. Guarda el proyecto.
4. Deploy > New deployment > Web app.
5. Ejecutar como: tú.
6. Acceso: cualquier usuario con el enlace (la app además usa una clave de sincronización).
7. Copia la URL que termina en `/exec`.
8. En Gastos > Configuración > Sincronización con Google Drive, pega esa URL y la misma clave que aparece al final del archivo `.gs`.
9. Pulsa Guardar conexión.
10. Pulsa Guardar en Drive para hacer la primera copia.
11. En otro dispositivo, configura la misma URL y clave y pulsa Recuperar de Drive.

La app no guarda contraseñas bancarias ni credenciales de Trade Republic. Drive se utiliza como almacén de la copia financiera.
