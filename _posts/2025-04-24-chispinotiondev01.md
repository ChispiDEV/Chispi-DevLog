---
layout: post
title: "Iniciando el DevBlog - Semana 1"
subtitle: "Primera semana del DevBlog.\n Conecto Notion con mi blog y exporto mis posts automáticamente usando Python."
date: 2025-04-24
tags: ['GitHub']
slug: "chispinotiondev01"
mood: "Motivada"
issues: "1. Error en el tipo de propiedad de la sección “Estado” → Cambiar en el script la propiedad buscada \n 2. El contenido no se escribía en el archivo .md → Modificar script para que lea el texto del apartado, comentar la sección del script en el que se genera el contenido de forma dinámica \n"
resources: "  []"
projects:   []
publish: true
status: "Publicado"
background: "https://prod-files-secure.s3.us-west-2.amazonaws.com/4693d737-61cb-40a9-aa45-c589c0378838/b8a26494-213e-4b0c-b2e5-e33c71a8ab9d/post-01.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WGO33A7V%2F20250426%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250426T124022Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDH15HFCSZvl%2BkobWFdmAmXQFaBp0H0acuNzJvwdpprpgIgBbq2I%2FvbuX3A5EvTdkbR1NxCyu9ONgy8PAQBvIHap%2B4q%2FwMIQBAAGgw2Mzc0MjMxODM4MDUiDMdtTqDntMyYj62ddSrcA5GdFW3NKKrsknHSupMwZl2FhgU7dgPkoiBL6dRPeYns4w1fLRM2RsBt35hhOlLA3gmaiYF1qy51MXhd78BXLDADONRcs4mJPe0xG2CNQvY01rcS9jxVMnDBcLkznv9TeppBHiZDdfYJ7x4c%2FUuZNnQeg0s4HBanAnURn6MMoBPm1MkoU7g4L1v4tVvpHouVD1WND0r%2F9sIe0MR3%2FUT%2BlyXYhyqbHXfloEMD7s9TuDdIv7%2ByMjQScwHJOGMEdi6xeNENDwzuCWfJlrrVq7rtKe35f2d0jEiKZ6jlSjiCrfFlipQWGcK8gNgjkr%2BklQ%2FKUp3NHOH0QcYr1Uh6Ox%2BbNKkdSz5n8e47%2B67VxyPCqCU0SDA9prFNNPmV2plQR0tZdBoDBQxUWwp8Kkm2sTwegcYLW5rd7Jaq9XKPO%2B7o8CtcJNFQYCe3bd2dOUKUDfSnmB7LZ2XrEohu4X3%2Bl4Ggz%2BEgGMDGTSMRe8w6mp0Tms9Z6d2k0f705nqCtI3yyRjJDTq5YiZEb9vXiNgKemtrc6lQnRO29rIAv9bYmGEVM4G9dDEzNrP1nhicIx0QblgXEHY%2FaNH2iqGBRXSqLNL9JEKu3RwanfbXMjy5qNb11TG5t3dIErjSDQqLazjvMM6CssAGOqUB5W%2F7WYpYsFquu1DQymekqHt11ZBDcZtlzf7riarIcfSgWpzNx0tc0wBwebkdmarBaYmUa8k69Z4Os%2B5iVGFLYXOMoCHSUcIN6V1cdTCitCOchzuJ%2BWBop%2Ba5haioVyIs2mIdF9cS1h%2B1uuyv0KO3tSl4H0enoMDTkmz95L14WU%2F3ww4BCiOI5XjdWDMoCGzQpx1swILrAIXMvc23%2Bz%2FJ%2FWpmnll%2F&X-Amz-Signature=994d1d7a600efd0006e18b707db91531f2907a52de6939dc87c1b711f1568ae4&X-Amz-SignedHeaders=host&x-id=GetObject"  # Aquí agregamos el campo de fondo
---

Buenos días!

Soy Cristina Fuentes, analista de datos y bióloga. He creado este Blog para poder tener un seguimiento de mis avances en programación y análisis de datos 😉 

En esta primera entrada voy a recoger los avances realizados en el desarrollo de los scripts necesarios para generar las entradas del blog en Notion y que se actualicen en GitHub. 

Por un lado, he generado en Notion una base de datos en la que se almacena la información de los proyectos (la podéis ver aquí), ordenando la información y creando las categorías necesarias para poder incorporarlas al script principal. 

Posteriormente generé el script de Python (del que hay una copia para usar de plantilla en la sección de recursos) que transforma la información de la base de datos en un archivo .md que se utilizará en los posts. 

A continuación creé un repositorio público con GitHub Pages integrado para que hubiera un lugar donde publicar las entradas. 

Para poner bonita la página, utilicé Jeckyll que también tiene integración con GitHub. 

Por último modifiqué el script que generaba los archivos .md para que también agregara una copia a la carpeta de _posts del repositorio, permitiendo que las entradas se actualicen de forma automática. 

Y de momento esto es todo por hoy. 

Un amable saludo y nos vemos en la próxima entrada. 

Cristina
