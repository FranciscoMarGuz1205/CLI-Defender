# CLI-Defender

Plataforma interactiva tipo consola para el aprendizaje de comandos básicos mediante gamificación.

## Problema

Los estudiantes de primeros semestres de carreras relacionadas con informática y computación en CUCEI presentan dificultades para comprender y utilizar la línea de comandos. Su enseñanza suele apoyarse principalmente en explicaciones teóricas y ejercicios estáticos, lo que limita la práctica y puede hacer que la terminal sea percibida como una herramienta compleja o intimidante.

Esta falta de práctica genera deficiencias que posteriormente afectan asignaturas en las que el uso de la terminal es importante, como sistemas operativos, redes y ciberseguridad.

La causa principal identificada es la falta de herramientas educativas interactivas, accesibles y progresivas que permitan aprender comandos mediante práctica directa y retroalimentación inmediata.

## MVP — Minimum Viable Product

El MVP de CLI Defender será una aplicación de escritorio funcional desarrollada en Godot Engine 4.x, con una interfaz visual inspirada en una terminal. Permitirá que un usuario aprenda y practique comandos básicos de línea de comandos mediante una experiencia gamificada y progresiva.

La versión mínima demostrará el funcionamiento de la propuesta mediante tres niveles jugables, cada uno con retos relacionados con comandos básicos. El usuario recibirá instrucciones sobre la acción que debe realizar, escribirá un comando en una terminal simulada y el sistema validará automáticamente su respuesta.

Cuando el usuario ingrese un comando correcto, la plataforma lo confirmará y permitirá continuar con el reto o el siguiente nivel. Cuando el comando sea incorrecto, mostrará retroalimentación inmediata que indique el error o proporcione una orientación para intentarlo nuevamente.

El MVP deberá incluir, como mínimo:

- Una pantalla inicial desde la que pueda comenzar la experiencia.
- Una interfaz claramente identificable como terminal.
- Un área de instrucciones que explique qué debe realizar el usuario.
- Un campo de entrada de comandos.
- Un sistema que distinga respuestas correctas e incorrectas.
- Retroalimentación inmediata después de cada intento.
- Tres niveles funcionales y progresivos, con dificultad creciente.
- Avance entre retos o niveles cuando el usuario complete las actividades correctamente.
- Un mensaje o pantalla que indique que se completó el contenido disponible.
- Funcionamiento local y seguro, sin ejecutar comandos directamente en el sistema operativo del usuario.
- Pruebas básicas para verificar que los niveles puedan completarse, los comandos se evalúen correctamente y no haya errores que impidan terminar la experiencia.

## Comandos del MVP

La siguiente es una propuesta de comandos de estilo Unix/Linux, organizados en tres niveles progresivos. La aplicación los simulará dentro del juego; no los ejecutará directamente en el sistema operativo del usuario.

| Nivel | Comandos | Función |
|---|---|---|
| 1. Exploración | `help`, `pwd`, `ls` | Consultar los comandos disponibles en el juego, mostrar la ubicación actual y listar su contenido. |
| 2. Navegación | `cd`, `cat`, `mkdir` | Cambiar de directorio, mostrar el contenido de un archivo y crear un directorio. |
| 3. Gestión de archivos | `touch`, `cp`, `mv` | Crear un archivo vacío, copiarlo, moverlo o cambiarle el nombre. |

Los niveles avanzan desde la consulta de información y la ubicación en la consola hasta la creación y modificación de elementos. La selección final de comandos se revisará con el equipo.

## Fuera de alcance

En esta primera versión del proyecto no se contempla:

- Ejecutar comandos directamente sobre el sistema operativo real del usuario.
- Desarrollar una terminal con acceso completo al sistema.
- Incluir comandos avanzados de administración de sistemas, redes o ciberseguridad.
- Desarrollar una aplicación móvil.
- Desarrollar una versión web.
- Implementar funciones multijugador.
- Incorporar un sistema de cuentas de usuario.
- Almacenar el progreso de los usuarios en servidores externos o bases de datos en la nube.
- Sustituir cursos formales relacionados con sistemas operativos o línea de comandos.