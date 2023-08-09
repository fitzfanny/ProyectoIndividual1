# ProyectoIndividual1 

![image](https://github.com/fitzfanny/ProyectoIndividual1/assets/122370500/46a90ee0-eb20-45e9-a8d0-8acf7c600b39)





  Bienvenidos a mi primer proyecto individual de Machine Learning Operations (MLOPS).

  SISTEMA DE RECOMENDACION DE PELICULAS
  
  En este proyecto lo primero que hice es crear un ETL (EXTRACTION TRANSFORM LOAD),donde se  ingestan los datos provistos en la 
  carpeta Datasets enviada por Henry.Luego se realiza la limpieza de datos para cada dataset y se corrigen los tipos de datos, 
  Y por ultimo se relacionan los datasets para poder acceder a su información por medio de consultas a la API.
  
  El segundo paso para el proyecto consistió en realizar el EDA (Análisis exploratorio de datos).
  Aquí realicé estadísticas descriptivas de los campos, distribución de las variables numéricas, matriz de relaciones sobre el 
  DataFrame “peliculas".

 El tercer paso concistió en la IMPLEMENTACION DE APIS (MAIN).
 En el archivo main.py se desarrolló una interfaz, utilizando las bibliotecas de FASTAPI que permite a los usuarios interactuar 
 con el modelo de Machine Learning, al brindarme los datos de entrada necesarios para obtener sus predicciones correspondientes.
 Mediante esta interfaz se pueden hacer consultas y obtener respuestasen tiempo real.
 
 Para finalizar realice mi  DESARROLLO DEL MODELO MACHINE LEARNING (MAIN), un sistema basado en recomendacion de peliculas en el 
 cual opté, segun las consignas asignadas, en seleccionar una pelicula y que me devuelva 5 similares. Luego creé una matriz de 
 características TF-ID, para calcular el algoritmo de similitud de cosenos.   Este modelo ha sido entrenado utilizando los datos 
 preprocesados y preparados. Una vez finalizado el entrenamiento, se procedió a crear el despliegue de la aplicación en RENDER. 
 Este permite poner en funcionamiento el modelo.

 
PRINCIPALES LIBRERIAS UTILIZADAS:
  
📊 Scikit Learn: Utilizado para vectorizar, tokenizar y calcular la similitud coseno. Esta es una librería de ML

🐍Python: Lenguaje de programación principal utilizado en el desarrollo del proyecto.

💻Numpy: Utilizado para realizar operaciones numéricas y manipulación de datos.

🐼Pandas: Utilizado para la manipulación y análisis de datos estructurados.

📈Matplotlib y Seaborn: Utilizados para la visualización de datos y generación de gráficos.

📳FastAPI: Utilizado para crear la interfaz de la aplicación y procesar los parámetros de funciones.

🌐Render: Plataforma utilizada para el despliegue del modelo y la aplicación.



Link a la API: https://mlopsi1fanny.onrender.com/docs

                                                                                                      

 


 
  
