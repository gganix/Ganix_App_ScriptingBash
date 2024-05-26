# Gestor de Copias de Seguridad

Este repositorio contiene un conjunto de scripts escritos en Bash para facilitar la gestión de copias de seguridad en sistemas Ubuntu.

## Uso

Para utilizar estos scripts, sigue los siguientes pasos:

1. Descarga todos los scripts y colócalos en la misma carpeta o directorio.
2. Abre una terminal y navega hasta la ubicación donde se encuentran los scripts utilizando el comando `cd`.
3. Otorga permisos de ejecución al script principal `scrMenu` ejecutando el comando `chmod +x ./scrMenu`.

## Ubicación de los Archivos

Las copias de seguridad se crean en la ruta `Home/usuario/CopiadeSeguridad`. Los mensajes de error generados por los scripts también se guardan en esta ubicación, permitiendo al usuario identificar y resolver cualquier problema que pueda surgir durante la ejecución de los scripts.

Se recomienda revisar los archivos de texto en esta ubicación en caso de que ocurran errores durante la ejecución de los scripts.

¡Disfruta de una gestión más sencilla de tus copias de seguridad con estos scripts!


## Descripción de los Scripts

### scrMenu

Este script es el punto de entrada principal para interactuar con las funciones de copia de seguridad. Proporciona un menú interactivo que te permite realizar las siguientes operaciones:

- **Programar Copia de Seguridad:** Te permite programar una copia de seguridad para que se ejecute automáticamente en determinados días de la semana.
- **Realizar Copia de Seguridad Ahora:** Inicia una copia de seguridad inmediata del directorio que elijas.
- **Cancelar Programación:** Permite cancelar la programación de una tarea de copia de seguridad previamente programada.
- **Salir:** Finaliza la ejecución del script.

### ScrProgramar

Este script permite al usuario programar una copia de seguridad automatizada para que se ejecute en días específicos de la semana. Solicita al usuario el directorio que desea respaldar, el nombre de la tarea, y los días en los que desea que se ejecute la copia de seguridad.

### ScrCopiar

Este script realiza una copia de seguridad inmediata del directorio seleccionado por el usuario. Pide al usuario que seleccione el directorio que desea respaldar y realiza la copia de seguridad en el directorio predeterminado.

### ScrCancelar

Este script permite al usuario cancelar una tarea de copia de seguridad programada previamente. Muestra una lista de las tareas programadas y solicita al usuario que elija la tarea que desea cancelar.

