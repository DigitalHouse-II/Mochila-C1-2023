## Introducción a la Informática
Actividad de investigación 14/3
¿Que es un usuario root en Linux?
El usuario root es uno de los dos tipos de usuarios en Linux. Root en particular Es el usuario administrador del sistema. Tiene los permisos necesarios para realizar cualquier tipo de tarea (instalar y desinstalar programas, modificar la configuración del sistema, cambiar permisos de archivos, etc).

¿Por qué ubuntu no me deja establecer la contraseña durante la instalación?
De forma predeterminada, en Ubuntu, el usuario root no tiene una contraseña establecida. Esto se debe a que el enfoque recomendado es utilizar el comando sudo (sudo permite a los “usuarios normales” ejecutar comandos con privilegios de root o superusuario) para ejecutar comandos con privilegios de root.

¿Cuáles son los procesos típicos de Linux?¿Cómo identificarlos?
Los procesos típicos de Linux son aquellos programas que se ejecutan en segundo plano para realizar diferentes tareas en el sistema operativo (el padre y principal de todos ellos se llama init). Algunos ejemplos de procesos típicos son el sistema de impresión, el servidor web, el daemon de correo electrónico, el sistema de copias de seguridad, entre otros. Estos procesos se ejecutan de manera autónoma y se encargan de realizar tareas específicas en el sistema operativo.

Para poder identificarlos existen varios comandos:

ps: Muestra información sobre los procesos que se están ejecutando en el sistema operativo.
top: El comando top que hace la misma función que el comando ps pero mantiene el listado de procesos monitoreando es decir los muestra en tiempo real.
