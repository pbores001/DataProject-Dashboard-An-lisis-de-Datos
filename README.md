# Objetivo dle proyecto
Este repositorio contiene un archivo CSV con los datos que he usado y un archivo Excel (`.xlsm`) diseñado para [mostrar los supervivientes del Titanic por genero, clase y origen de embarque para mostrar si dentro de estas variables hubo más probabilidad o no de sobrevivir en el naufragio del transatlántico británico]. Este proyecto busca identificar diferencias entre supervivientes y no supervivientes para aaveriguar un posible patrón. Por ello se valoran las variables de género, clase, pasajeros con familia y origen de embarque. Se cuenta para todo esto con un cuadro de mandos en el que se pueda identificar este patrón de supervivencia para poder llegar a unas conclusiones pertinentes. Dentro del dashboard están implementados los filtros de género, clase, pasajeros con o sin familia y el origen de embarque para obtener una visualización más interactiva del suceso.

## Contenido
- **Archivo principal**: `titanic_2.xlsm` (carpeta Dashboard)
- **Descripción**: La carpeta comprimida incluye [Tabla con los datos traidos del archivo `titanic.csv`, una pestaña con las tablas dinámicas de lo que se necesita analizar y por último la pestaña con el Dashboard].

## Uso
1. Descarga dentro de la carpeta Dashboard el archivo `titanic_2.xlsm`.
2. Abre el archivo en Microsoft Excel.
3. Revisar la tabla generada a partir del archivo `titanic.csv` (dentro de la carpeta Data), la pestaña de las tablas dinámicas (Tablas_Dinámicas) y la pestaña del cuadro de mandos (DB).

## Pasos
Para este proyecto realicé los siguientes pasos:
 1. Traer los datos al archivo excel del archivo csv `titanic.csv`
 2. Comprobar la correcta visualización y lectura de las columnas y valores
 3. Generar una columna de:
  - pasajeros duplicados
  - pasajeros fallecidos o supervivientes con texto (sin números booleanos)
  - edad real, con pasajeros de edad desconocida
  - nombre completo de la ciudad donde embarcaron 
  - nombre del país desde donde embarcaron
  - pasajeros sin o con algo de familia a bordo
4. En la pestaña de las tablas dinámicas:
  - Comprobar que el número de duplicados de nuevo
  - Comprobar que encajaban el número de supervivientes con fallecidos
  - Generar las tablas dinámicas pertinentes
5. Generar el cuadro de mandos
  - Segmento de género
  - Segmento de clase
  - Segmento de pasajeros con o sin familia a bordo
  - Segmento de origen de embarque

## Conclusiones
Para este proyecto realicé los siguientes pasos:
 1. Dentro de las clases sobrevivieron más de la clase 1 que de la clase 3, donde la hay una desproporción notable entre supervivientes y fallecidos en estos últimos. Se podrían tener en cuenta estas razones:
    - Prioridad en el acceso a los botes salvavidas. Por las diferencias en el tratamiento en la época de las clases, las personas de primera clase tenían un estatus social elevado y probablemente recibieron prioridad para abordar los botes salvavidas. Esto se refleja 
    en la proporción de supervivencia significativamente mayor en primera clase.
    - Familias numerosas en tercera clase. La mayoría de los pasajeros de tercera clase viajaban en familias grandes, lo que dificultaba la evacuación conjunta. Según el dashboard sobrevivieron mas pasajeros con familia de la clase 1 y 2 que de la clase 3. 
 3. Sobrevivieron muchos más pasajeros que venían desde Southampton pero también era el origen de embarque desde donde más pasajeros habían subido a bordo.
    - La mayoría de los pasajeros venían del puerto de Southampton, por tanto, hubo más supervivientes de este origen de embarque.
 4. Sobrevivieron muchas más mujeres que hombres. Esto puedo deberse a:
    - Políticas sociales y de género de la época de mujeres y niños primero.
 5. Sobrevivieron menos pasajeros con familia que sin ella. Esto seguramente pudo deberse a:
   - Sacrificios personales de algunos pasajeros que priorizaron las seguridad de sus seres queridos.
   - Dificultad para organizarse, ya que por desafío logístico las familias enfrentaron el reto de mantenerse juntas en una situación caótica. Intentar mover a varios integrantes al mismo tiempo, incluidos niños y mayores, pudo ralentizar su evacuación. Los 
     pasajeros que viajaban solos, al depender solo de sí mismos, pudieron tomar decisiones rápidas y moverse con mayor agilidad.
   - Razón de barreras sociales y de género. Por las normas de la época mujeres y niños primero beneficiaron a algunos miembros de las familias, pero los hombres (padres o hermanos mayores) quedaron relegados y con menos probabilidades de sobrevivir. Esto podría haber 
     llevado a una mortalidad desproporcionada en familias que incluían hombres adultos.
   - Distracción y estrés emocional ante una situación catastrófica. La preocupación por proteger a los demás y el estrés de cuidar a niños pequeños pudieron dificultar la respuesta rápida en la emergencia, generando mayor desorientación para sobrevivir.
   - Limitaciones de recursos de supervivencia. Ante la limitada cantidad de botes salvavidas, muchas familias se verían imposibilitadas de caber todos en el mismo bote. Aquí pudo haber separaciones de la familia por sobrevivir o familias que decidieron quedarse 
     totalmente juntas a bordo.

### Resultado final
El resultado refleja las profundas desigualdades sociales de la época. El acceso preferente y los prejuicios hacia las clases bajas influyeron directamente en la mortalidad de los pasajeros del Titanic. Los pasajeros de tercera clase al mismo tiempo además de ser la mayor parte de los pasajeros muchos de ellos viajaban en familia, por lo que sufrieron las mayores pérdidas. Al mismo tiempo, la variable género si supuso un punto importante a la hora de sobrevivir, ya que la tasa de mortandad de las mujeres en este estudio (y como refleja el dashboard) es de un 25.8%, mientras el de hombres un 81.1%. La variable edad no supone un punto relevante para sobrevivir, si no la clase y el género en segundo lugar. 

