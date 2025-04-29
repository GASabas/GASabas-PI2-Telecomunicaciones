# Análisis de las Telecomunicaciones: Internet, Telefonía Móvil y Televisión

Este proyecto tiene como objetivo analizar el comportamiento de las tecnologías de comunicación, como internet, telefonía móvil y televisión, para ofrecer soluciones personalizadas a un cliente. Los resultados pueden ayudar a diseñar estrategias para la expansión de productos, mejorar la calidad de los servicios y brindar mayores soluciones a los clientes.

# Estructura del Proyecto
El proyecto está compuesto por los siguientes elementos:

EDA: Análisis exploratorio de datos.    
georeferencia: Utilización de API para completar Georeferencia.         
Dashboard: Tablero interactivo en Power BI.
README.md: Este archivo explicativo del proyecto.
Datasets: carpeta que contiene los datasets descargados para trabajar

# Análisis Exploratorio de Datos (EDA)
En el EDA se examinan patrones de conectividad entre las diferentes provincias. Los puntos clave incluyen:
      Análisis de velocidades promedio contratadas comparadas con el ingreso per cápita por provincia.
      Comparación de localidades para identificar los usos tecnológicos más comunes o predominantes.
      Uso de gráficos y resúmenes estadísticos para obtener insights relevantes.

# Herramientas utilizadas
Se emplearon Python y sus librerías:
      Pandas: Manejo y análisis de datos.
      Matplotlib y Seaborn: Creación de visualizaciones.
      os: Manejo de archivos del sistema operativo.

# Tablero en Power BI
El tablero busca ofrecer una visión interactiva de los datos, permitiendo explorar tendencias por:
      Provincia.
      Tipos de tecnología (internet, telefonía móvil, televisión).
      Segmentaciones y accesos diferenciados.
![image](https://github.com/user-attachments/assets/3e9e04b9-93be-4e6b-aa2c-e1d81db68015)

En la calidad del servicio vemos cuáles son las teconologías utilizadas en ralción al Mbps contratados. Podemos ver que los Mbps de bajada, filtrados para la provincia de Buenos Aires, en el Trimestre 1 y 2, una desviación de 1 para el año 2024.

El KPI muestra la relación de la cantidad de accesos por hogar en relación a la cantidad de hogares que hay por provincia (esto se calculó a partir de un porcentaje de la población económicamente activa de cada provincia) con esto observamos como objetivo cuántos hogares nos faltan por crecer, teniendo en cuenta que tambíen existen otros productos para insertarce en el mercado y mejorar

![image](https://github.com/user-attachments/assets/2045532a-ec9c-443f-8a72-c0fb3ae1a3f5)

En esta imagen siguiente podemos ver el KPI donde indica la relación entre los accesos en relación a la población y el objetivo a llegar según estudios sobre el crecimiento del sector, también la distribución de los accesos a internet con los diferentes usos de tecnologías y las localidades que nos ayudará a medir la Calidad del servicio

![image](https://github.com/user-attachments/assets/e897560c-03ec-4bf9-b09f-8fbb7c93ee0b)

Cuando hablamos de otros productos, nos referimos a "TV por suscripción y satelital" y a "Telefonía prepago, postpago y operativo" podemos ver otro nicho con mucha oportunidad. 

![image](https://github.com/user-attachments/assets/3b798478-dee4-4ffe-83bb-7c7ea7c01ff8)

# Conclusiones
Tecnologías predominantes: La fibra óptica y el cable módem son las más utilizadas. Su prevalencia varía entre provincias.
Desigualdad de acceso: Las provincias rurales tienen menos accesos a internet, independientemente de la tecnología.
Provincias con mayor conectividad: Buenos Aires, Santa Fe, Córdoba y Mendoza son las líderes en accesos.

# Requisitos para Ejecutar el Proyecto
Python (con las siguientes librerías):
      pandas
      matplotlib
      seaborn
      os
      Power BI: Para visualizar el tablero interactivo.
Power BI.

