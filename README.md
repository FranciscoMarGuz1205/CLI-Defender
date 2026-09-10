# CLI-Defender
Plataforma interactiva tipo consola para el aprendizaje de comandos básicos mediante gamificación.

Problema

Los estudiantes de primeros semestres de carreras relacionadas con informática y computación en CUCEI presentan dificultades para comprender y utilizar la línea de comandos. Su enseñanza suele apoyarse principalmente en explicaciones teóricas y ejercicios estáticos, lo que limita la práctica y puede hacer que la terminal sea percibida como una herramienta compleja o intimidante.

Esta falta de práctica genera deficiencias que posteriormente afectan asignaturas en las que el uso de la terminal es importante, como sistemas operativos, redes y ciberseguridad.

La causa principal identificada es la falta de herramientas educativas interactivas, accesibles y progresivas que permitan aprender comandos mediante práctica directa y retroalimentación inmediata.

MVP — Minimum Viable Product

El MVP de CLI Defender será una aplicación de escritorio funcional desarrollada en Godot Engine 4.x, con una interfaz visual inspirada en una terminal, que permita a un usuario aprender y practicar comandos básicos de línea de comandos mediante una experiencia gamificada y progresiva.

La versión mínima deberá permitir demostrar el funcionamiento de la propuesta mediante tres niveles jugables, cada uno con retos relacionados con comandos básicos. El usuario recibirá instrucciones sobre la acción que debe realizar, podrá escribir un comando en una terminal simulada y el sistema deberá validar automáticamente su respuesta.

Cuando el usuario ingrese un comando correcto, la plataforma deberá confirmarlo y permitirle continuar con el reto o nivel siguiente. Cuando el comando sea incorrecto, deberá mostrar una retroalimentación inmediata que indique el error o proporcione una orientación que permita intentarlo nuevamente.

El MVP deberá incluir, como mínimo:

Pantalla inicial desde la que pueda comenzar la experiencia.
Interfaz tipo terminal claramente identificable.
Área de instrucciones donde se explique qué debe realizar el usuario.
Campo de entrada de comandos para que el usuario interactúe con la plataforma.
Sistema de validación de comandos, capaz de diferenciar respuestas correctas e incorrectas.
Retroalimentación inmediata después de cada intento.
Tres niveles funcionales y progresivos, aumentando gradualmente la dificultad.
Sistema de avance entre retos o niveles cuando el usuario complete correctamente las actividades.
Mensaje o pantalla de finalización que indique que el usuario completó el contenido disponible.
Funcionamiento local y seguro, sin ejecutar los comandos directamente sobre el sistema operativo del usuario.
Pruebas básicas de funcionamiento, verificando que los niveles puedan completarse, los comandos sean evaluados correctamente y no existan errores que impidan terminar la experiencia.
Fuera de alcance

En esta primera versión del proyecto no se contempla:

Ejecutar comandos directamente sobre el sistema operativo real del usuario.
Desarrollar una terminal con acceso completo al sistema.
Incluir comandos avanzados de administración de sistemas, redes o ciberseguridad.
Desarrollar una aplicación móvil.
Desarrollar una versión web.
Implementar funciones multijugador.
Incorporar un sistema de cuentas de usuario.
Almacenar el progreso de los usuarios en servidores externos o bases de datos en la nube.
Sustituir cursos formales relacionados con sistemas operativos o línea de comandos.
