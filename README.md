# EDA y Dashboard con Analisis de Datos
Este repositorio contiene un archivo CSV con los datos que he usado y un archivo Excel (`.xlsm`) diseñado para [mostrar los supervivientes del Titanic por genero, clase y origen de embarque].

## Contenido
- **Archivo principal**: `titanic_2.xlsm`
- **Descripción**: La carpeta comprimida incluye [Tabla con los datos traidos del archivo `titanic.csv`, una pestañana con los valores duplicados, una pestaña con las tablas dinámicas de lo que se necesita analizar y por último la pestaña con el Dashboard].

## Uso
1. Descarga el archivo `titanic_2.xlsm`.
2. Abre el archivo en Microsoft Excel.
3. Revisar la tabla generada a partir del archivo `titanic.csv`, la pestaña de las tablas dinámicas y la pestaña del cuadro de mandos.

## Pasos
Para este proyecto realicé los siguientes pasos:
 1. Traer los datos al archivo excel del archivo csv
 2. Comprobar la correcta visualización y lectura de las columnas y valores
 3. Generar una columna de:
  - pasajeros duplicados
  - pasajeros fallecidos o supervivientes con texto (sin números booleanos)
  - edad real, con pasajeros con edad desconocida
  - nombre completo de la ciudad donde embarcaron 
  - nombre del país desde donde embarcaron
  - pasajeros sin o con algo de familia a bordo
4. En la pestaña de la stablas dinámicas:
  - Comprobar que el número de duplicados de nuevo
  - Comprobar que encajaban el número de supervivientes con fallecidos
  - Generar las tablas dinámicas pertinentes
5. Generar el cuadro de mandos
  - Segmento de género
  - Segmento de clase
  - Segmento de origen de embarque

## Conclusiones
Para este proyecto realicé los siguientes pasos:
 1. Dentro de las clases sobrevivieron más de la clase 1 que de la clase 3, donde la hay una desproporción notable entre supervivientes y fallecidos en estos últimos.
 2. Sobrevivieron muchos más pasajeros que venían desde Southampton pero también era el origen de embarque desde donde más pasajeros habían subido a bordo.
 3. Sobrevivieron muchas más mujeres que hombres
 4. Sobrevivieron menos pasajeros con familia que sin ella.
