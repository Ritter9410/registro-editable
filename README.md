# Registro editable

Página con NIT, dígito de verificación y razón social editables, y fecha de consulta automática.

Los datos se ingresan manualmente y se guardan en el navegador. La página no consulta bases de datos ni recibe formularios en un servidor.

## Publicación

El archivo `index.html` funciona sin compilación ni dependencias. GitHub Pages puede publicarlo desde la rama `main`, carpeta raíz.

## Edición

Los visitantes pueden cambiar el NIT, el dígito de verificación y la razón social. Los cambios se guardan en el almacenamiento de su propio navegador y no modifican la página para otras personas.

La fecha usa el formato DD-MM-AAAA y la zona horaria `America/Bogota`. Se calcula al abrir la página y se actualiza al volver a la pestaña, antes de imprimir y cada minuto si la página sigue abierta. No se restaura desde el almacenamiento del navegador ni se puede editar manualmente.

Para cambiar los valores publicados para todos, actualiza los atributos `value` de los tres campos editables en `index.html` y cambia `data-document-id` a una versión nueva. Así los navegadores no recuperan los valores de la versión anterior. Guarda los cambios en `main` para volver a publicar.

El guardado es automático. La página no muestra una barra de instrucciones ni botones de descarga o impresión. La impresión sigue disponible desde el menú del navegador.
