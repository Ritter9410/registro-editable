# Registro editable

Página con cuatro campos editables: NIT, dígito de verificación, razón social y fecha.

Los datos se ingresan manualmente y se guardan en el navegador. La página no consulta bases de datos ni recibe formularios en un servidor.

## Publicación

El archivo `index.html` funciona sin compilación ni dependencias. GitHub Pages puede publicarlo desde la rama `main`, carpeta raíz.

## Edición

Los visitantes pueden cambiar los campos grises. Los cambios se guardan en el almacenamiento de su propio navegador y no modifican la página para otras personas.

Para cambiar los valores publicados para todos, actualiza los atributos `value` de los cuatro campos en `index.html` y cambia `data-document-id` a una versión nueva. Así los navegadores no recuperan los valores de la versión anterior. Guarda los cambios en `main` para volver a publicar.

El botón Descargar página conserva los valores visibles en una copia HTML independiente.
