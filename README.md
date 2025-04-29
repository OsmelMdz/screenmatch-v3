# Curso Java: Consumir API, escribir archivos y manejar errores

Este repositorio contiene el proyecto **Screenmatch versión 3**, desarrollado como parte del curso **"Java: Consumir API, escribir archivos y manejar errores"** impartido por **Bruno Darío Fernández Ellerbach** a través de **Alura Latam**.

En este curso, profundicé en técnicas para el consumo de APIs externas, el procesamiento de datos en formato JSON, la escritura de archivos y el manejo adecuado de excepciones, todo utilizando el lenguaje de programación Java.

## Descripción

Durante el curso, aprendí a aplicar los siguientes conceptos clave:
- **Consumo de APIs HTTP**: Realización de solicitudes a servicios web utilizando clases como `HttpURLConnection`.
- **Manipulación de datos JSON**: Uso de la biblioteca **Gson** para convertir datos JSON en objetos Java y viceversa.
- **Manejo de archivos**: Escritura de datos persistentes en archivos locales mediante clases del paquete `java.io`.
- **Gestión de excepciones**: Implementación de bloques `try-catch` para prevenir errores de red, parsing y escritura.
- **Buenas prácticas de POO**: Separación de responsabilidades, modularización del código y reutilización de clases.

Como parte del proyecto, desarrollé **Screenmatch versión 3**, una aplicación que accede a la **API de OMDB** para obtener información de películas y series. Esta API proporciona datos detallados sobre cada título, tales como su sinopsis, actores, directores, calificación y más. Además, también permite obtener la imagen de un póster asociado con cada película o serie.

## Tecnologías utilizadas
- **Java**: Lenguaje de programación utilizado para la creación del proyecto.
- **JDK 17.0.6**: Versión del Java Development Kit empleada.
- **IntelliJ IDEA**: IDE utilizado para el desarrollo del proyecto.
- **Gson**: Biblioteca externa para convertir datos entre JSON y objetos Java.
- **API OMDB**: Servicio web utilizado para obtener información de películas y series.

## Requisitos
- Tener instalado [Java JDK 17.0.6](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html).
- IntelliJ IDEA o cualquier otro IDE compatible con Java.
- Conexión a internet para consultar la API OMDB.
- Descargar la biblioteca Gson (si no se usa un gestor de dependencias como Maven o Gradle).
- Obtener una clave de API de OMDB en [https://www.omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx).

## Cómo ejecutar el proyecto

1. Clona el repositorio en tu máquina local.
2. Abre el proyecto con IntelliJ IDEA.
3. Asegúrate de tener añadida la biblioteca **Gson** al classpath.
4. Obtén una clave de API de OMDB y reemplaza `[yourkey]` en las URLs de la API en el código.
5. Ejecuta el archivo `PrincipalConBusqueda.java` como aplicación Java, ubicado en el paquete `com.aluracursos.screenmatch.principal`.

## Lo aprendido en este curso
- Realizar conexiones HTTP desde Java y leer sus respuestas.
- Convertir datos JSON a objetos Java utilizando Gson.
- Manejar y registrar excepciones comunes en conexiones y archivos.
- Persistir datos en archivos locales de forma organizada.
- Diseñar aplicaciones más robustas, reutilizables y listas para integrarse con servicios externos.

## Instructor
**Bruno Darío Fernández Ellerbach**  
Ingeniero en Sistemas de Información, egresado de la UTN Mendoza, Argentina.  
Especializado en desarrollo de aplicaciones Android y docente en Alura desde 2020.  
LinkedIn: [Bruno Darío Fernandez Ellerbach](https://www.linkedin.com/in/brunofernandezellerbach/)  
GitHub: [bfjeje](https://github.com/bfjeje)
