# Tecnologias a usar

## Front-end ✅

## Back-end ✅

## Testing ✅

## Data base ✅

## Analisis de datos - Bibliotecas ✅

## API extra ✅

## Por que se eligieron las tecnologias ✅

---

**Stack**

## Front

-   Lenguaje: TypeScript
-   Framework: React + Vite
-   Estilo: Tailwind + Tailwind Components
-   Otros: Axios, Chart.js (visualizacion de datos)

## Back

-   Lenguajes de programacion: Java
-   Frameworks: Spring Boot

## Testing

-   Front-end: Playright TS
-   Back-end: Postman

## DataBase

-   Modelado de la base de datos: Umletino
-   Tipo: NoSQL
-   Sistema: MongoDB
-   Lenguaje: Java

## Analisis de datos

-   Lenguaje: Python
-   Bibliotecas: Pandas, Numpy,
-   Formato de archivos: JSON

## API

-   Datos meteorologicos: https://openweathermap.org/api

## Porque se eligieron las tecnologias

En **front-end** la eleccion se dio con `TypeScript` por que tiene la ventaja de ser de tipado estatico que ayuda a prevenir errores en tiempo de desarrollo, mejora la legibilidad del codigo y facilita la refactorizacion.

Ademas de eso, es ideal para proyectos chicos y grandes, con baja y alta complejidad, ya que su estructura organizada y las herramientas de tipado facilitan la gestion de codigo largo plazo lo que lo hace perfectamente escalable.

TypeScript ademas se integra bien con otros lenguajes y herramientas, y su ecosistema es muy amplio.

En el caso de React + `Vite` es porque React es un framework maduro para crear interfaces de usuario declarativas y eficientes. Vite ofrece un servidor de desarrollo rapido y un sistema de modulos que mejora la experciencia de desarrollo.

`React` es altamente escalable y se adapta a proyectos de cualquier tamaño. Vite optimiza el rendimiento de las aplicaciones React.

Al tratarse de un proyecto pequeño es eficiente hacer el front con vite, y si el proyecto se amplia se podra migrar a `NEXT.js`.

En cuanto a los estilos `Tailwind CSS` proporciona una gran cantidad de clases CSS predefinidas que permiten crear interfaces de usuario personalizadas de forma rapida y eficiente.

`Tailwind components` ofrece componentes preconstruidos para acelarar aun mas el desarrollo, por ejemplos, tablas.

Ya que tailwind se integra muy bien con React, al potenciar su proposito es que fue el framework CSS elgido.

`Axios` elegida por su simpleza y popularidad para hacer peticione HTTP en JavaScript y TypeScript. Facilita la comunicacion con el back-end y la API de OpenWeatherMap.

En el caso del **back-end** con `Java` y `Spring Boot` es porque java es un lenguaje maduro y robusto, y Spring Boot es un framework que simplifica el desarrollo de aplicaciones Java.

Spring Boot ofrece caracteriticas como autoconfiguracion y gestion de beans que facilita la creacion de aplicaciones escalables. Es altamente configurable y se integra con un amplia variedad de tecnologias.

Para la **base de datos** elegimos `MongoDB` dado que es una base de datos NoSQL flexible y escalable, ideal para almacenar datos estructurados y no estructurados.

MongoDB se escala horizontalmente y puede manejar grandes volumenes de datos. No requiere un esquema rigido, lo que facilita la adaptacion a cambios en los datos.

Para modelar la base de datos elegimos `Umletino` porque es una herramienta util y sencilla para modelar bases de datos y viualizar la estructura de datos.

Es facil de entender y usar, perfecto para alguien nuevo con pocos conocimientos previos.

Con respecto al **analisis de datos** elegimos `Python` con las libreria `Pandas` y `NumPy`.

Python es un lenguaje popular para el analisis de datos, y Pandas y Numpy son bibliotecas fundamentales para manipular y analizar datos numericos, ademas ofrece una amplia gama de bibliotecas para realizar todo tipo de analisis de datos.

Para grande conjuntos de datos el proyecto podria implementar `Dask` o `PySpark`.

En cuenta a la tecnologia para el modelo predictivo usaremo Scikit-learn. Una biblioteca de aprendizaje automático para Python, que proporciona herramientas simples y eficientes para el análisis y modelado de datos. Es una opción popular para los profesionales del aprendizaje automático debido a su versatilidad y facilidad de uso.

La **API** `OpenWeatherMap` es popular y facil de usar para obtener datos meteorologicos.

**Conclusion**

-   TypeScript + React: Una combinacion solida para crear interfaces de usuario modernas y escalables.
-   Java y Spring Boot: Una opcion popular para back-ends empresariales, ofreciendo robustez y escalabilidad.
-   MongoDB: Ideal para almacenar datos de sensores, que pueden ser de naturaleza variable y crecer rapidamente.
-   Python: El lenguaje de facto para el analisis de datos, con una comunidad grande y una amplia gama de bibliotecas.

**Consideraciones adicionales**

-   Escalabilidad: La eleccion de MongoDB y Spring Boot garantiza una buena escalabilidad para manejar grandes volumenes de datos y un numero creciente de usuarios.

-   Flexibilidad: El uso de TypeScript y Python permite una gran flexibilidad en el desarrollo, adaptandose a los cambios en los requisitos del proyecto.

-   Usabilidad: Las herramienta seleccionadas facilitan el desarrollo y la gestion del proyecto, como Vite para el desarrollo rapido y Umletino para modelar la base de datos.

-   Integracion: Las tecnologia elegidas se integran bien entre si, lo que facilita la comunicacion entre el front-end, el back-end y la base de datos.

---
