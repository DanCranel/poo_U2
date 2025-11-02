🎬 Proyecto de Gestión de Contenidos Audiovisuales 🎧

Este proyecto es una aplicación desarrollada en Java cuyo propósito es gestionar distintos tipos de contenidos audiovisuales.
La idea principal es contar con una estructura que permita organizar y mostrar información detallada sobre películas, series, documentales, videos musicales y podcasts.
Es un ejemplo práctico del uso de la Programación Orientada a Objetos (POO), donde se aplican conceptos como herencia, polimorfismo y encapsulación.

📌 Objetivos del Proyecto

El objetivo de este proyecto es aplicar los principios fundamentales de la POO para construir un sistema modular y escalable.
Concretamente, se busca:

Organizar distintos tipos de contenido dentro de una misma clase base (ContenidoAudiovisual).

Implementar subclases específicas para cada tipo de contenido (película, serie, documental, etc.) con sus propios atributos y comportamientos.

Mostrar los detalles de cada contenido de forma clara, aprovechando el polimorfismo.

Facilitar futuras expansiones del programa, permitiendo agregar fácilmente nuevos tipos de contenido.

🚀 Clases y Funcionalidades Implementadas

A continuación, se describen las clases principales y las nuevas funcionalidades agregadas:

🧩 ContenidoAudiovisual

Es la clase base de todo el sistema.
Define los atributos generales compartidos por todos los tipos de contenido, como título, duración y género.

🎞️ Pelicula

Subclase que representa una película.
Incluye atributos como la productora y una lista de actores.
Se añadió el método agregarActor() para incorporar intérpretes a cada película.

📺 SerieDeTV

Representa una serie conformada por múltiples temporadas.
Cuenta con un método agregarTemporada() para registrar cada temporada y sus episodios correspondientes.

🎥 Documental

Modela los documentales, con atributos adicionales como tema e investigador principal, que aporta información sobre el área de estudio o investigación tratada.

🎵 VideoMusical

Subclase que representa un video musical.
Agrega los atributos artista y álbum para detallar la fuente musical.

🎙️ Podcast

Representa un podcast y añade atributos como presentador (host) y tema, permitiendo describir el contenido de forma más precisa.

💻 Cómo Clonar y Ejecutar el Proyecto

Sigue estos pasos para descargar y ejecutar el proyecto en tu equipo:

Clonar el repositorio:

git clone https://github.com/tuusuario/proyecto-gestion-contenidos.git


Importar el proyecto en Eclipse:

Abre Eclipse.

Ve a File → Import → Existing Projects into Workspace.

Selecciona la carpeta del proyecto descargado.

Ejecutar el programa:

Verifica que el proyecto compile sin errores.

Abre la clase PruebaAudioVisual.

Clic derecho → Run As → Java Application.

💡 Mejoras y Extras Implementados

Cada tipo de contenido cuenta con su propio método mostrarDetalles(), que imprime la información de manera estructurada.

Se empleó una arquitectura modular, que facilita la lectura, mantenimiento y ampliación del proyecto.

El sistema permite añadir nuevas categorías en el futuro sin afectar el código existente.

🔮 Posibles Mejoras Futuras

Incorporar pruebas unitarias para validar el correcto funcionamiento de las clases y métodos.

Integrar una base de datos para el almacenamiento persistente de los contenidos.

Desarrollar una interfaz gráfica o web para una experiencia de usuario más visual e interactiva.

🛠️ Herramientas Utilizadas

Lenguaje: Java

Entorno de desarrollo: Eclipse IDE

👨‍💻 Autor

Daniel Morales
Estudiante de Ingeniería en Software – Universidad Politécnica Salesiana
