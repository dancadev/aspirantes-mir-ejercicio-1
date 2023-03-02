Abrir la consola e imprimir la ubicación actual.
Para abrir la consola en mi caso Cmder: Click derecho/opción Cmder Here dentro de la carpeta o directorio. 

Para imprimir la ubicación actual en la consola se utiliza el comando pwd.

2. Crear una carpeta llamada ejercicios desde la consola.
	
-   Para crear la carpeta llamada ejercicios utilizamos el comando mkdir ejercicios

3. Cambiar la ubicación a la nueva carpeta que crearon.
	
-   Para cambiar la ubicación a la nueva carpeta utilizamos el comando: cd ejercicios

4. Abrir la carpeta con VSCode.

-   Para abrir la carpeta con VSCODE utilizamos dentro de Cmder el comando: code .

5. En VSCode crear una carpeta ejercicio1.

-   Para crear la carpeta se puede utilizar varias opciones:
    -   Abrir el terminal y desde este crear la carpeta con el comando mkdir
    -   Click en icono Nueva Carpeta ubicado en el explorador de archivos en VSCODE.

6. Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.

-   Para crear el archivo podemos utilizar varias opciones:
    -   Desde terminal con el comando touch README.md
    -   Click en icono Nuevo Archivo ubicado en el explorador de archivos en VSCODE.

7.Configurar nombre e email globalmente en git.

-   Para la configuración utilizamos en Cmder el siguiente comando: 
    -   git config –global user.name dancadev (nombre)
    -   git config –global user.email dancadev@gmail.com (email)

8.Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.

-   Seguiremos los siguientes pasos:
    -   Para salir de la ubicación: cd .. (ubicación carpeta ejercicios)
    -   Desde la cubicación indicada utilizamos el comando git init

9. Crear un primer commit con el mensaje “Versión Inicial”.

-   Utilizamos: git commit -m “Versión Inicial”

10. Agregar al README.md los comandos que ejecutaron en cada paso.

11. Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”

-   Para el siguiente commit usaremos:
    -   git commit -m "Agrega Solución primer ejercicio"

12. Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1.

-   para este paso cree un repositorio en github llamado 
-   para agregar origen el repositorio se utiliza lo siguiente : git remote add origin https://github.com/dancadev/aspirantes-mir-ejercicio-1.git
-   para publicar a github utilizamos lo siguiente: git push -u origin master.