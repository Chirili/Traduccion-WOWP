# Traduccion-WOWP
Traduccion del juego WOWP al español
### Requisitos

1. Tener instalar el programa PoEdit

### Proceso para decompilar el archivo mo a po

Lo primero es abrir un CMD como administrador ya que sino nos saltará un error diciendo ***Access Denied***, dentro de la consola primero nos movemos a la carpeta donde se encuentra la herramienta para decompilar, la cual esta ubicada en esta ruta: **C:\Program Files (x86)\Poedit\GettextTools\bin**, si se ha instalado PoEdit en su ruta por defecto.

Una vez dentro metemos en la misma ruta el archivo mo que se quiere decompilar yo lo he dividido en subcarpetas en una guardo los archivos mo a decompilar y en otra los archivos po:

- Esta captura es antes de ejecutar el comando, en la carpeta de arriba a la izquierda se ve un archivo mo y en la de abajo no hay ningun archivo po pero...
![Primera imagen de la decompilacion](imgs/captura1.png)

- Al ejecutar el comando nos da un archivo .po el cual podremos editar:
  ![Primera imagen de la decompilacion](imgs/captura2.png)

- Otra captura con VisualCode para que se vea que se puede editar el archivo po

![Primera imagen de la decompilacion](imgs/captura3.png)

Despues si se quiere volver a compilar el archivo .po cuando se haya terminado de modificar lo unico que tenemos que usar es la herramienta msgfmt:

- En esta primera captura muestro el comando sin ejecutar y como he borrado el archivo .mo
  
![Primera imagen de la decompilacion](imgs/captura4.png)

- Despues de ejecutar el comando en la carpeta de arriba a la izquierda nos aparece el archivo .mo ya compilado

![Primera imagen de la decompilacion](imgs/captura5.png)